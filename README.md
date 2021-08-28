<p align="center">
  <img width="320" src="https://wpimg.wallstcn.com/007ef517-bafd-4066-aae4-6883632d9646">
</p>

<p align="center">
   <a href="https://naiop.github.io">
    <img src="https://img.shields.io/badge/naiop-welcome-blue" alt="welcome">
  </a>
  
  <a href="https://github.com/naiop">
    <img src="https://img.shields.io/badge/naiop-me-green" alt="me">
  </a>
  <a href="https://naiop.github.io/blog">
    <img src="https://img.shields.io/badge/blog-naiop.github.io%2Fblog-green" alt="blog">
  </a>

</p>

简体中文 | [English](./README.md) 

<p align="center">
  <b>SPONSORED BY</b>
</p>
<table align="center" cellspacing="0" cellpadding="0">
  <tbody>
    <tr>
      <td align="center" valign="middle" width="250">
        <a href="https://www.duohui.cn/?utm_source=vue-element-admin&utm_medium=web&utm_campaign=vue-element-admin_github" title="img" target="_blank">
          Hexo
        </a>
      </td>
      <td align="center" valign="middle" width="250">
        <a href="https://youke.co/?utm_source=vue-element-admin&utm_medium=web&utm_campaign=vue-element-admin_github" title="img" target="_blank">
          Next          
        </a>
      </td>
    </tr>
  </tbody>
</table>

## 简介
Hexo是一款基于Node.js的静态博客框架，依赖少易于安装使用，可以方便的生成静态网页托管在GitHub和Heroku上，是搭建博客的首选框架。这里我们选用的是GitHub，你没看错，全球最大的同性恋交友网站。Hexo同时也是GitHub上的开源项目，参见：hexojs/hexo 如果想要更加全面的了解Hexo，可以到其官网 Hexo 了解更多的细节


## 前序准备
你需要在本地安装 [node](http://nodejs.org/) 和 [git](https://git-scm.com/)。

## 基本定义
在 Hexo 中有两份主要的配置文件，其名称都是 _config.yml。 其中，一份位于站点根目录下，主要包含 Hexo 本身的配置；另一份位于主题目录下，这份配置由主题作者提供，主要用于配置主题相关的选项。

```
~/hexo/_config.yml
~/hexo/themes/next/_config.yml
```

博客单间可以看我总结这篇文章 [博客搭建](https://naiop.github.io/blog/2021/05/21/Github&Hexo%E6%90%AD%E5%BB%BA%E4%B8%AA%E4%BA%BA%E5%8D%9A%E5%AE%A2/)，
**Hexo的主要**[操作命令](https://naiop.github.io/blog/2021/08/27/Hexo/)

我自己没有`Hexo Deploy`自动部署到GitHub上, `Hexo g`生成静态文件然后把 public里的静态文件手动放在GitHub pages 指定文件，hexo的路径需要修改，在hexo 配置文件config里修改，具体清空具体操作

