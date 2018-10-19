# Creat_pages

建站--从入门到入神的奋斗之路

------

2018-10-18：

1.使用HTML source 标签实现网站内播放音乐

对于src音乐地址的获取，直接使用外链即可（如何用数据库实现？）

[source]:http://www.runoob.com/tags/tag-source.html



```html
<audio controls>
    <source src="horse.ogg" type="audio/ogg">
    <source src="horse.mp3" type="audio/mpeg">
</audio>
```

2.对于字体..等 居中使用

```html
myHero {
    display:block;
    background: #ddd;
    padding: 50px;
    font-size: 50px;
    text-align: center;//居中不二之选
}
```

3.操作远程主机时关机，后登陆显示无法连接

解决：进入腾讯云主机重新绑定安全组

**4**.第二天重新进入网站发现乱码，写网页名为：01.html FTP上传 进后台移至wwwroot中 后发现404 或者乱码，经网查各种无果（伪静态、重启、删除面板中绑定的网站重新写入），重新写入后发现，将文件修改为 index.html即可正常显示 html页面

------

2018-10-19

**1**.建站那天再逛博客时，发现鼠标点击出现特效，今日便心生念想，正所谓 “念念不忘，必有回响”，以中午午睡时间实现此项功能。暂虽没有理解代码含义，黑盒吧。哈哈~

[鼠标点击特效](https://blog.csdn.net/m0_38092942/article/details/80746755?utm_source=blogxgwz6)



2.音乐外链的获取方法02:

```
https://music.163.com/#/song?id=16232697
对比两者区别下者为外链
http://music.163.com/song/media/outer/url?id=16232697.mp3
```

[音乐外链获取](https://www.douban.com/note/666274833/)



3.实现myhero和music_player的契合（使用 css : padding margin radius-border）



**4**.[实现蜂窝线条特效](https://www.cnblogs.com/LionheartCGJ/p/7641635.html)

<今早产生此想法--实现类似石学长的网站背景，下载网页看源码，百度得之>

[石璀亮网站](toscl.com)

<感谢CSDN的各位前辈>

今晚宿舍四人的羽毛球还是很好玩哒，嘿嘿嘿~



2018-10-20 am 00:24



**5**.实现title的小图标显示

步骤：

I.需要16px * 16px格式为 icon的图片

[转换格式网站](https://www.easyicon.net/covert/)

III.把icon图标用FTP至网站根目录中，待使用

II.在html文件中的<head></head>里加入代码其中href="www...."中加入网站根目录图片地址

```
<link rel="icon" href="picture.ico" type="image/x-icon"/>
```

02_03.html实现

------

