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

4.第二天重新进入网站发现乱码，写网页名为：01.html FTP上传 进后台移至wwwroot中 后发现404 或者乱码，经网查各种无果（伪静态、重启、删除面板中绑定的网站重新写入），重新写入后发现，将文件修改为 index.html即可正常显示 html页面

------

