1. 下载解压 
	tar -xvf  sublime_text_3_build_3176_x64.tar.bz2 解压

2. 解压完成以后，移动到/opt/这个目录下，这个目录是装软件的
	sudo mv sublime_text_3 /opt/

3. 复制subl命令脚本
	sudo cp subl /usr/bin/

4. 创一个快捷键执行
	cp /opt/sublime_text_3/sublime_text.desktop /usr/share/applications
	配置Sublime Text，
	vim /usr/share/applications/sublime_text.desktop
	执行命令更改配置文件

5. sublime 3176 注册
- 修改hosts文件：
```
	hosts文件位置
		Windows : c:/windows/system32/drivers/etc/hosts
		Linux : /etc/hosts
		Mac : /Private/etc
	输入
		0.0.0.0 www.sublimetext.com
		0.0.0.0 license.sublimehq.com
```
- sublime text 3 注册码（2018/06/19）：

```
----- BEGIN LICENSE -----
sgbteam
Single User License
EA7E-1153259
8891CBB9 F1513E4F 1A3405C1 A865D53F
115F202E 7B91AB2D 0D2A40ED 352B269B
76E84F0B CD69BFC7 59F2DFEF E267328F
215652A3 E88F9D8F 4C38E3BA 5B2DAAE4
969624E7 DC9CD4D5 717FB40C 1B9738CF
20B3C4F1 E917B5B3 87C38D9C ACCE7DD8
5F7EF854 86B9743C FADC04AA FB0DA5C0
F913BE58 42FEA319 F954EFDD AE881E0B
------ END LICENSE ------
```

- 禁用 Sublime Text 3 检测新版本
	1. 设置 Preferences -> Settings-User
	2. 添加 "update_check": false
	3. 或者把127.0.0.1 www.sublimetext.com加入到你的host文件

- 解决中文无法输入问题
	sudo cp ./libsublime-imfix.so /opt/sublime_text_3/
	sudo cp ./subl /usr/bin/

- 安装 YaHei Consolas Hybrid字体
	双击执行 YaHei.Consolas.1.11b.ttf

- 安装Package Control

- 插件安装

