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
| [2. Add Two Numbers](https://leetcode.com/problems/add-two-numbers/) | Medium | [2.md](solutions/2.md) | 链表-双链表-中等 | |
| [19. Remove Nth Node From End of List](https://leetcode.com/problems/remove-nth-node-from-end-of-list/) | Medium | [19.md](solutions/19.md) | 链表-单链表-中等 | 快慢指针实现单趟遍历 |
| [21. Merge Two Sorted Lists](https://leetcode.com/problems/merge-two-sorted-lists/) | Easy | [21.md](solutions/21.md) | 链表-双链表-简单 | |
| [23. Merge k Sorted Lists](https://leetcode.com/problems/merge-k-sorted-lists/) | Hard | [23.md](solutions/23.md) | 链表-双链表-困难 | |
| [24. Swap Nodes in Pairs](https://leetcode.com/problems/swap-nodes-in-pairs/) | Medium | [24.md](solutions/24.md) | 链表-单链表-中等 | |
| [25. Reverse Nodes in k-Group](https://leetcode.com/problems/reverse-nodes-in-k-group/) | Hard | [25.md](solutions/25.md) | 链表-单链表-困难 | |
| [61. Rotate List](https://leetcode.com/problems/rotate-list/) | Medium | [61.md](solutions/61.md) | 链表-单链表-中等 | |
| [82. Remove Duplicates from Sorted List II](https://leetcode.com/problems/remove-duplicates-from-sorted-list-ii/) | Medium | [82.md](solutions/82.md) | 链表-单链表-中等 | |
| [83. Remove Duplicates from Sorted List](https://leetcode.com/problems/remove-duplicates-from-sorted-list/) | Easy | [83.md](solutions/83.md) | 链表-单链表-简单 | |
| [86. Partition List](https://leetcode.com/problems/partition-list/) | Medium | [86.md](solutions/86.md) | 链表-单链表-中等 | |
| [92. Reverse Linked List II](https://leetcode.com/problems/reverse-linked-list-ii/) | Medium | [92.md](solutions/92.md) | 链表-单链表-中等 | |
| [94. Binary Tree Inorder Traversal](https://leetcode.com/problems/binary-tree-inorder-traversal/) | Easy | [94.md](solutions/94.md) | 树-遍历-简单 | |
| [101. Symmetric Tree](https://leetcode.com/problems/symmetric-tree/) | Easy | [101.md](solutions/101.md) | 树-路径 \| 深度 \| 翻转-简单 | |
| [102. Binary Tree Level Order Traversal](https://leetcode.com/problems/binary-tree-level-order-traversal/) | Medium | [102.md](solutions/102.md) | 树-遍历-中等 | |
| [103. Binary Tree Zigzag Level Order Traversal](https://leetcode.com/problems/binary-tree-zigzag-level-order-traversal/) | Medium | [103.md](solutions/103.md) | 树-遍历-中等 | |
| [104. Maximum Depth of Binary Tree](https://leetcode.com/problems/maximum-depth-of-binary-tree/) | Easy | [104.md](solutions/104.md) | 树-路径 \| 深度 \| 翻转-简单 | |
| [105. Construct Binary Tree from Preorder and Inorder Traversal](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/) | Medium | [105.md](solutions/105.md) | 树-构造-中等 | 前序中序构建 |
| [106. Construct Binary Tree from Inorder and Postorder Traversal](https://leetcode.com/problems/construct-binary-tree-from-inorder-and-postorder-traversal/) | Medium | [106.md](solutions/106.md) | 树-构造-中等 | 中序后序构建 |
| [107. Binary Tree Level Order Traversal II](https://leetcode.com/problems/binary-tree-level-order-traversal-ii/) | Medium | [107.md](solutions/107.md) | 树-遍历-中等 | |
| [108. Convert Sorted Array to Binary Search Tree](https://leetcode.com/problems/convert-sorted-array-to-binary-search-tree/) | Easy | [108.md](solutions/108.md) | 树-构造-简单 | |
| [109. Convert Sorted List to Binary Search Tree](https://leetcode.com/problems/convert-sorted-list-to-binary-search-tree/) | Medium | [109.md](solutions/109.md) | 链表-单链表-中等 | |
| [110. Balanced Binary Tree](https://leetcode.com/problems/balanced-binary-tree/) | Easy | [110.md](solutions/110.md) | 树-路径 \| 深度 \| 翻转-简单 | |
| [114. Flatten Binary Tree to Linked List](https://leetcode.com/problems/flatten-binary-tree-to-linked-list/) | Medium | [114.md](solutions/114.md) | 树-构造-中等 | |
| [138. Copy List with Random Pointer](https://leetcode.com/problems/copy-list-with-random-pointer/) | Medium | [138.md](solutions/138.md) | 链表-单链表-中等 | 新旧结点穿插 |
| [141. Linked List Cycle](https://leetcode.com/problems/linked-list-cycle/) | Easy | [141.md](solutions/141.md) | 链表-单链表-简单 | 快慢指针追逐 |
| [142. Linked List Cycle II](https://leetcode.com/problems/linked-list-cycle-ii/) | Medium | [142.md](solutions/142.md) | 链表-单链表-中等 | Floyd's Algorithm |
| [143. Reorder List](https://leetcode.com/problems/remove-element/) | Medium | [143.md](solutions/143.md) | 链表-单链表-中等 | |
| [144. Binary Tree Preorder Traversal](https://leetcode.com/problems/binary-tree-preorder-traversal/) | Easy | [144.md](solutions/144.md) | 树-遍历-简单 | |
| [145. Binary Tree Postorder Traversal](https://leetcode.com/problems/binary-tree-postorder-traversal/) | Easy | [145.md](solutions/145.md) | 树-遍历-简单 | |
| [147. Insertion Sort List](https://leetcode.com/problems/insertion-sort-list/) | Medium | [147.md](solutions/147.md) | 链表-单链表-中等 | |
| [148. Sort List](https://leetcode.com/problems/sort-list/) | Medium | [148.md](solutions/148.md) | 链表-单链表-中等 | 归并排序 |
| [160. Intersection of Two Linked Lists](https://leetcode.com/problems/intersection-of-two-linked-lists/) | Easy | [160.md](solutions/160.md) | 链表-双链表-简单 | 串接双链表 |
| [203. Remove Linked List Elements](https://leetcode.com/problems/remove-linked-list-elements/) | Easy | [203.md](solutions/203.md) | 链表-单链表-简单 | |
| [206. Reverse Linked List](https://leetcode.com/problems/reverse-linked-list/) | Easy | [206.md](solutions/206.md) | 链表-单链表-简单 | |
| [226. Invert Binary Tree](https://leetcode.com/problems/invert-binary-tree/) | Easy | [226.md](solutions/226.md) | 树-路径 \| 深度 \| 翻转-简单 | |
| [234. Palindrome Linked List](https://leetcode.com/problems/palindrome-linked-list/) | Easy | [234.md](solutions/234.md) | 链表-单链表-简单 | |
| [237. Delete Node in a Linked List](https://leetcode.com/problems/delete-node-in-a-linked-list/) | Easy | [237.md](solutions/237.md) | 链表-单链表-简单 | 题目表述有坑 |
| [257. Binary Tree Paths](https://leetcode.com/problems/binary-tree-paths/) | Easy | [257.md](solutions/257.md) | 树-路径 \| 深度 \| 翻转-简单 | |
| [328. Odd Even Linked List](https://leetcode.com/problems/odd-even-linked-list/) | Medium | [328.md](solutions/328.md) | 链表-单链表-中等 | |
| [430. Flatten a Multilevel Doubly Linked List](https://leetcode.com/problems/flatten-a-multilevel-doubly-linked-list/) | Medium | [430.md](solutions/430.md) | 链表-单链表-中等 | |
| [445. Add Two Numbers II](https://leetcode.com/problems/add-two-numbers-ii/) | Medium | [445.md](solutions/445.md) | 链表-双链表-中等 | |
| [543. Diameter of Binary Tree](https://leetcode.com/problems/diameter-of-binary-tree/) | Easy | [543.md](solutions/543.md) | 树-路径 \| 深度 \| 翻转-简单 | TBR |
| [589. N-ary Tree Preorder Traversal](https://leetcode.com/problems/n-ary-tree-preorder-traversal/) | Easy | [589.md](solutions/589.md) | 树-遍历-简单 | |
| [590. N-ary Tree Postorder Traversal](https://leetcode.com/problems/n-ary-tree-postorder-traversal/) | Easy | [590.md](solutions/590.md) | 树-遍历-简单 | |
| [707. Design Linked List](https://leetcode.com/problems/design-linked-list/) | Medium | [707.md](solutions/707.md) | 链表-单链表-中等 | |
| [725. Split Linked List in Parts](https://leetcode.com/problems/split-linked-list-in-parts/) | Medium | [725.md](solutions/725.md) | 链表-单链表-中等 | |
| [876. Middle of the Linked List](https://leetcode.com/problems/middle-of-the-linked-list/) | Easy | [876.md](solutions/876.md) | 链表-单链表-简单 | |
| [889. Construct Binary Tree from Preorder and Postorder Traversal](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-postorder-traversal/) | Medium | [889.md](solutions/889.md) | 树-构造-中等 | 前序后序创建 |
| [1008. Construct Binary Search Tree from Preorder Traversal](https://leetcode.com/problems/construct-binary-search-tree-from-preorder-traversal/) | Medium | [1008.md](solutions/1008.md) | 树-构造-中等 | |
| [1669. Merge In Between Linked Lists](https://leetcode.com/problems/merge-in-between-linked-lists/) | Medium | [1669.md](solutions/1669.md) | 链表-双链表-中等 | |

*：按照`xx-yy-zz`格式标注的分类标准，出自[Leetcode-retag](reference/Leetcode-retag.md)这里；其他的分类则是自己的补充

**：用到的特定罕见算法、难以想到的点、值得注意的语言特性、易错点、重大启发等；TBR表示To Be Reviewed，表示需要复习，待完善
