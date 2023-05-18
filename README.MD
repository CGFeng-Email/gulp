打开目录终端
进入每个站点目录里面的 build 
终端输入开启运行 gulp 

window运行gulp报错
1.首先打开https://so.csdn.net/so/search?q=Powershell&spm=1001.2101.3001.7020以管理员身份运行。
2.输入：set-executionpolicy remotesigned
3.回车然后输入Y即可。退出powershell重新用就可以了

mac
报错：bash: gulp: command not found
1、进入到build目录
2、sudo npm install -g gulp
