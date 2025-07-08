# 博客使用说明

## 📝 如何添加新文章

1. **创建新的Markdown文件**
   ```bash
   # 在blog目录下创建新的.md文件
   touch blog/second-post.md
   ```

2. **编写文章内容**
   ```markdown
   # 文章标题
   
   *发布时间：2024年12月20日 | 分类：技术分享 | 作者：赵一欢*
   
   ---
   
   文章内容...
   ```

3. **更新文章列表**
   在 `viewer.html` 的 `mdFiles` 数组中添加新文件名：
   ```javascript
   const mdFiles = [
     'first-post.md',
     'second-post.md'  // 添加新文件名
   ];
   ```

## 🔗 查看文章

- 文章列表：`viewer.html`
- 具体文章：`viewer.html?file=文章名.md`

## 📞 联系我

如有问题，请通过以下方式联系我：
- 邮箱：zhaoyihuan@example.com
- GitHub：[@zhaoyihuan](https://github.com/zhaoyihuan) 