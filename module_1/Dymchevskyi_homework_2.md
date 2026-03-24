<!-- Завдання 1. Ієрархія каталогів Linux -->

artyr@Arhivar:/etc$ cd /

artyr@Arhivar:/$ ls -l

<!-- Перейди в кореневий каталог / і покажи вміст -->

total 2452
drwxr-xr-x 3 root root 4096 Apr 2 2025 Docker
lrwxrwxrwx 1 root root 7 Apr 22 2024 bin -> usr/bin
drwxr-xr-x 2 root root 4096 Feb 26 2024 bin.usr-is-merged
drwxr-xr-x 2 root root 4096 Apr 22 2024 boot
drwxr-xr-x 16 root root 3580 Mar 23 19:35 dev
drwxr-xr-x 91 root root 4096 Mar 23 19:35 etc
drwxr-xr-x 4 root root 4096 Mar 23 15:21 home
-rwxrwxrwx 1 root root 2424984 Mar 19 2025 init
lrwxrwxrwx 1 root root 7 Apr 22 2024 lib -> usr/lib
drwxr-xr-x 2 root root 4096 Apr 8 2024 lib.usr-is-merged
lrwxrwxrwx 1 root root 9 Apr 22 2024 lib64 -> usr/lib64
drwx------ 2 root root 16384 Apr 2 2025 lost+found
drwxr-xr-x 2 root root 4096 Feb 15 2025 media
drwxr-xr-x 7 root root 4096 Apr 2 2025 mnt
drwxr-xr-x 2 root root 4096 Feb 15 2025 opt
dr-xr-xr-x 280 root root 0 Mar 23 19:35 proc
drwx------ 6 root root 4096 Mar 20 07:48 root
drwxr-xr-x 19 root root 560 Mar 23 19:35 run
lrwxrwxrwx 1 root root 8 Apr 22 2024 sbin -> usr/sbin
drwxr-xr-x 2 root root 4096 Mar 31 2024 sbin.usr-is-merged
drwxr-xr-x 2 root root 4096 Apr 2 2025 snap
drwxr-xr-x 2 root root 4096 Feb 15 2025 srv
dr-xr-xr-x 11 root root 0 Mar 23 19:35 sys
drwxrwxrwt 11 root root 4096 Mar 23 19:35 tmp
drwxr-xr-x 12 root root 4096 Feb 15 2025 usr
drwxr-xr-x 13 root root 4096 Apr 2 2025 var

<!-- Перейди в /etc і покажи вміст -->

artyr@Arhivar:/$ cd /etc

artyr@Arhivar:/etc$ ls -l

