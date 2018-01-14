# Coursera-OperatingSystems

## Week 12 Test

1. 在计算机系统拥有的各种软硬件资源中，内存是属于
 * **可重用资源**
 * 独占资源
 * 不可重用资源
 * 临界资源

2. 下列描述的各种现象中，属于活锁现象的是
 * 相关进程进入阻塞状态，且可以唤醒
 * 相关进程没有阻塞，但是调度时刻被延迟推后
 * **相关进程没有被阻塞，可被调度，但是执行没有进展**
 * 相关进程进入阻塞状态，且无法唤醒

3. 在系统运行过程中，通过检查系统是否处于安全状态而不让死锁发生的策略是
 * **死锁避免**
 * 死锁解除
 * 死锁检测
 * 死锁预防

4. 对资源采用按序分配策略能达到下列哪一个目的？
 * 死锁检测
 * **死锁预防**
 * 死锁解除
 * 死锁避免

5. 在下列解决死锁的方法中，属于死锁避免策略的是
 * 资源分配图化简法
 * **银行家算法**
 * 死锁检测算法
 * 资源有序分配法

6. 某计算机系统中有3个进程P1、P2和P3，3类资源r1、r2和r3。其中r1和r3每类资源只有1个，r2资源有2个，如图1所示。   
假设系统当前的资源分配如下：
![](https://d28rh4a8wq0iu5.cloudfront.net/os/images/%E5%9B%BE1.png?response-content-type=application%2Foctet-stream&a=1&response-content-disposition=attachment)
E={(P1，r1)，(P2，r3)，(r2，P1)，(r1，P2)，(r2，P2)，(r3，P3)}  
如果进程P3申请一个r2类资源，那么系统进入下列哪一种状态？
 * 无死锁
 * 饥饿
 * 活锁
 * **死锁**

7. 图2所示的十字路口死锁的情况可以采用多种方法进行预防。
![](https://d28rh4a8wq0iu5.cloudfront.net/os/images/%E5%9B%BE2.png?response-content-type=application%2Foctet-stream&a=1&response-content-disposition=attachment)
那么，使用交通红绿灯的方法破坏的是产生死锁的哪一个条件？
 * 资源独占条件
 * 不可抢占条件
 * **请求和保持条件**
 * 循环等待条件

8. 假设系统中有4个进程P1、P2、P3和P4，在某一时刻系统状态如下，其中，系统中剩余资源数量为1。
![](https://d28rh4a8wq0iu5.cloudfront.net/os/images/%E5%9B%BE3.png?response-content-type=application%2Foctet-stream&a=1&response-content-disposition=attachment)
该系统状态是安全状态，如果此时进程P3申请1个资源，分配后系统的状态是
 * 安全状态
 * 不安全状态
 * **死锁状态**
 * 临界状态

9. 系统有某类资源5个，供3个进程共享，每个进程最多申请多少个该类资源时系统仍然是安全的？
 * 1
 * 5
 * **2**
 * 3

10. 形成死锁的必要条件是
 * 资源的互斥使用
 * 系统资源不足
 * 进程对资源的申请形成环路
 * 不可剥夺已分配资源
 * 部分分配资源

11. 假设系统中有3种类型的资源（A，B，C）和5个进程P1、P2、P3、P4、P5。A资源的数量为17，B资源的数量为5，C资源的数量为20。在某一时刻系统状态如下表所示。那么，下列哪些进程执行序列是安全序列？
![](https://d28rh4a8wq0iu5.cloudfront.net/os/images/%E5%9B%BE4.png?response-content-type=application%2Foctet-stream&a=1&response-content-disposition=attachment)

A 2 B 3 C 3

P1 3 4 7

P2 1 3 4

P3 0 0 6

P4 2 2 1

P5 1 1 0

 * P1→P2→P3→P4→P5
 * P2→P3→P4→P5→P1
 * **P4→P3→P2→P5→P1**
 * **P5→P4→P3→P2→P1**
 * P4→P3→P2→P1→P5

12. 有两个线程P和Q，系统中有总量为M的资源。P和Q都需要使用这一资源来完成任务。其中，P的最大资源需求量为A，Q的最大资源需求量为B。直方图中，P轴和Q轴分别代表为P和Q分配的资源量。带圈的字符1、2、3、4所属的区域，代表着死锁检测中的状态。
![](https://d28rh4a8wq0iu5.cloudfront.net/os/images/%E5%9B%BE5.png?response-content-type=application%2Foctet-stream&a=1&response-content-disposition=attachment)
在图中，O1、O2点分别属于区域③、②。
 * 错
 * **对**

13. 在图中，O3点属于区域④。
 * **错**
 * 对

14. 在图中，边O1O2（不含两个端点）表示死锁状态。
 * 错
 * **对**

15. 解决经典的哲学家进餐问题时，若规定每个哲学家先取左边筷子、再取右边筷子，则可以避免死锁发生。
 * **错**
 * 对