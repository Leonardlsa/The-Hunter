# The-Hunter   
<font color=gold>a solo command line game</font>   
author: lsamc    
modified:charley-xiao     
working...    
2020/06/06:现在我打算将文件分离了，一个文件写那么多感觉不太好，找也不方便。先试着分离TOOL.c吧    
2020/06/06:读入程序已经更新到 THC0.3

## 注意！  
关于文件读写，数据保存在同目录下的 1.txt 文件中，read_data()用于读入数据，write_data()用于写入数据，Debug()用于输出数据到显示台。  
**注意！！任何一个需要存档的地方都需要调用write_data()！！！**  
**一共有这么几个参数，需要用的时候直接调用即可，注意下划线！！！！**  
id_,year_,month_,tons,damage_status,level_,expert_level,Tingyuan_level,xunhang_process

目标：更新数据库部分字段改为数组，更新write_data和read_data
具体：damage_status为多元数组，expert_level为4元数组，xunhang_process为2元数组
另外，需要增加player（玩家姓名字段），person_name（人物名称，后期使用，多元数组），join_time服役时间,missionName,missionType，award,achievement(这是个多元数组）字段
lsamc已更新文件查找，文件创建，删除数据库ID字段
