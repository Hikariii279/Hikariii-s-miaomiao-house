# 朵朵花园合成记

这是一个可直接托管的网页小游戏。

## 直接打开

- 本地试玩：打开 `index.html`
- 嵌入示例：打开 `embed-example.html`

## 放到网站上

把 `index.html` 上传到任意静态网站目录后，就可以直接通过网址访问。

常见方式：

- GitHub Pages
- Netlify
- Vercel
- 你自己的服务器静态目录

## 嵌入到别人的网页

把下面这段代码放进网页里：

```html
<iframe
  src="https://你的域名/游戏目录/index.html?embed=1"
  width="100%"
  height="980"
  style="border:0;display:block;"
  title="朵朵花园合成记"
></iframe>
```

如果你希望页面更矮一点，可以把 `height` 改成 `860` 到 `980` 之间。
