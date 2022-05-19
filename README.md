# Android_Learner
Android成长笔记

一、Java

1、Java数据结构

java hashmap https://www.jianshu.com/p/dde9b12343c1

java LinkedHashMap https://www.jianshu.com/p/8f4f58b4b8ab

红黑树 https://blog.csdn.net/u011240877/article/details/53329023

红黑树 https://blog.csdn.net/21aspnet/article/details/88939297

haspmap 和红黑树 https://blog.csdn.net/wushiwude/article/details/75331926

2、Java并发

java 线程池  https://blog.csdn.net/ye17186/article/details/89467919

Java 锁 https://tech.meituan.com/2018/11/15/java-lock.html

Java 并发和锁 https://juejin.cn/post/6844904036026548237

Java 死锁 https://www.cnblogs.com/xiaoxi/p/8311034.html

并发 cas 无锁自增原理https://ld246.com/article/1543212684107

cas https://cloud.tencent.com/developer/article/1656853

LOCK源码分析 https://juejin.cn/post/6844904152183603213

AQS https://tech.meituan.com/2019/12/05/aqs-theory-and-apply.html

锁汇总归纳 https://blog.csdn.net/weixin_36393718/article/details/112071591

锁总结分类 https://mp.weixin.qq.com/s?__biz=MjM5NjQ5MTI5OA==&mid=2651749434&idx=3&sn=5ffa63ad47fe166f2f1a9f604ed10091&chksm=bd12a5778a652c61509d9e718ab086ff27ad8768586ea9b38c3dcf9e017a8e49bcae3df9bcc8&scene=38#wechat_redirect
volotile https://www.cnblogs.com/paddix/p/5428507.html

3、Java内存

内存 和GC https://www.infoq.cn/article/3wyretkqrhivtw4frmr3

java 引用 https://juejin.cn/post/6844903440682844174

jvm 内存https://www.huaweicloud.com/articles/4799df506d5b9ae8bd0a5cb5247723b5.html

4、注解

apt https://www.jianshu.com/p/9616f4a462bd

5、jni

jni 内存 https://www.jianshu.com/p/d77ffc785303

jni内存管理 https://juejin.cn/post/6844903743352209422

6、Java源码解读

Java全栈知识体系  https://pdai.tech/md/java/thread/java-thread-x-juc-executor-ThreadPoolExecutor.html

二、Android

1、view体系

view 事件冲突 https://blog.csdn.net/chuhe1989/article/details/105933963

view事件体系 https://blog.yorek.xyz/android/framework/View%E7%9A%84%E4%BA%8B%E4%BB%B6%E4%BD%93%E7%B3%BB/#423-view

viewRoot https://cloud.tencent.com/developer/article/1771047

viewroot https://wizardforcel.gitbooks.io/deepin-android-vol3/content/6.html

window、view https://wizardforcel.gitbooks.io/deepin-android-vol3/content/4.html

2、跨进程

binder https://zhuanlan.zhihu.com/p/35519585

3、图片处理

图片处理细节  https://www.jianshu.com/p/0f56f35068e2

图片压缩方法  https://blog.csdn.net/qq_30379689/article/details/78884167

图片所占内存大小的计算  https://juejin.cn/post/6844903693230276616

4、framework解读

wms https://wizardforcel.gitbooks.io/deepin-android-vol3/content/4.html

ams  https://zhuanlan.zhihu.com/p/86266649

5、handler

handler postdelay 解读 https://zhuanlan.zhihu.com/p/260661053#:~:text=%E8%BF%99%E9%87%8C%E6%88%91%E4%BB%AC%E4%B8%BB%E8%A6%81%E6%9D%A5%E5%85%B3%E6%B3%A8%E6%9C%80%E5%90%8E%E4%B8%80%E7%A7%8D%E6%96%B9%E6%B3%95%EF%BC%8C%E4%BD%BF%E7%94%A8%20Handler%E7%9A%84postDelayed%20%E6%96%B9%E6%B3%95%E6%9D%A5%E5%A4%84%E7%90%86%E5%BB%B6%E6%97%B6%EF%BC%9A%20new%20Handler%28%29.postDelayed%28new%20Runnable%28%29%20%7B%20%40Override,%7B%20%2F%2F%E5%BB%B6%E6%97%B6%E5%88%B0%E4%BA%86%E7%9A%84%E6%93%8D%E4%BD%9C%20%7D%20%7D%2C%201000%29%3B%2F%2F%E6%AF%AB%E7%A7%92%20%E8%BF%99%E9%87%8C%E5%B0%B1%E5%BE%88%E7%AE%80%E5%8D%95%E7%9A%84%E5%AE%9E%E7%8E%B0%E4%BA%86%E4%B8%80%E4%B8%AA%201%E7%A7%92%20%E7%9A%84%E5%BB%B6%E6%97%B6%EF%BC%8C%E4%B8%94%E4%B8%8D%E4%BC%9A%E9%98%BB%E5%A1%9E%E4%B8%BB%E7%BA%BF%E7%A8%8B%E3%80%82

