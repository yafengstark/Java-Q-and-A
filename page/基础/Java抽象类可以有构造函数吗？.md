可以有，抽象类可以声明并定义构造函数。因为你不可以创建抽象类的实例，所以构造函数只能通过构造函数链调用（Java中构造函数链指的是从其他构造函数调用一个构造函数），例如，当你创建具体的实现类。现在一些面试官问，如果你不能对抽象类实例化那么构造函数的作用是什么？好吧，它可以用来初始化抽象类内部声明的通用变量，并被各种实现使用。另外，即使你没有提供任何构造函数，编译器将为抽象类添加默认的无参数的构造函数，没有的话你的子类将无法编译，因为在任何构造函数中的第一条语句隐式调用super()，Java中默认超类的构造函数。