total 832
drwxr-xr-x 2 root root 4096 Mar 4 12:45 PackageKit
drwxr-xr-x 7 root root 4096 Feb 15 2025 X11
-rw-r--r-- 1 root root 3444 Jul 5 2023 adduser.conf
drwxr-xr-x 2 root root 4096 Mar 8 12:04 alternatives
drwxr-xr-x 3 root root 4096 Mar 8 12:04 apache2
drwxr-xr-x 2 root root 4096 Mar 4 12:45 apparmor
drwxr-xr-x 9 root root 12288 Mar 23 15:26 apparmor.d
drwxr-xr-x 3 root root 4096 Feb 26 18:19 apport
drwxr-xr-x 8 root root 4096 Feb 15 2025 apt
-rw-r--r-- 1 root root 2319 Mar 31 2024 bash.bashrc
-rw-r--r-- 1 root root 45 Jan 24 2020 bash_completion
drwxr-xr-x 2 root root 4096 Mar 8 12:05 bash_completion.d
-rw-r--r-- 1 root root 367 Aug 2 2022 bindresvport.blacklist
drwxr-xr-x 2 root root 4096 Apr 19 2024 binfmt.d
drwxr-xr-x 2 root root 4096 Feb 15 2025 byobu
drwxr-xr-x 3 root root 4096 Feb 15 2025 ca-certificates
-rw-r--r-- 1 root root 6288 Feb 15 2025 ca-certificates.conf
drwxr-xr-x 5 root root 4096 Mar 4 12:45 cloud
drwxr-xr-x 2 root root 4096 Feb 15 2025 console-setup
drwx------ 2 root root 4096 Apr 19 2024 credstore
drwx------ 2 root root 4096 Apr 19 2024 credstore.encrypted
drwxr-xr-x 2 root root 4096 Feb 15 2025 cron.d
drwxr-xr-x 2 root root 4096 Mar 4 12:45 cron.daily
drwxr-xr-x 2 root root 4096 Feb 15 2025 cron.hourly
drwxr-xr-x 2 root root 4096 Feb 15 2025 cron.monthly
drwxr-xr-x 2 root root 4096 Feb 15 2025 cron.weekly
drwxr-xr-x 2 root root 4096 Feb 15 2025 cron.yearly
-rw-r--r-- 1 root root 1136 Mar 30 2024 crontab
drwxr-xr-x 4 root root 4096 Feb 15 2025 dbus-1
drwxr-xr-x 3 root root 4096 Feb 15 2025 dconf
-rw-r--r-- 1 root root 2967 Apr 12 2024 debconf.conf
-rw-r--r-- 1 root root 11 Apr 22 2024 debian_version
drwxr-xr-x 2 root root 4096 Mar 4 12:45 default
-rw-r--r-- 1 root root 1706 Jul 5 2023 deluser.conf
drwxr-xr-x 2 root root 4096 Feb 15 2025 depmod.d
drwxr-xr-x 3 root root 4096 Feb 15 2025 dhcp
-rw-r--r-- 1 root root 1429 Mar 31 2024 dhcpcd.conf
drwxr-xr-x 4 root root 4096 Mar 8 12:04 dpkg
-rw-r--r-- 1 root root 685 Apr 8 2024 e2scrub.conf
-rw-r--r-- 1 root root 106 Feb 15 2025 environment
drwxr-xr-x 2 root root 4096 Feb 15 2025 environment.d
-rw-r--r-- 1 root root 1853 Oct 17 2022 ethertypes
drwxr-xr-x 4 root root 4096 Feb 15 2025 fonts
-rw-r--r-- 1 root root 37 Feb 15 2025 fstab
-rw-r--r-- 1 root root 694 Apr 8 2024 fuse.conf
-rw-r--r-- 1 root root 2584 Jan 30 2024 gai.conf
drwxr-xr-x 3 root root 4096 Feb 15 2025 glvnd
drwxr-xr-x 2 root root 4096 Feb 28 16:25 gnutls
-rw-r--r-- 1 root root 3986 Aug 7 2024 gprofng.rc
drwxr-xr-x 2 root root 4096 Feb 15 2025 groff
-rw-r--r-- 1 root root 806 Mar 23 15:23 group
-rw-r--r-- 1 root root 801 Mar 23 15:22 group-
-rw-r----- 1 root shadow 683 Mar 23 15:23 gshadow
-rw-r----- 1 root shadow 678 Mar 23 15:22 gshadow-
drwxr-xr-x 3 root root 4096 Feb 15 2025 gss
drwxr-xr-x 2 root root 4096 Mar 4 12:45 gtk-3.0
-rw-r--r-- 1 root root 92 Apr 22 2024 host.conf
-rw-r--r-- 1 root root 8 Mar 23 19:35 hostname
-rw-r--r-- 1 root root 400 Mar 23 19:35 hosts
drwxr-xr-x 2 root root 4096 Mar 23 15:26 init.d
-rw-r--r-- 1 root root 1875 Mar 31 2024 inputrc
drwxr-xr-x 4 root root 4096 Mar 4 12:45 iproute2
-rw-r--r-- 1 root root 26 Feb 6 02:23 issue
-rw-r--r-- 1 root root 19 Feb 6 02:23 issue.net
drwxr-xr-x 4 root root 4096 Feb 15 2025 kernel
drwxrwxr-x 2 root landscape 4096 Mar 4 12:45 landscape
-rw-r--r-- 1 root root 20503 Mar 23 19:35 ld.so.cache
-rw-r--r-- 1 root root 34 Aug 2 2022 ld.so.conf
drwxr-xr-x 2 root root 4096 Mar 8 12:04 ld.so.conf.d
drwxr-xr-x 2 root root 4096 Mar 4 12:45 ldap
-rw-r--r-- 1 root root 267 Apr 22 2024 legal
-rw-r--r-- 1 root root 191 Mar 30 2024 libaudit.conf
drwxr-xr-x 2 root root 4096 Mar 20 08:26 libnl-3
drwxr-xr-x 4 root root 4096 Mar 8 12:04 lighttpd
-rw-r--r-- 1 root root 2996 Mar 30 2024 locale.alias
-rw-r--r-- 1 root root 13 Feb 15 2025 locale.conf
-rw-r--r-- 1 root root 9565 Feb 28 16:25 locale.gen
lrwxrwxrwx 1 root root 35 Mar 23 19:35 localtime -> /usr/share/zoneinfo/America/Toronto
drwxr-xr-x 3 root root 4096 Feb 15 2025 logcheck
-rw-r--r-- 1 root root 12345 Feb 22 2024 login.defs
-rw-r--r-- 1 root root 586 Apr 8 2024 logrotate.conf
drwxr-xr-x 2 root root 4096 Mar 4 12:45 logrotate.d
-rw-r--r-- 1 root root 104 Feb 6 02:22 lsb-release
-r--r--r-- 1 root root 33 Apr 2 2025 machine-id
-rw-r--r-- 1 root root 111 Mar 31 2024 magic
-rw-r--r-- 1 root root 111 Mar 31 2024 magic.mime
-rw-r--r-- 1 root root 5230 Apr 8 2024 manpath.config
-rw-r--r-- 1 root root 75113 Jul 12 2023 mime.types
-rw-r--r-- 1 root root 744 Apr 8 2024 mke2fs.conf
drwxr-xr-x 2 root root 4096 Feb 15 2025 modprobe.d
-rw-r--r-- 1 root root 212 Feb 15 2025 modules
drwxr-xr-x 2 root root 4096 Mar 4 12:45 modules-load.d
lrwxrwxrwx 1 root root 19 Feb 15 2025 mtab -> ../proc/self/mounts
-rw-r--r-- 1 root root 11424 May 23 2023 nanorc
-rw-r--r-- 1 root root 767 Mar 30 2024 netconfig
drwxr-xr-x 2 root root 4096 Apr 18 2024 netplan
drwxr-xr-x 4 root root 4096 Feb 15 2025 network
drwxr-xr-x 8 root root 4096 Feb 15 2025 networkd-dispatcher
-rw-r--r-- 1 root root 91 Apr 22 2024 networks
drwxr-xr-x 2 root root 4096 Feb 15 2025 newt
-rw-r--r-- 1 root root 526 Feb 15 2025 nsswitch.conf
drwxr-xr-x 2 root root 4096 Feb 15 2025 opt
lrwxrwxrwx 1 root root 21 Feb 6 02:23 os-release -> ../usr/lib/os-release
-rw-r--r-- 1 root root 552 Oct 13 2022 pam.conf
drwxr-xr-x 2 root root 4096 Mar 23 15:26 pam.d
-rw-r--r-- 1 root root 1466 Mar 23 15:22 passwd
-rw-r--r-- 1 root root 1463 Mar 23 15:21 passwd-
drwxr-xr-x 3 root root 4096 Feb 15 2025 perl
drwxr-xr-x 3 root root 4096 Feb 15 2025 pm
drwxr-xr-x 3 root root 4096 Feb 15 2025 polkit-1
-rw-r--r-- 1 root root 582 Apr 22 2024 profile
drwxr-xr-x 2 root root 4096 Mar 23 15:26 profile.d
-rw-r--r-- 1 root root 3144 Oct 17 2022 protocols
drwxr-xr-x 2 root root 4096 Feb 15 2025 python3
drwxr-xr-x 2 root root 4096 Mar 13 08:57 python3.12
drwxr-xr-x 2 root root 4096 Feb 15 2025 rc0.d
drwxr-xr-x 2 root root 4096 Feb 15 2025 rc1.d
drwxr-xr-x 2 root root 4096 Feb 15 2025 rc2.d
drwxr-xr-x 2 root root 4096 Feb 15 2025 rc3.d
drwxr-xr-x 2 root root 4096 Feb 15 2025 rc4.d
drwxr-xr-x 2 root root 4096 Feb 15 2025 rc5.d
drwxr-xr-x 2 root root 4096 Feb 15 2025 rc6.d
drwxr-xr-x 2 root root 4096 Feb 15 2025 rcS.d
lrwxrwxrwx 1 root root 20 Mar 23 19:35 resolv.conf -> /mnt/wsl/resolv.conf
lrwxrwxrwx 1 root root 13 Apr 8 2024 rmt -> /usr/sbin/rmt
-rw-r--r-- 1 root root 911 Oct 17 2022 rpc
-rw-r--r-- 1 root root 1213 Mar 21 2024 rsyslog.conf
drwxr-xr-x 2 root root 4096 Mar 4 12:45 rsyslog.d
drwxr-xr-x 4 root root 4096 Feb 26 18:20 security
drwxr-xr-x 2 root root 4096 Feb 15 2025 selinux
drwxr-xr-x 2 root root 4096 Feb 15 2025 sensors.d
-rw-r--r-- 1 root root 10593 Mar 30 2024 sensors3.conf
-rw-r--r-- 1 root root 12813 Mar 27 2021 services
drwxr-xr-x 2 root root 4096 Feb 15 2025 sgml
-rw-r----- 1 root shadow 899 Mar 23 15:22 shadow
-rw-r----- 1 root shadow 801 Mar 4 12:20 shadow-
-rw-r--r-- 1 root root 132 Feb 15 2025 shells
drwxr-xr-x 2 root root 4096 Feb 15 2025 skel
drwxr-xr-x 3 root root 4096 Mar 23 15:26 ssh
drwxr-xr-x 4 root root 4096 Feb 28 16:25 ssl
-rw-r--r-- 1 root root 37 Mar 23 15:21 subgid
-rw-r--r-- 1 root root 19 Mar 4 12:20 subgid-
-rw-r--r-- 1 root root 37 Mar 23 15:21 subuid
-rw-r--r-- 1 root root 19 Mar 4 12:20 subuid-
-rw-r--r-- 1 root root 4343 Apr 8 2024 sudo.conf
-rw-r--r-- 1 root root 9804 Apr 8 2024 sudo_logsrvd.conf
-r--r----- 1 root root 1800 Jan 29 2024 sudoers
drwxr-xr-x 2 root root 4096 Mar 23 15:26 sudoers.d
drwxr-xr-x 2 root root 4096 Feb 15 2025 supercat
-rw-r--r-- 1 root root 2209 Mar 24 2024 sysctl.conf
drwxr-xr-x 2 root root 4096 Mar 4 12:45 sysctl.d
drwxr-xr-x 6 root root 4096 Mar 4 12:45 systemd
drwxr-xr-x 2 root root 4096 Feb 15 2025 terminfo
-rw-r--r-- 1 root root 16 Mar 23 19:35 timezone
drwxr-xr-x 2 root root 4096 Apr 19 2024 tmpfiles.d
drwxr-xr-x 2 root root 4096 Mar 4 12:45 ubuntu-advantage
-rw-r--r-- 1 root root 1260 Jan 27 2023 ucf.conf
drwxr-xr-x 4 root root 4096 Mar 4 12:45 udev
drwxr-xr-x 3 root root 4096 Mar 4 12:45 update-manager
drwxr-xr-x 2 root root 4096 Mar 4 12:45 update-motd.d
lrwxrwxrwx 1 root root 16 Feb 15 2025 vconsole.conf -> default/keyboard
drwxr-xr-x 2 root root 4096 Mar 23 15:26 vim
lrwxrwxrwx 1 root root 23 Feb 26 2024 vtrgb -> /etc/alternatives/vtrgb
drwxr-xr-x 5 root root 4096 Feb 15 2025 vulkan
-rw-r--r-- 1 root root 4942 Jun 19 2024 wgetrc
-rw-r--r-- 1 root root 204 Feb 15 2025 wsl-distribution.conf
-rw-r--r-- 1 root root 42 Mar 4 12:20 wsl.conf
-rw-r--r-- 1 root root 80 Mar 20 07:49 wsl.conf.save
-rw-r--r-- 1 root root 681 Apr 8 2024 xattr.conf
drwxr-xr-x 5 root root 4096 Feb 15 2025 xdg
drwxr-xr-x 2 root root 4096 Feb 15 2025 xml
-rw-r--r-- 1 root root 460 Jan 20 2023 zsh_command_not_found

