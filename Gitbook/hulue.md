# 设置忽略文件

---

在 SUMMARY.md 中未列出的文件。所有静态文件，包含图片、JS、CSS都会复制到对应目录下，  
对于一些不需要的文件，GitBook将读取 .gitignore、.bookignore 和 .ignore 文件，以获取要忽略的文件和文件夹的列表。  
被忽略的文件不会被上传到版本中。  
这些文件的语法和 Git 中的 gitignore 语法相同。  


```
# This is a comment

# Ignore the file test.md
test.md

# Ignore everything in the directory "bin"
bin/*
```