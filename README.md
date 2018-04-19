### sublime 格式化代码快捷键设置
```s
    sublime中自建的有格式化按钮：

    Edit  ->  Line  ->  Reindent  
    

    只是sublime并没有给他赋予快捷键，所以只需加上快捷键即可

    
    Preference  ->  Key Bindings -user 


    打开用户快捷键绑定设置添加(比如添加：alt + shift + f)


    [{ "keys": ["ctrl+alt+l"], "command": "reindent" }, ]  //注意不要忘记加逗号

    注:
        1. 这里为了和 vscode 保持一致就把格式化代码的快捷键设置成  alt + shift + f
        2. 如果已经设置过 快捷键，外边已经有 [] 就不需要加 [] ,如果是第一次设置 就需要 [] 不然不会生肖
```

