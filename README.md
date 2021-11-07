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
| [1. Two Sum](https://leetcode.com/problems/two-sum/) | Easy | [1.md](solutions/1.md) | Hash-Table | |
| [2. Add Two Numbers](https://leetcode.com/problems/add-two-numbers/) | Medium | [2.md](solutions/2.md) | 链表-双链表-中等 | |
| [5. Longest Palindromic Substring](https://leetcode.com/problems/longest-palindromic-substring/) | Medium | [5.md](solutions/5.md) | 动态规划-二维-中等 DP | TBR |
| [15. 3Sum](https://leetcode.com/problems/3sum/) | Medium | [15.md](solutions/15.md) | Two-Pointers | |
| [16. 3Sum Closest](https://leetcode.com/problems/3sum-closest/) | Medium | [16.md](solutions/16.md) | 双指针与滑动窗口-中等 Two-Pointers | |
| [17. Letter Combinations of a Phone Number](https://leetcode.com/problems/letter-combinations-of-a-phone-number/) | Medium | [17.md](solutions/17.md) | 回溯-中等 | |
| [18. 4Sum](https://leetcode.com/problems/4sum/) | Medium | [18.md](solutions/18.md) | 双指针与滑动窗口-中等 Two-Pointers | |
| [19. Remove Nth Node From End of List](https://leetcode.com/problems/remove-nth-node-from-end-of-list/) | Medium | [19.md](solutions/19.md) | 链表-单链表-中等 | 快慢指针实现单趟遍历 |
| [20. Valid Parentheses](https://leetcode.com/problems/valid-parentheses/) | Easy | [20.md](solutions/20.md) | 栈-基础栈-简单 | |
| [21. Merge Two Sorted Lists](https://leetcode.com/problems/merge-two-sorted-lists/) | Easy | [21.md](solutions/21.md) | 链表-双链表-简单 | |
| [22. Generate Parentheses](https://leetcode.com/problems/generate-parentheses/) | Medium | [22.md](solutions/22.md) | 回溯-中等 | |
| [23. Merge k Sorted Lists](https://leetcode.com/problems/merge-k-sorted-lists/) | Hard | [23.md](solutions/23.md) | 链表-双链表-困难 | |
| [24. Swap Nodes in Pairs](https://leetcode.com/problems/swap-nodes-in-pairs/) | Medium | [24.md](solutions/24.md) | 链表-单链表-中等 | |
| [25. Reverse Nodes in k-Group](https://leetcode.com/problems/reverse-nodes-in-k-group/) | Hard | [25.md](solutions/25.md) | 链表-单链表-困难 | |
| [37. Sudoku Solver](https://leetcode.com/problems/sudoku-solver/) | Hard | [37.md](solutions/37.md) | 回溯-困难 | |
| [39. Combination Sum](https://leetcode.com/problems/combination-sum/) | Medium | [39.md](solutions/39.md) | 回溯-中等 | |
| [40. Combination Sum II](https://leetcode.com/problems/combination-sum-ii/) | Medium | [40.md](solutions/40.md) | 回溯-中等 | |
| [42. Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water/) | Hard | [42.md](solutions/42.md) | 栈-单调栈-困难 Monotonic-Stack,Two-Pointers | |
| [43. Multiply Strings](https://leetcode.com/problems/multiply-strings/) | Easy | [43.md](solutions/43.md) | | |
| [45. Jump Game II](https://leetcode.com/problems/jump-game-ii/) | Medium | [45.md](solutions/45.md) | Greedy | |
| [46. Permutations](https://leetcode.com/problems/permutations/) | Medium | [46.md](solutions/46.md) | 回溯-中等 | |
| [47. Permutations II](https://leetcode.com/problems/permutations-ii/) | Medium | [47.md](solutions/47.md) | 回溯-中等 | |
| [51. N-Queens](https://leetcode.com/problems/n-queens/) | Hard | [51.md](solutions/51.md) | 回溯-困难 Backtracking | |
| [52. N-Queens II](https://leetcode.com/problems/n-queens-ii/) | Hard | [52.md](solutions/52.md) | Backtracking | |
| [53. Maximum Subarray](https://leetcode.com/problems/maximum-subarray/) | Easy | [53.md](solutions/53.md) | 动态规划-一维-简单 | Kadane's Algorithm |
| [55. Jump Game](https://leetcode.com/problems/jump-game/) | Medium | [55.md](solutions/55.md) | Greedy | |
| [61. Rotate List](https://leetcode.com/problems/rotate-list/) | Medium | [61.md](solutions/61.md) | 链表-单链表-中等 | |
| [62. Unique Paths](https://leetcode.com/problems/unique-paths/) | Medium | [62.md](solutions/62.md) | 动态规划-二维-中等 DP | |
| [63. Unique Paths II](https://leetcode.com/problems/unique-paths-ii/) | Medium | [63.md](solutions/63.md) | DP | |
| [64. Minimum Path Sum](https://leetcode.com/problems/minimum-path-sum/) | Medium | [64.md](solutions/64.md) | 动态规划-二维-中等 DP | |
| [70. Climbing Stairs](https://leetcode.com/problems/climbing-stairs/) | Easy | [70.md](solutions/70.md) | 动态规划-一维-简单 DP | |
| [71. Simplify Path](https://leetcode.com/problems/simplify-path/)  | Medium | [71.md](solutions/71.md) | 栈-基础栈-中等 | |
| [77. Combinations](https://leetcode.com/problems/combinations/) | Medium | [77.md](solutions/77.md) | 回溯-中等 | |
| [78. Subsets](https://leetcode.com/problems/subsets/) | Medium | [78.md](solutions/78.md) | 回溯-中等 | |
| [79. Word Search](https://leetcode.com/problems/word-search/) | Medium | [79.md](solutions/79.md) | 回溯-中等 | |
| [82. Remove Duplicates from Sorted List II](https://leetcode.com/problems/remove-duplicates-from-sorted-list-ii/) | Medium | [82.md](solutions/82.md) | 链表-单链表-中等 | |
| [83. Remove Duplicates from Sorted List](https://leetcode.com/problems/remove-duplicates-from-sorted-list/) | Easy | [83.md](solutions/83.md) | 链表-单链表-简单 | |
| [86. Partition List](https://leetcode.com/problems/partition-list/) | Medium | [86.md](solutions/86.md) | 链表-单链表-中等 | |
| [89. Gray Code](https://leetcode.com/problems/gray-code/) | Medium | [89.md](solutions/89.md) | 回溯-中等 | |
| [90. Subsets II](https://leetcode.com/problems/subsets-ii/) | Medium | [90.md](solutions/90.md) | 回溯-中等 | |
| [91. Decode Ways](https://leetcode.com/problems/decode-ways/) | Medium | [91.md](solutions/91.md) | DP | |
| [92. Reverse Linked List II](https://leetcode.com/problems/reverse-linked-list-ii/) | Medium | [92.md](solutions/92.md) | 链表-单链表-中等 | |
| [93. Restore IP Addresses](https://leetcode.com/problems/restore-ip-addresses/) | Medium | [93.md](solutions/93.md) | 回溯-中等 | |
| [94. Binary Tree Inorder Traversal](https://leetcode.com/problems/binary-tree-inorder-traversal/) | Easy | [94.md](solutions/94.md) | 树-遍历-简单 | |
| [95. Unique Binary Search Trees II](https://leetcode.com/problems/unique-binary-search-trees-ii/) | Medium | [95.md](solutions/95.md) | 树-二叉搜索树-中等 | |
| [96. Unique Binary Search Trees](https://leetcode.com/problems/unique-binary-search-trees/) | Medium | [96.md](solutions/96.md) | 树-二叉搜索树-中等 DP | DP |
| [97. Interleaving String](https://leetcode.com/problems/interleaving-string/) | Medium | [97.md](solutions/97.md) | BFS | TBR |
| [98. Validate Binary Search Tree](https://leetcode.com/problems/validate-binary-search-tree/) | Medium | [98.md](solutions/98.md) | 树-二叉搜索树-中等 | 二叉搜索树的中序遍历序列有序 |
| [99. Recover Binary Search Tree](https://leetcode.com/problems/recover-binary-search-tree/) | Medium | [99.md](solutions/99.md) | 树-二叉搜索树-中等 | 定位交换点，递归/迭代/Morris中序遍历，TBR |
| [100. Same Tree](https://leetcode.com/problems/same-tree/) | Easy | [100.md](solutions/100.md) | 树-路径 \| 深度 \| 翻转-简单 | |
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
| [111. Minimum Depth of Binary Tree](https://leetcode.com/problems/remove-element/) | Easy | [111.md](solutions/111.md) | 树-路径 \| 深度 \| 翻转-简单 | |
| [112. Path Sum](https://leetcode.com/problems/path-sum/) | Easy | [112.md](solutions/112.md) | 树-路径 \| 深度 \| 翻转-简单 | |
| [113. Path Sum II](https://leetcode.com/problems/path-sum-ii/) | Medium | [113.md](solutions/113.md) | 树-路径 \| 深度 \| 翻转-中等 | |
| [114. Flatten Binary Tree to Linked List](https://leetcode.com/problems/flatten-binary-tree-to-linked-list/) | Medium | [114.md](solutions/114.md) | 树-构造-中等 | |
| [116. Populating Next Right Pointers in Each Node](https://leetcode.com/problems/populating-next-right-pointers-in-each-node/) | Medium | [116.md](solutions/116.md) | 树-路径 \| 深度 \| 翻转-中等 | |
| [118. Pascal's Triangle](https://leetcode.com/problems/pascals-triangle/) | Easy | [118.md](solutions/118.md) | | |
| [119. Pascal's Triangle II](https://leetcode.com/problems/pascals-triangle-ii/) | Easy | [119.md](solutions/119.md) | | |
| [120. Triangle](https://leetcode.com/problems/triangle/) | Medium | [120.md](solutions/120.md) | DP | |
| [121. Best Time to Buy and Sell Stock](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/) | Easy | [121.md](solutions/121.md) | 动态规划-一维-简单 | |
| [122. Best Time to Buy and Sell Stock II](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-ii/) | Medium | [122.md](solutions/122.md) | | |
| [124. Binary Tree Maximum Path Sum](https://leetcode.com/problems/binary-tree-maximum-path-sum/) | Hard | [124.md](solutions/124.md) | 树-路径 \| 深度 \| 翻转-困难 | 递归子问题返回值设计 |
| [126. Word Ladder II](https://leetcode.com/problems/word-ladder-ii/) | Hard | [126.md](solutions/126.md) | 回溯-困难 | BFS构建DAG |
| [129. Sum Root to Leaf Numbers](https://leetcode.com/problems/sum-root-to-leaf-numbers/) | Medium | [129.md](solutions/129.md) | 树-路径 \| 深度 \| 翻转-中等 | |
| [130. Surrounded Regions](https://leetcode.com/problems/surrounded-regions/) | Medium | [130.md](solutions/130.md) | 图论-DFS-中等 DFS,BFS,Union-Find | |
| [137. Single Number II](https://leetcode.com/problems/single-number-ii/) | Medium | [137.md](solutions/137.md) | 位运算-中等 | |
| [138. Copy List with Random Pointer](https://leetcode.com/problems/copy-list-with-random-pointer/) | Medium | [138.md](solutions/138.md) | 链表-单链表-中等 | 新旧结点穿插 |
| [139. Word Break](https://leetcode.com/problems/word-break/) | Medium | [139.md](solutions/139.md) | 动态规划-一维-中等 DP,BFS | |
| [141. Linked List Cycle](https://leetcode.com/problems/linked-list-cycle/) | Easy | [141.md](solutions/141.md) | 链表-单链表-简单 | 快慢指针追逐 |
| [142. Linked List Cycle II](https://leetcode.com/problems/linked-list-cycle-ii/) | Medium | [142.md](solutions/142.md) | 链表-单链表-中等 | Floyd's Algorithm |
| [143. Reorder List](https://leetcode.com/problems/remove-element/) | Medium | [143.md](solutions/143.md) | 链表-单链表-中等 | |
| [144. Binary Tree Preorder Traversal](https://leetcode.com/problems/binary-tree-preorder-traversal/) | Easy | [144.md](solutions/144.md) | 树-遍历-简单 | |
| [145. Binary Tree Postorder Traversal](https://leetcode.com/problems/binary-tree-postorder-traversal/) | Easy | [145.md](solutions/145.md) | 树-遍历-简单 | |
| [146. LRU Cache](https://leetcode.com/problems/lru-cache/) | Medium | [146.md](solutions/146.md) | 设计-中等 | 必会题 |
| [147. Insertion Sort List](https://leetcode.com/problems/insertion-sort-list/) | Medium | [147.md](solutions/147.md) | 链表-单链表-中等 | |
| [148. Sort List](https://leetcode.com/problems/sort-list/) | Medium | [148.md](solutions/148.md) | 链表-单链表-中等 | 归并排序 |
| [150. Evaluate Reverse Polish Notation](https://leetcode.com/problems/evaluate-reverse-polish-notation/) | Medium | [150.md](solutions/150.md) | 栈-基础栈-中等 | |
| [152. Maximum Product Subarray](https://leetcode.com/problems/maximum-product-subarray/) | Medium | [152.md](solutions/152.md) | 动态规划-一维-中等 | Kadane's Algorithm |
| [155. Min Stack](https://leetcode.com/problems/min-stack/) | Easy | [155.md](solutions/155.md) | 栈-基础栈-简单 | |
| [160. Intersection of Two Linked Lists](https://leetcode.com/problems/intersection-of-two-linked-lists/) | Easy | [160.md](solutions/160.md) | 链表-双链表-简单 | 串接双链表 |
| [173. Binary Search Tree Iterator](https://leetcode.com/problems/binary-search-tree-iterator/) | Easy | [173.md](solutions/173.md) | 树-二叉搜索树-中等 | 栈 |
| [198. House Robber](https://leetcode.com/problems/house-robber/) | Medium | [198.md](solutions/198.md) | DP | |
| [199. Binary Tree Right Side View](https://leetcode.com/problems/binary-tree-right-side-view/) | Medium | [199.md](solutions/199.md) | 树-路径 \| 深度 \| 翻转-中等 | |
| [200. Number of Islands](https://leetcode.com/problems/number-of-islands/) | Medium | [200.md](solutions/200.md) | 并查集-中等 | BFS/DFS更简单 |
| [203. Remove Linked List Elements](https://leetcode.com/problems/remove-linked-list-elements/) | Easy | [203.md](solutions/203.md) | 链表-单链表-简单 | |
| [206. Reverse Linked List](https://leetcode.com/problems/reverse-linked-list/) | Easy | [206.md](solutions/206.md) | 链表-单链表-简单 | |
| [207. Course Schedule](https://leetcode.com/problems/course-schedule/) |  Medium | [207.md](solutions/207.md) | 图论-拓扑排序-中等 Graph,DFS,Topological-Sort  | |
| [210. Course Schedule II](https://leetcode.com/problems/course-schedule-ii/) |  Medium | [210.md](solutions/210.md) | 图论-拓扑排序-中等 Graph,DFS,Topological-Sort  | |
| [213. House Robber II](https://leetcode.com/problems/house-robber-ii/) | Medium | [213.md](solutions/213.md) | DP | |
| [216. Combination Sum III](https://leetcode.com/problems/combination-sum-iii/) | Medium | [216.md](solutions/216.md) | 回溯-中等 | |
| [221. Maximal Square](https://leetcode.com/problems/maximal-square/) | Medium | [221.md](solutions/221.md) | 动态规划-二维-中等 DP | |
| [222. Count Complete Tree Nodes](https://leetcode.com/problems/count-complete-tree-nodes/) | Medium | [222.md](solutions/222.md) | 树-路径 \| 深度 \| 翻转-中等 | 完全二叉树算高度 |
| [224. Basic Calculator](https://leetcode.com/problems/basic-calculator/) | Hard | [224.md](solutions/224.md) | 栈-基础栈-困难 | |
| [226. Invert Binary Tree](https://leetcode.com/problems/invert-binary-tree/) | Easy | [226.md](solutions/226.md) | 树-路径 \| 深度 \| 翻转-简单 | |
| [227. Basic Calculator II](https://leetcode.com/problems/basic-calculator-ii/) | Medium | [227.md](solutions/227.md) | 栈-基础栈-中等 | |
| [230. Kth Smallest Element in a BST](https://leetcode.com/problems/remove-element/) | Medium | [230.md](solutions/230.md) | 树-二叉搜索树-中等 | |
| [232. Implement Queue using Stacks](https://leetcode.com/problems/implement-queue-using-stacks/) | Easy | [232.md](solutions/232.md) | 栈-基础栈-简单 | 倒置 |
| [234. Palindrome Linked List](https://leetcode.com/problems/palindrome-linked-list/) | Easy | [234.md](solutions/234.md) | 链表-单链表-简单 | |
| [236. Lowest Common Ancestor of a Binary Tree](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/) | Medium | [236.md](solutions/236.md) | 树-路径 \| 深度 \| 翻转-中等 | TBR |
| [237. Delete Node in a Linked List](https://leetcode.com/problems/delete-node-in-a-linked-list/) | Easy | [237.md](solutions/237.md) | 链表-单链表-简单 | 题目表述有坑 |
| [257. Binary Tree Paths](https://leetcode.com/problems/binary-tree-paths/) | Easy | [257.md](solutions/257.md) | 树-路径 \| 深度 \| 翻转-简单 | |
| [260. Single Number III](https://leetcode.com/problems/single-number-iii/) | Medium | [260.md](solutions/260.md) | 位运算-中等 Bit-Manipulation | `x & (-x)`提取最右侧的`1` |
| [264. Ugly Number II](https://leetcode.com/problems/ugly-number-ii/) | Medium | [264.md](solutions/264.md) | 贪心-中等 动态规划-一维-中等 DP | |
| [297. Serialize and Deserialize Binary Tree](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/) | Hard | [297.md](solutions/297.md) | 树-构造-困难 | |
| [304. Range Sum Query 2D - Immutable](https://leetcode.com/problems/range-sum-query-2d-immutable/) | Medium | [304.md](solutions/304.md) | | |
| [309. Best Time to Buy and Sell Stock with Cooldown](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-with-cooldown/) | Medium | [309.md](solutions/309.md) | 动态规划-一维-中等 DP | TBR |
| [316. Remove Duplicate Letters](https://leetcode.com/problems/remove-duplicate-letters/) | Medium | [316.md](solutions/316.md) | 栈-单调栈-中等 | |
| [328. Odd Even Linked List](https://leetcode.com/problems/odd-even-linked-list/) | Medium | [328.md](solutions/328.md) | 链表-单链表-中等 | |
| [341. Flatten Nested List Iterator](https://leetcode.com/problems/flatten-nested-list-iterator/) | Medium | [341.md](solutions/341.md) | 栈-基础栈-中等 | |
| [385. Mini Parser](https://leetcode.com/problems/mini-parser/) | Medium | [385.md](solutions/385.md) | 栈-基础栈-中等 | |
| [394. Decode String](https://leetcode.com/problems/decode-string/) | Medium | [394.md](solutions/394.md) | 栈-基础栈-中等 | |
| [402. Remove K Digits](https://leetcode.com/problems/remove-k-digits/) | Medium | [402.md](solutions/402.md) | 栈-单调栈-中等 | 剩余数字单调递增 |
| [404. Sum of Left Leaves](https://leetcode.com/problems/sum-of-left-leaves/) | Easy | [404.md](solutions/404.md) | | |
| [413. Arithmetic Slices](https://leetcode.com/problems/arithmetic-slices/) | Medium | [413.md](solutions/413.md) | | |
| [423. Reconstruct Original Digits from English](https://leetcode.com/problems/reconstruct-original-digits-from-english/) | Medium | [423.md](solutions/423.md) | | 奥数题 |
| [430. Flatten a Multilevel Doubly Linked List](https://leetcode.com/problems/flatten-a-multilevel-doubly-linked-list/) | Medium | [430.md](solutions/430.md) | 链表-单链表-中等 | |
| [437. Path Sum III](https://leetcode.com/problems/path-sum-iii/) | Medium | [437.md](solutions/437.md) | 树-路径 \| 深度 \| 翻转-中等 | 记忆化 |
| [441. Arranging Coins](https://leetcode.com/problems/arranging-coins/) | Easy | [441.md](solutions/441.md) | Binary-Search | TBR |
| [445. Add Two Numbers II](https://leetcode.com/problems/add-two-numbers-ii/) | Medium | [445.md](solutions/445.md) | 链表-双链表-中等 | |
| [496. Next Greater Element I](https://leetcode.com/problems/next-greater-element-i/) | Easy | [496.md](solutions/496.md) | 栈-单调栈-简单 | |
| [503. Next Greater Element II](https://leetcode.com/problems/next-greater-element-ii/) | Medium | [503.md](solutions/503.md) | 栈-基础栈-中等 | |
| [509. Fibonacci Number](https://leetcode.com/problems/fibonacci-number/) | Easy | [509.md](solutions/509.md) | Recursion,Memoization,DP | |
| [515. Find Largest Value in Each Tree Row](https://leetcode.com/problems/find-largest-value-in-each-tree-row/) | Medium | [515.md](solutions/515.md) | 树-路径 \| 深度 \| 翻转-中等 | |
| [543. Diameter of Binary Tree](https://leetcode.com/problems/diameter-of-binary-tree/) | Easy | [543.md](solutions/543.md) | 树-路径 \| 深度 \| 翻转-简单 | TBR |
| [589. N-ary Tree Preorder Traversal](https://leetcode.com/problems/n-ary-tree-preorder-traversal/) | Easy | [589.md](solutions/589.md) | 树-遍历-简单 | |
| [590. N-ary Tree Postorder Traversal](https://leetcode.com/problems/n-ary-tree-postorder-traversal/) | Easy | [590.md](solutions/590.md) | 树-遍历-简单 | |
| [617. Merge Two Binary Trees](https://leetcode.com/problems/merge-two-binary-trees/) | Easy | [617.md](solutions/617.md) | 树-路径 \| 深度 \| 翻转-简单 | |
| [636. Exclusive Time of Functions](https://leetcode.com/problems/exclusive-time-of-functions/) | Medium | [636.md](solutions/636.md) | 栈-基础栈-中等 | |
| [662. Maximum Width of Binary Tree](https://leetcode.com/problems/maximum-width-of-binary-tree/) | Medium | [662.md](solutions/662.md) | 树-路径 \| 深度 \| 翻转-中等 | |
| [682. Baseball Game](https://leetcode.com/problems/baseball-game/) | Easy | [682.md](solutions/682.md) | 栈-基础栈-简单 | |
| [695. Max Area of Island](https://leetcode.com/problems/remove-element/) | Medium | [695.md](solutions/695.md) | 图论-DFS-中等 DFS,BFS,Union-Find | |
| [707. Design Linked List](https://leetcode.com/problems/design-linked-list/) | Medium | [707.md](solutions/707.md) | 链表-单链表-中等 | |
| [714. Best Time to Buy and Sell Stock with Transaction Fee](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-with-transaction-fee/) | Medium | [714.md](solutions/714.md) | | TBR |
| [725. Split Linked List in Parts](https://leetcode.com/problems/split-linked-list-in-parts/) | Medium | [725.md](solutions/725.md) | 链表-单链表-中等 | |
| [726. Number of Atoms](https://leetcode.com/problems/number-of-atoms/) | Hard | [726.md](solutions/726.md) | 栈-基础栈-困难 | |
| [739. Daily Temperatures](https://leetcode.com/problems/daily-temperatures/) | Medium | [739.md](solutions/739.md) | 栈-单调栈-中等 | |
| [740. Delete and Earn](https://leetcode.com/problems/delete-and-earn/) | Medium | [740.md](solutions/740.md) | DP | |
| [746. Min Cost Climbing Stairs](https://leetcode.com/problems/min-cost-climbing-stairs/) | Easy | [746.md](solutions/746.md) | 动态规划-一维-简单 Recursion,Memoization,DP | |
| [842. Split Array into Fibonacci Sequence](https://leetcode.com/problems/split-array-into-fibonacci-sequence/) | Medium | [842.md](solutions/842.md) | 回溯-中等 | |
| [844. Backspace String Compare](https://leetcode.com/problems/backspace-string-compare/) | Easy | [844.md](solutions/844.md) | 栈-基础栈-简单 | |
| [856. Score of Parentheses](https://leetcode.com/problems/score-of-parentheses/) | Medium | [856.md](solutions/856.md) | 栈-基础栈-中等 | |
| [876. Middle of the Linked List](https://leetcode.com/problems/middle-of-the-linked-list/) | Easy | [876.md](solutions/876.md) | 链表-单链表-简单 | |
| [889. Construct Binary Tree from Preorder and Postorder Traversal](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-postorder-traversal/) | Medium | [889.md](solutions/889.md) | 树-构造-中等 | 前序后序创建 |
| [907. Sum of Subarray Minimums](https://leetcode.com/problems/sum-of-subarray-minimums/) | Medium | [907.md](solutions/907.md) | 栈-单调栈-中等 | 单调栈详解 |
| [918. Maximum Sum Circular Subarray](https://leetcode.com/problems/maximum-sum-circular-subarray/) | Medium | [918.md](solutions/918.md) | | Kadane's Algorithm |
| [931. Minimum Falling Path Sum](https://leetcode.com/problems/minimum-falling-path-sum/) | Medium | [931.md](solutions/931.md) | DP | |
| [980. Unique Paths III](https://leetcode.com/problems/unique-paths-iii/) | Hard | [980.md](solutions/980.md) | Backtracking | |
| [1014. Best Sightseeing Pair](https://leetcode.com/problems/best-sightseeing-pair/) | Medium | [1014.md](solutions/1014.md) | DP | 单变量DP共性总结 |
| [1021. Remove Outermost Parentheses](https://leetcode.com/problems/remove-outermost-parentheses/) | Easy | [1021.md](solutions/1021.md) | 栈-基础栈-简单 | |
| [1047. Remove All Adjacent Duplicates In String](https://leetcode.com/problems/remove-all-adjacent-duplicates-in-string/) | Easy | [1047.md](solutions/1047.md) | 栈-基础栈-简单 | |
| [1008. Construct Binary Search Tree from Preorder Traversal](https://leetcode.com/problems/construct-binary-search-tree-from-preorder-traversal/) | Medium | [1008.md](solutions/1008.md) | 树-构造-中等 | |
| [1124. Longest Well-Performing Interval](https://leetcode.com/problems/longest-well-performing-interval/) | Medium | [1124.md](solutions/1124.md) | 栈-单调栈-中等 | 核心思路与单调栈无关 |
| [1137. N-th Tribonacci Number](https://leetcode.com/problems/n-th-tribonacci-number/) | Easy | [1137.md](solutions/1137.md) | Recursion,Memoization,DP | |
| [1190. Reverse Substrings Between Each Pair of Parentheses](https://leetcode.com/problems/reverse-substrings-between-each-pair-of-parentheses/) | Medium | [1190.md](solutions/1190.md) | 栈-基础栈-中等 | |
| [1249. Minimum Remove to Make Valid Parentheses](https://leetcode.com/problems/minimum-remove-to-make-valid-parentheses/) | Medium | [1249.md](solutions/1249.md) | 栈-基础栈-中等 | |
| [1314. Matrix Block Sum](https://leetcode.com/problems/matrix-block-sum/) | Medium | [1314.md](solutions/1314.md) | | |
| [1448. Count Good Nodes in Binary Tree](https://leetcode.com/problems/count-good-nodes-in-binary-tree/) | Medium | [1448.md](solutions/1448.md) | Tree,BFS,DFS | |
| [1567. Maximum Length of Subarray With Positive Product](https://leetcode.com/problems/maximum-length-of-subarray-with-positive-product/) | Medium | [1567.md](solutions/1567.md) | | |
| [1669. Merge In Between Linked Lists](https://leetcode.com/problems/merge-in-between-linked-lists/) | Medium | [1669.md](solutions/1669.md) | 链表-双链表-中等 | |

*：按照`xx-yy-zz`格式标注的分类标准，出自[Leetcode-retag](reference/Leetcode-retag.md)这里；其他的以分号分隔Tag（例如`xx,yy,zz`）的分类则是自己的补充

**：用到的特定罕见算法、难以想到的点、值得注意的语言特性、易错点、重大启发等；`TBR`表示`To Be Reviewed`，表示需要复习，待完善
