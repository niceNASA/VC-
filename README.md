# MFC Music Player 0.0.1

### 简介

​	vc程序设计的课程作业，其实就是给Windows Media Player套了层壳，我想都0202年了，除非为了应付作业，应该不会再有人用MFC写这种东西了吧。

### 按钮功能说明

- 添加文件：打开电脑中的MP3文件，并将文件名添加到列表框中

- 播放列表：打开电脑中已经存在的播放列表(.txt)文件，并将其中保存的列表信息加载到本程序中，且会清空当前程序中的播放列表

- 保存列表：将当前列表框中的播放列表保存到PlayList.txt文件中，保存格式为一首歌曲占两行，第一行是歌曲在列表框中显示的名字，第二行是歌曲对应的MP3文件在电脑中的绝对路径，“播放列表”按钮所加载的播放列表文件也必须是这个格式。由于mfc的打开文件操作会更改程序当前的工作路径，且在我的电脑上的vc6.0使用绝对路径进行保存会出现bug，因此我还是使用相对路径进行保存，保存的PlayList.txt会出现在打开过的歌曲文件目录、打开过的播放列表文件目录或程序本身所在的目录下

- 重命名条目：使用重命名编辑框中的值替换列表框中选择的条目的值

- 删除条目：删除列表框中的所有条目

- 开始播放：从头开始播放选择的歌曲

- 播放：从暂停处恢复播放歌曲

- 暂停：暂停当前播放的歌曲

### 主界面截图

![photo](https://github.com/niceNASA/MFC_MusicPlayer/blob/main/%E4%B8%BB%E7%95%8C%E9%9D%A2%E6%88%AA%E5%9B%BE.png)



Copyright (c) 2020 niceNASA