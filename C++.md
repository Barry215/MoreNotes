1. 当派生类的指针赋给基类时，如Person * p = new Student；需要将基类析构定义为virtual，不然用delete的时候，只会调用基类的析构而不会用派生类的析构。
