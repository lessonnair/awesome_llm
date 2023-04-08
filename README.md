# awesome_llm
收集最新的llm相关的知识，做关键笔记

|    论文题目    |   关键词＋概述   | 资源路径 | 说明（创新点） |
| ----------- | ------------------- | ----- | -------|
|[RWKV-v2-RNN](https://zhuanlan.zhihu.com/p/514840332)|优化RNN达到transformer的效果||设时间维度为t, 特征维度为H，对于next token，transformer计算逻辑为 norm（[1,H]*[H,t]）* (t,H)，而RWKV为[1,H]*norm（[H,t]* (t,H)）。由于norm位置的差异，造成后者可以通过动态优化的方法将计算复杂度降到1，相较于前者的t更优|
