# tinymodulez
小模组QZ的附件表

BiliBili小模组QZ 10月26日建立的附件表
QQ群：652188416（群主禁止交流）
Skype群：join.skype.com/u8LcM1yj3Xmf（群主正常聊天）
注意：该附件表将在2025年2月20日迁移到github及新文档上
QQ群：

Skype群：

受云视听小电视（哔哩哔哩TV端）支持的视频：
1.分享六款实用小工具 发布日期 2024年8月28日（首发视频）
2.记录Ubuntu 18.04升级到20.04的过程 发布日期 2024年9月14日
3.2024年，我用回了XP系统 发布日期 2024年9月16日
4.全新的界面但有着bug，Ubuntu 24.10 Beta版抢先体验 发布日期 2024年10月2日
5.Windows 11 24H2正式版安装体验（含LTSC版）发布日期 2024年10月4日
6.Lubuntu适合老电脑让老电脑变身服务器 发布日期 2024年11月2日
7.Windows Server 2025服务器系统（包括VMware虚拟机安装教程） 发布日期 2024年11月9日
8.2024年，Ubuntu 18.04还能用吗？ 发布日期 2024年11月16日
9.解开极域（无剪辑制作） 发布日期 2024年11月30日
10.全新版本的Windows 11 IoT LTSC 2024，能全自动化的安装，下载包含网盘 发布日期 2024年12月1日
11.PPC版Mac OS X安装 发布日期 2024年12月8日
12.huang1111网盘将在2025年关闭的事故，我都没法更新资源分享库了 发布日期 2024年12月12日
13.我电脑装了三个系统...... 发布日期 2025年1月14日
14.2025年1月Windows 10或11的累积更新，建议装上（上集） 发布日期 2025年1月15日
15.小模组QZ自己制作的Win11 IoT LTSC，默认永久激活 发布日期 2025年1月17日
16.我把一些好用的资源分享给大家，你们可以去看看 发布日期 2025年1月25日 单次播放

2025年1月31日 15:13统计：云视听小电视收到小模组QZ视频的总播放量为1732

资源分享链接：
链接1：https://pan.huang1111.cn/s/Wz11ou3
链接2：https://pan.xiaomuxi.cn/s/9mZGtd
警告：链接1与链接2有差异

链接2提供：
提供新资源更新，暂时没有huang1111网盘关闭之前转移的文件
这里免登录，免注册，就可以高速下载哪些视频想要的内容
Part 1：默认桌面太卡，容易死机？XUbuntu轻量级系统如何让老电脑更流畅，搭建服务器
如果你的老电脑是机械硬盘，装Win7、Win10、Win11系统，那么开机速度慢，打开软件慢，如果用的是精简版的系统，那么会导致某些系统组件出现问题，如果这样慢的话，装XP系统虽然有稳定性要求，但是会蓝屏死机，而Ubuntu的原版桌面系统比较卡顿，打开个软件卡半天，因为基于GNOME环境可是舍不得买一块固态硬盘，因为固态硬盘要200~300了。

那么废旧的老电脑不要扔，变身一台SSH、FTP、NAS、Docker的电脑，再战5年

那么有没有兼容性好，速度快的系统有没有呢？

答案应该有，就是XUbuntu了

如何下载？

1.打开官网：https://xubuntu.org

2.找到Xubuntu 24.04这里的Download按钮

问题：Xubuntu虽然有24.10的版本，但是战了1年后，就无法获取软件包以及更新（不推荐下载该版本）

3.国内使用种子下载的话，速度会慢，这里选择下面的Mirror downloads里面的China，然后会跳转到清华源里面的xubuntu的下载点

xubuntu分为了两个版本，一个是桌面版，一个是迷你版

这边我为了更好的体验，我就选xubuntu-24.04.1-desktop-amd64.iso，也就是桌面版，大小3.81G，而原版的ubuntu-24.04.1-desktop-amd64.iso的大小为5.77G，相差了1.96G，我为什么是选xubuntu呢？因为xubuntu的兼容性多，功能齐全

4.使用烧录软件，准备一个8G的U盘，使用的工具可以是Rufus或balenaEtcher进行烧录制作（注：该操作会格式化U盘，请备份好所有数据）

如果你使用的是已经制作好Ventoy的U盘，可以把ISO文件拖进U盘里面方便启动，资料及ISO不受影响

如果没有制作Ventoy的U盘，可以去官网下载Ventoy，执行Ventoy2Disk程序来制作VentoyU盘（注：该操作会格式化U盘，请备份好所有数据）

怎么安装？

5.开机，按键盘的Delete、F1、F2键进入BIOS设置（不同品牌的主板会有所不同）

设置步骤，将SATA模式改为AHCI，提高硬盘效率

