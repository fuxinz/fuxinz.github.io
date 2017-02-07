# 前端知识
---
- ## html
1. 基本结构 
    ```
    <!DOCTYPE HTML>
    <html lang='cn'>
    <head>
    <meta charset="utf-8"
    <title></title>
    </head>
    <body>
    <h1></h1>
    <p></p>
    </body
    </html>
    ```
2. 标签属性
   
    doctype:告诉浏览器解析器以何种文档标准解析这个文档

    lang:规定内容语言
    
    meta：
    
        meta标签分为两大部分http标题信息（HTTP-EQUIV）和页面描述信息（NAME）
            
        HTTP-EQUIV相当于http的头部协议，回应浏览器有用的信息以便正确的显示当前的网页内容
                
            1.content-type和content-langruage  （显示字符集）
                <meta http-equiv='Content-Type'content='text/html'charset=''utf-8>
            2.refresh  （多久刷新或链接到其他网页）
            
        NAME描述网页以便于分类和搜索
            
            1.keywords(关键字)
                <meta name='keywords' content='关键字，关键字'>
            2.description（简介）网页的简述
            3.移动端viewport
            <meta name='viewport' content="width=,height=user-scalable=yes,initial-scale=1.5,maximun-scale=1.5,minimum-sclae=1.0"
    常用标签：
    
        1）行内元素有：a b span img input select strong（强调的语气）
        
        2）块级元素有：div ul ol li dl dt dd h1 h2 h3 h4…p
    
        3）常见的空元素：
        <br> <hr> <img> <input> <link> <meta>
        
        4）alt和title的区别
        
        5）a的target的值
        
        6）table的用法
3.表单

    表单提交的概念：
    named作用：
    post和get:
    多项提交：
    radio分组：
    
