---
layout: post
title: "我的第一个博客"
date: 2016-07-05 07:23:22 +0800
comments: true
categories：javascript
---
#我的第一个博客
##学习markdown语法
>引用


**加粗**

`标亮`

- 一级
- 一级
    - 二级
    - 二级
- 一级


[百度](www.baidu.cn)

![img](https://pic3.zhimg.com/6d4722fa8850de8c58e77cdbe341d2c4_270x225.png)

{% video https://www.youtube.com/watch?v=o4PFDKIc2fs https://i.ytimg.com/vi/o4PFDKIc2fs/hqdefault.jpg?custom=true&w=196&h=110&stc=true&jpg444=true&jpgq=90&sp=68&sigh=b3xIMHuisErvUHu4kyEny2xg5g8 %}

```
 function getCookie(c_name){
        if (document.cookie.length>0){ 
            c_start=document.cookie.indexOf(c_name + "=")
            if (c_start!=-1){ 
                c_start=c_start + c_name.length+1 
                c_end=document.cookie.indexOf(";",c_start)
                if (c_end==-1) c_end=document.cookie.length
                return unescape(document.cookie.substring(c_start,c_end))
            } 
        }
        return ""
```

{%codeblock%}
  function getCookie(c_name){
        if (document.cookie.length>0){ 
            c_start=document.cookie.indexOf(c_name + "=")
            if (c_start!=-1){ 
                c_start=c_start + c_name.length+1 
                c_end=document.cookie.indexOf(";",c_start)
                if (c_end==-1) c_end=document.cookie.length
                return unescape(document.cookie.substring(c_start,c_end))
            } 
        }
        return ""
{%endcodeblock%}

