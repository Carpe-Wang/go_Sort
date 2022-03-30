# go_Sort
go语言的基础排序算法和二叉查找树


# 快速排序算法

是对插入算法的一种优化，利用对问题的二分化，实现递归完成快速排序，在所有算法中二分化是最常用的方式，将问题尽量的分成两种情况加以分析，最终以形成类似树的方式加以利用，因为在比较模型中的算法中，最快的排序时间负载度为 O(nlgn).

```步骤```：

将数据根据一个值按照大小分成左右两边，左边小于此值，右边大于

将两边数据进行递归调用步骤1

将所有数据合并


# 堆排序算法
首先建一个堆，然后调整堆，调整过程是将节点和子节点进行比较，将其中最大的值变为父节点，递归调整调整次数lgn,最后将根节点和尾节点交换再n次调整O(nlgn).

```步骤```：

创建最大堆或者最小堆（我是最小堆）

调整堆

交换首尾节点(为了维持一个完全二叉树才要进行收尾交换)


# 冒泡排序算法

没啥可说的，循环

# 二分查找方法

在一组有序数组中，将数组一分为二，将要查询的元素和分割点进行比较，分为三种情况


```步骤```：
相等直接返回

元素大于分割点，在分割点右侧继续查找

元素小于分割点，在分割点左侧继续查找