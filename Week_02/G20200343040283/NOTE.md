学习笔记

HashMap总结：
   因为一些原因（基础比较薄弱等）对HashMap数据结构一知半解，对了解的做一点小总结，下周会做一个补充，通过看大量的数据
   
    1、HashMap采用了数组和链表的数据结构，能在查询和修改方便继承了数组的线性查找和链表的寻址修改
    2、HashMap是一个散列桶(数组和链表)，以键值对方式进行存储的
    3、HashMap是通过get()和put()方法来获取和存储对象的。当我们存储值时，将键值对传给put()方法时，他调用键的hashCode()方法来计算hashCode值，然后找到对应的bucket位置来存储对象。当获取对象时，通过调用键的equals()方法找到正确的键值对，来返回值对象
    4、HashMap通过链表的方式解决hash碰撞的，当发生碰撞时，对象会存储在链表的下一个节点中。
    5，哈希碰撞应该还有其他方法，接下来会加强看，谢谢。
    
