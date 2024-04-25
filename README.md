# 💎 obsidian 使用

![awesome obsidian](https://img.shields.io/badge/awesome%20obsidian-7C3AED) ![last commit](https://shields.io/github/last-commit/linqing24/obsidian-usage)

> 简洁，易用

## 001 书籍卡片（豆瓣样式）

书籍卡片清单
![cardList](assets/cardList.png)

```js
TABLE without id
("![test](" + 豆瓣封面 + ")") AS 封面,
书名,
作者 + " / "+ 出版社 + " / " + dateformat(出版时间, "yyyy-MM") AS 书籍信息,
评星 + "  " + 评分 AS 评分,
摘要
FROM ""
where 书名
```

当前书籍卡片

![card](assets/card.png)

```js
TABLE without id
("![test](" + 豆瓣封面 + ")") AS 封面,
书名,
作者 + " / "+ 出版社 + " / " + dateformat(出版时间, "yyyy-MM") AS 书籍信息,
评星 + "  " + 评分 AS 评分,
摘要
FROM ""
where file.path = this.file.path
```

### 使用

下载 [001 card](./001%20card/豆瓣%20TOP.md) 库，在 obsidian 中打开即可