artyr@Arhivar:~$ cd /home

artyr@Arhivar:/home$ ls -l

<!-- Перейди у каталог /home і покажи список користувачів -->

total 8
drwxr-x--- 9 artyr artyr 4096 Mar 20 08:26 artyr
drwxr-x--- 6 test test 4096 Mar 23 15:44 test

<!-- Завдання 2. Файли, каталоги та посилання -->

<!-- Створи новий каталог у домашньому каталозі -->

artyr@Arhivar:~$ mkdir new_dir
artyr@Arhivar:~$ cd new_dir/

<!-- Створи всередині файл -->

artyr@Arhivar:~/new_dir$ touch new_file
artyr@Arhivar:~/new_dir$ ls -l
total 0
-rw-r--r-- 1 artyr artyr 0 Mar 23 19:41 new_file

<!--Скопіюй файл у нове ім’я  -->

artyr@Arhivar:~/new_dir$ cp new_file ../rename_file
artyr@Arhivar:~/new_dir$ cd ..
artyr@Arhivar:~$ ls -l
total 16
drwxr-xr-x 2 artyr artyr 4096 Mar 19 10:28 new_Dir
drwxr-xr-x 2 artyr artyr 4096 Mar 23 19:41 new_dir
-rw-r--r-- 1 artyr artyr 0 Mar 23 19:42 rename_file
drwx------ 2 artyr artyr 4096 Mar 19 10:53 secure
-rwxr--r-- 1 artyr artyr 13 Mar 19 10:50 test.sh

