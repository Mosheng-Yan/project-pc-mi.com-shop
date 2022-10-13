# 小米商城 PC 端

## float + px

- reset.css `body{}`中

```css
/** 最小宽度与版心宽度保持一致,
防止用户放大网页导致通栏背景消失 **/
body {
  min-width: 1226px;
}
```

- reset.css 中关于`a{color:}`默认值问题,个人认为应当与`body{color:}`保持一致.(当只为 body 设置默认字体颜色,则 a 仍有其默认颜色)

- 行高继承问题

- 购物车部分(header-top-shoppingcart)当鼠标移到 cart-hidden-menu 后无法保留背景颜色问题

- 只有当鼠标移动到 header-bottom-nav 上时,header-bottom-nav-hidden 才能显示问题(不在 a 中包裹)
