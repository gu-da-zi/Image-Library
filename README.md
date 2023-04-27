# 使用 HTML、CSS 和 JavaScript 制作图片库

这是一个使用 HTML、CSS 和 JavaScript 制作的图片库项目，它使用 Pexels API 来获取图像数据。通过这个库，用户可以快速搜索、查看和下载任何他们想要的图像，所有这些都可以在几秒钟内完成。

## 安装和使用

1. 克隆此代码库。

```bash
git clone https://github.com/your_username/pexels-gallery-clone.git
```

2. 进入项目文件夹。

```bash
cd pexels-gallery-clone
```

3. 将你的 Pexels API 密钥添加到 `js/script.js` 文件中。

```javascript
const apiKey = 'YOUR_API_KEY_HERE';
```

4. 在浏览器中打开 `index.html` 文件，即可开始使用。

## 功能

- 搜索栏：输入关键词以搜索图像。
- 图像展示：通过瀑布流布局显示图像。
- 懒加载：仅在滚动到图像时才加载图像，提高加载速度。
- 图像放大：点击任意图像以查看大图。
- 图像下载：通过点击下载按钮来下载图像。
- 加载更多：点击“Load More”按钮加载更多图像。

## 技术栈

- HTML
- CSS
- JavaScript

## 贡献者

- [gu-da-zi](https://github.com/gu-da-zi)

## 许可证

本项目采用 [MIT License](https://github.com/your_username/pexels-gallery-clone/blob/master/LICENSE) 许可证。
