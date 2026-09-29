# 弱水三千，只取一瓢

一个简单的中文个人网站，使用纯 HTML 和内嵌 CSS 编写，无需安装依赖或构建工具。

## 内容

- `index.html`：网站主页，包含个人简介、数学公式示例和参考资料链接。
- `Deligne1971.pdf`、`Model.pdf`、`James E. Humphreys - Linear algebraic groups-Springer (1998).pdf`：主页链接的 PDF 资料。

主页使用 MathJax 显示数学公式，因此需要联网加载 MathJax CDN 脚本。

## 本地预览

可以直接在浏览器中打开 `index.html`。也可以从仓库根目录启动一个本地静态服务器：

```sh
python -m http.server 8000
```

然后访问 <http://localhost:8000>。
