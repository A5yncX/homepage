# Homepage

Based on [Jaredk3nt/homepage](https://github.com/Jaredk3nt/homepage)

## 自定义书签
书签现在保存在bookmarks.js文件中以便于更新. 是具有a和属性bookmarks的对象数组。定义“书签部分”框的标题。是一个链接对象数组，每个对象都有一个名称和一个要链接到的url.
```js
{ name: "xxx", url: "https://xxx.com" }
```

网站当前样式书签的长度为3, 如果您想要更多部分(超过4)，则需要更改widthcss类的属性bookmark-set.

## 自定义搜索引擎
`searchUrl`: 您可以通过将var中存储的url值更新index.html为适合您的引擎的正确字符串来更改搜索叠加层使用的搜索引擎。
```
DuckDuckGo：https://duckduckgo.com/?q=
必应：https://www.bing.com/search?q=
```

## 自定义背景

背景动画位于`styles.css:21`