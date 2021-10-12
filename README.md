# Data Structures and Algorithms

[数据结构](./data_structures.md)
[算法](./algorithms.md)
[刷题路线](./leetcode.md)

## 数据结构算法脑图

![数据结构算法脑图](./resource/data_structures_and_algorithms.jpg)

## 数据结构算法入门

- 基础数据结构：数组、链表、栈、队列、散列表、二叉树、堆、跳表、图、Trie 树
- 基础算法：递归、排序、二分查找、搜索、哈希算法、贪心算法、分治算法、回溯算法、动态规划、字符串匹配算法

## 复杂度分析

### 一.时间复杂度

![时间复杂度公式](./resource/time_complexity.png)

大 O 时间复杂度实际上并不具体表示代码真正的执行时间，而是表示代码执行时间随数据规模增长的变化趋势，所以，也叫作渐进时间复杂度（asymptotic time complexity），简称时间复杂度

#### 1.时间复杂度量级

1. 常量阶 O(1)
1. 对数阶 O(log n)
1. 线性阶 O(n)
1. 线性对数阶 O(n logn)
1. 次方阶 O(n^2), O(n^3),....,O(n^k)
1. 指数阶 O(2^n)
1. 阶乘阶 O(n!)

> 量级分为: `多项式量级`(常量阶,对数阶,线性阶,线性对数阶,次方阶) `非多项式`(指数阶,阶乘阶)

![复杂度趋势图](./resource/complexity_type.jpg)

#### 2.时间复杂度分析

1. 只关注循环执行次数最多的一段代码

1. 加法法则：总复杂度等于量级最大的那段代码的复杂度

1. 乘法法则：嵌套代码的复杂度等于嵌套内外代码复杂度的乘积

### 二.空间复杂度

> 空间复杂度:`渐进空间复杂度`(asymptotic space complexity)表示`算法的存储空间与数据规模之间的增长关系`。