<!--Перейменуй копію  -->

artyr@Arhivar:~$ mv rename_file new_file
artyr@Arhivar:~$ ls -l
total 16
drwxr-xr-x 2 artyr artyr 4096 Mar 19 10:28 new_Dir
drwxr-xr-x 2 artyr artyr 4096 Mar 23 19:41 new_dir
-rw-r--r-- 1 artyr artyr 0 Mar 23 19:42 new_file
drwx------ 2 artyr artyr 4096 Mar 19 10:53 secure
-rwxr--r-- 1 artyr artyr 13 Mar 19 10:50 test.sh

<!-- Створи жорстке посилання -->

artyr@Arhivar:~$ ln new_file hard_link
artyr@Arhivar:~$ ls -l
total 16
-rw-r--r-- 3 artyr artyr 0 Mar 23 19:42 hard_link
drwxr-xr-x 2 artyr artyr 4096 Mar 19 10:28 new_Dir
drwxr-xr-x 2 artyr artyr 4096 Mar 23 19:44 new_dir
-rw-r--r-- 3 artyr artyr 0 Mar 23 19:42 new_file
drwx------ 2 artyr artyr 4096 Mar 19 10:53 secure
lrwxrwxrwx 1 artyr artyr 8 Mar 23 19:45 soft_link -> new_file
-rwxr--r-- 1 artyr artyr 13 Mar 19 10:50 test.sh

