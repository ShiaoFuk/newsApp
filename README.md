# 今日头条app
## 项目功能
实现一个基本app功能，可以通过爬取今日头条网页端的内容实时呈现最新的不同类别的新闻，包括体育、金融、热点等类型。
## 代码运行
导入android studio等待gradle安装完毕，build后即可运行
## 使用说明
注意没有用异步爬取，直接调用python爬虫爬取，爬取速度较慢，同时等待时间较长
## 代码架构
│  AndroidManifest.xml
│  list.txt
│  
├─java
│  └─com
│      └─example
│          └─homework1
│                  Article.java
│                  GetNews.java
│                  hot.txt
│                  InputNew.java
│                  MainActivity.java
│                  NewsPage.java
│                  Path.java
│                  Type.java
│                  
├─python
│      scrapy.py
│      
└─res
## 许可证
apache 2.0
## 联系方式
mashufu@outlook.com