确保你的电脑使用的是支持UEFI模式启动的，将启动模式设置为UEFI启动，方便快捷。可以将带UEFI的U盘启动项设置为第一启动项，如果没有UEFI，可以把不带UEFI的U盘启动项设置为第一启动项

开启虚拟化技术：如果你想让老电脑跑KVM运行虚拟机，那么可以把Intel 虚拟化技术（Intel）/SVM Mode（AMD）进行开启，开启后，就可以跑KVM运行虚拟机了

设置完毕后，按F10保存

6.进入U盘启动，你会来到这个页面

按回车进入Xubuntu安装程序

安装界面跟原版ubuntu相同，比较简单

安装完成后会提示

Please remove the installation medium, then press ENTER:

拔出U盘，按回车重启电脑

就可以进入Xubuntu了，但是有一个问题就是xubuntu汉化不完全，我们需要解决一下

7.解决汉化不完全

打开一个终端，输入“sudo dpkg-reconfigure locales”

第一个问题我直接按回车

第二个问题这里选择第三项zh_CN.UTF8

设置完成后重启生效，因为软件仓库不断更新，需要执行软件更新器或在终端输入

“sudo apt update”

“sudo apt upgrade -y”

完成更新

8.安装SSH服务器外壳

打开一个终端，输入“sudo apt install openssh-server”

按y回车，就可以了

查看IP地址

直接输入ifconfig会提示“找不到命令”，我们需要输入“sudo apt install net-tools”

再次输入ifconfig

找到inet后面的192.168.xx.xxx就是服务器的IP

在你的电脑、手机上打开终端，输入ssh #ip地址# -l #用户名#

出现提示输入yes，输入密码就能连接到服务器的SSH了

9.安装XRDP远程桌面

如果想要在老电脑上远程使用电脑，那么可以安装一个xrdp桌面

打开一个终端，输入“sudo apt install xrdp”就可以安装了

安装完成之后，还需要配置一下

sudo adduser xrdp ssl-cert  

sudo systemctl restart xrdp

echo xfce4-session>>~/.Xsession

最后我们使用微软远程桌面连接服务器就可以了

（注：确保服务器的控制台不被登陆，自动登陆要关闭，防止连接后自动断开）

10.安装open-vm-tools（VMware虚拟机专用）

打开一个终端，输入“sudo apt install open-vm-tools”

按y回车安装，就可以复制文件

11.安装任务管理器，因为这个系统没有任务管理器，不能查看系统性能

常见的任务管理器有：

lxtask：“sudo apt install lxtask”

gnome的系统监视器：“sudo apt install gnome-system-monitor”

mate的系统监视器：“sudo apt install mate-system-monitor”

kde的系统监视器：“sudo apt install plasma-systemmonitor”

ukui的系统监视器：“sudo apt install ukui-system-monitor”

lxtask是轻量级的任务管理器，安装完会多出任务管理器

12.给xfce套上Yaru主题（ubuntu默认主题）

sudo apt install yaru-theme*

打开xfce设置里的外观，将样式设置为Yaru，开启有则设置匹配的 Xfwm4主题，将图标设置为Yaru就可以了，如果想深色模式，可以选择“Yaru-dark”

OK，这样我们的老电脑已经焕发一新了，不升级硬件就能搭建服务器了，是不是很神奇呢？别忘了一键三连，我们下期再见

下载链接：
普通版：https://mirrors.tuna.tsinghua.edu.cn/ubuntu-cdimage/xubuntu/releases/24.04/release/xubuntu-24.04.1-desktop-amd64.iso
迷你版：https://mirrors.tuna.tsinghua.edu.cn/ubuntu-cdimage/xubuntu/releases/24.04/release/xubuntu-24.04.1-minimal-amd64.iso

Part 2：给老旧电脑搭建一台frp服务器，配合公网IP建立实现内网穿透https://docs.qq.com/mind-addon
首先我们下载frp：
https://github.com/fatedier/frp/releases
1.这个软件支持安卓、FreeBSD、MacOS（Darwin）、Linux、Windows系统
上一个文章讲了这个老电脑可以变成服务器的系统的安装过程，现在可以做任何事情了，可以跑docker、ssh、xrdp、nas、ftp了，除了这些还可以跑MC、Frp服务器，对于老电脑来说，相当nice！
2.现在那个老电脑已经当成一台xubuntu服务器的话，那么只需要电源线和网线，开机就可以使用了，在客户端上打开远程桌面连接，输入服务器的IP地址，连接后，输入账号和密码，就能看到服务器的桌面了
解压并运行frps：
1.将下载好的文件复制（不是拖进服务器），在服务器上右键，粘贴，解压文件，在frp文件夹里面打开终端，执行./frps -c frps.toml按回车就可以启动frp服务端了
将frps设置为自启动
1.在这个frp的文件夹里面创建txt文档

2.名称为frps.sh
3.编辑以下内容

