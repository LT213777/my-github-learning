# Markdown 学习笔记

## 1. Markdown 是什么？

Markdown 是一种轻量级文本标记语言，文件后缀通常是 `.md`。

它可以用简单的符号写出标题、列表、加粗、代码块、链接、图片等格式。

GitHub 上大量使用 Markdown，尤其是 `README.md` 文件。

---

## 2. 为什么 GitHub 经常使用 Markdown？

因为 Markdown 有几个优点：

- 简单易学，不需要复杂排版
- 文件很轻，本质上是普通文本
- 适合写项目说明、学习笔记、技术文档
- 适合展示代码
- GitHub 可以自动把 Markdown 渲染成漂亮的页面
- 方便 Git 记录每一次修改

---

## 3. GitHub 中常见的 Markdown 文件

### README.md

仓库首页说明文件，别人打开项目时通常最先看到它。

一般用来写：

- 项目介绍
- 使用方法
- 安装步骤
- 学习记录
- 功能说明
- 后续计划

### CONTRIBUTING.md

贡献指南，告诉别人如何参与这个项目。

### CHANGELOG.md

更新日志，记录每个版本改了什么。

### LICENSE.md

许可证文件，说明项目代码允许别人如何使用。

---

## 4. Markdown 常用语法

### 标题

```markdown
# 一级标题

## 二级标题

### 三级标题
```

显示效果：

# 一级标题

## 二级标题

### 三级标题

---

### 无序列表

```markdown
- 学习 GitHub
- 学习 Markdown
- 学习 Python
```

显示效果：

- 学习 GitHub
- 学习 Markdown
- 学习 Python

---

### 有序列表

```markdown
1. 创建仓库
2. 创建 README.md
3. 提交 commit
```

显示效果：

1. 创建仓库
2. 创建 README.md
3. 提交 commit

---

### 加粗文字

```markdown
**这是加粗文字**
```

显示效果：

**这是加粗文字**

---

### 行内代码

```markdown
`README.md`
```

显示效果：

`README.md`

适合用来标记文件名、命令、变量名等。

---

### 代码块

````markdown
```python
print("Hello GitHub")
```
