背包DP變形題<br>
大小問題的關係
>if j路段右端座標<=i路段左端座標<br>
>dp[i路段右端]=max(dp[i路段右端],dp[j路段右端]+i路段長)<br>

這樣就算路段重疊也不會累加 因為這種作法會自動跳過i路段右端~j路段右端點之間的所有其他路段的左/右端點<br>
