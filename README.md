# minimal-music-for-c#
重构音乐播放器（功能和electron版一致）

无需安装，双击exe运行



播放器首次运行文件：

自动生成bitmapimage文件夹，加载歌曲将专辑封面存在bitmapimage文件夹（300首歌曲大概占用5m）

自动生成music.json

备注：重新加载歌曲，会刷新bitmapimage和music.json

外观
![image](Snipaste_2026-08-16_10-47-03.png)

内存占用[20-200，日常维持50]
![image](Snipaste_2026-08-16_11-07-59.png)

问题：

1.遇到内存占用升高[最高200m左右]如何解决？

切换歌曲，或重新打开

2.替换新exe后，使用旧数据直接运行exe，内存占用变高？

切换歌曲，或重新打开

不行就删除所有旧数据，重新运行exe


