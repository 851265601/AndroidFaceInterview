
# Android面试题集(2019-04-04总结)

> &emsp;&emsp;一份Android面试题集，适应于实习 & 初级工程师 & 中级工程师，高级工程师勉强吧。笔者不提供答案，但是会提供学习链接，旨在能帮助广大Android学习者找到心仪的Offer,文章底部是笔者收集的一些有关面试的文章链接，希望Android求职者认真研读，准备面试，并顺利找到Offer。如果你是Android学习者，请订阅笔者的[Android知识体系总结(全方面覆盖Android知识结构，面试&进阶)](https://blog.csdn.net/ClAndEllen/article/details/79257663)，本篇文章中的问题可以从文章中找到答案，谢谢支持。查阅答案，请star项目[AndroidFace](https://github.com/Ellen2018/AndroidFace)  
> 
> &emsp;&emsp;本面试题集只应对于Android求职者,有5个模块：  
> &emsp;&emsp;**Java部分**  
> &emsp;&emsp;**Android部分**  
> &emsp;&emsp;**数据结构与算法部分**  
> &emsp;&emsp;**常用的开源库部分**  
> &emsp;&emsp;**计算机网络认识**

## 1.Java部分

### 1.1 操作系统相关

- 1.什么是操作系统？
- 2.什么是线程，什么是进程？

### 1.2 JDK&JVM&JRE

- 1.JDK & JVM & JRE分别是什么以及它们的区别？
- 2.解释一下为什么Java可以跨平台？

### 1.3 面向过程 & 面向对象

- 1.什么是面向过程 & 什么是面向对象 & 区别？
- 2.给我说说Java面向对象的特征以及讲讲你代码中凸显这些特征的经验。
- 3.什么是重载 & 什么是重写 & 区别。
- 4.谈谈你对this和super的认识。
- 5.接口和抽象类的区别。
- 6.静态属性和静态方法能被继承吗？静态方法又是否能被重写呢？
- 7.给我说说权限修饰符特性。
- 8.给我谈谈Java中的内部类。
- 9.闭包和内部类的区别？
- 10.Java多态的实现机制是什么？
- 11.谈谈你对对象生命周期的认识？
- 12.static关键字的作用？
- 13.final关键字的作用。

### 1.4 八大基本数据类型&引用类型

- 1.说说Java中的8大基本类型 & 内存中占有的字节 & 什么是引用类型？
- 2.什么是拆箱 & 装箱，能给我举栗子吗？
- 3.知道float和double类型为什么会出现精度丢失的情况吗？
- 4.基本类型的初始化值为多少？引用类型的初始值为多少？

### 1.5 数组

- 1.能说说多维数组在内存上是怎么存储的吗？
- 2.你对数组二次封装过吗？说说封装了什么

### 1.6 Java异常

- 1.说说Java异常体系主要用来干什么的 & 异常体系？
- 2.Error和Exception的区别？
- 3.说说运行时异常和非运行时异常的区别？
- 4.如何自定义一个异常？
- 5.throw和throws 的区别？
- 6.try{}catch{}finally{}可以没有finally吗？
- 7.finally语块有什么特点？
- 8.return在try{}catch{}finally{}中执行具有哪些规则？
- 9.给我例举至少5个常见的运行时异常。
- 10.你如何看待Java加入异常这样的机制？

### 1.7 NIO/BIO/AIO

- 1.NIO是什么 & BIO是什么 & AIO是什么 & 它们之间的区别？
- 2.IO按照方向和数据类型划分能划分为哪些数据流？
- 3.能给我说说NIO有什么特点？平常开发中使用过吗？
- 4.如果读取一个txt文本文件乱码了，你觉得原因是什么？

### 1.8 集合(容器)

- 1.说说Java中集合的框架？
- 2.Collection & Map区别
- 3.谈谈你常用的集合 & 它们底层的实现方式 & 优缺点 & 使用场景。
- 4.Map的遍历方式有哪些？
- 5.给我说说ArrayList的扩容机制.
- 6.什么是深拷贝 & 浅拷贝 & 如何深拷贝一个List集合.
- 7.Set是如何确保它的唯一性的。
- 8.你觉得HashMap的元素顺序和什么有关？
- 9.Java中HashMap如何解决哈希碰撞的？
- 10.ConcurrentHashMap如何实现并发访问的？
- 11.谈谈Java集合中那些线程安全的集合 & 实现原理。
- 12.说说有哪些集合能加入null,哪些不能加入null,为什么？
- 13.说说LinkedHashMap原理。
- 14.Collection 和 Collections的区别？
- 15.比较一下ArrayMap & SparseArray & HashMap。
- 16.说说HashMap的原理。

### 1.9 线程

- 1.什么是线程？能解决什么问题。
- 2.Java中创建线程的2种方式 & 区别？
- 3.给我说说线程的生命周期。
- 4.线程死锁的原因 & 举个栗子 & 如何避免死锁。
- 5.Synchronized放在静态方法和非静态方法上的锁对象分别是什么？
- 6.如何停止掉一个线程？
- 7.给我说说线程池的种类 & 特点 & 内部原理 & 平时当中使用案例。
- 8.给我谈谈你是如何保证线程数据安全问题的？
- 9.wait()和sleep()的区别？
- 10.什么是公平锁&非公平锁&区别？
- 11.给我讲讲线程间通信
- 12.volatile关键字是如何使用的？原理是什么
- 13.说说使用5个线程去计算一个数组之和的思路。
- 14.谈谈线程阻塞的原因有哪些？
- 15.谈谈你对notify的理解？
- 16.你觉得Lock和Synchronized的区别是什么？
- 17.谈谈你对ReentrantLock的认识。
- 18.调用run()和start()的区别？
- 19.transient关键字的用法 & 作用 & 原理。
- 20.线程池的种类  & 工作原理 & ThreadPoolExecutor的工作策略有哪些？
- 21.ThreadLocal了解吗？说说原理。
- 22.权衡多线程的性能。
- 23.如何理解同步和异步，阻塞和非阻塞。

### 1.10 泛型

- 1.什么是泛型？能解决什么问题？
- 2.说说Java中泛型的工作机制？
- 3.在泛型种extends和super关键字的区别是什么？
- 4.比较一下其它语言中的泛型和Java泛型的区别。
- 5.在Java中List< A >和List< B >是一样的类型还是不一样的类型？为什么？
- 6.你可以例举一些自己使用泛型的栗子吗？

### 1.11 反射

- 1.什么是反射？
- 2.如何获取一个类的成员变量 & 成员方法 & 注解信息 & ...。
- 3.通常在项目当中用到反射多吗？都是用来干嘛？
- 4.你如何看待很多人认为反射效率很慢的问题？

### 1.12 注解

- 1.什么是注解 & 它和注释的区别？
- 2.注解的工作机制是什么？
- 3.如何解析注解？

### 1.13 Socket编程

- 1.什么是Socket编程？
- 2.什么是TCP,什么是UDP,二者之间区别如何？

### 1.14 设计模式

- 1.说说设计模式的六大原则。
- 2.请讲讲你会使用的一些设计模式？
- 3.请说说单例模式 & 你项目中常用的单例模式。
- 4.懒汉单例模式为什么要加volaitle？
- 5.能否给我说说Android中至少3个用到设计模式的栗子？

### 1.15 JVM相关

- 1.什么是class文件？
- 2.Java代码执行流程？
- 3.Java内存结构 & 内存模型。
- 4.GC回收机制。
- 5.Java虚拟机是如何加载一个类的？
- 6.给我谈谈类加载器。
- 7.谈谈static编译运行时的流程，在虚拟机中如何保存的？
- 8.说说Java种的4种引用以及用法？
- 9.如何判断一个对象是死亡的？
- 10.代码中直接调用System.gc()会发生什么？
- 11.一个强引用直接被null赋值，那么这个对象会被立刻回收吗？
- 12.String a = "a"+"b"+"c";在内存中创建了几个对象？
- 13.谈谈你对字符集的理解。
- 14.常见的编码格式有哪些？
- 15.utf-8中的中文占几个字节？int型占几个字节？
- 16.谈谈你对逻辑地址和物理地址的理解？
- 17.你知道对象什么时候会回调finalize方法吗？
- 18.可以给我谈谈匿名内部类的工作机制吗？

### 1.16 其它Java部分有关面试题

- 1.为什么局部内部类访问局部变量需要final?
- 2.String、StringBuffer、StringBuilder、CharSequence的区别。
- 3.equals和==的区别？
- 4.关于字符串的拼接你在项目中常常怎么操作的？为什么不能用“+”的方式进行拼接呢？
- 5.什么是Callback,讲讲你项目中使用的一些有关Callback的栗子。
- 6.retrun & break & continue 区别？
- 7.如何判断一个字符串是回文字符串？
- 8.final,finally,finalize的区别？
- 9.什么是动态代理 & 什么是静态代理？
- 10.String为什么会加final？
- 11.OOM可以try{}catch{}吗？
- 12.给我谈谈正则表达式。
- 13.如何将String转成int?
- 14.谈谈你对String的理解。
- 15.你如何理解序列化？有哪些方式序列化？
- 16.谈谈你对依赖注入的理解。
- 17.给我谈谈你对分派的理解。

## 2.Android 部分

- 四大组件是哪四个？ABCS(Activity,Braodcast,ContentProvider,Service)

### 2.1 Activity

- 1.Activity是什么？
- 2.典型情况下的Activity生命周期？
- 3.异常情况下的Activity的生命周期 & 数据如何保存和恢复？
- 4.从Activity A跳转到Activity B之后，然后再点击back建之后，它们的生命周期调用流程是什么？
- 5.如何统计Activity的工作时间？
- 6.给我说说Activity的启动模式 & 使用场景。
- 7.如何在任意位置关掉应用所有Activity & 如何在任意位置关掉指定的Activity？
- 8.Activity的启动流程(从源码角度解析)？
- 9.启动一个其它应用的Activity的生命周期分析。
- 10.Activity任务栈是什么？在项目中有用到它吗？说给我听听
- 11.什么情况下Activity不走onDestory?
- 12.什么情况下Activity会单独执行onPause?
- 13.a->b->c界面，其中b是SingleInstance的，那么c界面点back返回a界面，为什么？
- 14.如果一个Activity弹出一个Dialog,那么这个Acitvity会回调哪些生命周期函数呢？
- 15.Activity之间如何通信 & Activity和Fragment之间通信 & Activity和Service之间通信？
- 16.说说Activity横竖屏切换的生命周期。
- 17.前台切换到后台，然后在回到前台时Activity的生命周期。
- 18.下拉状态栏时Activity的生命周期？
- 19.Activity与Fragment的生命周期比较？
- 20.了解哪些Activity常用的标记位Flags？
- 21.谈谈隐式启动和显示启动Activity的方式？
- 22.Activity用Intent传递数据和Bundle传递数据的区别？为什么不用HashMap呢？
- 23.在隐式启动中Intent可以设置多个action,多个category吗 & 顺便讲讲它们的匹配规则？
- 24.Activity可以设置为对话框的形式吗？
- 25.如何给Activity设置进入和退出的动画？
- 26.Activity使用Intent传递数据是否有限制 & 如果传递一个复杂的对象，例如一个复杂的控件对象应该怎么做？
- 27.在Activity中可以多次调用setContentView方法吗？说说不同时机第二次调用setContentView会发生什么？
- 28.说说分别在Activity里每一个生命周期函数里调用finish方法后，接下来Activity的生命周期如何回调？
- 29.有什么方法可以启动一个没有在AndroidManifest.xml中注册过的Activity?
- 30.在Activity进行配置时，catrgory和action的区别是什么？

### 2.2 BroadcastReceiver

- 1.广播是什么？
- 2.广播的注册方式有哪些？
- 3.广播的分类 & 特性 & 使用场景？
- 4.说说系统广播和本地广播的原理 & 区别 & 使用场景。
- 5.有两个应用注册了一样的广播，一个是静态，一个是动态，连优先级也一样，那么当广播从系统发出来后，哪个应用先接收到广播？

### 2.3 ContentProvider

- 1.什么是内容提供者？
- 2.说说如何创建自己应用的内容提供者 & 使用场景。
- 3.说说ContentProvider的原理。
- 4.ContentProvider,ContentResolver,ContentObserver之间的关系？
- 5.说说ContentProvider的权限管理。

### 2.4 Service

- 1.什么是Service?
- 2.说说Service的生命周期。
- 3.Service和Thread的区别？
- 4.Android 5.0以上的隐式启动问题及其解决方案。
- 5.给我说说Service保活方案
- 6.IntentService是什么 & 原理 & 使用场景 & 和Service的区别。
- 7.创建一个独立进程的Service应该怎样做？
- 8.Service和Activity之间如何通信？
- 9.说说你了解的系统Service。
- 10.谈谈你对ActivityManagerService的理解。
- 11.在Activtiy中创建一个Thread和在一个Service中创建一个Thread的区别？

### 2.5 Handler

- 1.子线程一定不能更新UI吗？
- 2.给我说说Handler的原理
- 3.Handler导致的内存泄露你是如何解决的？
- 4.如何使用Handler让子线程和子线程通信？
- 5.你能给我说说Handler的设计原理？
- 6.HandlerThread是什么 & 原理 & 使用场景？
- 7.IdleHandler是什么？
- 8.一个线程能否创建多个Handler,Handler和Looper之间的对应关系？
- 9.为什么Android系统不建议子线程访问UI？
- 10.Looper死循环为什么不会导致应用卡死？
- 11.使用Handler的postDealy后消息队列有什么变化？
- 12.可以在子线程直接new一个Handler出来吗？
- 13.Message对象创建的方式有哪些 & 区别？
- 14.ANR和Handler存在什么联系吗？
- 15.子线程的Looper和主线程的Looper有什么区别？
- 16.说说Handler为什么不能进行跨进程通信？
- 17.Handler的消息延时是如何实现的？
- 18.什么是消息屏障？
- 19.假设主线程new了Handler A和Handler B以及Handler C,现在有个子线程，在子线程中通过Handler C发送了一条消息，那么Handler A和Handler B能接收到吗？为什么？

### 2.6 AsyncTask

- 1.AsyncTask是什么？能解决什么问题
- 2.给我谈谈AsyncTask的三个泛型参数作用 & 它的一些方法作用。
- 3.给我说说AsyncTask的原理。
- 4.你觉得AsyncTask有不足之处吗？

### 2.7 Fragment

- 1.Android中v4包下Fragment和app包下Fragment的区别是什么？
- 2.Fragment的生命周期 & 请结合Activity的生命周期再一起说说。
- 3.说说Fragment如何进行懒加载。
- 4.ViewPager + Fragment结合使用会出现内存泄漏吗 & 如何解决？
- 5.Fragment如何和Activity进行通信 & Fragment之间如何进行通信？
- 6.给我谈谈Fragment3种切换的方式以及区别 & 使用场景。
- 7.getFragmentManager,getSupportFragmentManager,getChildFragmentManager之间的区别？
- 8.FragmentPagerAdapter和FragmentStatePagerAdapter区别？
- 9.Fragment如何实现类似Activity栈的压栈和出栈效果的？

### 2.8 序列化

- 1.什么是序列化 & 能用来干什么？
- 2.Android中序列化方式有几种？说说它们的区别。
- 3.如果想要序列化的类中某些字段不序列化，那么应该怎么做？

### 2.9 IPC

- 1.说说你对Android多进程开发的认识？
- 2.Android中进程间通信的方式有哪些？
- 3.什么是AIDL?如何创建一个AIDL。

### 2.10 文件存储

- 1.说说Android中数据持久化的方式 & 使用场景。
- 2.接触过MMKV吗？说说SharedPreference和它的区别。
- 3.第三方数据库框架用过哪些？有没有自己封装过一个SQLite的库？
- 4.SQLite是线程安全的吗 & SharedPreference是线程安全的吗？
- 5.请简单的给我说说什么是三级缓存？
- 6.SharedPreference的apply和commit的区别。
- 7.谈谈你对SQLite事务的认识。
- 8.千奇百怪的SQL语句考察。
- 9.SharePreference跨进程使用会怎么样？如何保证跨进程使用安全？
- 10.谈谈SQLite升级要注意哪些地方？

### 2.11 ListView & RecyclerView

- 1.ListView是什么？如何使用？
- 2.RecyclerView是什么？如何使用？如何返回不一样的Item。
- 3.ListView和RecycyclerView的区别是什么？
- 4.分别讲讲你对ListView & RecyclerView的优化经验。
- 5.给我说说RecyclerView的回收复用机制
- 6.说说你是如何给ListView & RecyclerView加上拉刷新 & 下拉加载更多机制。
- 7.谈谈你是如何对ListView & RecycleView进行局部刷新的？
- 8.谈谈如何进行分页加载？
- 9.ScrollView下嵌套一个ListView通常会出现什么问题？
- 10.一个ListView或者一个RecyclerView在显示新闻数据的时候，出现图片错位，可能的原因有哪些 & 如何解决？

### 2.12 图片编程

- 1.你对Bitmap了解吗？它在内存中如何存在？
- 2.有关Bitmap导致OOM的原因知道吗？如何优化？
- 3.给我谈谈图片压缩。
- 4.LruCache & DiskLruCache原理。
- 5.说说你平常会使用的一些第三方图片加载库,最好给我谈谈它的原理。
- 6.如果让你设计一个图片加载库，你会如何设计？
- 7.有一张非常大的图片,你如何去加载这张大图片？
- 8.你知道Android中处理图片的一些库吗(OpenCv & GPUImage ...)？
- 9.如何计算一张图片在内存中占用的大小？

### 2.13 WebView

- 1.WebView是什么？
- 2.WebView会导致内存泄露吗？原因是什么？解决方式有哪些？
- 3.你知道Hybrid开发吗？说说你的相关经验。
- 4.说说WebSettings & WebViewClient & WebChromeClient这三个类的作用 & 用法。
- 5.说说你了解的Hybrid框架。

### 2.14 ViewPager

- 1.什么是ViewPager?说说它的那些适配器。
- 2.你了解ViewPager2吗？和ViewPager 1有哪些区别？
- 3.ViewPager + Fragment结合使用存在的内存泄漏的原因是什么？如何解决？

### 2.15 View事件分发机制

- 1.什么是事件分发机制？主要用来解决什么问题？
- 2.给我说说事件分发的流程 & 你项目解决事件冲突的一些案例。
- 3.分别讲讲有关事件分发的三个方法的作用及关系。
- 4.如果我在一个设置了点击事件的TextView中dispatchTouchEvent方法强制返回ture或者false会发生什么？
- 5.cancel事件是怎么产生的，说说详细的流程。
- 6.线性布局A下面放置一个Button,如果给Button设置了点击事件，在线性布局A中重写了dispatchTouchEvent,onInterceptHoverEvent，而且它们都回了true,那么Button的点击事件会被调用吗？当前Activity的onTouchEvent又是否会被调用呢？为什么？
- 7.多点触摸事件平时接触过吗？如何监听用户第二个手指，第三个...？
- 8.OnTouchListener & OnTouchEvent & OnClickListener三者之间的关系？
- 9.谈谈你对MotionEvent的认识？Cancel事件是什么情况下触发的？
- 10.能给我谈谈Android中坐标体系吗？

### 2.16 View绘制机制

- 1.说说View绘制流程。
- 2.说说Activity View树结构。
- 3.自定义View的方式有哪些?给我说说你之前项目中的案例。
- 4.invalidate和postvalidate的区别？
- 5.说说你在自定义View时常常重写的一些方法？
- 6.说说自定义View中如何自定义属性？
- 7.requestLayout(),onLayout(),onDraw(),drawChild()区别和联系？
- 8.如何计算出一个View的嵌套层级？
- 9.自定义View如何考虑机型适配？

### 2.17 布局

- 1.说说Android中有哪些布局 & 特点。
- 2.你知道布局文件到控件对象的过程吗？
- 3.有这么一个布局需求，一个文本控件放在屏幕一半的一半的中间位置，你如何进行布局？
- 4.LinearLayout,FrameLayout,RelativeLayout性能对比，为什么？

### 2.18 Binder

- 1.什么是Binder？用来干什么？
- 2.给我具体讲讲Binder机制。

### 2.19 动画机制

- 1.Android中的动画分为哪些种类 & 特点 & 缺点。
- 2.知道SVG & 矢量动画吗？
- 3.给我说说转场动画。
- 4.给我谈谈插值器 & 估值器 的作用。
- 5.说说Android动画框架实现的原理。

### 2.20 JNI

- 1.什么是JNI?它主要用来干什么。
- 2.Java Native方法如何和Native函数进行绑定的？
- 3.JNI如何实现数据传递？
- 4.如何全局捕获Native发生的异常？
- 5.只有C/C++能编写Native库吗？

### 2.21 Window & Appliction & Context

- 1.说说你对Android中Window的理解。
- 2.说说你对Application的理解 & 生命周期。
- 3.Android中有哪些上下文 & 区别 & 作用。
- 4.谈谈你对Android中Context的理解。

### 2.22 通知

- 1.Android 8.0如何适配通知？
- 2.自定义通知流程？

### 2.23 对话框(Dialog & DialogFragment & PopWindow)

- 1.说说Android中对话框可以用哪些方式完成？

### 2.24 蓝牙

- 1.说说最新的蓝牙版本？新版本的特性是什么？

### 2.25 冷启动&热启动

- 1.什么是冷启动 & 什么是热启动 & 它们的流程？
- 2.如何优化冷启动？
- 3.启动页白屏，黑屏，太慢如何解决？

### 2.26 悬浮窗

- 1.在做悬浮窗的时候你遇到了什么困难(主要指悬浮窗权限适配)？
- 2.如何制作一个悬浮窗？

### 2.27 Android版本

- 1.最新的Android版本多少知道吗？有哪些特性
- 2.说说更新较大的Android版本。
- 3.说说看如何兼容AndroidX？

### 2.28 Android Studio

- 1.你现在比较常用Android Studio那个版本 & 用的Gradle版本是多少？
- 2.如何理解gradle?
- 3.说说Android Studio中大致项目结构？
- 4.混淆是什么 & 为什么需要进行混淆 & 混淆的原理 & 为什么Java反射常常会和混淆冲突？

### 2.29 UI卡顿优化

- 1.ANR是什么？导致原因有哪些？
- 2.谈谈你项目中避免ANR的一些经验。
- 3.分别说说Activity & BroadcastReceiver & Serice最长可耗时时间为多少？

### 2.30 内存优化

- 1.什么是OOM & 什么是内存泄漏 & 什么是内存抖动？
- 2.谈谈你项目中内存优化的一些经验。

### 2.31 屏幕适配

- 1.说说Android中一些屏幕单位。
- 2.谈谈你项目中的一些屏幕适配的经验。
- 3.今日头条的轻量级适配方案了解吗 & 给我说说原理。

### 2.32 多渠道打包 & apk签名

- 1.apk为什么需要签名？
- 2.多渠道打包是什么 & 有类似经验吗？
- 3.简述多渠道打包及原理和常用操作？

### 2.33 项目架构

- 1.说说你用过的项目架构？
- 2.分别给我说说MVC,MVP,MVVM特点和区别。
- 3.以登陆界面为例子,设计MVP架构。
- 4.谈谈AndroidManifest.xml文件的理解。

### 2.34 Android前沿知识

- 1.谷歌新出的Flutter知道吗？
- 2.谷歌新出的官方开发语言Kotlin了解吗 & 和Java相比它有哪些特点。
- 3.谈谈Kotlin中协程的认识？

### 2.35 音视频开发(高薪)

- 1.之前有过音视频开发经验吗 & 说说用哪些开源架子开发的。
- 2.FFmpeng了解过吗？
- 3.Android中播放视频音频的方式有哪些？
- 4.Android中播放网络地址视频有哪些出色的开源库？
- 5.流媒体服务器了解吗？
- 6.谈谈你对编码格式的理解。
- 7.MediaPlayer和SoundPool的区别？
- 8.视频硬解码和软解码的区别？

### 2.36 Android虚拟机(高级及以上工程师涉及)

- 1.Android虚拟机经过了哪些版本？
- 2.简单说说Android虚拟机和Java虚拟机的区别。
- 3.如何理解Class格式文件和Dex格式文件区别。
- 4.ART虚拟机中JNI工作机制。

### 2.37 其它Android部分有关面试题

- 1.说说一个app的启动流程(从源码角度讲解)。
- 2.你知道无论是Kotlin或者是Java,程序运行的主要入口都是main()方法，那么Android的main方法在哪里？
- 3.Android Hock技术了解吗？
- 4.简述Android中的加固和使用平台？
- 5.谈谈你对Apk瘦身的经验？
- 6.为什么子线程不能更新UI？
- 7.你知道如何定位内存泄漏吗？
- 8.说说System.exit(0),onDestory(),Activity.finish()的区别？
- 9.在OnResume或者之前获取View的宽高为多少 & 为什么？
- 10.Art & Dvm 区别，特别是谈谈GC的区别。
- 11.说说你用的二维码框架 & 有过优化经验吗？
- 12.谈谈App多进程的好处 & 缺点。
- 13.说说AMS是怎么找到启动指定的Activity？
- 14.View的getWidth和getMeasureWidth有啥区别？
- 15.有插件化或者热修复经验吗？说说它的原理。
- 16.断点续传了解吗？谈谈你是如何通过多线程实现断点续传的。
- 17.给我谈谈你对SurfaceView的认识。
- 18.什么情况下你会使用到ScrollView。
- 19.低版本SDK如何使用高版本API？
- 20.AlertDialog,PopWindow,Activity之间的区别？
- 21.Application和Activity,Context的区别？
- 22.谈谈Android中多线程通信方式？
- 23.说说Android大体的架构图，试着画出来。
- 24.知道SpareArray吗？
- 25.Activity除了setContentView可以设置布局，还有其它方式吗？
- 26.Android为每个应用程序分配的内存大小为多少？
- 27.Android进程保活方案？
- 28.谈谈Android系统安装apk的过程？
- 29.Activity,Window,View三者的关系？
- 30.ActivityThread,ActivityManagerService,WindowManagerService的工作原理？
- 31.PackageManagerService的工作原理？
- 32.PowerManagerService的工作原理？
- 33.在桌面点击一个未启动的App的流程 & 点击一个已启动的App的流程？
- 34.Android中进程分为哪些种类？
- 35.什么是埋点，懂它的原理吗？
- 36.进程和Application生命周期之间的关系？
- 37.App相互唤醒的有哪些方式？
- 38.Android中如何开启多进程？应用是否可以开启N个进程？
- 39.谈谈消息推送的方式有哪些？
- 40.谈谈你对Root权限的理解。
- 41.谈谈项目如何进行国际化？
- 42.谈谈你对Intent和IntentFilter的理解。
- 43.一条最长的短信息约占多少byte？
- 44.如何理解组件化设计思想？

## 3.算法与数据结构部分

### 3.1 复杂度分析

- 1.什么是时间复杂度 & 什么是空间复杂度？
- 2.时间复杂度和空间复杂度之间存在什么联系？

### 3.2 数组

- 1.谈谈你对数组的理解。
- 2.数组和其它数据结构进行对比 & 使用场景。

### 3.3 链表

- 1.什么是单链表 & 双向链表 & 循环链表 & 双向循环链表 & 静态链表。
- 2.反转一个链表有哪些方式？
- 3.如何判断链表有环？
- 4.用Java语言设计一个LinkedList。

### 3.4 堆

- 1.如何理解堆？

### 3.5 栈

- 1.什么是栈 & 栈的特点是什么？
- 2.什么是顺序栈 & 链式栈？
- 3.你有没有基于栈封装的业务类？
- 4.你能用栈实现队列吗？
- 5.如何实现浏览器前进和后退功能？

### 3.6 队列

- 1.什么是队列 & 队列的特点是什么？
- 2.什么是优先队列？
- 3.什么是双端队列 & 阻塞队列?
- 4.你能用队列实现栈吗？

### 3.7 散列表

- 1.什么是散列函数？
- 2.什么是散列冲突？解决的方式有哪些？Java中的HashMap解决方式采用的哪一种？
- 3.什么是散列表的动态扩容？
- 4.什么是位图？

### 3.8 树

- 1.什么是二叉树？
- 2.什么是先序遍历 & 中序遍历 & 后序遍历。
- 3.什么是多路查找树？
- 4.什么是红黑树？

### 3.9 排序

- 1.给我说说你会的排序 & 复杂度如何？
- 2.现在有10万条数据需要进行排序，你会选择什么排序？

### 3.10 查找

- 1.说说你知道的查找算法 & 复杂度如何？

### 3.11 递归&回溯算法

- 1.什么是递归 & 什么是回溯？

### 3.12 贪心算法

- 1.什么是贪心算法？

### 3.13 其它有关算法与数据结构的面试题

- 1.什么是图？可以解决一些什么问题？
- 2.时针走一圈，时针分针重合几次？
- 3.有一个不均匀的绳子烧完要1个小时，如何算出1小时15分钟？
- 4.求1000以内的水仙花数以及40亿以内的水仙花数？
- 5.数据怎么压缩，数据的安全。
- 6.谈谈你对对称加密 & 非对称加密的理解。

## 4.常用的开源库部分

### 4.1 异步通信

- 1.RxJava用法 & RxJava2用法 & 原理 &用到的设计模式？
- 2.EventBus用法 & 原理。

### 4.2 网络

- 1.OkHttp用法 & 源码分析。
- 2.Retrofit用法 & 源码分析。
- 3.Volley用法 & 缺点。

### 4.3 依赖注入

- 1.ButterKnife用法 & 原理。
- 2.Dagger2用法 & 原理。

### 4.4 图片加载

- 1.Glide用法 & 原理。
- 2.Picasso用法 & 原理。
- 3.Fresco用法 & 原理。

### 4.5 数据库

- 1.GreenDao。
- 2.LitePal。
- 3.OrmLite。
- 4.DBFlow。
- 5.Realm。

### 4.6 其它

- 1.分享你觉得比较好用的开源库。
- 2.自己有封装库吗？给我说说你是如何设计的？
- 3.你是如何设计一个网络请求框架的？

## 5.计算机网络部分

- 1.给我介绍5层网络模型。
- 2.Http/Https协议工作在哪一层？
- 3.TCP/UDP协议工作在哪一层？
- 4.给我说说三次握手和四次挥手。
- 5.什么是请求头 & 响应头 ? 说说请求头中一些重要的字段。
- 6.什么是Cookie & Session & Token。
- 7.知道什么是心跳检测吗？
- 8.Http和Https的区别？
- 9.加密协议TLS/SSL加密过程是怎样的？
- 10.什么是DNS & 作用是什么 &工作机制？
- 11.浏览器访问一个url网址所经历的过程是什么？
- 12.Socket是协议吗？WebSocket是协议吗？它们的区别是什么？
- 13.Json解析方式有哪些？比较它们的优劣势。
- 14.XML解析方式有哪些？比较它们的优劣势。
- 15.http1.x & http 2.0区别是什么？
- 16.说说HTTP缓存的原理。
- 17.如果有个100M大的文件，需要上传至服务器中，而服务器form表单最大只能上传2M,可以使用什么方法？
- 18.说说你项目中即时通讯的方案有哪些？
- 19.为什么是三次握手而不是四次握手或者更多次呢？
- 20.用过哪些抓包工具？

------------------------------------------------------------------
文章整理：  
[亲爱的面试官，这个我可没看过！（Android部分）](https://www.jianshu.com/p/89f19d67b348)  
[Android大厂面试题锦集(BAT TMD JD 小米)](https://www.jianshu.com/p/cf5092fa2694)  
[最全的BAT大厂面试题整理](https://www.jianshu.com/p/c70989bd5f29)  
[我的 Android 开发实战经验总结](https://www.jianshu.com/p/4f152bc8f4f3)
                                                                                                                                                                                                 