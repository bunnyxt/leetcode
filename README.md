# 介绍

bunnyxt的LeetCode题解，使用Python3编码

# 一些资料

## 高频题分类顺序表

出处：[Leetcode-retag](https://github.com/resumejob/Leetcode-retag/blob/4a5587e994c326963dda445ac55cca2fb9dc597e/README.md)，推荐按照这里的分类与顺序依次练习。

备份：[Leetcode-retag.md](reference/Leetcode-retag.md)，修复了目录链接，并将题目链接改为国际版链接

## 完整题库

出处：[完整 LeetCode 题库分享，含频次，标签，面试公司等信息](https://www.1point3acres.com/bbs/thread-774337-1-1.html)，面试之前可以根据公司筛选，有针对地刷题。

备份：[LeetCode.xlsx](reference/LeetCode.xlsx)

# 实用技巧

## Python刷题实用技巧

虽然本人之前参加算法竞赛都是用的C/C++，个人主要职业方向是前端/全栈开发，但考虑到自己之前对Python的熟练度较高（不希望因为语言的熟练度不够从而影响刷题效率，刚准备刷题的时候手头确实Python熟练很多），再加上Python语言本身的一些很诱人的特性，个人觉得很适合拿Python来刷LeetCode，因此初刷使用的语言是Python。这里总结了一些刷题时会用到的Python技巧，包括：

```
// TODO  整理一些Python技巧，主要涉及到排序、数据结构、字符串处理、数组（列表）构建与初始化等，放在skills/python中
```

## JavaScript不比Python差

```
// TODO  等我第二轮开始刷250题的时候用JS（ES6）刷再来写这个部分，主要描述Python与JavaScript构建算法代码的区别，Python里的一些代码片段在JavaScript中的实现方式，以及JavaScript中独有的实用技巧，放在skills/javascript中
```

# 算法专题

```
// TODO
```

# 所有题解

本题解库里所有的题解目录，按照题号从小到大排序，并且标记上题目考察的算法等，完整列表如下：

| 题目 | 难度 | 题解 | 分类* | 备注** |
| --- | --- | --- | --- | --- |
| [19. Remove Nth Node From End of List](https://leetcode.com/problems/remove-nth-node-from-end-of-list/) | Medium | [19.md](solutions/19.md) | 链表-单链表-中等 | 快慢指针实现单趟遍历 |
| [21. Merge Two Sorted Lists](https://leetcode.com/problems/merge-two-sorted-lists/) | Easy | [21.md](solutions/21.md) | 链表-双链表-简单 | |
| [24. Swap Nodes in Pairs](https://leetcode.com/problems/swap-nodes-in-pairs/) | Easy | [24.md](solutions/24.md) | 链表-双链表-中等 | |
| [61. Rotate List](https://leetcode.com/problems/rotate-list/) | Medium | [61.md](solutions/61.md) | 链表-单链表-中等 | |
| [82. Remove Duplicates from Sorted List II](https://leetcode.com/problems/remove-duplicates-from-sorted-list-ii/) | Medium | [82.md](solutions/82.md) | 链表-单链表-中等 | |
| [83. Remove Duplicates from Sorted List](https://leetcode.com/problems/remove-duplicates-from-sorted-list/) | Easy | [83.md](solutions/83.md) | 链表-单链表-简单 | |
| [86. Partition List](https://leetcode.com/problems/partition-list/) | Medium | [86.md](solutions/86.md) | 链表-单链表-中等 | |
| [92. Reverse Linked List II](https://leetcode.com/problems/reverse-linked-list-ii/) | Medium | [92.md](solutions/92.md) | 链表-单链表-中等 | |
| [138. Copy List with Random Pointer](https://leetcode.com/problems/copy-list-with-random-pointer/) | Medium | [138.md](solutions/138.md) | 链表-单链表-中等 | 新旧结点穿插 |
| [141. Linked List Cycle](https://leetcode.com/problems/linked-list-cycle/) | Easy | [141.md](solutions/141.md) | 链表-单链表-简单 | 快慢指针追逐 |
| [142. Linked List Cycle II](https://leetcode.com/problems/linked-list-cycle-ii/) | Medium | [142.md](solutions/142.md) | 链表-单链表-中等 | Floyd's Algorithm |
| [143. Reorder List](https://leetcode.com/problems/remove-element/) | Medium | [143.md](solutions/143.md) | 链表-单链表-中等 | |
| [147. Insertion Sort List](https://leetcode.com/problems/insertion-sort-list/) | Medium | [147.md](solutions/147.md) | 链表-单链表-中等 | |
| [148. Sort List](https://leetcode.com/problems/sort-list/) | Medium | [148.md](solutions/148.md) | 链表-单链表-中等 | 归并排序 |
| [203. Remove Linked List Elements](https://leetcode.com/problems/remove-linked-list-elements/) | Easy | [203.md](solutions/203.md) | 链表-单链表-简单 | |
| [206. Reverse Linked List](https://leetcode.com/problems/reverse-linked-list/) | Easy | [206.md](solutions/206.md) | 链表-单链表-简单 | |
| [234. Palindrome Linked List](https://leetcode.com/problems/palindrome-linked-list/) | Easy | [234.md](solutions/234.md) | 链表-单链表-简单 | |
| [237. Delete Node in a Linked List](https://leetcode.com/problems/delete-node-in-a-linked-list/) | Easy | [237.md](solutions/237.md) | 链表-单链表-简单 | 题目表述有坑 |
| [876. Middle of the Linked List](https://leetcode.com/problems/middle-of-the-linked-list/) | Easy | [876.md](solutions/876.md) | 链表-单链表-简单 | |

*：按照`xx-yy-zz`格式标注的分类标准，出自[Leetcode-retag](reference/Leetcode-retag.md)这里；其他的分类则是自己的补充

**：用到的特定罕见算法、难以想到的点、值得注意的语言特性、易错点、重大启发等
