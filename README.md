# aptana_plugins_eclipse

Aptana 
可以百度百科：http://baike.baidu.com/view/828014.htm

一、简介
1.由于国内网络已墙aptana安装服务器，顾采用本地安装
2.本地安装使用plug zip包形式安装可能还会遇到Aptana与eclipse不匹配的情况
3.本文使用绿色安装方式，如有不妥之处请指正,大家共同交流学习：QQ:3036512853

二、安装
1.下载aptana eclipse插件，已上传到github上
	下载链接：aptana_plugins_eclipse_links.part1.rar aptana_plugins_eclipse_links.part2.rar
2.安装方法，本人以Android集成开发eclipse环境(adt-bundle-windows-x86_64-20140702)为例，使用纯净版eclipse也可以
	(1)在adt-bundle-windows-x86_64-20140702\eclipse目录下创建links文件夹
	(2)在links文件夹下创建aptana_v3.4.0文件夹
	(3)在aptana_v3.4.0目录下创建eclipse文件夹
	(4)将下载下的aptana插件中的内容(features和plugins)拷贝到eclipse文件夹下
		本人机器路径: C:\xxxx\adt-bundle-windows-x86_64-20140702\eclipse\links\aptana_v3.4.0\eclipse
	(5)在lins目录下创建aptana.link文件(注意将xxxx换成自己机器路径，window是\\路径)
		C:\\xxxx\\adt-bundle-windows-x86_64-20140702\\eclipse\\links\\aptana_v3.4.0
		