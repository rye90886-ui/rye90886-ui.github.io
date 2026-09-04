# 我的个人博客

这是一个不需要安装任何软件的静态博客起点。双击 `index.html` 即可在浏览器预览。

## 发布到 GitHub Pages（免费）

1. 注册或登录 [GitHub](https://github.com)，点击右上角 **+** → **New repository**。
2. 仓库名填写 `你的用户名.github.io`，选择 **Public**，然后创建仓库。
3. 在仓库页面点 **Add file** → **Upload files**，把本文件夹中的 `index.html`、`style.css` 与 `posts` 文件夹拖进去，点击 **Commit changes**。
4. 进入 **Settings** → **Pages**，在 **Build and deployment** 选择 **Deploy from a branch**，分支选 `main` 与 `/ (root)`，保存。
5. 等待约一分钟，访问 `https://你的用户名.github.io`。

## 写下一篇文章

1. 复制 `posts/hello.html`，重命名为英文短名，例如 `my-first-note.html`。
2. 修改文章标题、日期与正文。
3. 在 `index.html` 的 `<section id="posts">` 中复制现有文章卡片，并将链接改为新文件名。
4. 将改动上传到同一个 GitHub 仓库，网站会自动更新。

## 个性化

- 博客名：搜索并替换 `我的博客`。
- 头像字母：把 `index.html` 中的 `M` 改成你的首字母。
- 主色：在 `style.css` 顶部把 `--accent:#287cff` 改成喜欢的颜色。
