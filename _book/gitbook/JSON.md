# JSON

----------------------------------

#### JSON 语法 验证

可以粘贴你的 book.json 去 [jsonlint.com](jsonlint.com) 验证 JSON 语法

---

#### JSON 添加注释

JSON 是不支持注释的，如果想要添加注释，可以使用两种方法

1.可以使用 key : value 添加描述
```
{
	"查询的返回结果":"",
	"resultcode":"200",
	"查询结果"："",
	"reason": "查询成功!"
}
```

2.使用JSON.minify()函数；

通过使用JSON.minify(test.json)可以删除test.json文件中的注释及空格，从而使带有注释的.json文件通过编译