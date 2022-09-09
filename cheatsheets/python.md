# Python刷题Cheat Sheet

> Work In Progress
>
> 不定期更新

收录一些使用`Python`刷算法题时经常遇到的实用技巧。

为保证简洁，本Cheat Sheet没有包含太多细节，如存在模糊或与规范文档有出入，请以文档为准。欢迎贡献指正。

## 数值

整除：`a // b`，等价于`math.floor(a / b)`，返回最大的不超过`a / b`的整数

带余数除：`quotient, remainder = divmod(a, b)`

获取比其他数都大的值：`math.inf`，是`float`类型

获取比其他数都小的值：`-math.inf`，是`float`类型

求平方根：`math.sqrt(x)`

向上取整：`math.ceil(x)`，返回最小的不低于`x`的整数，即向正无穷取整

向下取整：`math.floor(x)`，返回最大的不超过`x`的整数，即向负无穷取整

四舍五入取整：`round(x)`

求绝对值：`abs(x)`

## 切片

`[start : stop : steps]`，可用在字符串、列表、元组上，“左闭右开”

注意：
- 三个位置的值必须都是整数，`steps`不可为`0`
- 如果`steps`为正数，则`start`和`stop`的缺省值分别是开始和结束位置；如果是负数则相反

## 字符串

字符串翻转：`s[::-1]`

字符串拼接：`s1 + s2`，注意这个操作的时间复杂度为`O(len(s1) + len(s2))`，如果有大量字符串需要拼接，考虑使用`join`（见下）

基于分隔符`x`分割成列表：`s.split(x)`，注意如果有多个`x`相邻出现，则会出现分割出空字符串的情况（例如`'xxx'.split('x')`得到`['', '', '', '']`）

使用`x`作为连接符将列表`l`中的字符串拼接成一个字符串：`x.join(l)`，`x`可以是空字符串`''`，列表`l`中所有元素必须都是字符串

获得Unicode码中值为`n`的字符：`chr(n)`，`chr(48) == '0'`，`chr(65) == 'A'`，`chr(97) == 'a'`

获得字符`x`在Unicode码中的值：`ord(x)`，`ord('0') == 48`，`ord('A') == 65`，`ord('a') == 97`

## 列表

列表翻转：`l[::-1]`

列表拷贝：`l.copy()`，或`l[:]`，或`l + []`，注意都是浅拷贝

列表拼接：`l1 + l2`，返回一个全新的列表

列表扩展：`l1.extend(l2)`，将`l2`中的元素依次`append`进`l1`

列表推导式：例如`[i * i for i in range(n)]`构建列表`[0, 1, 4, 9, 16, ..., (n - 1) * (n - 1)]`

构建长度为`n`，初始化值为`x`的一维列表：`[x] * n`，注意`x`必须是不可变类型，否则修改其中一个元素会影响到其他元素；如果`x`为可变类型（列表、字典、集合等），需要用列表推导式`[x for _ in range(n)]`

构建`m`行`n`列，初始化值为`x`的二维列表（矩阵）：`[[x] * n for _ in range(m)]`，同上`x`必须是不可变类型，否则内层也要嵌套一个列表推导式

在列表`l`中找元素`x`的下标：`l.index(x)`，返回`x`第一次出现的坐标，如果`x`不在`l`中会报错

移除列表`l`中的元素`x`：`l.remove(x)`，移除第一次出现的`x`，如果`x`不在`l`中会报错

移除列表`l`中坐标为`idx`的元素：`l.pop(idx)`，支持负坐标，或`del l[idx]`，支持切片`del l[start:stop]`

作为栈使用：压栈用`l.append(x)`，出栈用`l.pop()`，获取栈顶元素用`l[-1]`，均在列表末尾操作，时间复杂度均为`O(1)`

## 元组

元组有些类似列表，是线性结构，但其是不可变类型，可哈希，因此可以作为字典的键，或者集合的元素。

