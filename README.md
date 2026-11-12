# 项目代码仓库页

打开 `index.html` 即可预览：

```text
C:\Users\MECHREUO\Desktop\portfolio\index.html
```

简历里的“项目代码仓库 ↗”目前链接到：

```text
file:///C:/Users/MECHREUO/Desktop/portfolio/index.html
```

这是本机文件链接，只在当前电脑上有效。

## 页面上的源码链接

目前指向本机项目目录：

- `03-BERT/`：`C:\Users\MECHREUO\Desktop\03-BERT`
- `edu-system/`：`C:\Users\MECHREUO\.anaconda\edu-system`

## 如果要发给 HR

`file:///` 链接对方打不开。需要把 `portfolio` 上传到 GitHub Pages，再把简历 PDF 里的链接换成公网地址。

简单步骤：

1. 新建 GitHub 仓库，例如 `portfolio`
2. 上传 `index.html` 和本文件
3. 仓库 `Settings → Pages` 选择 `Deploy from a branch`
4. 分支选 `main`，目录选 `/ (root)`
5. 得到类似 `https://你的用户名.github.io/portfolio/` 的地址
6. 把 `index.html` 里的两个 `file:///...` 源码链接改成 GitHub 仓库地址
7. 重新生成简历 PDF，把超链接改成这个公网地址

在没部署之前，这个页面适合本机演示和面试时打开。
