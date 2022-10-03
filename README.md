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

虽然本人之前参加算法竞赛都是用的C/C++，个人主要职业方向是前端/全栈开发，但考虑到自己之前对Python的熟练度较高（不希望因为语言的熟练度不够从而影响刷题效率，刚准备刷题的时候手头确实Python熟练很多），再加上Python语言本身的一些很诱人的特性，个人觉得很适合拿Python来刷LeetCode，因此初刷使用的语言是Python。这里整理了一些刷题时会用到的Python技巧，编成[Python刷题Cheat Sheet](cheatsheets/python.md)，供参考。

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
| [3. Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/) | Medium | [3.md](solutions/3.md) | 双指针与滑动窗口-中等 Sliding-Window | |
| [5. Longest Palindromic Substring](https://leetcode.com/problems/longest-palindromic-substring/) | Medium | [5.md](solutions/5.md) | 动态规划-二维-中等 Dynamic-Programming | TBR |
| [11. Container With Most Water](https://leetcode.com/problems/container-with-most-water/) | Medium | [11.md](solutions/11.md) | 双指针与滑动窗口-中等 Two-Pointers | |
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
| [27. Remove Element](https://leetcode.com/problems/remove-element/) | Easy | [27.md](solutions/27.md) | 双指针与滑动窗口-简单 | |
| [33. Search in Rotated Sorted Array](https://leetcode.com/problems/search-in-rotated-sorted-array/) | Medium | [33.md](solutions/33.md) | 二分查找-中等 Binary-Search | |
| [34. Find First and Last Position of Element in Sorted Array](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/) | Medium | [34.md](solutions/34.md) | 二分查找-中等 Binary-Search | |
| [35. Search Insert Position](https://leetcode.com/problems/search-insert-position/) | Easy | [35.md](solutions/35.md) | 二分查找-简单 | |
| [36. Valid Sudoku](https://leetcode.com/problems/valid-sudoku/) | Medium | [36.md](solutions/36.md) | | |
| [37. Sudoku Solver](https://leetcode.com/problems/sudoku-solver/) | Hard | [37.md](solutions/37.md) | 回溯-困难 | |
| [39. Combination Sum](https://leetcode.com/problems/combination-sum/) | Medium | [39.md](solutions/39.md) | 回溯-中等 | |
| [40. Combination Sum II](https://leetcode.com/problems/combination-sum-ii/) | Medium | [40.md](solutions/40.md) | 回溯-中等 | |
| [42. Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water/) | Hard | [42.md](solutions/42.md) | 栈-单调栈-困难 Monotonic-Stack,Two-Pointers | |
| [43. Multiply Strings](https://leetcode.com/problems/multiply-strings/) | Easy | [43.md](solutions/43.md) | | |
| [44. Wildcard Matching](https://leetcode.com/problems/wildcard-matching/) | Hard | [44.md](solutions/44.md) | 动态规划-二维-困难 Backtracking,Dynamic-Programming | TBR |
| [45. Jump Game II](https://leetcode.com/problems/jump-game-ii/) | Medium | [45.md](solutions/45.md) | Greedy | |
| [46. Permutations](https://leetcode.com/problems/permutations/) | Medium | [46.md](solutions/46.md) | 回溯-中等 | |
| [47. Permutations II](https://leetcode.com/problems/permutations-ii/) | Medium | [47.md](solutions/47.md) | 回溯-中等 | |
| [48. Rotate Image](https://leetcode.com/problems/rotate-image/) | Medium | [48.md](solutions/48.md) | 矩阵-中等 | |
| [49. Group Anagrams](https://leetcode.com/problems/remove-element/) | Medium | [49.md](solutions/49.md) | | |
| [51. N-Queens](https://leetcode.com/problems/n-queens/) | Hard | [51.md](solutions/51.md) | 回溯-困难 Backtracking | |
| [52. N-Queens II](https://leetcode.com/problems/n-queens-ii/) | Hard | [52.md](solutions/52.md) | Backtracking | |
| [53. Maximum Subarray](https://leetcode.com/problems/maximum-subarray/) | Easy | [53.md](solutions/53.md) | 动态规划-一维-简单 | Kadane's Algorithm |
| [54. Spiral Matrix](https://leetcode.com/problems/spiral-matrix/) | Medium | [54.md](solutions/54.md) | 矩阵-中等 | |
| [55. Jump Game](https://leetcode.com/problems/jump-game/) | Medium | [55.md](solutions/55.md) | Greedy | |
| [59. Spiral Matrix II](https://leetcode.com/problems/spiral-matrix-ii/) | Medium | [59.md](solutions/59.md) | 矩阵-中等 | |
| [61. Rotate List](https://leetcode.com/problems/rotate-list/) | Medium | [61.md](solutions/61.md) | 链表-单链表-中等 | |
| [62. Unique Paths](https://leetcode.com/problems/unique-paths/) | Medium | [62.md](solutions/62.md) | 动态规划-二维-中等 Dynamic-Programming | |
| [63. Unique Paths II](https://leetcode.com/problems/unique-paths-ii/) | Medium | [63.md](solutions/63.md) | Dynamic-Programming | |
| [64. Minimum Path Sum](https://leetcode.com/problems/minimum-path-sum/) | Medium | [64.md](solutions/64.md) | 动态规划-二维-中等 Dynamic-Programming | |
| [68. Text Justification](https://leetcode.com/problems/text-justification/) | Hard | [68.md](solutions/68.md) | | |
| [70. Climbing Stairs](https://leetcode.com/problems/climbing-stairs/) | Easy | [70.md](solutions/70.md) | 动态规划-一维-简单 Dynamic-Programming | |
| [71. Simplify Path](https://leetcode.com/problems/simplify-path/) | Medium | [71.md](solutions/71.md) | 栈-基础栈-中等 | |
| [72. Edit Distance](https://leetcode.com/problems/edit-distance/) | Hard | [72.md](solutions/72.md) | 动态规划-二维-困难 Dynamic-Programming | |
| [73. Set Matrix Zeroes](https://leetcode.com/problems/set-matrix-zeroes/) | Medium | [73.md](solutions/73.md) | 矩阵-中等 | |
| [75. Sort Colors](https://leetcode.com/problems/sort-colors/)  | Medium | [75.md](solutions/75.md) | Two-Pointers | |
| [77. Combinations](https://leetcode.com/problems/combinations/) | Medium | [77.md](solutions/77.md) | 回溯-中等 | |
| [78. Subsets](https://leetcode.com/problems/subsets/) | Medium | [78.md](solutions/78.md) | 回溯-中等 位运算-中等 Backtracking,Bit-Manipulation | |
| [79. Word Search](https://leetcode.com/problems/word-search/) | Medium | [79.md](solutions/79.md) | 回溯-中等 | |
| [82. Remove Duplicates from Sorted List II](https://leetcode.com/problems/remove-duplicates-from-sorted-list-ii/) | Medium | [82.md](solutions/82.md) | 链表-单链表-中等 Linked-List,Two-Pointers | |
| [83. Remove Duplicates from Sorted List](https://leetcode.com/problems/remove-duplicates-from-sorted-list/) | Easy | [83.md](solutions/83.md) | 链表-单链表-简单 | |
| [84. Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/) | Hard | [84.md](solutions/84.md) | 栈-单调栈-困难 Monotonic-Stack | |
| [85. Maximal Rectangle](https://leetcode.com/problems/maximal-rectangle/) | Hard | [85.md](solutions/85.md) | 栈-单调栈-困难 Monotonic-Stack | |
| [86. Partition List](https://leetcode.com/problems/partition-list/) | Medium | [86.md](solutions/86.md) | 链表-单链表-中等 | |
| [88. Merge Sorted Array](https://leetcode.com/problems/merge-sorted-array/) | Easy | [88.md](solutions/88.md) | 双指针与滑动窗口-简单 | 逆序归并 |
| [89. Gray Code](https://leetcode.com/problems/gray-code/) | Medium | [89.md](solutions/89.md) | 回溯-中等 位运算-中等 Backtracking,Bit-Manipulation | |
| [90. Subsets II](https://leetcode.com/problems/subsets-ii/) | Medium | [90.md](solutions/90.md) | 回溯-中等 | |
| [91. Decode Ways](https://leetcode.com/problems/decode-ways/) | Medium | [91.md](solutions/91.md) | Dynamic-Programming | |
| [92. Reverse Linked List II](https://leetcode.com/problems/reverse-linked-list-ii/) | Medium | [92.md](solutions/92.md) | 链表-单链表-中等 | |
| [93. Restore IP Addresses](https://leetcode.com/problems/restore-ip-addresses/) | Medium | [93.md](solutions/93.md) | 回溯-中等 | |
| [94. Binary Tree Inorder Traversal](https://leetcode.com/problems/binary-tree-inorder-traversal/) | Easy | [94.md](solutions/94.md) | 树-遍历-简单 | |
| [95. Unique Binary Search Trees II](https://leetcode.com/problems/unique-binary-search-trees-ii/) | Medium | [95.md](solutions/95.md) | 树-二叉搜索树-中等 | |
| [96. Unique Binary Search Trees](https://leetcode.com/problems/unique-binary-search-trees/) | Medium | [96.md](solutions/96.md) | 树-二叉搜索树-中等 Dynamic-Programming | 实际上是DP题 |
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
| [117. Populating Next Right Pointers in Each Node II](https://leetcode.com/problems/populating-next-right-pointers-in-each-node-ii/) | Medium | [117.md](solutions/117.md) | Tree | |
| [118. Pascal's Triangle](https://leetcode.com/problems/pascals-triangle/) | Easy | [118.md](solutions/118.md) | | |
| [119. Pascal's Triangle II](https://leetcode.com/problems/pascals-triangle-ii/) | Easy | [119.md](solutions/119.md) | | |
| [120. Triangle](https://leetcode.com/problems/triangle/) | Medium | [120.md](solutions/120.md) | Dynamic-Programming | |
| [121. Best Time to Buy and Sell Stock](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/) | Easy | [121.md](solutions/121.md) | 动态规划-一维-简单 | |
| [122. Best Time to Buy and Sell Stock II](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-ii/) | Medium | [122.md](solutions/122.md) | | |
| [124. Binary Tree Maximum Path Sum](https://leetcode.com/problems/binary-tree-maximum-path-sum/) | Hard | [124.md](solutions/124.md) | 树-路径 \| 深度 \| 翻转-困难 | 递归子问题返回值设计 |
| [125. Valid Palindrome](https://leetcode.com/problems/valid-palindrome/) | Easy | [125.md](solutions/125.md) | 双指针与滑动窗口-简单 Two-Pointers | |
| [126. Word Ladder II](https://leetcode.com/problems/word-ladder-ii/) | Hard | [126.md](solutions/126.md) | 回溯-困难 | BFS构建DAG |
| [128. Longest Consecutive Sequence](https://leetcode.com/problems/longest-consecutive-sequence/) | Medium | [128.md](solutions/128.md) | | |
| [129. Sum Root to Leaf Numbers](https://leetcode.com/problems/sum-root-to-leaf-numbers/) | Medium | [129.md](solutions/129.md) | 树-路径 \| 深度 \| 翻转-中等 | |
| [130. Surrounded Regions](https://leetcode.com/problems/surrounded-regions/) | Medium | [130.md](solutions/130.md) | 图论-DFS-中等 DFS,BFS,Union-Find | |
| [131. Palindrome Partitioning](https://leetcode.com/problems/palindrome-partitioning/) | Medium | [131.md](solutions/131.md) | 动态规划-二维-中等 Dynamic-Programming,DFS | |
| [132. Palindrome Partitioning II](https://leetcode.com/problems/palindrome-partitioning-ii/) | Hard | [132.md](solutions/132.md) | 动态规划-二维-困难 Dynamic-Programming | |
| [136. Single Number](https://leetcode.com/problems/single-number/) | Easy | [136.md](solutions/136.md) | 位运算-简单 Bit-Manipulation | |
| [137. Single Number II](https://leetcode.com/problems/single-number-ii/) | Medium | [137.md](solutions/137.md) | 位运算-中等 | |
| [138. Copy List with Random Pointer](https://leetcode.com/problems/copy-list-with-random-pointer/) | Medium | [138.md](solutions/138.md) | 链表-单链表-中等 | 新旧结点穿插 |
| [139. Word Break](https://leetcode.com/problems/word-break/) | Medium | [139.md](solutions/139.md) | 动态规划-一维-中等 Dynamic-Programming,BFS | |
| [140. Word Break II](https://leetcode.com/problems/word-break-ii/) | Hard | [140.md](solutions/140.md) | Dynamic-Programming | |
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
| [162. Find Peak Element](https://leetcode.com/problems/find-peak-element/) | Medium | [162.md](solutions/162.md) | 二分查找-中等 | `[m, m + 1]`空间必在`[l, r]`中 |
| [167. Two Sum II - Input Array Is Sorted](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/) | Medium | [167.md](solutions/167.md) | 二分查找-简单 Two-Pointers | |
| [169. Majority Element](https://leetcode.com/problems/majority-element/) | Easy | [169.md](solutions/169.md) | | Boyer-Moore Voting Algorithm |
| [173. Binary Search Tree Iterator](https://leetcode.com/problems/binary-search-tree-iterator/) | Medium | [173.md](solutions/173.md) | 树-二叉搜索树-中等 | 栈 |
| [174. Dungeon Game](https://leetcode.com/problems/dungeon-game/) | Hard | [174.md](solutions/174.md) | Dynamic-Programming | |
| [190. Reverse Bits](https://leetcode.com/problems/reverse-bits/) | Easy | [190.md](solutions/190.md) | 位运算-简单 Bit-Manipulation,Divide-and-Conquer | |
| [191. Number of 1 Bits](https://leetcode.com/problems/number-of-1-bits/) | Easy | [191.md](solutions/191.md) | 位运算-简单 Bit-Manipulation | |
| [198. House Robber](https://leetcode.com/problems/house-robber/) | Medium | [198.md](solutions/198.md) | Dynamic-Programming | |
| [199. Binary Tree Right Side View](https://leetcode.com/problems/binary-tree-right-side-view/) | Medium | [199.md](solutions/199.md) | 树-路径 \| 深度 \| 翻转-中等 | |
| [200. Number of Islands](https://leetcode.com/problems/number-of-islands/) | Medium | [200.md](solutions/200.md) | 并查集-中等 | BFS/DFS更简单 |
| [201. Bitwise AND of Numbers Range](https://leetcode.com/problems/bitwise-and-of-numbers-range/) | Easy | [201.md](solutions/201.md) | Bit-Manipulation | |
| [202. Happy Number](https://leetcode.com/problems/happy-number/) | Easy | [202.md](solutions/202.md) | 数学-简单 | |
| [203. Remove Linked List Elements](https://leetcode.com/problems/remove-linked-list-elements/) | Easy | [203.md](solutions/203.md) | 链表-单链表-简单 | |
| [204. Count Primes](https://leetcode.com/problems/count-primes/) | Medium | [204.md](solutions/204.md) | 数学-中等 | |
| [206. Reverse Linked List](https://leetcode.com/problems/reverse-linked-list/) | Easy | [206.md](solutions/206.md) | 链表-单链表-简单 | |
| [207. Course Schedule](https://leetcode.com/problems/course-schedule/) |  Medium | [207.md](solutions/207.md) | 图论-拓扑排序-中等 Graph,DFS,Topological-Sort  | |
| [209. Minimum Size Subarray Sum](https://leetcode.com/problems/minimum-size-subarray-sum/) |  Medium | [209.md](solutions/209.md) | Sliding-Window | |
| [210. Course Schedule II](https://leetcode.com/problems/course-schedule-ii/) |  Medium | [210.md](solutions/210.md) | 图论-拓扑排序-中等 Graph,DFS,Topological-Sort  | |
| [213. House Robber II](https://leetcode.com/problems/house-robber-ii/) | Medium | [213.md](solutions/213.md) | Dynamic-Programming | |
| [215. Kth Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array/) | Medium | [215.md](solutions/215.md) | 堆-中等 Heap | |
| [216. Combination Sum III](https://leetcode.com/problems/combination-sum-iii/) | Medium | [216.md](solutions/216.md) | 回溯-中等 | |
| [217. Contains Duplicate](https://leetcode.com/problems/contains-duplicate/) | Easy | [217.md](solutions/217.md) | 双指针与滑动窗口-简单 | |
| [221. Maximal Square](https://leetcode.com/problems/maximal-square/) | Medium | [221.md](solutions/221.md) | 动态规划-二维-中等 Dynamic-Programming | |
| [222. Count Complete Tree Nodes](https://leetcode.com/problems/count-complete-tree-nodes/) | Medium | [222.md](solutions/222.md) | 树-路径 \| 深度 \| 翻转-中等 | 完全二叉树算高度 |
| [224. Basic Calculator](https://leetcode.com/problems/basic-calculator/) | Hard | [224.md](solutions/224.md) | 栈-基础栈-困难 | |
| [226. Invert Binary Tree](https://leetcode.com/problems/invert-binary-tree/) | Easy | [226.md](solutions/226.md) | 树-路径 \| 深度 \| 翻转-简单 | |
| [227. Basic Calculator II](https://leetcode.com/problems/basic-calculator-ii/) | Medium | [227.md](solutions/227.md) | 栈-基础栈-中等 | |
| [230. Kth Smallest Element in a BST](https://leetcode.com/problems/remove-element/) | Medium | [230.md](solutions/230.md) | 树-二叉搜索树-中等 | |
| [231. Power of Two](https://leetcode.com/problems/power-of-two/) | Easy | [231.md](solutions/231.md) | 位运算-简单 Bit-Manipulation | |
| [232. Implement Queue using Stacks](https://leetcode.com/problems/implement-queue-using-stacks/) | Easy | [232.md](solutions/232.md) | 栈-基础栈-简单 | 倒置 |
| [234. Palindrome Linked List](https://leetcode.com/problems/palindrome-linked-list/) | Easy | [234.md](solutions/234.md) | 链表-单链表-简单 | |
| [236. Lowest Common Ancestor of a Binary Tree](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/) | Medium | [236.md](solutions/236.md) | 树-路径 \| 深度 \| 翻转-中等 | TBR |
| [237. Delete Node in a Linked List](https://leetcode.com/problems/delete-node-in-a-linked-list/) | Easy | [237.md](solutions/237.md) | 链表-单链表-简单 | 题目表述有坑 |
| [238. Product of Array Except Self](https://leetcode.com/problems/product-of-array-except-self/) | Medium | [238.md](solutions/238.md) | | |
| [242. Valid Anagram](https://leetcode.com/problems/valid-anagram/) | Easy | [242.md](solutions/242.md) | | |
| [257. Binary Tree Paths](https://leetcode.com/problems/binary-tree-paths/) | Easy | [257.md](solutions/257.md) | 树-路径 \| 深度 \| 翻转-简单 | |
| [260. Single Number III](https://leetcode.com/problems/single-number-iii/) | Medium | [260.md](solutions/260.md) | 位运算-中等 Bit-Manipulation | `x & (-x)`提取最右侧的`1` |
| [264. Ugly Number II](https://leetcode.com/problems/ugly-number-ii/) | Medium | [264.md](solutions/264.md) | 贪心-中等 动态规划-一维-中等 Dynamic-Programming | |
| [268. Missing Number](https://leetcode.com/problems/missing-number/) | Easy | [268.md](solutions/268.md) | 位运算-简单 Bit-Manipulation | |
| [271. Encode and Decode Strings](https://leetcode.com/problems/encode-and-decode-strings/) | Medium | [271.md](solutions/271.md) | | |
| [279. Perfect Squares](https://leetcode.com/problems/perfect-squares/) | Medium | [279.md](solutions/279.md) | 图论-BFS-中等 动态规划-一维-中等 Dynamic-Programming | |
| [283. Move Zeroes](https://leetcode.com/problems/move-zeroes/) | Easy | [283.md](solutions/283.md) | 双指针-简单 Two-Pointers | |
| [289. Game of Life](https://leetcode.com/problems/game-of-life/) | Medium | [289.md](solutions/289.md) | | |
| [297. Serialize and Deserialize Binary Tree](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/) | Hard | [297.md](solutions/297.md) | 树-构造-困难 | |
| [300. Longest Increasing Subsequence](https://leetcode.com/problems/longest-increasing-subsequence/) | Medium | [300.md](solutions/300.md) | 动态规划-一维-中等 二分查找-中等 Dynamic-Programming,Binary-Search | Pacience Sorting |
| [304. Range Sum Query 2D - Immutable](https://leetcode.com/problems/range-sum-query-2d-immutable/) | Medium | [304.md](solutions/304.md) | | |
| [309. Best Time to Buy and Sell Stock with Cooldown](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-with-cooldown/) | Medium | [309.md](solutions/309.md) | 动态规划-一维-中等 Dynamic-Programming | TBR |
| [310. Minimum Height Trees](https://leetcode.com/problems/minimum-height-trees/) | Medium | [310.md](solutions/310.md) | Tree | |
| [316. Remove Duplicate Letters](https://leetcode.com/problems/remove-duplicate-letters/) | Medium | [316.md](solutions/316.md) | 栈-单调栈-中等 | |
| [322. Coin Change](https://leetcode.com/problems/coin-change/) | Medium | [322.md](solutions/322.md) | 动态规划-一维-中等 Dynamic-Programming | |
| [328. Odd Even Linked List](https://leetcode.com/problems/odd-even-linked-list/) | Medium | [328.md](solutions/328.md) | 链表-单链表-中等 | |
| [338. Counting Bits](https://leetcode.com/problems/counting-bits/) | Easy | [338.md](solutions/338.md) | 位运算-简单 动态规划-一维-简单 Bit-Manipulation,Dynamic-Programming | |
| [341. Flatten Nested List Iterator](https://leetcode.com/problems/flatten-nested-list-iterator/) | Medium | [341.md](solutions/341.md) | 栈-基础栈-中等 | |
| [343. Integer Break](https://leetcode.com/problems/integer-break/) | Medium | [343.md](solutions/343.md) | Dynamic-Programming | |
| [344. Reverse String](https://leetcode.com/problems/reverse-string/) | Easy | [344.md](solutions/344.md) | 双指针与滑动窗口-简单 Two-Pointers | |
| [347. Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements/) | Medium | [347.md](solutions/347.md) | 堆-中等 Heap | |
| [349. Intersection of Two Arrays](https://leetcode.com/problems/intersection-of-two-arrays/) | Easy | [349.md](solutions/349.md) | 双指针与滑动窗口-简单 Two-Pointers | |
| [354. Russian Doll Envelopes](https://leetcode.com/problems/russian-doll-envelopes/) | Hard | [354.md](solutions/354.md) | 动态规划-一维-困难 Dynamic-Programming,Binary-Search | Pacience Sorting |
| [368. Largest Divisible Subset](https://leetcode.com/problems/largest-divisible-subset/) | Medium | [368.md](solutions/368.md) | Dynamic-Programming | |
| [370. Range Addition](https://leetcode.com/problems/range-addition/) | Medium | [370.md](solutions/370.md) | Prefix-Sum | |
| [371. Sum of Two Integers](https://leetcode.com/problems/sum-of-two-integers/) | Medium | [371.md](solutions/371.md) | 位运算-中等 Bit-Manipulation | |
| [376. Wiggle Subsequence](https://leetcode.com/problems/remove-element/) | Medium | [376.md](solutions/376.md) | Dynamic-Programming | |
| [377. Combination Sum IV](https://leetcode.com/problems/combination-sum-iv/) | Medium | [377.md](solutions/377.md) | Dynamic-Programming | |
| [378. Kth Smallest Element in a Sorted Matrix](https://leetcode.com/problems/kth-smallest-element-in-a-sorted-matrix/) | Medium | [378.md](solutions/378.md) | 堆-中等 Heap | 元组封装后`heapq` |
| [382. Linked List Random Node](https://leetcode.com/problems/linked-list-random-node/) | Medium | [382.md](solutions/382.md) | | Reservoir Sampling |
| [384. Shuffle an Array](https://leetcode.com/problems/shuffle-an-array/) | Medium | [384.md](solutions/384.md) | | Fisher-Yates Algorithm |
| [385. Mini Parser](https://leetcode.com/problems/mini-parser/) | Medium | [385.md](solutions/385.md) | 栈-基础栈-中等 | |
| [387. First Unique Character in a String](https://leetcode.com/problems/first-unique-character-in-a-string/) | Easy | [387.md](solutions/387.md) | | |
| [389. Find the Difference](https://leetcode.com/problems/find-the-difference/) | Easy | [389.md](solutions/389.md) | 位运算-简单 Bit-Manipulation | |
| [392. Is Subsequence](https://leetcode.com/problems/is-subsequence/) | Easy | [392.md](solutions/392.md) | Two-Pointers,Dynamic-Programming | |
| [393. UTF-8 Validation](https://leetcode.com/problems/remove-element/) | Medium | [393.md](solutions/393.md) | Bit-Manipulation | |
| [394. Decode String](https://leetcode.com/problems/decode-string/) | Medium | [394.md](solutions/394.md) | 栈-基础栈-中等 | |
| [402. Remove K Digits](https://leetcode.com/problems/remove-k-digits/) | Medium | [402.md](solutions/402.md) | 栈-单调栈-中等 | 剩余数字单调递增 |
| [404. Sum of Left Leaves](https://leetcode.com/problems/sum-of-left-leaves/) | Easy | [404.md](solutions/404.md) | | |
| [405. Convert a Number to Hexadecimal](https://leetcode.com/problems/convert-a-number-to-hexadecimal/) | Easy | [405.md](solutions/405.md) | 位运算-简单 Bit-Manipulation | |
| [406. Queue Reconstruction by Height](https://leetcode.com/problems/queue-reconstruction-by-height/) | Medium | [406.md](solutions/406.md) | Greedy | |
| [409. Longest Palindrome](https://leetcode.com/problems/longest-palindrome/) | Easy | [409.md](solutions/409.md) | | |
| [412. Fizz Buzz](https://leetcode.com/problems/fizz-buzz/) | Easy | [412.md](solutions/412.md) | | |
| [413. Arithmetic Slices](https://leetcode.com/problems/arithmetic-slices/) | Medium | [413.md](solutions/413.md) | | |
| [423. Reconstruct Original Digits from English](https://leetcode.com/problems/reconstruct-original-digits-from-english/) | Medium | [423.md](solutions/423.md) | | 奥数题 |
| [424. Longest Repeating Character Replacement](https://leetcode.com/problems/longest-repeating-character-replacement/) | Medium | [424.md](solutions/424.md) | 双指针与滑动窗口-中等 Sliding-Window | TBR |
| [429. N-ary Tree Level Order Traversal](https://leetcode.com/problems/n-ary-tree-level-order-traversal/) | Medium | [429.md](solutions/429.md) | | |
| [430. Flatten a Multilevel Doubly Linked List](https://leetcode.com/problems/flatten-a-multilevel-doubly-linked-list/) | Medium | [430.md](solutions/430.md) | 链表-单链表-中等 | |
| [437. Path Sum III](https://leetcode.com/problems/path-sum-iii/) | Medium | [437.md](solutions/437.md) | 树-路径 \| 深度 \| 翻转-中等 | 记忆化 |
| [438. Find All Anagrams in a String](https://leetcode.com/problems/find-all-anagrams-in-a-string/) | Medium | [438.md](solutions/438.md) | Sliding-Window |
| [441. Arranging Coins](https://leetcode.com/problems/arranging-coins/) | Easy | [441.md](solutions/441.md) | Binary-Search | TBR |
| [445. Add Two Numbers II](https://leetcode.com/problems/add-two-numbers-ii/) | Medium | [445.md](solutions/445.md) | 链表-双链表-中等 | |
| [448. Find All Numbers Disappeared in an Array](https://leetcode.com/problems/find-all-numbers-disappeared-in-an-array/) | Easy | [448.md](solutions/448.md) | | 在原数组上交换 |
| [450. Delete Node in a BST](https://leetcode.com/problems/delete-node-in-a-bst/) | Medium | [450.md](solutions/450.md) | Binary-Search-Tree | |
| [461. Hamming Distance](https://leetcode.com/problems/hamming-distance/) | Easy | [461.md](solutions/461.md) | 位运算-简单 Bit-Manipulation | |
| [462. Minimum Moves to Equal Array Elements II](https://leetcode.com/problems/minimum-moves-to-equal-array-elements-ii/) | Medium | [462.md](solutions/462.md) | Math | 中位数 |
| [472. Concatenated Words](https://leetcode.com/problems/concatenated-words/) | Hard | [472.md](solutions/472.md) | | |
| [496. Next Greater Element I](https://leetcode.com/problems/next-greater-element-i/) | Easy | [496.md](solutions/496.md) | 栈-单调栈-简单 | |
| [503. Next Greater Element II](https://leetcode.com/problems/next-greater-element-ii/) | Medium | [503.md](solutions/503.md) | 栈-基础栈-中等 | |
| [509. Fibonacci Number](https://leetcode.com/problems/fibonacci-number/) | Easy | [509.md](solutions/509.md) | Recursion,Memoization,Dynamic-Programming | |
| [515. Find Largest Value in Each Tree Row](https://leetcode.com/problems/find-largest-value-in-each-tree-row/) | Medium | [515.md](solutions/515.md) | 树-路径 \| 深度 \| 翻转-中等 | |
| [516. Longest Palindromic Subsequence](https://leetcode.com/problems/longest-palindromic-subsequence/) | Medium | [516.md](solutions/516.md) | Dynamic-Programming | |
| [518. Coin Change 2](https://leetcode.com/problems/coin-change-2/) | Medium | [518.md](solutions/518.md) | Dynamic-Programming | |
| [540. Single Element in a Sorted Array](https://leetcode.com/problems/single-element-in-a-sorted-array/) | Medium | [540.md](solutions/540.md) | Binary-Search | |
| [543. Diameter of Binary Tree](https://leetcode.com/problems/diameter-of-binary-tree/) | Easy | [543.md](solutions/543.md) | 树-路径 \| 深度 \| 翻转-简单 | TBR |
| [547. Number of Provinces](https://leetcode.com/problems/number-of-provinces/) | Medium | [547.md](solutions/547.md) | Union-Find | |
| [557. Reverse Words in a String III](https://leetcode.com/problems/reverse-words-in-a-string-iii/) | Easy | [557.md](solutions/557.md) | | |
| [560. Subarray Sum Equals K](https://leetcode.com/problems/subarray-sum-equals-k/) | Medium | [560.md](solutions/560.md) | Prefix-Sum | |
| [563. Binary Tree Tilt](https://leetcode.com/problems/binary-tree-tilt/) | Easy | [563.md](solutions/563.md) | | |
| [567. Permutation in String](https://leetcode.com/problems/permutation-in-string/) | Medium | [567.md](solutions/567.md) | Sliding-Window | |
| [572. Subtree of Another Tree](https://leetcode.com/problems/subtree-of-another-tree/) | Easy | [572.md](solutions/572.md) | Tree | |
| [583. Delete Operation for Two Strings](https://leetcode.com/problems/delete-operation-for-two-strings/) | Medium | [583.md](solutions/583.md) | Dynamic-Programming | |
| [589. N-ary Tree Preorder Traversal](https://leetcode.com/problems/n-ary-tree-preorder-traversal/) | Easy | [589.md](solutions/589.md) | 树-遍历-简单 | |
| [590. N-ary Tree Postorder Traversal](https://leetcode.com/problems/n-ary-tree-postorder-traversal/) | Easy | [590.md](solutions/590.md) | 树-遍历-简单 | |
| [606. Construct String from Binary Tree](https://leetcode.com/problems/construct-string-from-binary-tree/) | Easy | [606.md](solutions/606.md) | Depth-First-Search | |
| [609. Find Duplicate File in System](https://leetcode.com/problems/find-duplicate-file-in-system/) | Medium | [609.md](solutions/609.md) | | |
| [617. Merge Two Binary Trees](https://leetcode.com/problems/merge-two-binary-trees/) | Easy | [617.md](solutions/617.md) | 树-路径 \| 深度 \| 翻转-简单 | |
| [622. Design Circular Queue](https://leetcode.com/problems/design-circular-queue/) | Medium | [622.md](solutions/622.md) | 设计-中等 | |
| [630. Course Schedule III](https://leetcode.com/problems/course-schedule-iii/) | Hard | [630.md](solutions/630.md) | Greedy,Heap | 堆辅助贪心 |
| [636. Exclusive Time of Functions](https://leetcode.com/problems/exclusive-time-of-functions/) | Medium | [636.md](solutions/636.md) | 栈-基础栈-中等 | |
| [637. Average of Levels in Binary Tree](https://leetcode.com/problems/average-of-levels-in-binary-tree/) | Easy | [637.md](solutions/637.md) | | |
| [658. Find K Closest Elements](https://leetcode.com/problems/find-k-closest-elements/) | Medium | [658.md](solutions/658.md) | Binary-Search | |
| [662. Maximum Width of Binary Tree](https://leetcode.com/problems/maximum-width-of-binary-tree/) | Medium | [662.md](solutions/662.md) | 树-路径 \| 深度 \| 翻转-中等 | |
| [668. Kth Smallest Number in Multiplication Table](https://leetcode.com/problems/kth-smallest-number-in-multiplication-table/) | Hard | [668.md](solutions/668.md) | Binary-Search | TBR |
| [673. Number of Longest Increasing Subsequence](https://leetcode.com/problems/remove-element/) | Medium | [673.md](solutions/673.md) | Dynamic-Programming | TBR |
| [680. Valid Palindrome II](https://leetcode.com/problems/valid-palindrome-ii/) | Easy | [680.md](solutions/680.md) | Two-Pointers | |
| [682. Baseball Game](https://leetcode.com/problems/baseball-game/) | Easy | [682.md](solutions/682.md) | 栈-基础栈-简单 | |
| [692. Top K Frequent Words](https://leetcode.com/problems/top-k-frequent-words/) | Medium | [692.md](solutions/692.md) | 栈-中等 Heap | 构造实现了`__lt__`的对象后`heapq` |
| [694. Number of Distinct Islands](https://leetcode.com/problems/number-of-distinct-islands/) | Medium | [694.md](solutions/694.md) | DFS,BFS,Union-Find | |
| [695. Max Area of Island](https://leetcode.com/problems/remove-element/) | Medium | [695.md](solutions/695.md) | 图论-DFS-中等 DFS,BFS,Union-Find | |
| [696. Count Binary Substrings](https://leetcode.com/problems/count-binary-substrings/) | Easy | [696.md](solutions/696.md) | | |
| [700. Search in a Binary Search Tree](https://leetcode.com/problems/search-in-a-binary-search-tree/) | Easy | [700.md](solutions/700.md) | Binary-Search-Tree | |
| [703. Kth Largest Element in a Stream](https://leetcode.com/problems/kth-largest-element-in-a-stream/) | Easy | [703.md](solutions/703.md) | 堆-简单 Heap | |
| [707. Design Linked List](https://leetcode.com/problems/design-linked-list/) | Medium | [707.md](solutions/707.md) | 链表-单链表-中等 | |
| [713. Subarray Product Less Than K](https://leetcode.com/problems/subarray-product-less-than-k/) | Medium | [713.md](solutions/713.md) | 双指针与滑动窗口-中等 | |
| [714. Best Time to Buy and Sell Stock with Transaction Fee](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-with-transaction-fee/) | Medium | [714.md](solutions/714.md) | | TBR |
| [718. Maximum Length of Repeated Subarray](https://leetcode.com/problems/maximum-length-of-repeated-subarray/) | Medium | [718.md](solutions/718.md) | 动态规划-二维-中等 Dynamic-Programming | |
| [722. Remove Comments](https://leetcode.com/problems/remove-comments/) | Medium | [722.md](solutions/722.md) | | |
| [725. Split Linked List in Parts](https://leetcode.com/problems/split-linked-list-in-parts/) | Medium | [725.md](solutions/725.md) | 链表-单链表-中等 | |
| [726. Number of Atoms](https://leetcode.com/problems/number-of-atoms/) | Hard | [726.md](solutions/726.md) | 栈-基础栈-困难 | |
| [739. Daily Temperatures](https://leetcode.com/problems/daily-temperatures/) | Medium | [739.md](solutions/739.md) | 栈-单调栈-中等 | |
| [740. Delete and Earn](https://leetcode.com/problems/delete-and-earn/) | Medium | [740.md](solutions/740.md) | Dynamic-Programming | |
| [746. Min Cost Climbing Stairs](https://leetcode.com/problems/min-cost-climbing-stairs/) | Easy | [746.md](solutions/746.md) | 动态规划-一维-简单 Recursion,Memoization,Dynamic-Programming | |
| [751. IP to CIDR](https://leetcode.com/problems/ip-to-cidr/) | Medium | [751.md](solutions/751.md) | Bit-Manipulation | |
| [780. Reaching Points](https://leetcode.com/problems/reaching-points/) | Hard | [780.md](solutions/780.md) | | |
| [781. Rabbits in Forest](https://leetcode.com/problems/rabbits-in-forest/) | Medium | [781.md](solutions/781.md) | 贪心-中等 Greedy | |
| [790. Domino and Tromino Tiling](https://leetcode.com/problems/domino-and-tromino-tiling/) | Medium | [790.md](solutions/790.md) | Dynamic-Programming | |
| [797. All Paths From Source to Target](https://leetcode.com/problems/all-paths-from-source-to-target/) | Medium | [797.md](solutions/797.md) | | |
| [814. Binary Tree Pruning](https://leetcode.com/problems/binary-tree-pruning/) | Medium | [814.md](solutions/814.md) | | Depth-First-Search |
| [832. Flipping an Image](https://leetcode.com/problems/flipping-an-image/) | Easy | [832.md](solutions/832.md) | 矩阵-简单 | |
| [838. Push Dominoes](https://leetcode.com/problems/push-dominoes/) | Medium | [838.md](solutions/838.md) | | |
| [842. Split Array into Fibonacci Sequence](https://leetcode.com/problems/split-array-into-fibonacci-sequence/) | Medium | [842.md](solutions/842.md) | 回溯-中等 | |
| [844. Backspace String Compare](https://leetcode.com/problems/backspace-string-compare/) | Easy | [844.md](solutions/844.md) | 栈-基础栈-简单 Two-Pointers | |
| [856. Score of Parentheses](https://leetcode.com/problems/score-of-parentheses/) | Medium | [856.md](solutions/856.md) | 栈-基础栈-中等 | |
| [867. Transpose Matrix](https://leetcode.com/problems/transpose-matrix/) | Easy | [867.md](solutions/867.md) | 矩阵-简单 | |
| [876. Middle of the Linked List](https://leetcode.com/problems/middle-of-the-linked-list/) | Easy | [876.md](solutions/876.md) | 链表-单链表-简单 | |
| [889. Construct Binary Tree from Preorder and Postorder Traversal](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-postorder-traversal/) | Medium | [889.md](solutions/889.md) | 树-构造-中等 | 前序后序创建 |
| [907. Sum of Subarray Minimums](https://leetcode.com/problems/sum-of-subarray-minimums/) | Medium | [907.md](solutions/907.md) | 栈-单调栈-中等 | 单调栈详解 |
| [910. Smallest Range II](https://leetcode.com/problems/smallest-range-ii/) | Medium | [910.md](solutions/910.md) | Greedy | TBR |
| [918. Maximum Sum Circular Subarray](https://leetcode.com/problems/maximum-sum-circular-subarray/) | Medium | [918.md](solutions/918.md) | | Kadane's Algorithm |
| [923. 3Sum With Multiplicity](https://leetcode.com/problems/3sum-with-multiplicity/) | Medium | [923.md](solutions/923.md) | Two-Pointers | |
| [931. Minimum Falling Path Sum](https://leetcode.com/problems/minimum-falling-path-sum/) | Medium | [931.md](solutions/931.md) | Dynamic-Programming | |
| [934. Shortest Bridge](https://leetcode.com/problems/shortest-bridge/) | Medium | [934.md](solutions/934.md) | Depth-First-Search Breadth-First-Search | |
| [937. Reorder Data in Log Files](https://leetcode.com/problems/reorder-data-in-log-files/) | Medium | [937.md](solutions/937.md) | | |
| [945. Minimum Increment to Make Array Unique](https://leetcode.com/problems/minimum-increment-to-make-array-unique/) | Medium | [945.md](solutions/945.md) | Greedy | |
| [948. Bag of Tokens](https://leetcode.com/problems/bag-of-tokens/) | Medium | [948.md](solutions/948.md) | Greedy | |
| [952. Largest Component Size by Common Factor](https://leetcode.com/problems/largest-component-size-by-common-factor/) | Hard | [952.md](solutions/952.md) | Union-Find | |
| [961. N-Repeated Element in Size 2N Array](https://leetcode.com/problems/n-repeated-element-in-size-2n-array/) | Easy | [961.md](solutions/961.md) | | |
| [967. Numbers With Same Consecutive Differences](https://leetcode.com/problems/numbers-with-same-consecutive-differences/) | Medium | [967.md](solutions/967.md) | Backtracking | |
| [974. Subarray Sums Divisible by K](https://leetcode.com/problems/subarray-sums-divisible-by-k/) | Medium | [974.md](solutions/974.md) | Prefix-Sum | |
| [977. Squares of a Sorted Array](https://leetcode.com/problems/squares-of-a-sorted-array/) | Easy | [977.md](solutions/977.md) | 双指针与滑动窗口 Two-Pointers | 从大到小构建 |
| [980. Unique Paths III](https://leetcode.com/problems/unique-paths-iii/) | Hard | [980.md](solutions/980.md) | Backtracking | |
| [986. Interval List Intersections](https://leetcode.com/problems/interval-list-intersections/) | Medium | [986.md](solutions/986.md) | Two-Pointers | |
| [987. Vertical Order Traversal of a Binary Tree](https://leetcode.com/problems/vertical-order-traversal-of-a-binary-tree/) | Hard | [987.md](solutions/987.md) | | |
| [990. Satisfiability of Equality Equations](https://leetcode.com/problems/satisfiability-of-equality-equations/) | Medium | [990.md](solutions/990.md) | Union-Find | |
| [1008. Construct Binary Search Tree from Preorder Traversal](https://leetcode.com/problems/construct-binary-search-tree-from-preorder-traversal/) | Medium | [1008.md](solutions/1008.md) | 树-构造-中等 | |
| [1014. Best Sightseeing Pair](https://leetcode.com/problems/best-sightseeing-pair/) | Medium | [1014.md](solutions/1014.md) | Dynamic-Programming | 单变量DP共性总结 |
| [1021. Remove Outermost Parentheses](https://leetcode.com/problems/remove-outermost-parentheses/) | Easy | [1021.md](solutions/1021.md) | 栈-基础栈-简单 | |
| [1026. Maximum Difference Between Node and Ancestor](https://leetcode.com/problems/maximum-difference-between-node-and-ancestor/) | Medium | [1026.md](solutions/1026.md) | | |
| [1046. Last Stone Weight](https://leetcode.com/problems/last-stone-weight/) | Easy | [1046.md](solutions/1046.md) | 堆-简单 Heap,Counting-Sort | |
| [1047. Remove All Adjacent Duplicates In String](https://leetcode.com/problems/remove-all-adjacent-duplicates-in-string/) | Easy | [1047.md](solutions/1047.md) | 栈-基础栈-简单 | |
| [1048. Longest String Chain](https://leetcode.com/problems/longest-string-chain/) | Medium | [1048.md](solutions/1048.md) | | |
| [1094. Car Pooling](https://leetcode.com/problems/car-pooling/) | Medium | [1094.md](solutions/1094.md) | | |
| [1124. Longest Well-Performing Interval](https://leetcode.com/problems/longest-well-performing-interval/) | Medium | [1124.md](solutions/1124.md) | 栈-单调栈-中等 | 核心思路与单调栈无关 |
| [1137. N-th Tribonacci Number](https://leetcode.com/problems/n-th-tribonacci-number/) | Easy | [1137.md](solutions/1137.md) | Recursion,Memoization,Dynamic-Programming | |
| [1143. Longest Common Subsequence](https://leetcode.com/problems/longest-common-subsequence/) | Medium | [1143.md](solutions/1143.md) | 动态规划-二维-中等 Dynamic-Programming | |
| [1155. Number of Dice Rolls With Target Sum](https://leetcode.com/problems/number-of-dice-rolls-with-target-sum/) | Medium | [1155.md](solutions/1155.md) | Dynamic-Programming | |
| [1165. Single-Row Keyboard](https://leetcode.com/problems/single-row-keyboard/) | Easy | [1165.md](solutions/1165.md) | | |
| [1178. Number of Valid Words for Each Puzzle](https://leetcode.com/problems/number-of-valid-words-for-each-puzzle/) | Hard | [1178.md](solutions/1178.md) | Hash-Table,Bit-Manipulation | TBR |
| [1190. Reverse Substrings Between Each Pair of Parentheses](https://leetcode.com/problems/reverse-substrings-between-each-pair-of-parentheses/) | Medium | [1190.md](solutions/1190.md) | 栈-基础栈-中等 | |
| [1217. Minimum Cost to Move Chips to The Same Position](https://leetcode.com/problems/minimum-cost-to-move-chips-to-the-same-position/) | Easy | [1217.md](solutions/1217.md) | | |
| [1239. Maximum Length of a Concatenated String with Unique Characters](https://leetcode.com/problems/maximum-length-of-a-concatenated-string-with-unique-characters/) | Medium | [1239.md](solutions/1239.md) | | |
| [1249. Minimum Remove to Make Valid Parentheses](https://leetcode.com/problems/minimum-remove-to-make-valid-parentheses/) | Medium | [1249.md](solutions/1249.md) | 栈-基础栈-中等 | |
| [1260. Shift 2D Grid](https://leetcode.com/problems/shift-2d-grid/) | Easy | [1260.md](solutions/1260.md) | 栈-基础栈-中等 | |
| [1268. Search Suggestions System](https://leetcode.com/problems/search-suggestions-system/) | Medium | [1268.md](solutions/1268.md) | Binary-Search | |
| [1272. Remove Interval](https://leetcode.com/problems/remove-interval/) | Medium | [1272.md](solutions/1272.md) | | |
| [1286. Iterator for Combination](https://leetcode.com/problems/iterator-for-combination/) | Medium | [1286.md](solutions/1286.md) | Backtracking | |
| [1290. Convert Binary Number in a Linked List to Integer](https://leetcode.com/problems/convert-binary-number-in-a-linked-list-to-integer/) | Easy | [1290.md](solutions/1290.md) | | |
| [1306. Jump Game III](https://leetcode.com/problems/jump-game-iii/) | Medium | [1306.md](solutions/1306.md) | | |
| [1314. Matrix Block Sum](https://leetcode.com/problems/matrix-block-sum/) | Medium | [1314.md](solutions/1314.md) | | |
| [1318. Minimum Flips to Make a OR b Equal to c](https://leetcode.com/problems/minimum-flips-to-make-a-or-b-equal-to-c/) | Medium | [1318.md](solutions/1318.md) | 位运算-中等 | |
| [1332. Remove Palindromic Subsequences](https://leetcode.com/problems/remove-palindromic-subsequences/) | Easy | [1332.md](solutions/1332.md) | | |
| [1413. Minimum Value to Get Positive Step by Step Sum](https://leetcode.com/problems/minimum-value-to-get-positive-step-by-step-sum/) | Easy | [1413.md](solutions/1413.md) | | |
| [1423. Maximum Points You Can Obtain from Cards](https://leetcode.com/problems/remove-element/) | Medium | [1423.md](solutions/1423.md) | Sliding-Window | |
| [1448. Count Good Nodes in Binary Tree](https://leetcode.com/problems/count-good-nodes-in-binary-tree/) | Medium | [1448.md](solutions/1448.md) | Tree,BFS,DFS | |
| [1457. Pseudo-Palindromic Paths in a Binary Tree](https://leetcode.com/problems/pseudo-palindromic-paths-in-a-binary-tree/) | Medium | [1457.md](solutions/1457.md) | Bit-Manipulation | Bit Mask |
| [1463. Cherry Pickup II](https://leetcode.com/problems/cherry-pickup-ii/) | Hard | [1463.md](solutions/1463.md) | Dynamic-Programming | |
| [1480. Running Sum of 1d Array](https://leetcode.com/problems/running-sum-of-1d-array/) | Easy | [1480.md](solutions/1480.md) | | |
| [1567. Maximum Length of Subarray With Positive Product](https://leetcode.com/problems/maximum-length-of-subarray-with-positive-product/) | Medium | [1567.md](solutions/1567.md) | | |
| [1576. Replace All ?'s to Avoid Consecutive Repeating Characters](https://leetcode.com/problems/replace-all-s-to-avoid-consecutive-repeating-characters/) | Easy | [1576.md](solutions/1576.md) | | |
| [1578. Minimum Time to Make Rope Colorful](https://leetcode.com/problems/minimum-time-to-make-rope-colorful/) | Medium | [1578.md](solutions/1578.md) | | |
| [1642. Furthest Building You Can Reach](https://leetcode.com/problems/furthest-building-you-can-reach/) | Medium | [1642.md](solutions/1642.md) | Greedy,Heap | TBR |
| [1658. Minimum Operations to Reduce X to Zero](https://leetcode.com/problems/minimum-operations-to-reduce-x-to-zero/) | Medium | [1658.md](solutions/1658.md) | Prefix-Sum,Two-Pointers,Sliding-Window | |
| [1669. Merge In Between Linked Lists](https://leetcode.com/problems/merge-in-between-linked-lists/) | Medium | [1669.md](solutions/1669.md) | 链表-双链表-中等 | |
| [1680. Concatenation of Consecutive Binary Numbers](https://leetcode.com/problems/concatenation-of-consecutive-binary-numbers/) | Medium | [1680.md](solutions/1680.md) | Bit-Manipulation | |
| [1689. Partitioning Into Minimum Number Of Deci-Binary Numbers](https://leetcode.com/problems/partitioning-into-minimum-number-of-deci-binary-numbers/) | Medium | [1689.md](solutions/1689.md) | | |
| [1695. Maximum Erasure Value](https://leetcode.com/problems/maximum-erasure-value/) | Medium | [1695.md](solutions/1695.md) | Sliding-Window| |
| [1721. Swapping Nodes in a Linked List](https://leetcode.com/problems/swapping-nodes-in-a-linked-list/) | Medium | [1721.md](solutions/1721.md) | Two-Pointers | |
| [1770. Maximum Score from Performing Multiplication Operations](https://leetcode.com/problems/maximum-score-from-performing-multiplication-operations/) | Medium | [1770.md](solutions/1770.md) | Dynamic-Programming | |
| [1935. Maximum Number of Words You Can Type](https://leetcode.com/problems/maximum-number-of-words-you-can-type/) | Easy | [1935.md](solutions/1935.md) | | |
| [1996. The Number of Weak Characters in the Game](https://leetcode.com/problems/the-number-of-weak-characters-in-the-game/) | Medium | [1996.md](solutions/1996.md) | | |
| [2007. Find Original Array From Doubled Array](https://leetcode.com/problems/remove-element/) | Medium | [2007.md](solutions/2007.md) | | |
| [2178. Maximum Split of Positive Even Integers](https://leetcode.com/problems/maximum-split-of-positive-even-integers/) | Medium | [2178.md](solutions/2178.md) | Greedy | |

*：按照`xx-yy-zz`格式标注的分类标准，出自[Leetcode-retag](reference/Leetcode-retag.md)这里；其他的以分号分隔Tag（例如`xx,yy,zz`）的分类则是自己的补充

**：用到的特定罕见算法、难以想到的点、值得注意的语言特性、易错点、重大启发等；`TBR`表示`To Be Reviewed`，表示需要复习，待完善