<!--Створи символічне посилання  -->

artyr@Arhivar:~$ ln -s new_file soft_link
artyr@Arhivar:~$ ls -l
total 16
drwxr-xr-x 2 artyr artyr 4096 Mar 19 10:28 new_Dir
drwxr-xr-x 2 artyr artyr 4096 Mar 23 19:44 new_dir
-rw-r--r-- 2 artyr artyr 0 Mar 23 19:42 new_file
drwx------ 2 artyr artyr 4096 Mar 19 10:53 secure
lrwxrwxrwx 1 artyr artyr 8 Mar 23 19:45 soft_link -> new_file
-rwxr--r-- 1 artyr artyr 13 Mar 19 10:50 test.sh

<!--Знайди файл по імені  -->

artyr@Arhivar:~$ find /home/artyr/new_file
/home/artyr/new_file

<!-- Завдання 3. Права доступу -->

<!-- Переглянь права файлу, який ти створив -->

artyr@Arhivar:~$ ls -l
total 16
-rw-r--r-- 3 artyr artyr 0 Mar 23 19:42 hard_link
drwxr-xr-x 2 artyr artyr 4096 Mar 19 10:28 new_Dir
drwxr-xr-x 2 artyr artyr 4096 Mar 23 19:44 new_dir
-rw-r--r-- 3 artyr artyr 0 Mar 23 19:42 new_file
drwx------ 2 artyr artyr 4096 Mar 19 10:53 secure
lrwxrwxrwx 1 artyr artyr 8 Mar 23 19:45 soft_link -> new_file
-rwxr--r-- 1 artyr artyr 13 Mar 19 10:50 test.sh