cd 是frp的文件夹路径
./frps -c frps.toml，保存即可
4.开始菜单，设置，会话和启动

应用程序自启动，添加

名称和描述随便填，命令这里输入sh #frps.sh文件的地址#，触发器选择登录时

不过这样做的话只能在xrdp登陆的时候会自动开启，直接开机是不行了
现在你可以使用frpc客户端连接服务器了
如何配置frpc？
1.编辑frpc.toml这里

serverAddr是frps的服务器IP地址
serverPort是frps的服务器端口（如果是自定义的端口，要跟着这个端口）
name是名称
type是类型，支持tcp/udp/http/https等
localIP是本地IP，如果想利用其它设备辅助，可以输入内网设备IP
localPort是本地端口
remotePort是远程端口，不要对服务器端口冲突
2.修改完毕后，保存退出即可
如何启动frpc？
打开终端，输入命令
./frpc -c frpc.toml，就可以执行了
想要使用公网IP？
1.如果没有公网IP，可以打电话申请公网IP
2.申请后，需要配置路由器，光猫等内网穿透，并且以拨号上网
3.操作完毕后，可以用服务器的公网IP连接frps了
Part 3：如何播放汕头新闻，汕头今日视线等内容？
汕头新闻：普通话 汕头新闻综合频道 中央新闻联播结束后+广告，首次播出时间为每天19：40
汕头今日视线：潮汕话 汕头经济生活频道 首次播出时间为每天19：00
汕头美食地图：普通话 汕头经济生活频道 首次播出时间为每星期五18：33
汕头中医非常道：潮汕/普通话 汕头经济生活频道 首次播出时间为每星期三18：33
汕头健康新生活：普通话 汕头经济生活频道 首次播出时间为每星期日18：33
汕头民生热线：未知
打开网站https://strtv.dahuawang.com
有很多节目，可以选择一个，播放观看，完全免费
手机也可以下载汕头橄榄台登陆观看电视直播或节目
汕头台：预祝11月18日汕头两大盛会
Part 4：Lubuntu系统，最轻量，超简单，一系列的下载
上期专栏中，我讲了Xubuntu让老电脑焕发一新，虽然是Linux系统，
但是内置了应用中心，特别适合新手装软件，搭建服务器，
并且在专栏里面有Xubuntu的某些教程。
那么走进Lubuntu的安装过程
安装方式跟原版不同的是，使用的是传统的ubiquity的安装程序
安装完成后，我们可以一些步骤：
安装SSH服务端：sudo apt install openssh-server
安装XRDP服务端：sudo apt install xrdp
安装open-vm-tools：sudo apt install open-vm-tools
安装Wine：sudo apt install wine
安装snap商店：sudo snap install snap-store
安装lxtask：sudo apt install lxtask
软件更新器会帮你更新APT缓存，无需使用apt更新命令
如果想安装deb包，例如QQ、ToDesk、OBS等软件
就输入sudo apt install 本地软件包.deb
在分配4G内存的时候，内存占用583MB


官网：https://lubuntu.me/
下载链接：
https://mirrors.tuna.tsinghua.edu.cn/ubuntu-cdimage/lubuntu/releases/24.04.1/release/lubuntu-24.04.1-desktop-amd64.iso
Part 5：Ubuntu Server下载安装，如何设置北京时间、中文、当网盘？
如何下载？
打开官网https://cn.ubuntu.com/server
点击下载服务器版
点击下载Ubuntu Server 24.04.1 LTS
如果下载速度慢，可以去https://mirrors.tuna.tsinghua.edu.cn/ubuntu-releases/24.04.1/ubuntu-24.04.1-live-server-amd64.iso
下载完成后，可以制作U盘启动盘
如何安装？
1.从U盘启动
2.按回车
3.看到这个界面

