# 1. 文件系统

| 目录名 | 存放的内容 |
|:---   | :---      |
| /     | 根目录，一般根目录下只存放目录，不要存放文件，/etc、/bin、/dev、/lib、/sbin应该和根目录放置在一个分区 |
| /bin  | 必备的用户命令程序，例如ls、cp等 |
| /boot | 放置Linux系统启动时用到的一些文件。比如：/boot/vmlinuz为linux的内核文件。**建议单独分区，分区大小100MB即可** |
| /sbin | 必备的系统管理员命令，例如ifconfig、reboot等 |
| /dev  | 设备文件，例如mtdblock(),tty1等 |
| /etc  | 系统配置文件存放目录，**不建议在此目录下存放可执行文件**，重要的配置文件有/etc/inittab、/etc/fstab、/etc/init.d、/etc/X11、/etc/sysconfig、/etc/xinetd 等 |
| /lib  | 必要的链接库，例如C链接库、内核模块 |
| /home | 普通用户主目录 |
| /root | root用户主目录 |
| /usr/bin | 非必备的用户程序，例如find,du等 |
| /usr/sbin | 非必备的管理员程序，例如chroot,inetd等 |
