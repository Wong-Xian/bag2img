# 目的：练习从 .bag 文件中提取图片并在图形化界面中显示出来

用到的命令：

``` shell
rosbag info [bagfile]   // 查看 bagfile 的属性信息

rosbag record (-a / -O) // 记录数据，-a 表示记录所有 topic -O 表示修改输出 bag 文件的文件名

rosbag play -r 2 [bagfile]   // 重现 bag 文件，-r 表示设置重现速率
```

了解rviz工具。

main line