---
layout: page
title:帅振华 
tagline: 专注于专业化、技术风格的质量改进
---
{% include JB/setup %}


## 最新的更新

终于使iszh.github.com开始工作。

目前关注的问题在于git命令不熟悉，可以同时使用本目录和blog,ts两个目录测试

下一步肯定会把course_units使用git管理起来

这是基于jekyllbootstrap搭建起来的，markdown很明显是另一个要熟悉的东西
    
## 博客

在没有思考清楚博客与主页的关系之前，均混合在这一页面下

博客、个人完全主页、生活、私密内容、培训业务运营主页，需要一个思考

以下为暂放置于_posts下的blog，建议有少量的tags,以减轻未来的分类工作,还未测试中文命名的后果，另外自已加日期看起来是烦人的人，应该可以自化之。

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## 当务之急

第一的要务大约是页面更新后需要手动选择UTF-8编码，我该在哪里告诉浏览器呢？

我打算把b-plan里的东西放上来吗。或者b-plan应该成为本目录下的一个文件，自动格式式化就可以了

说到自动格式化，对于latex文件，luatex读取数据库，整合HTML5的PPT,R下的动态图片，这些都是要学习的吗

我是要做一个计算机的码农吗？————这只能解释为技术型质量管理的工具吧。

