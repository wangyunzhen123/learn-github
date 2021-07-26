## 1143. 最长公共子序列
(https://leetcode-cn.com/problems/longest-common-subsequence/)

 ### 思路：典型的二维动态规划问题
 首先先回顾动态规划问题的解题步骤（五步三想）：
 五步：
 1. 确定dp数组（dp table）以及下标的含义
 2. 确定递推公式
 3. dp数组如何初始化
 4. 确定遍历顺序
 5. 举例推导dp数组

三想：
-   这道题目我举例推导状态转移公式了么？
-   我打印dp数组的日志了么？
-   打印出来了dp数组和我想的一样么

解题：

 1. 确定dp数组以及下标的含义
 
假设字符串 \textit{text}_1text 
1
​
  和 \textit{text}_2text 
2
​
  的长度分别为 mm 和 nn，创建 m+1m+1 行 n+1n+1 列的二维数组 \textit{dp}dp，其中 \textit{dp}[i][j]dp[i][j] 表示 \textit{text}_1[0:i]text 
1
 [0:i] 和 \textit{text}_2[0:j]text 
2
​
 [0:j] 的最长公共子序列的长度。

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE0MTA3NTA2MjQsMTI1ODg5NTg0M119
-->