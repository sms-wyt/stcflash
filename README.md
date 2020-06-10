# stcflash
Add support for STC8 series and STC15 series
# 新增功能
1、添加对STC8和STC15系列单片机的下载支持;<br>
2、对于STC8系列，新增支持波特率4800-460800之间的任意波特率设定;<br>
3、新增对于STC8和STC15系列单片机的基本信息读取显示
# stcflash基本使用方法
## 使用条件
1、需要python环境，推荐python3;<br>
2、安装pyserial模块;<br>
## 使用命令
1、按照默认参数<br>
  ./stcflash.py xxx.hex<br>
2、指定波特率、端口和下载协议<br>
  ./stcflash.py xxx.hex --port COM3 --protocol 89
