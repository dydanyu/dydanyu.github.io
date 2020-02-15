---
title: 如何使用Markdown语法写博客
date: 2019-07-10 14:56:59
tags:
- Makdown
- Hexo
---
## Hexo 新建文章指令
```bash
    $hexo new post "blogname" //四个空格+code即为代码行  

    $hexo clean  //清除静态页面缓存
    $hexo g  //在本地生成静态页面
    $hexo s  //在本地服务器中预览
    $hexo d  //远程部署到Github
```
```javaScript
<script>
    window.onload=function(){
          var btn=document.getElementById("btn");
          btn.onclick=function(){
              alert("点我一下");
          };  
    };
</script>  //反引号··· code  ····之间可以放多行代码
```
> 测试   // > 表示引用，双空格加回车可以换行

- 123 //- 表示列表
- 345  
 *斜体* //* *

<!--more-->
