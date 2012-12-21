---
layout : post
category : lessons
tags : [开始]
---

##登录Github

##创建repo
## •名字必须是$username$.github.com
 
##创建disqus帐号
Site URL = $username$.github.com
shortname = $username$blogbygithub
Site Name = $username$-blog-by-github
Install Jekyll-Bootstrap
 •
git clone git@github.com:samrain/template4blog.git $username$.github.com
 
•
cd $username$.github.com
 
•
edit config.yml
 

title : 你的博客名称 name : 你的姓名 email : 你的邮箱 github : https://github.com/$username$/ production_url : http://$username$.github.com short_name : 你在disqus上注册用户的短名
 •
git remote set-url origin git@github.com:$username$/$username$.github.com.git
 
•
git push origin master
 

看看你的网站

新建一条博文
 •
Github允许用md或者html文件，本文只介绍使用Jekyll生成blog，所以只使用md文件
 
•
md文件请放在目录_posts下
 
•
md文件中---包围的是文件生成信息
      layout指的是用那个模版，默认都是post

      category:目录名称，按照个人喜好随意

      tags:标签清单，中括号包围，中间用逗号和空格隔开 
•
md文件下面是正文，必须符合Markdown语法
 
•
最后别忘记上传到Github
 
•
如果文件没有错误那么1分钟后就能看见你的新博文

