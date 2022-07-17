# Github Page + Jekyll 搭建个人博客

## [官方文档](https://pages.github.com)

[模板文档](https://github.com/kitian616/jekyll-TeXt-theme)

- [ ] liquid syntax 学习一下语法糖
- [ ] yml 专门写配置的语言 也可以学习了解一下

https://lzy940610.github.io

[我的GitHub Page](https://lzy940610.github.io)

## Blogging with Jekyll

### [Quickstart](https://jekyllrb.com/docs/)

#### 前置安装项

Jekyll requires the following:

-   Ruby version **2.5.0** or higher
-   RubyGems
-   GCC and Make

[安状引导](https://jekyllrb.com/docs/installation/#requirements)

检查一下是否安装好 （Macos下）

```shell

ruby -v
gem -v
gcc -v
g++ -v
make -v


```

![](https://cdn.jsdelivr.net/gh/lzy940610/assets/img/20220516234114.png)

### 安装 Jekyll bundler

####  Gem::FilePermissionError ❌ 错误？

![](https://cdn.jsdelivr.net/gh/lzy940610/assets/img/20220516235217.png)


##### 方案一：升级 ruby 通过 brew 、rvm或

[stackoverflow](https://stackoverflow.com/questions/18599889/error-while-executing-gem-gemfilepermissionerror)

[升级的几种方案](https://www.delftstack.com/howto/ruby/update-ruby-version-in-macos/)

rvm 安装失败

![](https://cdn.jsdelivr.net/gh/lzy940610/assets/img/20220517000842.png)


![](https://cdn.jsdelivr.net/gh/lzy940610/assets/img/20220517000842.png)


brew 升级也失败？

![](https://cdn.jsdelivr.net/gh/lzy940610/assets/img/20220517001114.png)

#### brew install 报错 ❌ 

![[Pasted image 20220517002235.png]]

方案：使用 brew doctor 提示解决


https://stackoverflow.com/questions/18599889/error-while-executing-gem-gemfilepermissionerror


#### 最终方案 sudo 给予权限 ✅ 解决问题 brew doctor 查看


![](https://cdn.jsdelivr.net/gh/lzy940610/assets/img/20220517003817.png)



### 创建一个新 Jekyll 站点

![](https://cdn.jsdelivr.net/gh/lzy940610/assets/img/20220517004321.png)

### 启动 jekyll 服务

### 浏览 dev serve

### jekyll 如何 GH一起使用

