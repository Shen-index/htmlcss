# day-01

## 课程简介

### 内容

- 前端的课程
- HTML-CSS基础课程（从0开始）
- 直播课的速度肯定会比你自学的速度要慢，但是效果会好一些
- 欲速则不达！

### 时间安排

- 周一、周二、周四、周五（三、六、日休息）
- 时间：上午8:30 - 11:30   下午13:30 - 16:30（6个小时）
- 每天讲课时间：4个小时左右（不轻松）

### 学习方法

- 问题：记不住，不会用
- 解决办法：笨方法
  - 多敲代码！（三遍）
  - 三遍：
    1. 照着老师的代码敲一遍
    2. 在心里敲一遍
    3. 独立完成代码
- 注意：
  - 虽然每天6个小时的课程已经很辛苦了，但是为了确保你的知识学的足够的扎实，每天还需要拿出一定的时间来总结和敲代码

### 代码地址

- https://gitee.com/ymhold/html-css.git

## 前端工程师的职责

- 无论是前端还是后台工程师我们的工作都是开发软件
- 现在的主流软件都是C/S架构，C即客户端，S即服务器
  - 用户通过客户端来使用软件
  - 服务器为用户提供各种服务器
- 客户端的呈现形式：
  1. 传统的图形化界面的客户端
     - office、qq、360安全卫士、王者荣耀、和平精英...
     - 特点：
       - 需要安装，跨平台性差！
       - 开发成本高
  2. 以网页为界面的客户端（B/S架构）
     - 京东、淘宝、知乎...
     - 特点：
       - 不需要安装，跨平台性好！ 
       - 开发成本低
- 前端工程师就是负责写网页的

## 网页的概述

- 万维网的发明者是伯纳斯李
- 网页需要运行到浏览器中，有些企业嗅到这个商机开始着手制作浏览器
- 网景公司、微软公司，当时比较大的浏览器厂商
- 生产浏览器的公司，为了竞争市场份额开始了第一次浏览器大战，最终微软的ie浏览器取得了胜利
- 由于浏览器之间的恶性竞争，引发了网页的兼容问题，同样一个网页在不同的浏览器中显示效果不同
- 为了解决这个问题，伯纳斯李创建了W3C（万维网联盟）专门负责指定万维网中的各种标准
- 由于在第二次浏览器大战中，Google公司的Chrome取得绝对的胜利， 所以现在开发中几乎不再需要考虑兼容性问题了
- 根据W3C的规范，一个网页被分成了三个部分：
  - 结构、表现和行为
    - 结构，网页的结构，网页中哪里是标题、哪里是图片、哪里是链接
      - HTML负责定义网页的结构
    - 表现，网页的外在样式，网页的颜色，网页的布局..
      - CSS负责网页的表现
    - 行为，网页和用户的交互行为
      - JavaScript负责网页的行为
  - 文档：
    - https://developer.mozilla.org/zh-CN/
  - 简历：
    - 熟悉W3C的网页规范，能开发符合W3C标准的页面

## HTML

- HTML负责网页的结构

- Hyper Text Markup Language（超文本标记语言）

  - 文本：在计算机中使用纯文本编辑器编写的内容被称为文本
    - word编写的内容不是纯文本，而是富文本
  - 网页的扩展名为.html，一个网页最终由浏览器渲染呈现
  - 标记：标记用来告诉浏览器中，网页中的不同内容
    - 在网页中使用html标签作为标记，来标记出不同的内容
    - html标签：
      - 成对出现:
      - <标签名></标签名>

- HTML就是通过不同的标签来标识出网页中的不同内容，学习HTML就是学习各种标签

- 在实际开发中，不推荐使用记事本去编写代码，可以使用一些其他的纯文本编辑器来编写代码（Notepad++）

  - 但更多的是我们会采用一些更加智能开发工具来帮助我们编写代码（IDE）（vscode、webstorm）

- 网页的基本结构：

  ```html
  <!DOCTYPE html>
  <html>
  <head>
      <meta charset="UTF-8">
      <title>Title</title>
  </head>
  <body>
  
  </body>
  </html>
  ```

- !DOCTYPE html

  - 文档声明，用来声明当前网页的版本，这个用来表示当前网页是遵循HTML5规范的
  - doc 指 Document，表示文档，文档就是网页，一个网页就是一个文档
  - type 指类型 

- html

  - html根标签，一个网页有且只有一个根标签，其他标签都应该在根标签的内部

- head

  - html的子标签（子元素）
  - head表示网页的头部，可以在head中设置网页的各种数据，head中的内容不会在网页中直接显示
  - meta
    - head的子元素，用来设置网页的元数据
    - charset="UTF-8"，主要用来避免乱码问题
  - title
    - head的子元素，用来设置网页的标题，会显示在标签上

- body

  - html的子标签（子元素）
  - 网页中所有可见的内容都应该写在body的里边









