[问题链接](https://codeforces.com/problemset/problem/1806/C)

- 对于一个长度为 $2m$ 的序列 $q$ （ $m$ 为正整数），其被认为“好的”，当且仅当对于其中所有长度为 $m$ 的子序列，其每个元素的**乘积**等于所有不在这个子序列中的元素的**和**；（形式化地说，令 $U = \{1, 2, 3, \ldots 2m \}$ ，对于所有 $S \subseteq U$ ，其中 $|S| = m$ ，有 $\prod_{i \in S} q_i = \sum_{i \in U \setminus S} q_i$ ）

- 定义长度为 $k$ 的序列 $a_i$ 和 $b_i$ 的“距离”为 $\sum_{i = 1}^k |a_i - b_i|$ ，即对应元素的差的绝对值之和。

- 给定 $n$ 和长度为 $2n$ 的序列 $p$ ，求和 $p$ 距离最小的“好的” $q$ ，无需输出 $q$ ，输出最小距离即可。


