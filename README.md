# Linux-To-Windows

适用于 甲骨文 ubuntu 

KVM架构才可以，openvz架构不适用

# 0.获得管理员权限

sudo -i

# 1.先运行以下代码

#Debian/Ubuntu:
apt-get update

安装运行库
#Debian/Ubuntu:
apt-get install -y xz-utils openssl gawk file

apt-get install wget

# 2.代码安装

wget --no-check-certificate -qO InstallNET.sh 'https://moeclub.org/attachment/LinuxShell/InstallNET.sh' && bash InstallNET.sh -dd 'Windows的软件包'

（注意：不适用于新出的ARM框架机型）

# DD Windows Server 2012 R2 64位 精简版 [账户Administrator密码nat.ee]
wget --no-check-certificate -qO InstallNET.sh 'https://moeclub.org/attachment/LinuxShell/InstallNET.sh' && bash InstallNET.sh -dd 'https://oss.sunpma.com/Windows/Oracle_Win_Server2012R2_64_Administrator_nat.ee.gz'


# DD Windows7 sp1 64位 企业精简版 [账户Administrator密码nat.ee]
wget --no-check-certificate -qO InstallNET.sh 'https://moeclub.org/attachment/LinuxShell/InstallNET.sh' && bash InstallNET.sh -dd 'https://oss.sunpma.com/Windows/Oracle_Win7_sp1_64_Administrator_nat.ee.gz'