4.按回车
5.键盘选择chinese
6.
有两个选项，可以选择
7.网络只要看IP地址就行了，如果是笔记本，
需要连接WIFI或插入网线（部分台式机有WIFI）
镜像源列表：
Ubuntu的十大常见国内镜像源地址：
1.华为源：https://mirrors.huaweicloud.com/ubuntu/
2.清华源：https://mirrors.tuna.tsinghua.edu.cn/ubuntu/
3.中科大源：https://mirrors.ustc.edu.cn/ubuntu/
4.腾讯源：https://mirrors.tencent.com/ubuntu/
5.山东源：https://mirrors.sdu.edu.cn/ubuntu/
6.南京源：https://mirrors.nju.edu.cn/ubuntu/
7.上海源：https://mirrors.shanghaitech.edu.cn/ubuntu/
8.上海交通大学源：https://mirror.sjtu.edu.cn/ubuntu/
9.阿里云源：https://mirrors.aliyun.com/ubuntu/
10.网易云源：https://mirrors.163.com/ubuntu/
一些步骤视频后略过
如何设置亚洲上海，安装更新，安装中文语言
设置亚洲上海：
sudo timedatectl set-timezone Asia/Shanghai
安装更新：
更新软件缓存：sudo apt update
更新系统：sudo apt upgrade
安装中文语言：sudo apt install language-pack-zh-hans
设置中文语言（控制台登陆会出现某些文字出现菱形）：sudo dpkg-reconfigure locales
出现提示直接回车，选择zh_CN.UTF8，完成后，重启电脑
结局：
这样老旧电脑已经变成了纯命令行服务器，但是内置了SFTP、SSH双功能，就能使用SFTP服务器当网盘，SSH当学习Linux用
Part 6：Windows Server 2025服务器系统（包括VMware虚拟机安装教程）
链接、密钥：
下载链接：ed2k://|file|zh-cn_windows_server_2025_x64_dvd_1d93dd12.iso|6222254080|ADB825759C4D4B8CAADCE106D9C50A73|/
博通官网：broadcom.com
密钥：
标准版：TVRH6-WHNXV-R9WG3-9XRFY-MY832
数据中心版：D764K-2NDRG-47T6Q-P8T8W-YP6DF
如何开启远程访问：
服务器：winrm quickconfig
客户端：Set-Item wsman:\localhost\Client\TrustedHosts WIN-8BTFAL6AEU0.local -Concatenate -Force
注：WIN-8BTFAL6AEU0.local为服务器名
Part 7：VirtualBox虚拟机下载链接
下载链接：https://mirrors.tuna.tsinghua.edu.cn/virtualbox/7.1.4/VirtualBox-7.1.4-165100-Win.exe
Part 8：2024年，Ubuntu 18.04还能用吗？
兼容性：
OBS：27.2.4
VirtualBox：6.1.50
星火应用商店：不兼容
下载链接：
桌面版：https://mirrors.tuna.tsinghua.edu.cn/ubuntu-releases/18.04.6/ubuntu-18.04.6-desktop-amd64.iso
桌面版（备用链接）：https://mirrors.ustc.edu.cn/ubuntu-releases/18.04.6/ubuntu-18.04.6-desktop-amd64.iso
服务器版：https://mirrors.tuna.tsinghua.edu.cn/ubuntu-releases/18.04.6/ubuntu-18.04.6-live-server-amd64.iso
服务器版（备用链接）：https://mirrors.ustc.edu.cn/ubuntu-releases/18.04.6/ubuntu-18.04.6-live-server-amd64.iso
Part 9：如何安装Arch？
启动一键安装：
archinstall
中文必备包：
fcitx5 wqy-zenhei wqy-microhei
下载链接：
主链接：https://mirrors.tuna.tsinghua.edu.cn/archlinux/iso/latest/archlinux-x86_64.iso
备用链接：https://mirrors.ustc.edu.cn/archlinux/iso/latest/archlinux-x86_64.iso
Part 10：在VMware虚拟机里面安装黑苹果macOS系统呢？（非视频）
安装需求：
1.你的电脑必须是Intel i3及以上的处理器（AMD、奔腾、赛扬、至强需要多加几行代码）
2.内存最低8GB及以上，推荐16GB及以上
3.80GB的可用空间，最好是固态硬盘
准备工作
1.下载工具
2.下载macOS镜像
3.解锁
4.安装macOS
5.安装VMware Tools
下载工具：
工具会放在粉丝群里，有兴趣可以加入
//docs.qq.com/scenario/qq-contact-card-addon.html

将三个文件下载下来
下载macOS镜像：
准备的下载链接：
10.9:https://cloud.mfpud.com/mfpud/macOS/cdr/Mavericks/OS%20X%20Mavericks%2010.9.5%20VMimg%20KealOS.iso
10.10:https://cloud.mfpud.com/mfpud/macOS/cdr/Yosemite/OS%20X%20Yosemite%2010.10.5%20VMimg%20KealOS.iso
10.11:https://cloud.mfpud.com/mfpud/macOS/cdr/El%20Capitan/OS%20X%20El%20Capitan%2010.11.6%20VMimg%20KealOS.iso
10.12:https://cloud.mfpud.com/mfpud/macOS/cdr/Sierra/macOS%20Sierra%2010.12.6%20VMimg%20KealOS.iso
10.13:https://cloud.mfpud.com/mfpud/macOS/cdr/High%20Sierra/macOS%20High%20Sierra%2010.13.6%20VMimg%20KealOS.iso
10.14:https://cloud.mfpud.com/mfpud/macOS/cdr/Mojave/macOS%20Mojave%2010.14.6%20VMimg%20KealOS.iso
10.15:https://cloud.mfpud.com/mfpud/macOS/cdr/Catalina/Install%20macOS%20Catalina%2010.15.7.cdr
11:https://cloud.mfpud.com/mfpud/macOS/cdr/Big%20Sur/Install%20macOS%20Big%20Sur%2011.7.9.cdr
12:https://cloud.mfpud.com/mfpud/macOS/cdr/Monterey/Install%20macOS%20Monterey%2012.7.5.cdr
13:https://cloud.mfpud.com/mfpud/macOS/cdr/Ventura/Install%20macOS%20Ventura%2013.7.1.cdr
14:https://cloud.mfpud.com/mfpud/macOS/cdr/Sonoma/Install%20macOS%20Sonoma%2014.7.1.cdr
15:https://cloud.mfpud.com/mfpud/macOS/cdr/Sequoia/Install%20macOS%20Sequoia%2015.1.cdr
解锁：
先把unlocker.zip解压
解压后，打开unlocker文件夹，以管理员身份运行win-install.cmd
如果是Linux系统，则打开终端输入以下命令：
cd #unlocker所在的文件夹#
sudo sh ./lnx-install.sh
执行完毕后，就可以创建虚拟机了
安装macOS：
Windows：







