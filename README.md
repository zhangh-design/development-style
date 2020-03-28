# development-style
开发风格

1. 回调事件函数中的`event`参数不要简写成`e`

```
// 不好的写法
onClick(e){}

// 好的写法
onClick(event){}
```

2. 目录如果是文件夹建议在最后加上`/`

```
// src和css都是文件夹目录，所以在css后面加上 / 表示是一层目录
// 不好的写法
gulp.dest("./src/css")

// 好的写法
gulp.dest("./src/css/")
```










