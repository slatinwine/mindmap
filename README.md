# Mind Map · 清水混凝土

单文件思维导图工具，清水混凝土风格。无需构建、无需服务器，离线可用。

**在线使用**：<https://slatinwine.github.io/mindmap/>

## 功能

- **编辑**：`Tab` 子主题 / `Enter` 同级 / `F2` 或双击改文字 / `Del` 删除 / `Space` 折叠 / 方向键导航 / `Ctrl+Z·Y` 撤销重做；拖动节点到另一节点可重新挂接；`Ctrl+D` 重点标记；`Ctrl+C·V` 复制粘贴分支；内容自动保存在浏览器本地
- **导入**：JSON / Markdown 大纲 / FreeMind `.mm`
- **导出**：JSON / Markdown / FreeMind `.mm` / PNG（带图签）
- **共享**：生成一条内嵌全部数据的链接（deflate 压缩，URL hash），对方打开即还原

## 技术

零依赖单 HTML 文件。SVG 渲染 + 手写树布局；分享链路用 `CompressionStream` 压缩进 `#m=`。

## License

MIT

---

## 关注

| 公众号 | 小红书 · 酒里加盐 |
| :---: | :---: |
| ![公众号二维码](qrcode.jpg) | ![小红书二维码](xhs-qr.jpg) |

小红书号 `6100441379` · 酒馆会往酒里加盐，让顾客越喝越渴
