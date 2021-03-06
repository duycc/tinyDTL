该仓库主要使用C++语言实现各种数据结构以及常用算法总结，暂时没有时间，后续复习数据结构时会一并完成。



> **个人LeetCode刷题笔记：[leetcode](https://github.com/duycc/leetcode)**



## 一、基础数据结构



## 二、常用算法

### [排序算法](https://blog.csdn.net/weixin_42482896/article/details/114296302?spm=1001.2014.3001.5501)

* 各排序算法实现：[sort.hpp](algorithm/sort.hpp)

| 排序算法 | 平均时间复杂度        | 最差时间复杂度        | 空间复杂度          | 数据对象稳定性       |
| -------- | --------------------- | --------------------- | ------------------- | -------------------- |
| 冒泡排序 | O(n<sup>2</sup>)      | O(n<sup>2</sup>)      | O(1)                | 稳定                 |
| 选择排序 | O(n<sup>2</sup>)      | O(n<sup>2</sup>)      | O(1)                | 数组不稳定、链表稳定 |
| 插入排序 | O(n<sup>2</sup>)      | O(n<sup>2</sup>)      | O(1)                | 稳定                 |
| 快速排序 | O(n*log<sub>2</sub>n) | O(n<sup>2</sup>)      | O(log<sub>2</sub>n) | 不稳定               |
| 堆排序   | O(n*log<sub>2</sub>n) | O(n*log<sub>2</sub>n) | O(1)                | 不稳定               |
| 归并排序 | O(n*log<sub>2</sub>n) | O(n*log<sub>2</sub>n) | O(n)                | 稳定                 |
| 希尔排序 | O(n*log<sup>2</sup>n) | O(n<sup>2</sup>)      | O(1)                | 不稳定               |
| 计数排序 | O(n+m)                | O(n+m)                | O(n+m)              | 稳定                 |
| 桶排序   | O(n)                  | O(n)                  | O(m)                | 稳定                 |
| 基数排序 | O(k*n)                | O(n<sup>2</sup>)      |                     | 稳定                 |

> * 均按从小到大排列
> * k：代表数值中的 “数位” 个数
> * n：代表数据规模
> * m：代表数据的最大值减最小值

### 查找算法

| 查找算法     | 平均时间复杂度                         | 空间复杂度 | 查找条件   |
| ------------ | -------------------------------------- | ---------- | ---------- |
| 顺序查找     | O(n)                                   | O(1)       | 无序或有序 |
| 二分查找     | O(log<sub>2</sub>n)                    | O(1)       | 有序       |
| 插值查找     | O(log<sub>2</sub>(log<sub>2</sub>n))   | O(1)       | 有序       |
| 斐波那契查找 | O(log<sub>2</sub>n)                    | O(1)       | 有序       |
| 哈希查找     | O(1)                                   | O(n)       | 无序或有序 |
| 二叉查找树   | O(log<sub>2</sub>n)                    |            |            |
| 红黑树       | O(log<sub>2</sub>n)                    |            |            |
| 2-3树        | O(log<sub>2</sub>n - log<sub>3</sub>n) |            |            |
| B树/B+树     | O(log<sub>2</sub>n)                    |            |            |

### 贪婪算法



### 分而治之



### 动态规划



### 回溯法



### 分支定界

