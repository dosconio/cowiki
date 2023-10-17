---
{"dg-publish":true,"permalink":"/datura-grammar/","tags":["Datura/COTLAB"],"noteIcon":""}
---


### 字符串

- 字符串允许跨行
```Datura
a = "
Multi-line string
"
```

- 如果字符串没有闭合，则默认到达文件终止，以下例程运行后 a 会被赋值为 “`a #\n# b`”
```Datura
a = "a #
# b
```
