---
title: Github Pages快速教程
tags: github 网站 blog 教程 
---

Github Pages是一个快速免费构建个人博客的方法, 现在可以结合 jekyll(博客模板 类似 hexo) 通过 github actions自动化构建博客网站, 用户只需要```git commit``` markdown文件就可以自动更新博客到对应的网址上, 比较方便.

本文将会给一个最基本版的方法去构建个人博客.

<!--more-->

## 主题模板选定
jekyll 有很多定制的模板, 为了方便可以直接去模板网站搜一个自己喜欢的, 我这里用的是这个 [TeXt Theme](https://kitian616.github.io/jekyll-TeXt-theme/). 如果想换一个的话可以在下方这些网站中去翻阅, 确定一个.
- [https://jamstackthemes.dev/ssg/jekyll/](https://jamstackthemes.dev/ssg/jekyll/)
- [http://jekyllthemes.org/](http://jekyllthemes.org/)
- [jekyllthemes.io](jekyllthemes.io)
- [jekyll-themes.com](jekyll-themes.com)


## fork 对应主题的 repo
确定好了之后就直接找到对应的 github repo, 然后点击 fork.
记得 fork 后要把名字改成 ```username.github.io``` 对于我来说就是 ```KevinvFeng.github.io``` 

按照这个格式填写就可以保证 github page 可以识别到并且这个网址可以访问这个 repo 的内容了.

## 构建github actions
在repo 的设置界面, 找到 __Pages__ (注意不是 actions), 里面的Build and deployment 选择Github Actions. 之后一路默认就行, 不太需要配置什么.

## 等待并进入 site
稍等一会, 重新刷新 settings 界面, 就能看到一个提醒是github pages设置好了, 可以进入网页访问你的博客了. 点击确认就可以搞定咯.

## 更新博客内容
首先 ```git clone```对应的repo.
之后在_posts文件夹新建对应格式的 md 文件然后仿照其他示例填写对应的文件头描述信息 剩下的更新内容就好了. 最后别忘了 ```git commit```

## TeXt Theme 教程链接
[TeXt Theme](https://kitian616.github.io/jekyll-TeXt-theme/docs/zh/quick-start)