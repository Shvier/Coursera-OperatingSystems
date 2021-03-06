# Coursera-OperatingSystems

## Week 11 Test

1. 下列I/O控制方式中，哪一个不需要硬件支持？
 * 中断方式
 * I/O处理机方式
 * **轮询方式**
 * DMA方式

2. 下列关于虚设备技术的叙述中，哪一个是错误的？
 * **通常采用虚设备技术是用低速设备来模拟高速设备**
 * SPOOLing技术是一类典型的虚设备技术
 * 虚设备技术是指在一类设备上模拟另一类设备的技术
 * 引入虚设备技术是为了提高设备利用率

3. 下列关于SPOOLing技术的叙述中，哪一个是错误的？
 * SPOOLing技术解决了独占设备利用率低的问题
 * **SPOOLing没有解决CPU的速度与设备速度的差异性**
 * SPOOLing技术需要利用磁盘空间作为缓冲
 * SPOOLing技术可用于打印机的管理

4. 在设备管理中，缓冲技术主要用于
 * **提高主机和设备交换信息的速度**
 * 提供内存与外存之间的接口
 * 扩充地址空间
 * 提高设备利用率

5. 下列关于I/O端口地址的叙述中，哪一个是错误的？
 * I/O独立编址方式需要特定的I/O指令
 * I/O端口地址是指设备接口寄存器的地址
 * 内存映像编址方式下I/O端口地址空间可以比较大
 * **内存映像编址方式下允许缓存设备接口寄存器的内容**

6. 下列关于操作系统设备管理的叙述中，哪些是正确的？
 * 操作系统应尽量对设备提供各种不同的接口
 * **设备管理利用各种技术提高CPU与设备、设备与设备之间的并行工作能力**
 * **操作系统对用户屏蔽了实现具体设备I/O操作的细节**
 * **设备管理使用户能独立于具体设备的复杂物理特性而方便地使用设备**
 * **SPOOLing技术是一类典型的虚拟设备技术**

7. 下列哪些方案可以提高I/O性能？
 * **缓冲技术**
 * 静态设备分配策略
 * **DMA方式**
 * **异步I/O方式**
 * 轮询方式

8. I/O设备的传输速率差异性、接口的复杂性等给操作系统设备管理带来复杂性。
 * **对**
 * 错

 
9. 利用设备内部的缓冲区可以进行数据格式加工等处理。
 * **对**
 * 错

10. 内存映像I/O模式下设备驱动程序可以用C语言编写。
 * **对**
 * 错

11. 通过把独占设备改造成**共享设备**，可以提高独占设备利用率

12. 通常按层次组织I/O软件，典型的四层I/O软件包括用户进程I/O、**设备独立性软件**、设备驱动程序和中断处理程序。

