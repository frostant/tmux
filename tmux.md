# TMUX

tmux是一个插件。 作用简单来说就是在一个cmder可以运行多个程序，即把部分程序放到后台运行（例如：网址运行程序）。我用于防止云服务器断开连接（云服务器在你一段时间没有行动后会自动断开连接）

[入门博客](https://blog.csdn.net/skykingf/article/details/46345057) 

## 基本用法:

ctrl+b是tmux的快捷键开始键（即快捷键为ctrl+b 再按其他键）

1. tmux ls 查看目前session
2. tmux new -s session-name 新建session
3. tmux a -t session-name 接入session（就是进入session）
4. tmux detach（快捷键：ctrl+b d）断开session（退出窗口）
5. tmux kill-session -t session-name 删除session（删除这个窗口（进程））



## 其他快捷键：

![tmux快捷键](C:\Users\sky48\Desktop\github\tmux\tmux快捷键.png)