元祖`t1 = (a1, b1, c1)`与`t2 = (a2, b2, c2)`比较大小，就是先比`a1 a2`之后`b1 b2`最后`c1 c2`。由于这个特性，元组也可以做为简单的包装，用在`heapq`的操作中，详见[堆](## 堆)章节末尾的`拓展：更方便的包装，基于元组`部分。

## 字典

字典推导式：例如`{key: val for key, val in [(1, 'a'), (2, 'b')]}`构建字典`{1: 'a', 2: 'b'}`

遍历字典：`for key, val in d.items():`

获取字典某个键的值：`d.get(key, default_val)`，当`key`不存在时返回`default_val`，避免报错

带默认值的字典：`from collections import defaultdict`，创建时接受一个函数作为参数，该函数用于生成，当访问的键不存在时该键的默认值，例：`dd = defaultdict(list)`、`dd = defaultdict(lamnda: 1)`

计数器：`from collections import Counter`，类似`defaultdict(int)`，且`Counter`对象支持`+`、`-`、`&`、`|`操作，类似`set`，也可以直接通过`c = Counter(l)`生成，返回`{ key1: count1, ... }`这样的结构

// TODO sor

// TODO filter via

// TODO get


## 集合

列表去重：`list(set(l))`

取交集：`s1 & s2`

取并集：`s1 | s2`

取差集：`s1 - s2`

## 双向队列

// TODO deque

## 堆

构建堆：`heapq.heapify(l)`，`l`是一个`list`，注意构建的是最小堆，且时间复杂度为`O(n)`

获取堆顶元素：`heapq.heappop(heap)`，`heap`是经过`heapify`的`list`，下同；因为构建的是最小堆，因此返回的是最小值；此操作会导致堆顶元素出堆，若只想检查堆顶元素，使用`heap[0]`

向堆内添加元素：`heapq.heappush(heap, item)`，添加完成后`heap`依旧保持堆结构

向堆内添加元素后堆顶元素出堆：`heapq.heappushpop(heap, item)`，比单独先执行`push`再执行`pop`效率更高

堆顶元素出堆且向堆内添加元素：`heapq.heapreplace(heap, item)`，比单独先执行`pop`再执行`push`效率更高

返回可遍历集合中最大的`n`个元素：`heapq.nlargest(n, iterable, key=None)`，与`sorted(iterable, key=key, reverse=True)[:n]`等价；同理还有返回最小的`n`个元素：`heapq.nsmallest(n, iterable, key=None)`；以上两个方法基于固定大小的堆来实现，在`n`较小时效率更高，对于较大的`n`依旧考虑使用`sorted`

拓展：维护自定义对象元素堆，只需要实现自定义对象的`__lt__(self, other)`魔法函数即可

<details>
  <summary>例：维护自定义对象元素堆</summary>

  [LeetCode 692. Top K Frequent Words](https://leetcode.com/problems/top-k-frequent-words/)

  ```python
  from collections import Counter
  import heapq


  class Element:
      def __init__(self, count, word):
          self.count = count
          self.word = word

      def __lt__(self, other):
          if self.count == other.count:
              return self.word > other.word
          return self.count < other.count


  class Solution():
      def topKFrequent(self, words: List[str], k: int) -> List[str]:
          counter = Counter(words)

          heap = []
          for word, count in counter.items():
              element = Element(count, word)
              if len(heap) < k:
                  heapq.heappush(heap, element)
              elif element > heap[0]:
                  heapq.heappushpop(heap, element)

          results = []
          for _ in range(k):
              results.append(heapq.heappop(heap).word)
          return results[::-1]
```
</details>

拓展：更方便的包装，基于元组，`(value, info1, info2)`

<details>
  <summary>例：维护元组对象元素堆</summary>

  [LeetCode 378. Kth Smallest Element in a Sorted Matrix](https://leetcode.com/problems/kth-smallest-element-in-a-sorted-matrix/)

  ```python
  import heapq
  
  class Solution:
      def kthSmallest(self, matrix: List[List[int]], k: int) -> int:
          n = len(matrix)
          
          heap = []
          for row in range(min(k, n)):
              heap.append((matrix[row][0], row, 0))
          heapq.heapify(heap)
          
          while k:
              value, row, col = heapq.heappop(heap)
              if col < n - 1:
                  heapq.heappush(heap, (matrix[row][col + 1], row, col + 1))
              k -= 1
          
          return value
  ```
</details>

## 循环

从`0`到`n - 1`：`for i in range(n):`

从`n - 1`到`0`：`for i in range(n - 1, -1, -1):`，或者直接翻转`for i in reversed(range(n)):`

带下标遍历：`for idx, num in enumerate(nums):`，`idx`默认从`0`开始递增，可通过`enumerate(nums, start)`第二个参数指定起始坐标

## 排序

// TODO .sort()

// TODO reversed()

// TODO key

## 随机数

`import random`

从`a`到`b`中随机返回一个整数：`random.randint(a, b)`，闭区间

从序列中`seq`随机返回一个元素：`random.choice(seq)`，如果`seq`为空会报错

从`[0.0, 1.0)`中随机返回一个浮点数：`random.random()`

## 函数工具

// TODO lru_cache
