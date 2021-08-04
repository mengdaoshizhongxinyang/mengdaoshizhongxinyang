面试题？具体数学第一章不谢，约瑟夫环，书里魔法般的推出了递归过程（这书真的，到处魔法般推出公式

```cpp
class Solution {
public:
    int lastRemaining(int n, int m) {
        int a=0;
        for(int i=2;i<=n;i++){
            a=(a+m)%i;
        }
        return a;
    }
};
```