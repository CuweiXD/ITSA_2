# 題目2. 英哩轉公里
### 問題描述：
試撰寫一程式，可由鍵盤輸入英哩，程式的輸出為公里，其轉換公式如下：
1 英哩= 1.6 公里

### 輸入說明：
輸入欲轉換之英哩數(int)。

### 輸出說明：
輸出公里(double)，取到小數點以下第一位。

### 範例：
#### 輸入範例:
90

95

#### 輸出範例:
144.0

152.0

### 解答
```
#include <iostream>
#include<iomanip>
using namespace std;

int main()
{
    double x = 0;
    double ans = 0;

    cin >> x;
    ans = x * 1.6;

    cout << fixed << setprecision(1) << ans << endl;

    return 0;
}
```
