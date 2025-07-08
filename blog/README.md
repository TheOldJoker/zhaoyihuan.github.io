# 博客使用说明

这个目录包含我的技术博客文章，使用Markdown格式编写。

## 📁 文件结构

- `blogList.html` - 博客文章列表页面
- `first-post.md` - 第一篇文章
- `viewer.html` - Markdown查看器
- `README.md` - 本说明文件

## 📝 如何添加新文章

1. **创建新的Markdown文件**
   ```bash
   # 例如：创建第二篇文章
   touch second-post.md
   ```

2. **编写文章内容**
   ```markdown
   # 文章标题
   
   *发布时间：2024年12月20日 | 分类：技术分享 | 作者：赵一欢*
   
   ---
   
   文章内容...
   ```

3. **更新文章列表**
   在 `blogList.html` 的 `articles` 数组中添加新文章信息：
   ```javascript
   const articles = [
     {
       filename: 'first-post.md',
       title: '我的第一篇博客文章',
       category: '技术分享',
       date: '2024年12月19日',
       excerpt: '文章摘要...'
     },
     {
       filename: 'second-post.md',
       title: '第二篇文章标题',
       category: '项目经验',
       date: '2024年12月20日',
       excerpt: '第二篇文章的摘要...'
     }
   ];
   ```

## 🎨 支持的Markdown语法

- **标题**：`# ## ###`
- **粗体**：`**粗体文本**`
- **斜体**：`*斜体文本*`
- **代码**：`` `代码` ``
- **代码块**：``` ``` ```
- **链接**：`[链接文本](URL)`
- **图片**：`![alt文本](图片URL)`
- **列表**：`- 项目` 或 `1. 项目`
- **引用**：`> 引用文本`

## 🔗 查看文章

- 文章列表：`blogList.html`
- 具体文章：`viewer.html?file=文章名.md`

## 📞 联系我

如有问题，请通过以下方式联系我：
- 邮箱：zhaoyihuan@example.com
- GitHub：[@zhaoyihuan](https://github.com/zhaoyihuan) 