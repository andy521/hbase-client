### 介绍
Hbase-client包含一个基于javascript的客户端容器和一个对用户透明的server，这种设计使得桌面应用具备了web工程的特性，在网络无法联通的情况下，你可以将server和客户端分离，同时也意味着你可以使用web的开发方式开发桌面应用，遵循Apache 2.0协议 
 
### Quick Start
解压后双击`hclient.exe`启动程序；单击右上侧`配置`，配置连接信息，也可在`app/hclient.ini`文件中配置

### 特性
* 左侧为表区域，支持创建表、删除表（按Ctrl可以多选）、清空表
* 支持按rowkey查询（支持正则）和ColumnValue过滤器链查询
* 支持新增、删除、统计行数、批量删除
* 在表格上右击参数可以直接复制内容
