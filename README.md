# 💎 obsidian 使用

![awesome obsidian](https://img.shields.io/badge/awesome%20obsidian-7C3AED) ![last commit](https://shields.io/github/last-commit/linqing24/obsidian-usage)

> 简洁，易用

## 001 书籍卡片（豆瓣样式）

### 书籍卡片清单

![cardList](assets/cardList.png)

### 当前书籍卡片

![card](assets/card.png)

### 使用

下载 [001 card](./001%20card/) 库，在 obsidian 中打开即可

## 002 图片描述展示



### 说明

图片描述中 & 开头的内容会被显示在图片下方

markdown 写法如下

```markdown
![[preview.png|&图片描述]]
![&图片描述](./preview.png)
```

显示效果如下

![image-alt](assets/image-alt.png)

### 使用

下载 [002 image-alt](./002%20image-alt) 库，在 obsidian 中打开即可，或者直接使用代码片段

```css
.internal-embed.media-embed.image-embed.is-loaded[alt^="&"]::after {
    content: attr(alt);
    text-align: center;
    color: var(--text-accent);
    display: block;
    margin-bottom: 1.5em;
}
```
