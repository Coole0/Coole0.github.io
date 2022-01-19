<!-- # VBlog
![](https://img.shields.io/badge/vue-2.5.2-brightgreen.svg) ![](https://img.shields.io/badge/element--ui-2.3.5-brightgreen.svg) ![](https://img.shields.io/badge/vant-1.1.2-brightgreen.svg)
## 目录
- [简介](#简介)
- [演示地址](#演示地址)
- [项目源码](#项目源码)
- [项目特点](#项目特点)
- [更新记录](#更新记录)
- [快速使用](#快速使用)

## 简介

博客基于 GitHub Pages 与 Github API 实现无后台，可动态发布博客的系统
博客数据储存于gist 通过Github API 进行增删改查
喜欢的话留下你的星星╭(●｀∀´●)╯╰(●’◡’●)╮


## 演示地址
[https://github-laziji.github.io][1]

## 项目源码
[https://github.com/GitHub-Laziji/vblog][3]

## 项目特点

- [x] 基于 GitHub Pages 无需服务器
- [x] 改进传统 GitHub Pages 不能动态发布的缺陷
- [x] 包含电脑端和移动端
- [x] 单页面应用


## 更新记录

#### 2018.5.19 更新
- 增加使用帮助页面
- 修复没有README.md时候出现的BUG

#### 2018.5.16 更新
- 显示粉丝数量
- 增加粉丝详情页面

#### 2018.5.15 更新
- 粉丝页面优化没有粉丝的情况
- 修改有的图片越界
- 配置增加是否自动播放音乐
- 去除默认音乐

#### 2018.5.13 更新
- 电脑端增加社交圈, 查看粉丝和关注的用户

#### 2018.5.11 更新
- 移动端增加博客, 项目, 个人中心, 移动端和PC端共用API, 页面独立 
- 修复文章样式奇怪的BUG

#### 2018.5.8 更新
- 增加配置选项
- 改善富文本编辑器

#### 2018.5.6 更新
- 状态栏增加音乐播放器

#### 2018.5.5 更新
- 增加了系统配置, 可以动态修改标题, 描述, 背景等配置 

#### 2018.5.2 更新
- 增加博客和项目列表的分页 
- 增加分享链接 
- 改进Token登陆验证 
- 修改代码结构 

#### 2018.4.30 更新
- 添加了从github获取个人开源项目的功能,显示信息更加全面,显示开源项目列表
- Readme 从github动态获取

#### 2018.4.29 更新
- 增加个人信息的状态栏
- 修复发图片博文的BUG 



## 快速使用
搭建博客只需2步
- 点击github头像旁边的 "+" 号 选择 ```Import repository ```克隆地址填 ```https://github.com/GitHub-Laziji/GitHub-Laziji.github.io ```项目名填 ```你的用户名.github.io ```
- 克隆完成后 修改文件 ```/static/configuration.json``` 中的 ```githubUsername``` 为自己的github用户名


类似演示地址其中 GitHub-Laziji 为我的用户名


现在 ```https://你的用户名.github.io``` 就是你的个人博客了,例如[https://github-laziji.github.io][1]



#### 获取Token

在 ```github > settings > Developer settings > Personal access tokens```  勾选```gist``` 和 ```repo```权限 获取```Token```


------


作者 *Laziji*



  [1]: https://github-laziji.github.io
  [2]: https://github.com/GitHub-Laziji/GitHub-Laziji.github.io
  [3]: https://github.com/GitHub-Laziji/vblog -->
