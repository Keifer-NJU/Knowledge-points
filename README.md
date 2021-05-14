# Java

### ThreadLocalMap

### InheritableThreadLocal

### WeakReference

，WeakReference如字面意思，弱引用， 当一个对象仅仅被weak reference（弱引用）指向, 而没有任何其他strong reference（强引用）指向的时候, 如果这时GC运行, 那么这个对象就会被回收，不论当前的内存空间是否足够，这个对象都会被回收。

WeakReference(T referent, ReferenceQueue<? super T> q)：与上面的构造方法比较，多了个ReferenceQueue，**在对象被回收后，会把弱引用对象，也就是WeakReference对象或者其子类的对象，放入队列ReferenceQueue中**，注意不是被弱引用的对象，被弱引用的对象已经被回收了

### ThreaLocal 弱引用与内存泄露

### [ThreadLocal 封装及原因](https://zhuanlan.zhihu.com/p/167955824)

### [为什么ThreadLocalMap 设计为ThreadLocal 内部类](https://juejin.cn/post/6844903959539220493)

### [java类访问权限及类的成员方法访问权限](https://www.runoob.com/java/java-modifier-types.html#protected-desc)

### [@ControllerAdvice注解与统一异常处理](https://zhuanlan.zhihu.com/p/73087879)

### Spring boot自动配置原理及实现、按条件配置（@Condition）

### [JDK SPI机制和Springboot 自动配置中的SPI机制](https://juejin.cn/post/6844903890173837326#heading-2)

### Spring @Import

### SpringBoot restTemplate源码相关阅读

下面仅仅是其中创建请求涉及到的一些类图，批注了一些理解及设计模式，结合源码看更配

![image-20210511203714507](D:\OneDriver_edu\OneDrive - smail.nju.edu.cn\Java\MarkDown_AE86\知识点目录\assets\image-20210511203714507.png)

### [容器单例和ThreadLocal “单例”](https://juejin.cn/post/6844903747689136136)

### [Netty 中AttributeMap](https://zhuanlan.zhihu.com/p/89933318)

### [Java 8 CompletableFuture ](https://juejin.cn/post/6844903594165026829#heading-0)

### [Java的异步回调](https://juejin.cn/post/6958017668012048414#heading-12)

