# Ci-Aria2BDY  
### 基于CX-百度云盘脚本修改  
>可用于远程下载百度云盘共享文件至路由器存储设备，或家庭NAS存储设备，或调用本地Aria2加速下载文件到本地磁盘  
>1.增加Aria2远程下载支持  
>2.增加服务器RPC令牌设置提升安全性  
>3.增加本机下载支持  
>4.增加Aria2远程HTTPS接口支持  
>5.增加下载进度查看，直接在网页显示Aria2下载进度

### 插件使用教程：
>1.下载对应浏览器的油猴插件http://tampermonkey.net/  
>2.下载后拖动插件到浏览器中，有的浏览器需要打开应用中心或扩展中心页面才能安装（如果你的浏览器支持插件中心可搜索tampermonkey直接下载安装，可忽略前两步）   
>3.安装完插件后打开https://greasyfork.org/zh-CN/scripts/40496-ci-aria2  
>4.点击安装后弹出新页面，继续点击安装即可  
>5.安装完成后可以在百度云文件分享页面看到【CiAria2-下载】按钮  
>6.鼠标移上去显示下拉菜单，点击【CiAria2-下载设置】，填入你的Aria2 RPC配置后保存，如果RPC采用https协议需要在地址前指定https://  
>7.此时再点击【CiAria2-下载】可发送下载任务到你的Aria2服务器  
>8.你也可以点击【CiAria2-下载管理】打开Web管理界面查看任务下载进度

### Aria2客户端使用教程(Ci-Aria2BDY链接: https://pan.baidu.com/s/1x6Ln3z4M6h83otkgInkIKw 密码: 4e13)  
>1.从网盘分享Aria2文件夹内下载最新软件，并解压（路径最好不要包含中文）  
>2.从网盘分享下载aria2_conf.zip并解压到Aria2的目录（默认下载到Aria2目录下的/Download文件夹内）  
>3.下载HideRun.vbs放到Aria2目录，用于后台运行Aria2（如果你会使用命令启动，无需下载）  
>4.双击运行HideRun.vbs  

引用来源，你也可以自行下载  
Aria2下载地址：https://github.com/aria2/aria2/releases  
Aria2配置下载地址：http://www.pc6.com/softview/SoftView_506016.html  
