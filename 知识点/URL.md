在 HTML 中，URL（Uniform Resource Locator）用于指定链接的目标地址。URL 是一个包含协议、主机名、路径和其他可选组件的字符串，它定义了在 Web 上定位资源的方式。

在 HTML 中，URL 主要用于以下几个方面：

1. 链接（Links）：使用 `<a>` 元素创建超链接，将文本或图像链接到其他页面或资源。URL 作为 `<a>` 元素的 `href` 属性的值被指定，例如：

   

   

   ```html
   <a href="https://www.example.com">访问示例网站</a>
   ```

2. 图像资源（Image Resources）：使用 `<img>` 元素在网页中嵌入图像。图像的 URL 通过 `<img>` 元素的 `src` 属性指定，例如：

   

   

   ```html
   <img src="https://www.example.com/images/example.jpg" alt="示例图像">
   ```

3. 脚本和外部资源（Scripts and External Resources）：使用 `<script>`、`<link>` 或 `<iframe>` 等元素引入外部 JavaScript 文件、样式表或嵌入其他网页。URL 通过这些元素的 `src` 或 `href` 属性指定，例如：

   

   

   ```html
   <script src="https://www.example.com/scripts/example.js"></script>
   <link rel="stylesheet" href="https://www.example.com/css/styles.css">
   <iframe src="https://www.example.com/embedded-content.html"></iframe>
   ```

4. 媒体资源（Media Resources）：使用 `<video>`、`<audio>` 或 `<source>` 等元素嵌入视频、音频或其他媒体内容。URL 通过这些元素的 `src` 或 `srcset` 属性指定，例如：

   

   

   ```html
   <video src="https://www.example.com/videos/example.mp4" controls></video>
   <audio src="https://www.example.com/audio/example.mp3" controls></audio>
   ```

这些示例展示了在 HTML 中使用 URL 的常见用法。URL 可以是相对路径（相对于当前文档的路径）或绝对路径（完整的网络地址），它们允许在 Web 上定位和加载各种资源。