因为macOS的要求非常高，至少2核以上，推荐4核以上

内存推荐8GB以上










Linux：



















安装：
如果你是AMD处理器，需要加一些代码，左边选中的虚拟机右键，打开虚拟机目录
找到.vmx的文件，用记事本编辑，加这些代码
smc.version = "0"
cpuid.0.eax = "0000:0000:0000:0000:0000:0000:0000:1011"
cpuid.0.ebx ="0111:0101:0110:1110:0110:0101:0100:0111"
cpuid.0.ecx = "0110:1100:0110:0101:0111:0100:0110:1110"
cpuid.0.edx = "0100:1001:0110:0101:0110:1110:0110:1001"
cpuid.1.eax = "0000:0000:0000:0001:0000:0110:0111:0001"
cpuid.1.ebx = "0000:0010:0000:0001:0000:1000:0000:0000"
cpuid.1.ecx = "1000:0010:1001:1000:0010:0010:0000:0011"

cpuid.1.edx = "0000:0111:1000:1011:1111:1011:1111:1111"
保存开启虚拟机即可（注：一个空行一定要留上，否则无法开机）
开启虚拟机，就可以进入安装程序了


语言选择简体中文，点击窗口右下角的箭头按钮

点击磁盘工具，点击继续

点击最上面的那个VMware Virtual那个
点击抹掉

名称随便填，点抹掉

完成关闭

点击窗口左上角的红点按钮，关闭

执行安装，点击继续
接受同意协议
选择磁盘，点击安装，等待安装完成，安装完会自动重启，耐心等待，安装完成后就会让你设置，根据你的需求设置即可

安装增强工具：
将下载好的darwin.iso和darwinPre15.iso复制到VMware虚拟机的文件夹，如果是Linux，那么要复制到/usr/lib/vmware/isoimages文件夹里（Linux需要ROOT权限才能复制）

在虚拟机上，光盘右键，推出
在虚拟机选项卡右键，安装 VMware Tools

双击安装 VMware Tools

Part 11：Windows 11 IoT LTSC 2024 26100.2454 （快捷安装懒人包 · 一键安装运行库及激活）
系统介绍：






1.无人值守
2.系统经过优化（关闭了UAC、VBS等功能）
3.修复安装程序的汉化问题
4.默认为Administrator账户
5.强制在2D显卡上开启了透明效果及圆角
6.集成了运行库
7.添加了UWP版截图工具及终端，修复了某些问题
8.安装镜像使用了esd格式
在分配1.14G的虚拟内存情况下，占用8.87G（如果是在其它安装器安装该系统的话，占用会大一些）
新版安装程序默认在安装的时候开启Compact压缩
如何下载：
下载可从链接2进行下载：
https://pan.xiaomuxi.cn/s/9mZGtd
Part 12：Mac OS X 10.3 Panther（PPC版）
Mac OS X 10.3.0
https://macos.mediy.cn/Mac%20OS%20X%2010.3%20Panther/10.3/

启动代码：qemu-system-ppc64 -M mac99 -cpu g4 -m 512 -hda macos10.3.qcow2 -cdrom '/mnt/win10data/Apple Mac OS X 10.3.0 - Disk 1.iso' -boot c -net user -net nic,model=rtl8139 -usb -device usb-tablet -g 1024x768x32
该代码仅供示例
change ide1-cd0 “ISO文件”

Part 13：给老电脑或服务器装上Windows Server Core
这个系统没有桌面，但是有性价比的，可以搭建任何服务器
做SSH、Hyper-V、打印机服务器、Docker、IIS等服务功能
因此我把镜像优化了下，加上了VNC服务器功能
你可以在链接2里下载：
https://pan.xiaomuxi.cn/s/9mZGtd

