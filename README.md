# Stylus 用户样式

存放供浏览器 [Stylus](https://github.com/openstyles/stylus) 扩展使用的 `.user.css` 样式脚本。

## 贴吧手机视图适配

- `tieba-mobile/tieba-mobile.user.css` — **v3.0.7（推荐使用）**。一个文件同时适配 PC 版百度贴吧的吧内列表页（`/f?kw=`）与帖子详情页（`/p/`）在窄视口 / 浏览器手机视图下的显示：放大字号、统一并限制图片高度、修掉详情页 `min-width: 473px` 造成的横向溢出。作用域为 `@-moz-document domain("tieba.baidu.com")`。
- `tieba-mobile/legacy/tieba-list.user.css` — v2.0.0 旧版，仅列表页。
- `tieba-mobile/legacy/tieba-thread.user.css` — v2.0.0 旧版，仅帖子详情页。保留作历史参考。

### 安装

在 Stylus 中选择「从 URL 安装」并填写：

```
https://raw.githubusercontent.com/zwxbest/stylus/main/tieba-mobile/tieba-mobile.user.css
```

或直接把这个 `.user.css` 文件拖进浏览器，由 Stylus 接管安装。
