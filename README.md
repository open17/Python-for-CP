# Python-for-CP
## 简介
个人的算法竞赛python模板  

如果没有特殊说明,默认版本`3.8`,编译器`cpython`(一般来说`pypy`也基本检验过)

其中`best-template.py`开启本地测试需要传入`--open17`
```R
python best-template.py --open17
```

## 我的c++模板仓库
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=open17&repo=CPP-for-CP)](https://github.com/open17/CPP-for-CP)

## 模板目录
### count
> 计数相关的数据结构与算法

- [x]  离散化
- [x]  前缀和与差分
  - [x]  一维前缀和与差分
  - [x]  二维前缀和与差分
- [x] 二分
  - [x] 整数二分
  - [x] 浮点二分
  - [x] 二分答案
- [x] 倍增
  - [x] 倍增优化
  - [x] 快速幂
    - [x] 快速幂取模
    - [x] 矩阵快速幂
  - [ ] 树上倍增
  - [x] ST表
- [x] 双指针
  - [x] 相向双指针
  - [x] 滑动窗口 
- [x] 树状数组
- [x] 01Tire
- [x] 堆
  - [x] 二叉堆
    - [x] 大根堆&小根堆
    - [x] 对顶堆
  - [ ] 可并堆
    - [ ] 左偏树
    - [ ] 配对堆
    - [ ] 可持久化可并堆
- [ ] 线段树
  - [ ] 普通线段树
  - [ ] 动态开点
  - [ ] 可持久化
  - [ ] 权值
  - [ ] 合并
  - [ ] 分裂
  - [ ] zkw线段树
- [x] 平衡树
  - [x] AVL
  - [x] B树(sqlite3模拟) 
  - [ ] 01Tire
  - [ ] Treap
- [ ] 单调栈
- [ ] 单调队列
- [ ] 分块
- [ ] 莫队
### graph
> 图论
- [ ] 搜索
  - [ ] DFS
  - [ ] BFS
  - [ ] 双向BFS
  - [ ] 迭代加深
- [x] 最短路
  - [x] 多源最短路
    - [x] floyd 
  - [x] 单源最短路
    - [x]  dijkstra
    - [x]  bellman-ford
    - [x]  spfa
    - [ ]  01bfs
- [ ] 最小生成树
  - [ ] Kruskal
  - [ ] Prim 
- [x]  并查集
  - [x]  按秩合并&路径压缩并查集
  - [ ]  边权并查集
- [x]  拓扑排序
- [ ] 二分图
  - [ ] 二分图判定
  - [ ] 二分图最大匹配
### math
> 数学
- [x]  数论
  - [x] 欧几里得  
  - [x]  扩展欧几里得
  - [ ]  线性同余方程
  - [ ]  费马小定理
  - [ ]  逆元
  - [ ]  原根
  - [ ]  欧拉函数
  - [x]  数论分块
  - [ ]  素数筛
  - [ ]  质因数分解
  - [ ]  积性函数与筛法
  - [ ]  莫比乌斯反演
  - [ ]  中国剩余定理
- [x]  位运算
  - [x] 位运算与集合论 
  - [ ] 位运算常见性质 
- [ ] 线性代数
  - [ ] 线性基
  - [ ] 高斯消元
- [ ] 概率论
  - [ ] 全概率
  - [ ] 贝叶斯 
  - [ ] 马尔科夫链与随机游走 
- [ ] 计算几何
  - [x] Pick定理 
  - [ ] 凸包
  - [ ] 最近点对
  - [ ] 旋转卡壳 
- [ ] 博弈论
  - [ ] 巴什博弈
  - [ ] 对称博弈
  - [ ] Nim博弈
  - [ ] SG函数 
### string
> 字符串
- [x]  字典树
- [ ]  后缀树
- [x]  后缀数组
- [ ]  KMP
- [ ]  Z函数
- [ ]  马拉车
- [ ]  字符串哈希

### dp
- [ ] 背包
    - [ ] 0-1 背包
    - [ ] 完全背包
    - [ ] 多重背包
      - [ ] 二进制优化
      - [ ] 单调队列优化
      - [ ] 同余前缀和优化（求方案数）
    - [ ] 分组背包
    - [ ] 树上背包（依赖背包）
    - [ ] 字典序最小方案
- [ ] 线性 DP
  - [ ] 最大子段和
  - [ ] LCS
  - [ ] LPS
  - [ ] LIS
    - [ ] 狄尔沃斯定理
  - [ ] LCIS
  - [ ] 长度为 m 的 LIS 个数
  - [ ] 本质不同子序列个数
- [ ] 区间 DP
- [ ] 环形 DP
- [ ] 博弈 DP
- [ ] 概率 DP
- [ ] 期望 DP
- [ ] 状压 DP
  - [ ] 全排列 DP
  - [ ] 旅行商问题（TSP）
  - [ ] 子集 DP
  - [ ] 高维前缀和（SOS DP）
  - [ ] 插头 DP
- [ ] 数位 DP
  - [ ] 记忆化搜索（同时跑上下界）
- [ ] 倍增优化 DP
- [ ] 斜率优化 DP（CHT）
- [ ] WQS 二分优化 DP（凸优化 DP / 带权二分）
- [ ] 树形 DP
  - [ ] 树的直径个数
  - [ ] 在任一直径上的节点个数
  - [ ] 树上最大独立集
  - [ ] 树上最小顶点覆盖
  - [ ] 树上最小支配集
  - [ ] 树上最大匹配
  - [ ] 换根 DP（二次扫描法）
### others
> 一些其他的内容
- [x]  卡常
- [x]  输入输出
- [x]  语法糖


## 常见疑问
### 除法
在python中`/`是浮点除法,整除是`//`
### 深拷贝
python中对于可变对象一般都是浅拷贝(复制指针)
很多时候对数组我们需要深拷贝,通常方法如下
- `deepcopy(a)`
- `a[::]`
### 字典序
python的str可以直接比较字典序
### 浮点高精度
在python中浮点数的精度是有限的!!![^1]

我们可以通过导入decimal库来实现浮点高精,其中高精度数用字符串传入
```py
from decimal import Decimal, getcontext
# 精度范围
getcontext().prec = 20
a=Decimal('6.0000003')
```
### 负数取余
python负数取余为正数,无需处理

## 学习参考

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=EndlessCheng&repo=codeforces-go)](https://github.com/EndlessCheng/codeforces-go)

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=OI-wiki&repo=OI-wiki)](https://github.com/OI-wiki/OI-wiki)

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=enkerewpo&repo=OI-Public-Library)](https://github.com/enkerewpo/OI-Public-Library)

模板中的IOWrapper和FastIO源自CF看到的pypy做法,[原链接](https://codeforces.com/profile/Yawn_Sean)

[^1]: 2023CCPC哈尔滨站血痛的教训
