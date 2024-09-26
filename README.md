# LATIA113-1
## 學習分析工具
* 科技115李騰騏
#### W3作業內容
```python
def nth_power(times , num):
    try: 
        times = int(times)
        num = int(num)
    except ValueError:
        return "Both 'times' and 'num' must be integers."
    if times < 0:
        return "times must be non-negetive intergers"
    result = [k ** times for k in range(num)]
    return result

times = input("請輸入次方數 :")
num = input("請輸入尾數 :")
print(nth_power(times,num))
```
#### W4作業內容  
##### 本次課堂中學到的東西
* interpolate工具-可以模擬出遺失的資料
* def自訂函數-可以自訂一些計算方式，方便重複使用
* pandas工具-可以建立DataFrames格式的資料，方便整理及輸出到Excel端
* open工具-可以開啟檔案
* write工具-可以寫入檔案內容
