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

 1. 确定dp数组（dp table）以及下标的含义：
 
    设字符串 text1和特性t的长度分别为m和n，创建m+1行n+1列的二维数组的dp，其中dp[i][j]表示text1[0:i]和text2[0:j]的最长公共子序列的长度，上述表示中，text1[0:i]和text2[0:j]

 3. List item

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTk0MTA1NDI5NywxMjU4ODk1ODQzXX0=
-->