# 系统信息和管理
uname -a 显示系统信息
cat /etc/os-release 查看操作系统版本信息
uptime 查看系统时间
top 系统性能和进程
free -h 内存使用情况
df -h 磁盘使用情况
lsblk 磁盘分区
du -sh _____目录____ 目录大小
hostname 显示设备主机名
nvidia-smi 驱动版本
nvcc --version cuda版本

# 文件和目录
cd
- cd _____ 进入目录
- cd ~/cd ，主目录
- cd .. 上级目录
- cd - 之前的目录
ls 当前目录内容
pwd 当前路径
which file_name  返回文件路径**
mkdir directory_name 创建目录
rm file_name 删除文件
rm -r firectory_name 删除文件夹
cp source destination 复制粘贴
mv source destination 移动/重命名

# 文件查看与编辑
cat file_name
more file_name
head -n 10 file_name 查看文件前十行
tail -n 10 file_name 查看文件后十行
touch file_name 创建新文件

# 软件管理
sudo apt update 更新软件包列表
sudo apt upgrade 升级已经安装的软件包
sudo apt install package_name 安装软件包
sudo apt remove package_name 删除软件包
dpkg -l 列出所有已经安装的软件包
sudo snap install package_name 安装软件包
sudo snap install package_name --classic
wget URL 下载文件到当前目录

# 压缩与解压zip
zip -r achive_name.zip dir_name	压缩文件夹(不要用中文路径)
unzip achive_name.zip	解压
unzip -l achive_name.zip 查看压缩包内容不解压