<!--Надай файлу права тільки на читання  -->

artyr@Arhivar:~$ chmod 444 new_file
artyr@Arhivar:~$ ls -l
total 16
-r--r--r-- 3 artyr artyr 0 Mar 23 19:42 hard_link
drwxr-xr-x 2 artyr artyr 4096 Mar 19 10:28 new_Dir
drwxr-xr-x 2 artyr artyr 4096 Mar 23 19:44 new_dir
-r--r--r-- 3 artyr artyr 0 Mar 23 19:42 new_file
drwx------ 2 artyr artyr 4096 Mar 19 10:53 secure
lrwxrwxrwx 1 artyr artyr 8 Mar 23 19:45 soft_link -> new_file
-rwxr--r-- 1 artyr artyr 13 Mar 19 10:50 test.sh

<!--Надай власнику право на запис  -->

artyr@Arhivar:~$ chmod 644 new_file
artyr@Arhivar:~$ ls -l
total 16
-rw-r--r-- 3 artyr artyr 0 Mar 23 19:42 hard_link
drwxr-xr-x 2 artyr artyr 4096 Mar 19 10:28 new_Dir
drwxr-xr-x 2 artyr artyr 4096 Mar 23 19:44 new_dir
-rw-r--r-- 3 artyr artyr 0 Mar 23 19:42 new_file
drwx------ 2 artyr artyr 4096 Mar 19 10:53 secure
lrwxrwxrwx 1 artyr artyr 8 Mar 23 19:45 soft_link -> new_file
-rwxr--r-- 1 artyr artyr 13 Mar 19 10:50 test.sh

<!-- Переглянь значення umask -->

artyr@Arhivar:~$ umask
0022

<!-- Встанови нове значення, наприклад 022 -->

artyr@Arhivar:~$ umask 044
artyr@Arhivar:~$ umask
0044

<!-- Завдання 4. Користувачі -->
<!--Створи нового користувача  -->

artyr@Arhivar:~$ adduser new_user
fatal: Only root may add a user or group to the system.
artyr@Arhivar:~$ sudo adduser new_user
[sudo] password for artyr:
info: Adding user `new_user' ...
info: Selecting UID/GID from range 1000 to 59999 ...
info: Adding new group `new_user' (1003) ...
info: Adding new user `new_user' (1003) with group `new_user (1003)' ...
info: Creating home directory `/home/new_user' ...
info: Copying files from `/etc/skel' ...
New password:
Retype new password:
passwd: password updated successfully
Changing the user information for new_user
Enter the new value, or press ENTER for the default
Full Name []:
Room Number []:
Work Phone []:
Home Phone []:
Other []:
Is the information correct? [Y/n] y
info: Adding new user `new_user' to supplemental / extra groups `users' ...
info: Adding user `new_user' to group `users' ...

<!--Додай його до sudo-групи  -->

artyr@Arhivar:~$ sudo usermod -aG sudo new_user

<!--Перевір, що користувач існує  -->

artyr@Arhivar:~$ cat /etc/passwd | grep new_user
new_user:x:1003:1003:,,,:/home/new_user:/bin/bash

artyr@Arhivar:~$ id new_user
uid=1003(new_user) gid=1003(new_user) groups=1003(new_user),27(sudo),100(users)
