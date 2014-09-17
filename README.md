Front-End-Wiki
==============

整理工作中遇到问题和一些资料


###CSS:###

1. 用到极致的css3伪类（before、after）http://a.singlediv.com/

###Javascript###

1. js词法作用域

    http://zh.wikipedia.org/wiki/%E4%BD%9C%E7%94%A8%E5%9F%9F

    http://www.nowamagic.net/javascript/js_ScopeBase.php

    http://www.zhihu.com/question/20032419

```
var tt = 'aa';
function test(){
    alert(tt); //undefined
    var tt = 'dd';
    alert(tt); //dd
}
test();
```

```
var tt = 'aa';
function test(){
    alert(tt); //aa
    tt = 'dd';
    alert(tt); //dd
}
test();
```
