## html2image demo

工具：
[html2canvas](https://github.com/niklasvh/html2canvas)

启动：

```
npm install -g browser-sync

browser-sync start --server --files "index.html"
```

tips: 不要直接打开index.html，因浏览器同源政策将无法将canvas转化为图片

