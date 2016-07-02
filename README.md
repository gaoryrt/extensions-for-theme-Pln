# extensions for theme Pln
***
本项目的目的在于分享[个人博客](http://gaoryrt.com/)中的「[关于我](http://gaoryrt.com/CV/)」和「[友链](http://gaoryrt.com/links.html)」页面。

由于并没有用到 [hexo-theme-pln](https://github.com/gaoryrt/hexo-theme-pln) 的模板生成，所以这两个页面并不属于 Pln 主题的一部分。

相反的，这里的每一个html文件都包含了它所需的所有内容，并没有对外部css/js的请求。
***
# Install
1. 将所需的html文件放到`hexo/source`文件夹下。
2. 执行`hexo g`，得到对应的页面。
3. 得到的页面链接应为`yoursitedomain/CV.html`或`yoursitedomain/links.html`。
***
# Customize
## CV.html
以 129 - 140 行为例，该段代码在浏览器中展示如下：  
![1.png](/screenShots/1.png)  
`class="line blueback"` 蓝底黑字 路径
`class="Arr blueRightArr"` 黑底蓝色箭头
`class="line blackback"` 黑底绿字 git分支
`class="line blackback1"` 黑底蓝字 git状态
`class="line blackback2"` 黑底黄字 git状态
`class="Arr blackRightArr"` 透明底黑色箭头 
`class="line opeText"` 透明底绿字 命令
`class="line plainText"` 透明底白字 命令行的白字
`class="line plainOut"` 透明底白字 输出

通过以上class自定义页面的效果
## page.html
以 49 - 51 行为例，每一个`class="link"`表示一个友链按钮
```
<div class="link">
    <a href="https://www.logcg.com" title="落格博客">落格博客</a>
</div>
```
***
# Issues
[Issues](https://github.com/gaoryrt/extensions-for-theme-Pln/issues) are always welcome.  
欢迎您对本项目提供和意见和建议。  
(请直接提issue，或在[微博](http://weibo.com/R1T1AN)上私信，一般回复时间不超过12小时)
***
# license
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/80x15.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
