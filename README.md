# 21181320
专业英语
[jump](https://github.com/possession15/21181320/blob/main/%E9%A3%8E%E7%81%B5%E7%8E%89%E7%A7%80.png)
# 上面是一张图片
## 上面是一张卡通图片
### 上面是一张二次元图片
* It is beautiful *
~~ It is beautiful ~


---
---

[外部网址:哔哩哔哩]
(https://www.bilibili.com/)



>sutudent number:21181320
[动态规划题解]
(https://github.com/possession15/21181320/blob/main/%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92)

* 动态规划
* 动态规划
* 动态规划
 * 动态规划
 * 动态规划
 * 动态规划
1. 2元
2. 3元
3. 5元

![本页面网址]
(https://github.com/possession15/21181320/blob/main/README.md)


'''
#include <iostream>
using namespace std;
int function(int x,int a[]){
    int *f=new int[x+1];
    int n=3;
    f[0]=0;
    for(int i=1;i<x+1;i++){
        f[i]=INT32_MAX;
        for(int j=0;j<n;j++){
            if(i>=a[j]&&f[i-a[j]]!=INT32_MAX)
        f[i]=min(f[i-a[j]]+1,f[i]);
        }
    }
    if(f[x]==INT32_MAX){
        return -1;
    }
    else 
    return f[x];
}
int main(){
    int x;
    int a[3];
    cin>>x;
    for(int i=0;i<3;i++){
        cin>>a[i];
    }
    cout<<function(27,a)<<endl;
    system("pause");
    return 0;
}
'''
| 随便敲的(左对齐) | 乱敲的（右对齐） | 居中对齐 |
|:---------|--------:|：--------:|


* [2333]stepfirst
* [2233]stepsecond
