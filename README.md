此工具是为了树莓派镜像备份压缩

例子：（步骤一两个路径换成自己的sd卡挂载下的roots和boot,步骤二分别是镜像压缩位置和复制位置，步骤三是打包，可选项）
1. 先执行 backup.sh /dev/sda1 /dev/sda2 
2. 执行 sudo -s ./pishrink.sh ~/backupimg/rpi-20220627-1109.img ~/Downloads/nfs
3. xz -z rpi-20220627-1109.img
