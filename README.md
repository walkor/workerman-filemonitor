# workerman-filemonitor
监控文件更新并自动reload workerman。默认只监控Applications目录，如果要监控其它目录，请更改Applications/FileMonitor/start.php中$monitor_dir，路径最好使用绝对路径。

# 注意
只能更新onXXX中加载的文件，启动脚本直接加载的文件和代码无法自动更新

只有在debug模式启动后才有效，daemon模式不生效。

# 使用
直接将Applications下的FileMonitor目录拷贝到你自己的Applications目录下，重启workerman即可
