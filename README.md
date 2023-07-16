# hihids

#### 一 、介绍
hihids是一款linux下永久免费的主机安全系统，专注未知攻击对抗，也可以开源，是业界最好用的hids。

#### 二、承诺和不承诺
承诺：为了保证服务器安全，除首次安装，任何时候绝不联网，大量实战稳定可靠。

不承诺：无论任何原因引发的任何问题，都不负任何责任；请务必在测试环境完美演练后，再谨慎部署到生产环境。

注意：WEB管理9998端口禁止向公网开放，或者严格设置IP白名单访问权限。

#### 三 、主要功能
    包括物理安全、流量安全、进程安全、基线检查、SSH安全、文件防篡改、漏洞扫描等。

#### 四、安装步骤
支持Linux x86 64位系统，保证可以上网，以root权限运行下面命令：

    1、  wget http://59.110.1.135/hihids
    2、 chmod +x ./hihids
    3、 ./hihids

首次安装下载大约半分钟，出现System is running.....代表安装成功，可以WEB管理口9998（防火墙允许）登录进去。

#### 五、运行停止卸载
启动运行:  ./hihids         后台模式运行:   ./hihids daemon

停止运行:  ./hihids stop    卸载 :   rm  /hiproc/ -rf

默认没加开机启动，请自行把hihids加入开机启动程序。

#### 六、免费演示地址

实战地址 [http://59.110.1.135/hihids.html](http://59.110.1.135/hihids.html)

#### 七、付费演示地址

单机版永远免费，但开放源码、分布式集中管控、技术支持、功能增加等要收费。请用大屏电脑观看，首次加载大屏组件需要10秒：
攻击态势大屏 [http://59.110.1.135/atkmap.html](http://59.110.1.135/atkmap.html)
集中管控大屏 [http://59.110.1.135/center.html](http://59.110.1.135/center.html)

#### 八、源码部署请加微信号httpwaf

![](https://gitee.com/httpwaf/httpwaf/raw/master/img/wechat.png)

#### 九、来一张首页图片

![](https://gitee.com/httpwaf/httpwaf/raw/master/img/home.png)
