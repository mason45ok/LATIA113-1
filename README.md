# LATIA113-1
## 學習分析工具
* 科技115李騰騏
* W3作業內容
:::spoiler Code
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