Part 14：从Windows 11 24H2降级到23H2（专栏）
有些运行24H2的小伙伴们，会遇到很多bug
例如资源管理器点更多弹出位置错误，部分设备蓝屏，强制开启VBS等
小模组QZ这寒假的三天做了一个降级包
此程序是实验性程序，请谨慎使用
注意：以下截图是工厂测试

暂时仅兼容24H2正式版的X64版且非LTSC：
一共13个版本

此外，小模组QZ将会制作一个重装工具，兼容在解压的降级包文件夹里面执行，兼容更多版本，更多功能

有三个选项，其中第一项是实验性的，小模组QZ经过了很多次保留数据都提示回滚，小白尽量不要选择第一项
其中二选项和三选项是完美的，但注意，资料要备份好

降级前注意：
1.降级过程中一旦确认不能关闭此窗口
2.降级前建议你关闭所有的应用程序
3.降级前你需要使用本地账户，关闭BitLocker、CompactOS及关闭VBS（否则可能降级失败）
4.确保选择没有问题可以降级
5.降级前你可能需要备份数据
6.降级有风险，请谨慎降级

降级成功后，你可能需要重新设置
此功能只适用于回滚功能不可用的电脑来降级该系统（实验性）

暂未正式发布

Part 15：2025年1月 Windows首个更新下载链接：
Win11/Server 24H2 X64：https://catalog.sf.dl.delivery.mp.microsoft.com/filestreamingservice/files/66557ecc-650e-4c70-8baf-c624c4de912f/public/windows11.0-kb5050009-x64_97aac2ab4f607b11d50ad2fd88a5841ee0b18dd5.msu
Win11/Server 24H2 ARM64：https://catalog.sf.dl.delivery.mp.microsoft.com/filestreamingservice/files/fb50861d-95ca-47ee-80f0-7bee850d0674/public/windows11.0-kb5050009-arm64_d3440f1c6b2b9471cd2cdfae7b360006d847d505.msu
Win11 23H2 X64：https://catalog.sf.dl.delivery.mp.microsoft.com/filestreamingservice/files/db0d5972-d5ac-4706-ae45-d2fb38680308/public/windows11.0-kb5050021-x64_d1c06c1c0d32a7ff8879f1e2a386d26df113a227.msu
Win11 23H2 ARM64：https://catalog.sf.dl.delivery.mp.microsoft.com/filestreamingservice/files/8ce7bc4e-0832-4954-b2ff-4afda05b55a3/public/windows11.0-kb5050021-arm64_6f8c64e63fc619e78e6640226465a2520c090a83.msu
WinServer 23H2 X64：https://catalog.sf.dl.delivery.mp.microsoft.com/filestreamingservice/files/c0cc09df-8617-42fe-8a07-61bf078a0b08/public/windows11.0-kb5049984-x64_185d3d0edb6a53b859619b34932533711299b16a.msu
Win10 21H2/22H2 X64：https://catalog.s.download.windowsupdate.com/d/msdownload/update/software/secu/2025/01/windows10.0-kb5049981-x64_bda073f7d8e14e65c2632b47278924b8a0f6b374.msu
Win10 21H2/22H2 X86：https://catalog.s.download.windowsupdate.com/d/msdownload/update/software/secu/2025/01/windows10.0-kb5049981-x86_c991f0d6727f0f577a89dfa76b6e00036d83f1f5.msu
Win10 21H2/22H2 KB5049981 ARM64：https://catalog.s.download.windowsupdate.com/d/msdownload/update/software/secu/2025/01/windows10.0-kb5049981-arm64_912b957ab176b5388fc2c442ed1f1e4fd259e54f.msu
Win10 1809/Server KB5050008 X64：https://catalog.s.download.windowsupdate.com/d/msdownload/update/software/secu/2025/01/windows10.0-kb5050008-x64_80eb33a0afcef07b95b6d5925b174e6a189bb6c9.msu
Win10 1809 KB5050008 X86：https://catalog.s.download.windowsupdate.com/d/msdownload/update/software/secu/2025/01/windows10.0-kb5050008-x86_576e056f26be578d746dafecab072e901409f524.msu
Win10 1607/Server KB5049993 X64：https://catalog.s.download.windowsupdate.com/d/msdownload/update/software/secu/2025/01/windows10.0-kb5049993-x64_6a123d9d7dba130d2a5ebfaa38ce380680ff52ed.msu
Win10 1607 KB5049993 X86：https://catalog.s.download.windowsupdate.com/d/msdownload/update/software/secu/2025/01/windows10.0-kb5049993-x86_6bc90770611345bc7b5a8d629ef761f96fa83a67.msu
Win10 1607/Server SSU KB5050109 X64：https://catalog.s.download.windowsupdate.com/d/msdownload/update/software/secu/2024/12/windows10.0-kb5050109-x64_e915f9605715432ac0878df761df326f7cbd6532.msu
Win10 1607 SSU KB5050109 X86：https://catalog.s.download.windowsupdate.com/d/msdownload/update/software/secu/2024/12/windows10.0-kb5050109-x86_cebb7f1763e8ee6568da599394b6d539fd385e52.msu
Win10 1507 KB5050013 X64：https://catalog.s.download.windowsupdate.com/d/msdownload/update/software/secu/2025/01/windows10.0-kb5050013-x64_bf09ad87e839b7c468964a67e580c188571547ce.msu
Win10 1507 KB5050013 X86：https://catalog.s.download.windowsupdate.com/d/msdownload/update/software/secu/2025/01/windows10.0-kb5050013-x86_216e24f37f2abc9d4387f6389b29d8a7d1519a34.msu
Win10 1507 SSU KB5050112 X64：https://catalog.s.download.windowsupdate.com/c/msdownload/update/software/secu/2024/12/windows10.0-kb5050112-x64_30856a1c7487db70a3358296fd7196093fbd8709.msu
Win10 1507 SSU KB5050112 X86：https://catalog.s.download.windowsupdate.com/d/msdownload/update/software/secu/2024/12/windows10.0-kb5050112-x86_e0a101f69ac3126545818414190cc480fb055e09.msu
Win8.1/Server KB5050048 X64：https://catalog.s.download.windowsupdate.com/c/msdownload/update/software/secu/2025/01/windows8.1-kb5050048-x64_47f67087ec282fa83136c75fb4bf4c7f76584be6.msu
Win8.1/Server SSU KB5050115 X64：https://catalog.s.download.windowsupdate.com/c/msdownload/update/software/secu/2025/01/windows8.1-kb5050115-x64_029c0ba38baf02e4f61abb2c91e76308fed40453.msu
Win7/Server KB5050049 X64：https://catalog.s.download.windowsupdate.com/d/msdownload/update/software/secu/2025/01/windows6.1-kb5050049-x64_fe8c03f11116a09cea40aa9737071e456965c6e7.msu
Win7/Server SSU KB5050681 X64：https://catalog.s.download.windowsupdate.com/d/msdownload/update/software/secu/2025/01/windows6.1-kb5050681-x64_c69ead5825f461a2218e25000efdadf571bbfb0d.msu


