https://www.cnblogs.com/yunche/p/9530927.html
- 1.使用new创建对象
使用new关键字创建对象应该是最常见的一种方式，但我们应该知道，使用new创建对象会增加耦合度。无论使用什么框架，都要减少new的使用以降低耦合度。
- 2.使用反射的机制创建对象
使用Class类的newInstance方法
- 3.采用clone
clone时，需要已经有一个分配了内存的源对象，创建新对象时，首先应该分配一个和源对象一样大的内存空间。要调用clone方法需要实现Cloneable接口
- 4.采用序列化机制
使用序列化时，要实现实现Serializable接口，将一个对象序列化到磁盘上，而采用反序列化可以将磁盘上的对象信息转化到内存中。

