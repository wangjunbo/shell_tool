Linux and Mac shell tools
一些可以运行在Linux和Mac上的小工具。大都是日常工作中总结出的小工具。

### 1.  rm -rf,mv 的替换工具 wmv
工作中经常遇到不小心使用 <code>rm -rf</code>命令把重要文件删除的情况，为了防止此类事件的再次发生，请使用以下命令：   
在命令行中执行以下命令，以获取wmv命令。
```
wget www.hohode.com/static/resource/wmv && chmod 777 wmv && mv wmv /usr/bin/
```
以后想要删除文件，使用以下方式进行删除：
```
wmv filename.txt
```
文件会被移动到类似 /tmp/peace/20171216220146/ 的目录下。
