# JavaScript Algorithms & Data Structures 学习计划 (1周)

这份计划旨在帮助你在7天内系统地学习本仓库的核心内容。计划按照**由浅入深**的原则设计，并为难点预留了缓冲时间。

## 课程概览

| 天数  | 主题                | 难度       | 重点内容                           |
| :---- | :------------------ | :--------- | :--------------------------------- |
| Day 1 | 基础数据结构与算法  | ⭐         | 链表, 栈, 队列, 哈希表, 基础搜索   |
| Day 2 | 进阶数据结构 & 排序 | ⭐⭐       | 堆, 优先队列, 基础与高级排序       |
| Day 3 | 树与遍历            | ⭐⭐       | 二叉搜索树, 树的遍历 (DFS/BFS)     |
| Day 4 | 图论基础            | ⭐⭐⭐     | 图结构, 图的遍历 (DFS/BFS)         |
| Day 5 | 高级图算法          | ⭐⭐⭐⭐   | 最短路径 (Dijkstra), 最小生成树    |
| Day 6 | 动态规划 & 字符串   | ⭐⭐⭐⭐   | 动态规划基础, Trie, 字符串算法     |
| Day 7 | 复习与挑战          | ⭐⭐⭐⭐⭐ | 复杂数据结构, 疑难点攻克, 综合练习 |

---

## 详细日程安排

### Day 1: 基础夯实 (Foundations)

**目标**: 熟悉项目结构，掌握最基础的数据结构和简单算法。

- **数据结构**:
  - `linked-list` (单向链表): 理解节点的概念，实现增删改查。
  - `stack` (栈) & `queue` (队列): 理解 LIFO 和 FIFO 原理。
  - `hash-table` (哈希表): 理解哈希函数和冲突解决。
- **算法**:
  - `math`: 浏览 `factorial` (阶乘), `fibonacci` (斐波那契) 理解递归与迭代。
  - `search`: 掌握 `linear-search` (线性搜索) 和 `binary-search` (二分搜索)。

### Day 2: 排序与堆 (Sorting & Heaps)

**目标**: 掌握核心排序算法，理解堆结构及其应用。

- **数据结构**:
  - `heap` (堆): 最小堆/最大堆的实现，堆化操作。
  - `priority-queue` (优先队列): 基于堆的实现。
- **算法**:
  - `sorting`:
    - 基础: `bubble-sort`, `selection-sort`, `insertion-sort`.
    - 进阶: `merge-sort` (归并排序 - 分治思想), `quick-sort` (快速排序).

### Day 3: 树 (Trees)

**目标**: 深入理解树形结构，特别是二叉搜索树。

- **数据结构**:
  - `tree`:
    - `binary-search-tree` (BST): 插入、搜索、删除节点。
- **算法**:
  - 树的遍历: 前序 (Pre-order), 中序 (In-order), 后序 (Post-order).
  - 理解递归在树操作中的核心作用。

### Day 4: 图论入门 (Graphs Basics)

**目标**: 理解图的表示方法和基本遍历算法。

- **数据结构**:
  - `graph`: 顶点 (Vertex) 和 边 (Edge) 类。
  - 图的存储: 邻接矩阵 vs 邻接表。
- **算法**:
  - `graph` 目录下的遍历算法:
    - `breadth-first-search` (BFS - 广度优先).
    - `depth-first-search` (DFS - 深度优先).

### Day 5: 高级图算法 (Advanced Graphs)

**目标**: 解决图论中的经典问题（最短路径、最小生成树）。**（难点预警）**

- **前置知识**: 复习 `priority-queue` 和 `disjoint-set` (并查集)。
- **算法**:
  - `dijkstra`: 单源最短路径算法。
  - `kruskal` 或 `prim`: 最小生成树算法。
- **建议**: 这一天内容较难，建议结合画图来理解算法流程。

### Day 6: 动态规划与字符串 (DP & Strings)

**目标**: 接触算法中最具挑战性的动态规划思想，以及高效字符串处理。

- **数据结构**:
  - `trie` (字典树): 用于前缀匹配。
- **算法**:
  - `dynamic-programming`:
    - `knapsack-problem` (背包问题) 或 `climbing-stairs` (爬楼梯).
    - 理解 "状态转移方程" 和 "记忆化" (Memoization).
  - `string`:
    - `levenshtein-distance` (编辑距离) - 也是 DP 的一种应用。

### Day 7: 复习与挑战 (Review & Buffer)

**目标**: 查漏补缺，挑战更高阶内容，或利用 Playground 进行实战。

- **缓冲时间**: 利用这段时间深入研究 Day 5 或 Day 6 中未完全掌握的难点。
- **挑战内容 (可选)**:
  - `tree/avl-tree` (AVL 树) 或 `red-black-tree` (红黑树) - 自平衡树的实现。
  - `bloom-filter` (布隆过滤器).
- **实战**:
  - 在 `playground` 目录下尝试自己实现一个算法，并编写测试用例。

## 学习建议

1.  **多画图**: 对于树、图和递归过程，画图是最好的理解方式。
2.  **Debug**: 利用 VS Code 的调试功能，单步执行代码，观察变量变化。
3.  **看测试**: 阅读 `__test__` 目录下的测试用例，了解代码的预期行为和边界条件。
