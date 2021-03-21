# 学习日记

<details>
<summary>2021.03.09 : </summary>


- 某司waf功能分析，寻找攻击面
- 复习之前做过的虚拟化相关ctf题，以及几道与kvm虚拟机、ptrace实现的沙盒、printf实现的虚拟机相关的题
- rust 所有权、引用与借用、slices 部分知识的学习
- unix 环境高级编程阅读线程一章的线程同步一节，这一节主要包含了互斥量、锁机制、临界区等知识
- 由于白天的大部分时间都需要放在第一件事上，所以计划周六周日来补充unix以及rust的笔记

</details>


<details>
<summary>2021.03.10 : </summary>


- 今天没什么进度，停下来思考了一天

</details>


<details>
<summary>2021.03.11 : </summary>


- rust 5、6、7、8、9章的学习，rust的错误处理比C好用很多，C需要弄一堆分支来输出的错误信息，rust仅仅只需要一行即可完成，爱了爱了
- rustlings 项目的if、move\_semantics、primitive\_types、structs、variables、quiz1、function小节的内容做完了

</details>                                                                                                


<details>
<summary>2021.03.12 : </summary>


- unix 环境高级编程多线程部分的学习，做了几道和多线程有关的题，对于多线程初窥门径 
- 尝试用rust出一道逆向的题 

</details>

<details>
<summary>2021.03.13 : </summary>


- 找了一天的招聘信息，但是没有什么合适的岗位，有些想放弃安研转方向的想法

</details>


<details>
<summary>2021.03.14 : </summary>


- unix 环境高级编程第12章线程控制备份的内容学习，写了一些个demo，发现多线程相关的特性也是比较多的，但是这些api虽然知道了，但是实际上的应用场景还不是很了解，后面需要多coding
- unix 网络编程第一卷，现在看的都是为了补自己之前计网的知识，看了第一章，第一章主要内容是关于linux的一些简单内容，还有一个从获取服务器时间的客户端以及服务端程序demo，了解了一下基本的流程是什么，客户端会首先创建一个sockaddr\_in结构用于指明交互的端口以及ip地址，然后做一些跟格式有关的操作，最后建立连接即可，此时如果连接成功了的话会返回一个描述符，读取这个描述符就可以接收到从服务器发送过来的数据了，服务端和客户端操作差不多，只不过最后连接成功服务端是进行写操作来写描述符，这时服务器就可以把数据发送到客户端了
- 计算机网络自顶向下阅读第一章
- 继续使用rust出一道迷宫题，主要思路是先生成一个伪迷宫，然后通过一些变换才可以得到真正的迷宫，之后就是正常的走迷宫即可

</details>

<details>
<summary>2021.03.15 : </summary>


- java 阅读java相关的内容,head first java 看到第4章,敲了些代码

</details>

<details>
<summary>2021.03.16 : </summary>


- 继续java相关内容的学习,head first java 上面的内容比较简单,很多东西没有讲到,所以更换了另一个学习的资料,继续敲代码熟悉java

</details>

<details>
<summary>2021.03.17 : </summary>


- java的学习,主要是围绕着之前head first java上面没涉及到的东西,白天课上的效率不高
- HTTP协议相关知识学习,主要通过阅读图解HTTP来学习,对网络相关的知识又了解了一些

</details>

<details>
<summary>2021.03.18 : </summary>


- java相关的学习,用java做了几道算法题,学习效率不高

</details>

<details>
<summary>2021.03.19 : </summary>


- 主要和另一名小伙伴进行了交流,对于之后的道路的一些想法

</details>

<details>
<summary>2021.03.20 : </summary>


- 摸了一天鱼,看了一些数据结构相关的内容

</details>

<details>
<summary>2021.03.21 : </summary>


- leetcode 刷题,补数据结构与算法的知识,读了读OI WIKI,发现OI WIKI上面涉及到的东西过多,而且有些过于深入,有些数据结构并没有很好的讲述出具体的应用场景,如果说不打OJ而对于面试来说搞明白基本的数据结构即可,算法也是学会基本算法即可,过深的算法可以以后来进行补习
- 继续阅读图解HTTP并记录相关章节的笔记

</details>