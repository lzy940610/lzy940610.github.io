
# github建仓

## 参考文档

[GH + PicGO搭建图床](https://zhuanlan.zhihu.com/p/353775844)

[使用jsdelivr对gh进行cdn加速](https://www.jsdelivr.com/?docs=gh ) 

token: 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

自定义域名： https://cdn.jsdelivr.net/gh/lzy940610/assets

![](https://cdn.jsdelivr.net/gh/lzy940610/assets/img/20220508162036.png)

### 场景：原始截图很大如何破？（1M酱紫）

[Issues 地址](https://github.com/Molunerfinn/PicGo/issues/532)


在日常使用中我想大部分还是用来上传自己的一些演示demo截图比较多，但是有个问题我无论是 Macos自带的截图工具亦或是 微信、钉钉、飞书等协同软件截图出来的源文件大差不差，比如：一张全屏的截图差不多进行 1.5M ，对于这种情况有如下解决方案

![](https://raw.githubusercontent.com/lzy940610/assets/main/img/20220504171503.png)

#### 自行（手动）对原图进行一次压缩 如：tinypng 小熊猫压一下

这个还是比较笨重和繁琐的，作为有DRY（Don’t repeat yourself）原则的一名程序员，肯定不要这么搞，比较笨

#### 在上传前自动化压缩一次（本地、online）

在准备自己搞之前，去PicGo仓库下的Issues搜索了一下，看有木有现成的轮子，果不其安然有个老哥写了差点，我就不用重复造轮子了（不重复造轮子 也是DRY原则之一😊）

![](https://raw.githubusercontent.com/lzy940610/assets/main/img/20220504172139.png)

### 如何使用PicGo压缩插件？

[文档传送门](https://github.com/JuZiSang/picgo-plugin-compress)

### 使用后效果如何？

1.5M -> 268kb  🐼 🐮 🍺 ！！

![](https://raw.githubusercontent.com/lzy940610/assets/main/img/20220504172449.png)




