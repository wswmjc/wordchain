# 成语小状元 或者 单词小王者 类似游戏的游戏逻辑

# 主要的数据结构为二维数组，游戏逻辑主要是 二维数组的遍历计算等

```javascript
// 棋盘数据结构
const gameboard = new Array(11).fill(0).map((item) => {
  return new Array(11).fill(0).map((item) => {
    return {
      f: 0, // isFill 是否为空白
      c: "", // content 非空白时内容
      a: "", // answer  空白时应该填的答案
    };
  });
});
```
