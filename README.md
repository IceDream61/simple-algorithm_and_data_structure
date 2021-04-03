# simple-algorithm
简洁优质的算法学习路线。

## 这篇教程的目的
1. 让初学者明白自己的算法与数据结构水平、明确学习目标
2. 提供足够简洁优质的学习路线
3. 提供相关学习资料的链接（待持续完善）

## 目录
1. [如何评价你的算法水平](#如何评价你的算法水平)
2. [怎样的算法水平是够用的](#怎样的算法水平是够用的)
    2.1. [新生](#新生)
    2.2. [竞赛生](#竞赛生)
    2.3. [程序员](#程序员)
3. [如何提高算法水平](#如何提高算法水平)
4. [相关资料](#相关资料)

## 如何评价你的算法水平
本文所说的算法，专指计算机系两门专业课《数据结构》《算法》中所教授的经典算法内容，而非广义的算法或专有领域的算法。
这部分内容，往往在初学时并未配合足够的题目训练、扩展思考，而在随后的专业课学习中逐步深入。

经典算法按照大类来分，至少应包含：
- 数据结构
- 字符串算法
- 图论算法
- 搜索算法
- 数学算法
- 动态规划算法

其中每个大类又有许多小类，除了这些之外还有通用的基础知识部分。
那么，如何评价你的算法水平呢？针对每个具体知识点，都有如下几个阶段：
1. **懂得原理**，这样你便可以清楚明白地使用相关的标准库了。
2. **掌握基本实现**，即可以用你熟悉的语言来从零实现这个算法。
3. **较灵活应用**，此时你已经可以做出间接使用此算法的题目，并能够处理相关的琐碎编程细节。
4. **扩展许多、深入研究**，到这个阶段，你已经开始能够分辨近似算法的优劣，并接触相关前沿算法的研究。

**对于任何一个知识点，你都可以大致这样评价自己的水平。**

## 怎样的算法水平是够用的

### 新生
大一大二的新生，只是刚开始学习计算机，专业课也一般只接触了《数据结构》与《算法》。
这时候，针对几乎所有的知识点，只需要 **懂得原理** 就足够了，以便为后续的专业课学习打好基础。

当然，如果能较多地 **掌握基本实现** ，那是更好的~

### 竞赛生
若是希望参与ACM竞赛（或者中学OI竞赛），则几乎所有内容都应至少掌握到 **较灵活应用** 的程度。
而且书上的知识点远远不够，至少应该拓展很多竞赛常见的知识点。

这里不多介绍，只推荐一个优质的相关wiki：[oi-wiki](https://oi-wiki.org/)

### 程序员
当你已经决定成为一名程序员的时候，那么你的算法水平应该至少保证可以通过笔试面试。

除了一些惨烈的顶级公司应聘战场（例如Google的中国区）会以竞赛生的标准来要求应聘者外，大部分公司的应聘标准不会那么夸张，毕竟这只是程序员的通用基础，用来证明基础能力而已，并非岗位核心技能。

以目前（2021年4月）的市场行情来说，如果想在应聘国内一线大厂时保证不拖后腿，大致应掌握到如下程度：

| 专题     | 知识点               | 基本实现 | 灵活应用 | 扩展探究 |
|----------|----------------------|----------|----------|----------|
| 数据结构 | 栈、队列、链表       | Yes      | Yes      |          |
|          | 并查集               | Yes      | Yes      |          |
|          | 哈希表、堆、单调队列 | Yes      | Yes      |          |
|          | 平衡树               | Yes      |          |          |
| 字符串   | Trie、字符串哈希     | Yes      | Yes      |          |
|          | KMP                  | Yes      | Yes      |          |
|          | 标准库               | Yes      |          |          |
| 图论     | 存储、基本操作       | Yes      | Yes      |          |
|          | BFS、DFS、DAG        | Yes      | Yes      |          |
|          | 拓扑排序             | Yes      | Yes      |          |
|          | 最小生成树、最短路   | Yes      |          |          |
| 搜索     | 双向搜索             | Yes      | Yes      |          |
|          | 启发式搜索、A*       | Yes      | Yes      |          |
|          | 迭代加深搜索、回溯法 | Yes      |          |          |
| 数学     | 高精度               | Yes      | Yes      |          |
|          | 位运算               | Yes      | Yes      |          |
|          | 快速幂               | Yes      |          |          |
|          | 线性规划             | Yes      |          |          |
| 动态规划 | 记忆化搜索           | Yes      | Yes      |          |
|          | 背包DP               | Yes      | Yes      |          |
|          | 各类DP、DP优化       | Yes      |          |          |

## 如何提高算法水平
提高水平的方法很单纯：
- 针对每个知识点：学习知识点、练习基本题目、练习灵活题目、扩展相关知识。
- 针对整体实力：在应用中加深基础知识理解、练习综合题目和针对性训练题目（例如编程复杂度极高的模拟题）。
- 针对应用实力：参与公开比赛。

## 相关资料

### OnlineJudge
OJ（OnlineJudge，在线评测系统），是一类专做算法题在线评测的网站。根据服务人群来分，至少有：
- 面对职场人员的一类，例如[LeetCode](https://leetcode.com/)
- 面对大学ACM竞赛的，例如[ZOJ](http://acm.zju.edu.cn)、[POJ](http://acm.pku.edu.cn/JudgeOnline/)、[USACO](http://ace.delos.com/usacogate)
这类网站一般会提供很多题目与比赛，允许你用常见的语言来提交自己的代码，并立即用其精心准备的数据来评测这段代码的正误。

当然，网站各有优劣，例如leetcode的题目和资料、讨论都专门面向求职，但其评测系统的质量远不如ACM竞赛的众多OJ，于是你可以练习到一些公司的笔试面试真题，但评测出来的运行时间、空间都非常不靠谱=.=