Part 16：2025年1月的第二个更新，修复了很多漏洞及添加了新功能

Windows 11,version 24H2：26100.3037 KB5050094
高亮：
逐步推出：
新增的功能：
任务栏：此更新改进了将光标悬停在任务栏上的应用上时显示的预览。此更新还改进了动画。
Windows Studio 效果：使用支持 Windows Studio 效果的应用时，系统托盘中将显示一个图标。这仅在具有 NPU) 的神经处理单元 (设备上发生。选择图标以在“快速设置”中打开“工作室效果”页。若要查看使用相机的应用，请将鼠标悬停在工具提示的图标上。
字体：此更新添加了Simsun-ExtG，这是一种新的简体中文字体它包括 Biangbiang 面条字符。某些应用可能还无法显示这些新的扩展字符。字体有 9,753 种象形字，支持Unicode 扩展 G、H 和 I。请参阅下面的列表。
●Unicode 范围 G 30000-3134A (4,939 个字符)
●Unicode 范围 H 31350-323AF (4,192 个字符)
●Unicode 范围 I 2EBF0-2EE5D (622 个字符)
文件资源管理器：右键单击左窗格中的项目时，上下文菜单上会显示“新建文件夹”命令。

设置：可以在 “设置 >时间 & 语言 > 日期 & 时间”中更改时区。无需是管理员就可以进行此更改。
修复的问题：
文件资源管理器：
●执行搜索后，当你不希望搜索时，该搜索可能会重复。
●复制文件后，文件的日期和时间属性可能会更新。
●更改主题时，详细信息窗格上的图标可能不会按预期更新。 这使得在深色和浅色主题之间切换时，很难查看更改。
●键入时，搜索框可能会失去输入焦点。
鼠标：
●鼠标光标可能会消失。将鼠标悬停在某些应用程序中的文本字段上时，会出现这种情况。
●如果打开指针跟踪，鼠标光标将变为透明，并且其后面会显示一个黑框。
●鼠标光标在屏幕上移动时可能会断断续续。 即使系统未使用大量资源，也会发生这种情况。
拼音输入法编辑器 (输入法)：切换应用窗口时，IME 语言可能会从中文更改为英语。
截图工具：截图工具屏幕截图可能扭曲。 使用两台或更多具有不同显示缩放比例的监视器时，会出现这种情况。
Microsoft Excel 2016：打开某些文件时，Excel 会打开，但屏幕可能保留在加载屏幕上。


正常推出：
修复的问题：
高动态范围 (HDR)：某些游戏的显示显示为过度饱和。 使用自动 HDR 时会发生这种情况。
数字/模拟转换器 (DAC) (已知问题)：USB 音频设备可能会遇到问题。 使用基于 USB 1.0 的 DAC 音频驱动程序时，这种情况更可能。 USB 音频设备可能会停止工作，从而停止播放。
USB 音频设备驱动程序：显示代码 10 错误消息“此设备无法启动”。 连接到某些外部音频管理设备时，会出现这种情况。
中文拼音输入法编辑器 (IME)：必应将停止在搜索框中为搜索引擎网站（如百度）提供自动建议。 若要获取手动建议，请使用 Ctrl+Tab 或 v 形按钮 (>) 。
USB 相机：设备无法识别相机是否打开。 安装 2025 年 1 月安全更新后，会出现此问题。
Passkey：此更新删除在手机上使用密钥时的一分钟超时。


改进：
逐步推出：
修复的问题：
域：设备可能无法加入域。
任务管理器：关闭应用后关闭时间过长。
Dam.sys（看门狗内核驱动程序）：当电脑从睡眠状态恢复时，可能会出现监视器超时错误。        
Windows 更新安装：可能不会安装累积更新。 错误代码为0x800736b3。 在按需功能无法安装后，会发生此情况。


正常推出：
修复的问题：
内存泄漏：预测输入想法显示时发生泄漏。
Windows 内核易受攻击的驱动程序阻止列表文件 (DriverSiPolicy.p7b)：此更新将添加到面临“自带易受攻击驱动程序” (BYOVD) 攻击风险的驱动程序列表中。
远程桌面网关：连接到Windows 11工作站时出现错误或无法签名。 强制实施设备重定向时会发生此情况。


如果已安装较早的更新，那么此程序包中只有新的更新程序会下载并安装到设备上。

.NET Framework 4.8.1 For Windows 11,version 24H2 KB5050577
质量与可靠性改进：
WPF：解决了由于 OutOfMemory 异常而打印大量页面的问题。

Windows 10,version 22H2：19045.5440 KB5050081
高亮：
新增的功能：
邮件：你现在有了新的 Outlook for Windows 应用。 新应用图标显示在“开始”菜单上的“应用”部分中，靠近经典 Outlook。 没有任何设置或默认值的更改。 如果你是 IT 管理员，请在 控制新 Outlook 的安装和使用中了解如何管理此更新。
屏幕捕获：捕获服务和截图工具停止响应。 当你在“讲述人”处于打开状态时多次按 Windows 徽标键+Shift+S 时，会出现这种情况。
中文拼音输入法编辑器 (IME)：必应将停止在搜索框中为搜索引擎网站（如百度）提供自动建议。 若要获取手动建议，请使用 Ctrl+Tab 或 v 形按钮 (>) 。
数字/模拟转换器 (DAC) (已知问题)：USB 音频设备可能会遇到问题。 使用基于 USB 1.0 的 DAC 音频驱动程序时，这种情况更可能。 USB 音频设备可能会停止工作，从而停止播放。
USB 音频设备驱动程序：显示代码 10 错误消息“此设备无法启动”。 连接到某些外部音频管理设备时，会出现这种情况。        
USB 相机：设备无法识别相机是否打开。 安装 2025 年 1 月安全更新后，会出现此问题。


改进：
GB18030-2022：此更新添加了对此修订的支持。
虚拟内存：问题耗尽了虚拟内存，这可能会导致某些应用失败。
近场通信 (NFC) 阅读器：有时，它们无法读取 UUID) (通用唯一标识符卡。 这发生在许多销售点 (POS) 应用扫描之后。
USB 打印和基于 USB 的 IPP：后台处理程序初始化时，已安装的打印机失败。
Windows 内核易受攻击的驱动程序阻止列表文件 (DriverSiPolicy.p7b)：此更新将添加到面临“自带易受攻击驱动程序” (BYOVD) 攻击风险的驱动程序列表中。
如果已安装较早的更新，那么此程序包中只有新的更新程序会下载并安装到设备上。

.NET Framework 4.8、4.8.1 For Windows 10,version 22H2 KB5050579/KB5050576
质量与可靠性改进：
WPF：解决了由于 OutOfMemory 异常而打印大量页面的问题。

Windows的累计更新中，更新了超1000个系统文件
修复的bug你可以尝试更新，1月29日会自动接收我们的更新
更新目录中的独立更新包：
KB5050094：https://catalog.update.microsoft.com/Search.aspx?q=KB5050094
KB5050081：https://catalog.update.microsoft.com/Search.aspx?q=KB5050081
KB5050577：https://catalog.update.microsoft.com/Search.aspx?q=KB5050577
KB5050576：https://catalog.update.microsoft.com/Search.aspx?q=KB5050576
KB5050579：https://catalog.update.microsoft.com/Search.aspx?q=KB5050579

