# 字节跳动客户端一二面面经

{% embed url="https://www.nowcoder.com/discuss/415012" %}

## 4.21 下午4点 一面

1. 自我介绍 

2. 项目难点

3. Handler机制，Looper.loop会不会阻塞线程，为什么？

[答案](../../bytedance-collect/android.md#handler-ji-zhi-looperloop-hui-bu-hui-zu-sai-xian-cheng-wei-shen-me)

4. gc算法，收集器，stop the world

5. jvm内存区域，为什么要有jvm，我答的是为了隔离物理存储，方便移植，面试官又问会不会影响效率，答会影响，接着问怎么优化 😂，我枯了

6. 进程和线程的区别

7. 框架源码（没看过，不会），**eventbus**有哪些缺点，什么类可以作为event，为什么不用广播

8. 设计模式

9. 手写**单例**

10. 类加载过程，我扯到了invokestatic，面试官问什么时候调用？我答在调用静态方法时调用

11. **dex**了解吗？我答只知道65535，了解类的编译过程吗，不了解；知道源文件编译成什么吗？class文件；为什么要有dex？在dex做了优化；哪些优化？不了解

12. dalvik和hotspot虚拟机了解吗，不了解

13. 异常体系，可以catch error吗？我不确定，面完之后测试了，catch可以捕获thowable，所以可以catch error

13. 算法：

反转链表；

反转指定区间的链表

需要自定义节点，处理输入输出



一面记得的 内容大致就这些了，顺序记不清

下午6点多打来电话，约的第二天下午2点二面



## 4.22 下午2点 二面

1. 上来先强调了面试纪律，不能作弊（我可是四有青年😀）

2. 自我介绍

3. 项目中用到了哪些技术，除了框架

4. 我做的是音乐播放器，所以面试官问音乐播放在哪里实现，activity还是**service**，用thread可以吗？为什么？

5. 我简历中写到了做人脸识别，他就问有哪些网络，有哪些改进，GAN了解吗？（我又枯了）

6. 为什么有多进程也有多线程？我扯到了虚拟内存空间，面试官就问为什么要这样设计？解决什么问题？**分段和分页**有什么区别？（我的OS都还给老师了😰）

7. http和https区别，**CA证书怎么生成**，怎么保证安全，加密过程，对称加密怎么保证安全？

8. 抽象类和接口

9. **多态**，有哪些实现

10. 算法：求二叉树叶子节点之间的最长路径，没有思路，面试官慢慢引导，最后有了思路，还没写完，面试官就说结束了



面完到现在都没消息，估计是凉了吧，感觉抖音团队面试难度明显比其他团队高，我也太菜了，希望能有三面吧



4.28 问了hr，已经凉了，唉，到现在还是0offer，太难了
