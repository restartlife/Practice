## ArrayList 和 LinkedList的区别
1. 底层实现机制不一样. arrayList底层通过数组实现,LinkedList通过双向链表实现（jdk1.8）之前是双向循环链表但不知道从哪里开始改成双向链表

2. 如果知道集合的大小的最好设置容器的容量以避免一直扩容从而影响效率

3. 都不是线程安全的
