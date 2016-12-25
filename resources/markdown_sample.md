![输入图片说明](http://www.freddon.com/images/logo.png "在这里输入图片标题")
[博客主页>>>](http://snackblogs.com/)

**第一个程序**
###HelloWorld
> javascript版 (`js` `javascript`均可)

```js
(function(w){
    var str='Hello World';
    w.alert(str);
    console.log('执行完成 %s',str);
})(window)
```

> php版

```php
<?php namespace App;
class HelloWold{
    public static function printStr($str){
        echo $str;
    }
}
HelloWold::printStr('Hello World');
```
###表格

ABCD | EFGH | IGKL
-----|------|----
a    | b    | c
d    | e    | f
g    | h    | i

| ABCD | EFGH | IJKL |
| -----|:----:| ----:|
| a    | b    | c    |
| d    | e    |  f   |
| g    | h    |   i  |

###转义字符
```
\\
\`
\*
\_
\{\}
\[\]
\(\)
\#
\+
\-
\.
\!
```