handler nativepoll https://www.cnblogs.com/jiy-for-you/p/11707356.html#:~:text=nativePollOnce%E5%92%8C%20nativeWake%E7%9A%84%E6%A0%B8%E5%BF%83%E9%AD%94%E6%9C%AF%E5%8F%91%E7%94%9F%E5%9C%A8%20native%20%E4%BB%A3%E7%A0%81%E4%B8%AD.%20native%20MessageQueue%E5%88%A9%E7%94%A8%E5%90%8D%E4%B8%BA%20epoll%E7%9A%84%20Linux,%E4%BA%8B%E4%BB%B6.%20nativePollOnce%E5%9C%A8%E6%9F%90%E4%B8%AA%E6%96%87%E4%BB%B6%E6%8F%8F%E8%BF%B0%E7%AC%A6%E4%B8%8A%E8%B0%83%E7%94%A8%20epoll_wait%2C%20%E8%80%8C%20nativeWake%E5%86%99%E5%85%A5%E4%B8%80%E4%B8%AA%20IO%20%E6%93%8D%E4%BD%9C%E5%88%B0%E6%8F%8F%E8%BF%B0%E7%AC%A6%2C%20epoll_wait%E7%AD%89%E5%BE%85.

6、性能优化和架构

Android 性能优化 https://github.com/Timdk857/Android-Architecture-knowledge-2-/blob/master/%E9%9D%A2%E8%AF%95%E9%A2%98/Android%E9%AB%98%E7%BA%A7%E9%9D%A2%E8%AF%95%E9%A2%98.md

组件化通讯 https://www.jianshu.com/p/9cf03cff0f0f

三、三方框架

1、okhttp

okhttp  https://www.bookstack.cn/read/Android-Interview/%E6%BA%90%E7%A0%81%E5%88%86%E6%9E%90-okhttp%E5%86%85%E6%A0%B8%E5%89%96%E6%9E%90.md

okhttp  https://cloud.tencent.com/developer/article/1601358

okhttp https://www.cnblogs.com/jimuzz/p/13935677.html

okhttp https://cloud.tencent.com/developer/article/1601358

2、retrofit

retrofit https://www.jianshu.com/p/45cb536be2f4

retrofit 设计模式 https://www.jianshu.com/p/fb8d21978e38

3、rxjava 

rxjava 面试一 https://juejin.cn/post/6900870262062120967

Rxjava 面试二  https://juejin.cn/post/6905725515521835015

4、图片框架

glide、fresco https://cloud.tencent.com/developer/article/1385853

四、计算机基础

1、网络

tcp https://mp.weixin.qq.com/s?__biz=MzUxMjEyNDgyNw==&mid=2247489273&idx=2&sn=b689b37bb4905af206074f7a8e8b5a0e&chksm=f968640dce1fed1b77764dbdefd6a1408c20c18d8a0920a7317642577ae9955a29fae7f8f9c6&mpshare=1&scene=1&srcid=07052oJfOEMLCVyB8Q8dDhvp&sharer_sharetime=1625466717539&sharer_shareid=14fac18fb904b36ad70e54956b91824a&version=3.1.8.70033&platform=mac#rd

通俗易懂的tcp http://www.52im.net/forum.php?mod=viewthread&tid=515

https https://zhuanlan.zhihu.com/p/43789231

ssl/tsl https://segmentfault.com/a/1190000021559557

三、知识点总结引导

大牛知识点总结 https://www.kancloud.cn/aslai/interview-guide/1113683

大牛知识点总结 https://blog.yorek.xyz/android/framework/View%E7%9A%84%E7%BB%98%E5%88%B6%E5%8E%9F%E7%90%86/

面经整理 https://www.nowcoder.com/discuss/582808?source_id=discuss_experience_nctrack&channel=-1

github 知识整理 https://github.com/Timdk857/Android-Architecture-knowledge-2-

面试题目录大纲  https://www.nowcoder.com/discuss/578600?source_id=discuss_experience_nctrack&channel=-1
