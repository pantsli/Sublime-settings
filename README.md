1. Data 为protable版本的用户数据文件夹
	默认位置:~/.config/sublime-text-3/

2. sublime_text.desktop 为桌面快捷方式图标

3. 备份命令：
- Data目录： cp -r ~/.config/sublime-text-3/ ./Data
- 图标： cp /usr/share/applications/sublime_text.desktop ./
- 用户设置: cp -r ~/.config/sublime-text-3/Packages/User ./Data/Packages/User
- subl命令： cp /usr/bin/subl ./
- 中文支持： cp /opt/sublime_text_3/libsublime-imfix.so ./

