
###### 简单介绍
宝塔linux工具箱是一个主要面向Linux系统的脚本管理工具，已做兼容处理，兼容全部linux系统。
它包含了一键修改宝塔面板模板、去除强制登陆、一键修复面板、清除系统垃圾缓存、系统优化等一系列常见的Linux运维需求。
###### 作品截图
 ![btpanel_tools](https://gitee.com/gacjie/btpanel_tools/raw/master/btpanel_tools.jpg)   

###### 技术交流
脚本官网：www.btpanel.cm  
技术教程：www.baota.me  
QQ交流群：365208828       
TG交流群：t.me/btfans   

###### 码云项目地址命令   
 **[(点此免费领取0.99元专业版体验券，3188元大礼包)](https://www.bt.cn/?invite_code=MV9yaHFycXY=)**   
```shell-session
wget -O btpanel_tools.sh https://gitee.com/gacjie/btpanel_tools/raw/master/btpanel_tools.sh && bash btpanel_tools.sh
``` 
###### 功能说明
()清理垃圾[清理系统面板网站产生的缓存日志文件慎用]   
()系统优化[优化系统部分设置暂时只支持centos7.X]  
()登陆限制[去除宝塔linux面板强制登陆的限制]  
()停止服务[停止面板LNMP,Redis,Memcached服务]  
()修复面板[清理破解版修复面板环境并更新到官方最新]  
()修复环境[安装升级宝塔lnmp的环境只支持centos7]  
()挂载磁盘[官方的一键自动挂载工具]  
()自动换源[目前只支持更换centos7的yum源]  
()面板美化[此功能可将面板首页显示为永久企业版]  
()面板降级[支持历史版本降级操作]  
()插件优化[暂时支持所有安全插件木马查杀库的升级]  
()面板离线[用来屏蔽宝塔的通讯接口，会影响安装升级面板插件功能]  
()卸载面板[替换为官方的卸载脚本，支持只删面板不删环境，删除环境注意 ]  
()版本检测[可检测您安装的面板是否为盗版 ]  
###### 更新日志：   
2022年4月1日   
尝试兼容linux所有系统   
优化清理垃圾网站日志需要确认才会清理   
优化去登陆限制 增加检查版本号 确认是否需要降级面板    
去除广告、验证计算、修复拉黑以及彩虹一键优化等功能合并为面板优化功能    
修复面板增加与宝塔通信网络的检测与修复拉黑     
增加腾讯云专享版升级恢复功能     
减少wget的命令代码尽量本地化执行    
增加漏洞修复功能，尝试修复已知漏洞     
部分功能移除后将迁移至Linux_Tools脚本内    
2022年2月16日   
去除生成userinfo配置文件功能，修复面板增加防止被拉黑的相关功能。
新增修复拉黑功能，可修复面板并去除拉黑限制（破解版提示）。 
2022年1月9日   
更新去登陆验证，使用小号配置文件。   
2021年12月22日   
去除登陆验证兼容支持7.8.0正式版   
由于宝塔少部分推送新版本    
因此脚本支持升级到7.8.0正式版   
可能会有许多BUG，正式推送之前，生产环境建议不要升级。    
2021年12月10日   
宝塔linux7.8.27版本增加了账号解绑功能，会自动删除配置文件，而获取列表需要配置文件解密，因此后续将没办法支持去除登录限制了    
修复面板功能新增加更多文件解锁，配置文件恢复等功能。 登陆限制功能，添加选项功能，增加提示，按需使用。   
2021年11月21日   
新增功能（证书更新）更新系统中的根证书解决证书导致的问题  
本次集成从Mozilla提取的CA证书集https://curl.se/docs/caextract.html  
如：我们在配置smtp时，使用465端口无法发送，其他服务器却可以  
2021年11月08日  
()登陆限制[因新版本判断用户文件，因此增加随机生成用户登陆配置文件]   
()计算验证[集成彩虹博客的去除宝塔linux面板各种计算题与延时等待的功能]   
2021年9月7日  
()快捷启动[新增功能将本工具添加进系统，可使用btt命令快速启动]   
2021年9月3日   
()面板降级[修复无法使用报404错误]   
2021年8月29日   
()面板离线[增加api.bt.cn以及破解版域名的离线]   
()系统优化[新功能上线 暂时只支持centos7]   
()版本检测[新功能上线 可检测您安装的面板是否为盗版 ]   
()脚本更新[更改脚本升级为手动触发检测升级]   
()面板美化[删除该系列功能]    
()插件优化[查杀库升级改为一键智能升级]   
()合作宝塔[删除该系列功能]     
###### 免责条款
一、承诺不牺牲用户任何利益，无木马后门；  
二、免费开源脚本，用户可随意审查脚本内容；  
三、做好数据备份，因环境不同可能会出问题，如有问题可联系我处理，但不保证能够解决！  
