###### JDK

[JDK JRE Java虚拟机的关系](https://www.cnblogs.com/52Test/p/7575778.html)

https://blog.csdn.net/kingscoming/article/details/78860702   JRE 和 JDK 的区别详解

 [JVM到底在哪里？](https://www.cnblogs.com/ctaixw/p/5406625.html)



###### JavaAgent

[javaagent使用指南](https://www.cnblogs.com/rickiyang/p/11368932.html)

https://www.infoq.cn/article/fh69pypqzpf6cj1ujy7x   JavaAgent 原理与实践  

https://mp.weixin.qq.com/s/r5SGid-7d90BEOOoa_S-yA   JavaAgent



###### Java编译优化

[Java即时编译器原理解析及实践](https://tech.meituan.com/2020/10/22/java-jit-practice-in-meituan.html)

[Java中的逃逸分析](https://segmentfault.com/a/1190000016803174)

https://www.cnblogs.com/javastack/p/11023044.html     逃逸分析

https://juejin.cn/post/6844903639308304397    

https://ifeve.com/jvm优化之逃逸分析与分配消除/

https://zhuanlan.zhihu.com/p/59215831

https://www.zhihu.com/question/27963717  逃逸分析为何不能在编译期进行？

https://www.zhihu.com/question/360929863   为什么Go的web框架速度还不如Java？



###### 基础

https://mp.weixin.qq.com/s/mwgRxvYtDRV8zUlC9f7QIQ   循环用i++和++i哪个效率高？

https://www.zhihu.com/column/p/88555159    编译器优化

https://mp.weixin.qq.com/s/K9B0WXPxJnDdPi5mfN1BJw   equals和hashCode方法

https://mp.weixin.qq.com/s/DdJFheT5hLDgn3kJcv0yhQ  Integer



###### 泛型

https://juejin.cn/post/6844903917835419661   Java泛型中的通配符 T，E，K，V，？

https://mp.weixin.qq.com/s/XNYfLrnd7tYnTmuf1oyKQg   



###### JVM

https://mp.weixin.qq.com/s/A4-kyqzs5wUM5Npt2hVgVw   Java 进阶之字节码剖析

https://www.cnblogs.com/lixinjie/p/everyone-should-know-about-jvm-for-interview.html   了解JVM的结构

https://zhuanlan.zhihu.com/p/45354152  Java虚拟机—栈帧、操作数栈和局部变量表



###### 问题排查

https://mp.weixin.qq.com/s/6jZwVDVM3l20PtZr95rxpw#at  java线上故障排查全套路

https://zhuanlan.zhihu.com/p/603414466   Java微服务随机掉线排查



###### 集合类

https://mp.weixin.qq.com/s/xxauNrJY9HlVNvLrL5j2hg   Bitmap算法  

https://www.zhihu.com/question/31082722   用链表的目的是什么？

https://www.zhihu.com/question/20729324   堆排序中建堆过程时间复杂度O(n)计算

https://blog.csdn.net/YuZhiHui_No1/article/details/44258297   排序算法之 堆排序 及其时间复杂度和空间复杂度

https://zhuanlan.zhihu.com/p/365371983   ConcurrentHashMap有十个提升性能的地方

https://juejin.cn/post/6844904122429210632    ConcurrentHashMap 核心源码解析

https://mp.weixin.qq.com/s/mGj3BVBfqX5DGlFsKTXFPQ   ConcurrentHashMap的弱一致性

https://juejin.cn/post/6844904133351178254   ConcurrentHashMap 底层原理

https://blog.csdn.net/yunqiinsight/article/details/115240096   Java Map中那些巧妙的设计

https://tech.meituan.com/2016/06/24/java-hashmap.html  Java 8系列之重新认识HashMap

https://mp.weixin.qq.com/s/BBIMsAbnhjWKy8eqh2ossA



###### 枚举

https://blog.csdn.net/javazejian/article/details/71333103   深入理解Java枚举类型(enum)



###### 多态

多态实现原理: 方法表是实现动态调用的核心。为了优化对象调用方法的速度，方法区的类型信息会增加一个指针，该指针指向记录该类方法的方法表，方法表中的每一个项都是对应方法的指针。这些方法中包括从父类继承的所有方法以及自身重写（override）的方法

https://juejin.cn/post/6950788993168441381   从hotspot源码层面剖析Java的多态原理



###### 代理

https://www.jianshu.com/p/eea9a3acbaad    JDK 动态代理和Cglib性能对比

https://juejin.cn/post/6844903634019287047   基于 CGLIB 库的动态代理机制



###### JOL

https://juejin.cn/post/6996604411292319751   JOL(java object layout --java 对象内存布局)



###### 字符串常量池

http://tangxman.github.io/2015/07/27/the-difference-of-java-string-pool/    Java中几种常量池的区分

https://mp.weixin.qq.com/s/fMPSmlJZkNxzOPSTJ3oeZw

https://blog.csdn.net/xiaojin21cen/article/details/105300521

https://mp.weixin.qq.com/s/ga9kwZYqu45a0sd_wsRalA    String s = new String("xyz")创建了几个实例

https://tech.meituan.com/2014/03/06/in-depth-understanding-string-intern.html   深入解析String#intern

https://blog.csdn.net/Herishwater/article/details/100924191    Java 中方法区与常量池

https://juejin.cn/post/6844903988815478791   Java 基础：String——常量池与 intern

https://www.cnblogs.com/duanxz/p/3613947.html   运行时常量池与intern()方法

https://www.zhihu.com/question/55994121   Java 中new String("字面量") 中 "字面量" 是何时进入字符串常量池的?

https://www.zhihu.com/question/36908414   

https://www.zhihu.com/question/51102308  



###### String

https://mp.weixin.qq.com/s/xlsGPflZJQKpIB0jPTv3mw   Java中final和static修饰的变量是在什么时候赋值的

https://mp.weixin.qq.com/s/U8y7WT6l21TVtpZ-mQffEA   String



###### final

https://www.zhihu.com/question/55642203    final

https://www.zhihu.com/question/21395848  java为什么匿名内部类的参数引用时final？







































