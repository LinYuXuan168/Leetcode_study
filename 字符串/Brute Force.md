- 简称BF算法，暴力匹配
- 从第一个开始一个个往后与模式串进行匹配，失败后重新从第二个开始匹配
## 算法分析
- 效率较低，原因：回溯过多，匹配了许多没有必要的比较
- **时间复杂度** ：O（m * n)
