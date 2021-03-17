---
title: Hello World
---
如何搭建hexo 博客?推荐一个不错的方法！请查看[hexo个人博客](https://www.cnblogs.com/visugar/p/6821777.html)

## git 推送代码到github

```bash
    # 第一次提交
    git init
    git add README.md
    git commit -m "first commit"
    git branch -M main
    git remote add origin https://github.com/wuruixuan2464/personal.git
    git push -u origin main

    # 推送
    git add .
    git commit -m '提交说明'
    git push
```

## 一般报错

```bash
OpenSSL SSL_connect: Connection was reset in connection to github.com:443

解决方法

git config --global http.sslVerify false
```
