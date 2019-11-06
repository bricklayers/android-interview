#### Android基础

- [简述一下 Activity 的生命周期？](https://github.com/bricklayers/resources/blob/master/android-interview/1.%E7%AE%80%E8%BF%B0%E4%B8%80%E4%B8%8B%20Activity%20%E7%9A%84%E7%94%9F%E5%91%BD%E5%91%A8%E6%9C%9F.md)

- 两个Activity之间跳转时必然会执行的是哪几个方法？

- Activity的四种启动模式，singletop和singletask区别是什么？

- Fragment 跟 Activity 之间是如何传值的？

- 描述一下 Fragment 的生命周期？

- 如何加速启动Activity？

- Android中的Context,Activity，Appliction有什么区别？   

- Handler机制原理？子线程中能不能 new handler？为什么？

- 事件分发机制？

- View测量、布局及绘制原理

- ListView和RecyclerView区别，RecyclerView有什么优势？RecyclerView优化

- Adapter ViewHolder缓存导致显示错乱的坑

- IntentService源码分析

- HandlerThread详解

- 什么是过度绘制，如何优化？

- View测量、布局及绘制原理

- AsyncTask原理与使用   .请介绍下 AsyncTask 的内部实现，适用的场景是

- Service相关   

- 广播有哪几种，它们之间的区别是什么？

- 说说 LruCache 底层原理

- Zygote进程启动过程   

- 为什么要用ContentProvider？它和sql的实现上有什么差别

- AIDL的全称是什么？如何工作？能处理哪些类型的数据？AIDL 的全称是什么?如何工作?能处理哪些类型的数据？

- Serializable 和 Parcelable 的区别

- Android 中如何捕获未捕获的异常

- ANR 是什么？怎样避免和解决 ANR（重要）如何分析

- Android 线程间通信有哪几种方式（重要）进程间如何通信

- Framework 工作方式及原理，Activity 是如何生成一个 view 的，机制是什么？（2016.01.24）

- 多线程间通信和多进程之间通信有什么不同，分别怎么实现？（2016.01.24）

- 子线程发消息到主线程进行更新 UI，除了 handler 和 AsyncTask，还有什么？

- 谈谈你对 Bitmap 的理解, 什么时候应该手动调用 bitmap.recycle()

- 屏幕适配方式都有哪些（重要）屏幕适配的处理技巧都有哪些

####   Java基础     

- ArrayList、LinkedList、Vector区别   

- HashCode作用    equals 与 hashCode 的异同点在哪里？   

- HashMap的工作原理   

- SparseArray与Hashmap的区别？ 

- Java中ConcurrentHashMap的并发度是什么？   

- Java的四种引用，强弱软虚，用到的场景   

- Map、Set、List、Queue、Stack的特点与用法   

- Object公有方法以及wait和sleep区别   

- interface与abstract类的区别   

- 反射原理及应用   

- 类加载机制

- 泛型特点及其类型转换   

- synchronized、lock、reentrantLock区别   

- 线程以及ThreadLocal   

- [ThreadPool用法与示例](https://github.com/helen-x/AndroidInterview/blob/master/java/[Java] ThreadPool用法与示例.md)   

- 线程池的使用   

- Java线程池中submit() 和 execute()方法有什么区别？   

- 锁的等级：方法锁、对象锁、类锁 

- Java中活锁和死锁有什么区别？   

- 简述垃圾回收器的工作原理。   

- final 与 static 关键字可以用于哪里？它们的作用是什么？   

- 描述下 String,StringBuilder 以及 StringBuffer 区别。   

- 覆盖（Overriding）与重载（OverLoading）的区别在哪里。   

- 接口（Interface）与抽象类（Abstract Class）的区别在哪里。   

- foreach与for循环效率对比   

- 设计模式六大原则

#### 计算机网络 

- 3次握手和4次挥手过程 

- HTTP响应报文格式及各种响应码 

- HTTP请求报文格式

- Http怎么处理长连接 

- TCP与UDP区别及其各自优缺点

- TCP/IP 协议簇分哪几层？TCP、IP、XMPP、HTTP、分别属于哪一层？（2016.01.24）

- http与https区别   

- 打开一个网页，整个过程使用到哪些协议   

- 什么是 socket?

#### Java 中的设计模式

- 单例设计模式

- 观察者模式（Observer）

- 工厂设计模式

- 普通工厂模式

- 建造者模式（Builder）

- 装饰模式（Decorator

- 策略模式（strategy）

#### 性能优化

- 如何对 Android 应用进行性能分析

- 什么情况下会导致内存泄露

- 内存溢出的几点原因

#### 开发中都使用过哪些框架、平台

- EventBus（事件处理）

- fastGson（解析 json 数据框架）

- Picasso, ImageLoader, Fresco, Glide 优劣

- Ok-http  ,retrofit

- RxJava

#### 项目的流程

个在项目中不一定问，但是大家要知道项目开发的流程，作为有经验的程序员程序的流程是一定知道的。
按时间轴来排列：

立项：确定项目、负责人、开发的周期、成本、人力、物力需求：文档、原型图
开发：编码
测试：测试人员
上线：产品部门
维护：修复新的 bug
升级:改版、添加新的功能

#### 项目中常见的问题谈谈你在工作中是怎样解决一个 bug

异常附近多打印 log 信息；

分析 log 日志，实在不行的话进行断点调试；

调试不出结果，上 Stack Overflow 贴上异常信息，请教大牛

再多看看代码，或者从源代码中查找相关信

实在不行就 GG 了，找师傅来解决！

#### 各大公司面试备忘





  