# ext_log4j
ext_log4j

这个项目其中也没什么好讲的。
基于log4j 1.x 版本的修改了日子输出方式。
添加输出指定级别的日志，以及输出指定级别以外所有其他级别的日子这两种日志输出方式。
另外，添加按天输出日志的可以指定文件大小，即在同一天内，若业务多日志输出较多的话，日志文件达到指定大小后，在该天里新生成另一日志文件，以方便以后分析查看。官方默认是同一天里只生成一个文件。
