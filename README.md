# RL_Route
Route Planning Based on Reinforce Learning
探索强化学习在路径规划问题上的应用

符号说明
$$
N = \{1,2,...,n\}:客户节点集合
x_{ij}:车辆从i行驶到j为1，否则为0
c_ij:i到j的运费
u_i:辅助变量
$$
+ TSP问题
$$
Min \sum_{i \in N}{\sum_{j \in N}{c_{ij}x_{ij}}}

s.t.

\sum_{j \in N}{x_{ij}} = \sum_{j \in N}{x_{ij}} = 1\ \ \ \ i \in N

u_j - u_i + M(1-x{ij}) \geq 0

$$
