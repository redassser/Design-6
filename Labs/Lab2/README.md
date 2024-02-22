### [<- Return](../../)

# Lab 2

Find my progress on [Lesson 1](../../Lessons/Lesson1/) and [Lesson 2](../../Lessons//Lesson2/) over in the Lessons folder.

`hostname`: `rpi`
`env`:

```bash
SHELL=/bin/bash
LANGUAGE=en_US.UTF-8
NO_AT_BRIDGE=1
PWD=/home/ryan
LOGNAME=ryan
XDG_SESSION_TYPE=tty
MOTD_SHOWN=pam
HOME=/home/ryan
LANG=en_US.UTF-8
LS_COLORS=rs=0:di=01;34:ln=01;36:mh=00:pi=40;33:so=01;35:do=01;35:bd=40;33;01:cd=40;33;01:or=40;31;01:mi=00:su=37;41:sg=30;43:ca=30;41:tw=30;42:ow=34;42:st=37;44:ex=01;32:*.tar=01;31:*.tgz=01;31:*.arc=01;31:*.arj=01;31:*.taz=01;31:*.lha=01;31:*.lz4=01;31:*.lzh=01;31:*.lzma=01;31:*.tlz=01;31:*.txz=01;31:*.tzo=01;31:*.t7z=01;31:*.zip=01;31:*.z=01;31:*.dz=01;31:*.gz=01;31:*.lrz=01;31:*.lz=01;31:*.lzo=01;31:*.xz=01;31:*.zst=01;31:*.tzst=01;31:*.bz2=01;31:*.bz=01;31:*.tbz=01;31:*.tbz2=01;31:*.tz=01;31:*.deb=01;31:*.rpm=01;31:*.jar=01;31:*.war=01;31:*.ear=01;31:*.sar=01;31:*.rar=01;31:*.alz=01;31:*.ace=01;31:*.zoo=01;31:*.cpio=01;31:*.7z=01;31:*.rz=01;31:*.cab=01;31:*.wim=01;31:*.swm=01;31:*.dwm=01;31:*.esd=01;31:*.jpg=01;35:*.jpeg=01;35:*.mjpg=01;35:*.mjpeg=01;35:*.gif=01;35:*.bmp=01;35:*.pbm=01;35:*.pgm=01;35:*.ppm=01;35:*.tga=01;35:*.xbm=01;35:*.xpm=01;35:*.tif=01;35:*.tiff=01;35:*.png=01;35:*.svg=01;35:*.svgz=01;35:*.mng=01;35:*.pcx=01;35:*.mov=01;35:*.mpg=01;35:*.mpeg=01;35:*.m2v=01;35:*.mkv=01;35:*.webm=01;35:*.webp=01;35:*.ogm=01;35:*.mp4=01;35:*.m4v=01;35:*.mp4v=01;35:*.vob=01;35:*.qt=01;35:*.nuv=01;35:*.wmv=01;35:*.asf=01;35:*.rm=01;35:*.rmvb=01;35:*.flc=01;35:*.avi=01;35:*.fli=01;35:*.flv=01;35:*.gl=01;35:*.dl=01;35:*.xcf=01;35:*.xwd=01;35:*.yuv=01;35:*.cgm=01;35:*.emf=01;35:*.ogv=01;35:*.ogx=01;35:*.aac=00;36:*.au=00;36:*.flac=00;36:*.m4a=00;36:*.mid=00;36:*.midi=00;36:*.mka=00;36:*.mp3=00;36:*.mpc=00;36:*.ogg=00;36:*.ra=00;36:*.wav=00;36:*.oga=00;36:*.opus=00;36:*.spx=00;36:*.xspf=00;36:
SSH_CONNECTION=192.168.1.163 58491 192.168.1.156 22
XDG_SESSION_CLASS=user
TERM=xterm-256color
USER=ryan
SHLVL=1
XDG_SESSION_ID=4
XDG_RUNTIME_DIR=/run/user/1000
SSH_CLIENT=192.168.1.163 58491 22
LC_ALL=en_US.UTF-8
PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/local/games:/usr/games
DBUS_SESSION_BUS_ADDRESS=unix:path=/run/user/1000/bus
SSH_TTY=/dev/pts/0
TEXTDOMAIN=Linux-PAM
_=/usr/bin/env
```

`ps`:

```bash
  PID TTY          TIME CMD
 1352 pts/0    00:00:00 bash
 1392 pts/0    00:00:00 ps
```

`pwd`: `/home/ryan`

`ls`:

```ls
apps       health   lesson10  lesson4  lesson7  make       special_problems   systems
cases      hype     lesson2   lesson5  lesson8  projects   standards          tools
economics  lesson1  lesson3   lesson6  lesson9  README.md  startup_mailer.py
```

`df`:

```bash
Filesystem     1K-blocks    Used Available Use% Mounted on
/dev/root       30431968 3714844  25422284  13% /
devtmpfs          344520       0    344520   0% /dev
tmpfs             476104       0    476104   0% /dev/shm
tmpfs             190444    1100    189344   1% /run
tmpfs               5120       4      5116   1% /run/lock
/dev/mmcblk0p1    261108   52542    208566  21% /boot
tmpfs              95220      24     95196   1% /run/user/1000
```

`uname -a`:

```bash
Linux rpi 6.1.21-v7+ #1642 SMP Mon Apr  3 17:20:52 BST 2023 armv7l GNU/Linux
```

`ifconfig`:

```bash
eth0: flags=4099<UP,BROADCAST,MULTICAST>  mtu 1500
        ether b8:27:eb:89:40:7b  txqueuelen 1000  (Ethernet)
        RX packets 0  bytes 0 (0.0 B)
        RX errors 0  dropped 0  overruns 0  frame 0
        TX packets 0  bytes 0 (0.0 B)
        TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0

lo: flags=73<UP,LOOPBACK,RUNNING>  mtu 65536
        inet 127.0.0.1  netmask 255.0.0.0
        inet6 ::1  prefixlen 128  scopeid 0x10<host>
        loop  txqueuelen 1000  (Local Loopback)
        RX packets 26  bytes 2633 (2.5 KiB)
        RX errors 0  dropped 0  overruns 0  frame 0
        TX packets 26  bytes 2633 (2.5 KiB)
        TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0

wlan0: flags=4163<UP,BROADCAST,RUNNING,MULTICAST>  mtu 1500
        inet 192.168.1.156  netmask 255.255.255.0  broadcast 192.168.1.255
        inet6 2600:4040:a395:7900:c24a:d1fd:1cd0:f3fa  prefixlen 64  scopeid 0x0<global>
        inet6 fe80::1712:c47d:9dbc:2868  prefixlen 64  scopeid 0x20<link>
        ether b8:27:eb:dc:15:2e  txqueuelen 1000  (Ethernet)
        RX packets 4383  bytes 511746 (499.7 KiB)
        RX errors 0  dropped 0  overruns 0  frame 0
        TX packets 412  bytes 48173 (47.0 KiB)
        TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0
```

`ping localhost`:

```bash
PING localhost(localhost (::1)) 56 data bytes
64 bytes from localhost (::1): icmp_seq=1 ttl=64 time=0.143 ms
64 bytes from localhost (::1): icmp_seq=2 ttl=64 time=0.125 ms
64 bytes from localhost (::1): icmp_seq=3 ttl=64 time=0.126 ms
64 bytes from localhost (::1): icmp_seq=4 ttl=64 time=0.102 ms
64 bytes from localhost (::1): icmp_seq=5 ttl=64 time=0.113 ms
 ... etc ...
^C
--- localhost ping statistics ---
30 packets transmitted, 30 received, 0% packet loss, time 30194ms
rtt min/avg/max/mdev = 0.085/0.121/0.156/0.016 ms
```

`netstat`:

```bash
Active Internet connections (w/o servers)
Proto Recv-Q Send-Q Local Address           Foreign Address         State
tcp        0    216 raspberrypi:ssh         DESKTOP-5SFIIP6:58491   ESTABLISHED
tcp        0      0 localhost:45028         localhost:33819         ESTABLISHED
tcp        0      0 localhost:33819         localhost:45028         ESTABLISHED
Active UNIX domain sockets (w/o servers)
Proto RefCnt Flags       Type       State         I-Node   Path
unix  3      [ ]         STREAM     CONNECTED     16451
unix  2      [ ]         DGRAM      CONNECTED     13731
unix  2      [ ]         DGRAM      CONNECTED     12458
unix  2      [ ]         DGRAM      CONNECTED     11567
unix  3      [ ]         STREAM     CONNECTED     12584    /run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     14980
unix  3      [ ]         STREAM     CONNECTED     15471    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     14228    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     14319    /run/user/1000/bus
unix  3      [ ]         STREAM     CONNECTED     14639    /run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     12683    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     16463
unix  2      [ ]         DGRAM      CONNECTED     16460
unix  2      [ ]         DGRAM      CONNECTED     13976
unix  3      [ ]         STREAM     CONNECTED     13732
unix  3      [ ]         STREAM     CONNECTED     17848
unix  3      [ ]         STREAM     CONNECTED     15504    /run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     12788
unix  3      [ ]         STREAM     CONNECTED     16819    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     15348    /run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     5110     @/tmp/.X11-unix/X0
unix  3      [ ]         STREAM     CONNECTED     13933    /run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     11141    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     17146    /run/cups/cups.sock
unix  3      [ ]         STREAM     CONNECTED     13929
unix  2      [ ]         DGRAM                    12859    /run/user/1000/systemd/notify
unix  3      [ ]         STREAM     CONNECTED     17853
unix  3      [ ]         STREAM     CONNECTED     14956
unix  3      [ ]         STREAM     CONNECTED     14952
unix  3      [ ]         STREAM     CONNECTED     14316    /run/user/1000/bus
unix  3      [ ]         STREAM     CONNECTED     12682
unix  3      [ ]         STREAM     CONNECTED     13741
unix  2      [ ]         DGRAM      CONNECTED     17881
unix  3      [ ]         STREAM     CONNECTED     16818    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     15730    /run/user/1000/bus
unix  3      [ ]         STREAM     CONNECTED     14948    /run/systemd/journal/stdout
unix  2      [ ]         DGRAM                    14318
unix  3      [ ]         STREAM     CONNECTED     16553
unix  3      [ ]         STREAM     CONNECTED     12537
unix  3      [ ]         STREAM     CONNECTED     13930
unix  3      [ ]         STREAM     CONNECTED     5107     @/tmp/.X11-unix/X0
unix  3      [ ]         STREAM     CONNECTED     14951
unix  3      [ ]         STREAM     CONNECTED     16550    @/tmp/.X11-unix/X0
unix  2      [ ]         DGRAM      CONNECTED     11621
unix  3      [ ]         STREAM     CONNECTED     11611
unix  4      [ ]         DGRAM      CONNECTED     4308     /run/systemd/notify
unix  3      [ ]         STREAM     CONNECTED     14932
unix  2      [ ]         DGRAM      CONNECTED     12798
unix  3      [ ]         STREAM     CONNECTED     18442
unix  3      [ ]         STREAM     CONNECTED     15663    @/tmp/.X11-unix/X0
unix  3      [ ]         STREAM     CONNECTED     15601    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     14315
unix  3      [ ]         STREAM     CONNECTED     14928
unix  2      [ ]         DGRAM                    12575
unix  2      [ ]         DGRAM      CONNECTED     13774
unix  3      [ ]         DGRAM      CONNECTED     11625
unix  3      [ ]         STREAM     CONNECTED     11804
unix  3      [ ]         STREAM     CONNECTED     16552
unix  2      [ ]         DGRAM                    11017    /run/systemd/journal/syslog
unix  3      [ ]         STREAM     CONNECTED     16517
unix  2      [ ]         STREAM     CONNECTED     12760
unix  2      [ ]         DGRAM                    12792
unix  3      [ ]         DGRAM      CONNECTED     11624
unix  20     [ ]         DGRAM      CONNECTED     11024    /run/systemd/journal/dev-log
unix  3      [ ]         STREAM     CONNECTED     13893
unix  7      [ ]         DGRAM      CONNECTED     11026    /run/systemd/journal/socket
unix  3      [ ]         STREAM     CONNECTED     11806
unix  3      [ ]         STREAM     CONNECTED     15600    /run/user/1000/bus
unix  3      [ ]         STREAM     CONNECTED     12783
unix  3      [ ]         STREAM     CONNECTED     12189    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     14710
unix  3      [ ]         STREAM     CONNECTED     13733
unix  3      [ ]         STREAM     CONNECTED     17504    /run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     16549
unix  3      [ ]         STREAM     CONNECTED     11805    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     15554    /run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     12812
unix  3      [ ]         DGRAM      CONNECTED     14664
unix  3      [ ]         STREAM     CONNECTED     14638
unix  2      [ ]         DGRAM      CONNECTED     12647
unix  2      [ ]         DGRAM      CONNECTED     16462
unix  2      [ ]         DGRAM      CONNECTED     14294
unix  3      [ ]         STREAM     CONNECTED     14949
unix  3      [ ]         STREAM     CONNECTED     17476
unix  3      [ ]         STREAM     CONNECTED     17438    @/tmp/.X11-unix/X0
unix  3      [ ]         STREAM     CONNECTED     11807    /run/systemd/journal/stdout
unix  3      [ ]         DGRAM      CONNECTED     14663
unix  3      [ ]         STREAM     CONNECTED     13979
unix  3      [ ]         STREAM     CONNECTED     16817    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     16891    /run/user/1000/bus
unix  3      [ ]         STREAM     CONNECTED     14944    /run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     15648
unix  3      [ ]         STREAM     CONNECTED     14875
unix  3      [ ]         STREAM     CONNECTED     14568    /run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     12766    /run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     15758
unix  3      [ ]         STREAM     CONNECTED     17465
unix  2      [ ]         DGRAM      CONNECTED     14572
unix  3      [ ]         STREAM     CONNECTED     15725
unix  3      [ ]         STREAM     CONNECTED     17475
unix  3      [ ]         STREAM     CONNECTED     12577    /run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     13934    /run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     17154    /run/cups/cups.sock
unix  3      [ ]         STREAM     CONNECTED     15668    @/tmp/.X11-unix/X0
unix  3      [ ]         STREAM     CONNECTED     17448
unix  3      [ ]         STREAM     CONNECTED     15736
unix  3      [ ]         STREAM     CONNECTED     14849
unix  3      [ ]         STREAM     CONNECTED     14567
unix  3      [ ]         STREAM     CONNECTED     17469    /run/user/1000/bus
unix  3      [ ]         STREAM     CONNECTED     14943    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     4952
unix  3      [ ]         STREAM     CONNECTED     5041
unix  3      [ ]         STREAM     CONNECTED     18441
unix  3      [ ]         STREAM     CONNECTED     16776    /run/user/1000/bus
unix  3      [ ]         STREAM     CONNECTED     15998
unix  3      [ ]         STREAM     CONNECTED     16775    /run/user/1000/bus
unix  3      [ ]         STREAM     CONNECTED     14878
unix  3      [ ]         STREAM     CONNECTED     15741
unix  3      [ ]         STREAM     CONNECTED     16580    /run/user/1000/bus
unix  3      [ ]         STREAM     CONNECTED     12586    /run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     14338
unix  3      [ ]         STREAM     CONNECTED     16820    /run/user/1000/bus
unix  3      [ ]         STREAM     CONNECTED     15667
unix  3      [ ]         STREAM     CONNECTED     14856
unix  3      [ ]         STREAM     CONNECTED     4950
unix  3      [ ]         STREAM     CONNECTED     15706
unix  3      [ ]         STREAM     CONNECTED     14591
unix  3      [ ]         STREAM     CONNECTED     14880
unix  3      [ ]         STREAM     CONNECTED     14402
unix  3      [ ]         STREAM     CONNECTED     16665    /run/user/1000/bus
unix  3      [ ]         STREAM     CONNECTED     15696    @/tmp/.X11-unix/X0
unix  3      [ ]         STREAM     CONNECTED     14403    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     17463
unix  3      [ ]         STREAM     CONNECTED     14456
unix  3      [ ]         STREAM     CONNECTED     15053    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     15692    @/tmp/.X11-unix/X0
unix  3      [ ]         STREAM     CONNECTED     12228
unix  3      [ ]         STREAM     CONNECTED     15717
unix  3      [ ]         STREAM     CONNECTED     5046
unix  3      [ ]         STREAM     CONNECTED     15387
unix  3      [ ]         STREAM     CONNECTED     14569    /run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     17416
unix  3      [ ]         STREAM     CONNECTED     16734    @/tmp/.X11-unix/X0
unix  3      [ ]         STREAM     CONNECTED     16662    @/tmp/.X11-unix/X0
unix  3      [ ]         STREAM     CONNECTED     5057     /run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     5052
unix  3      [ ]         STREAM     CONNECTED     15693    @/tmp/.X11-unix/X0
unix  3      [ ]         STREAM     CONNECTED     16557    /run/user/1000/bus
unix  3      [ ]         STREAM     CONNECTED     15831
unix  3      [ ]         STREAM     CONNECTED     15691
unix  3      [ ]         STREAM     CONNECTED     14573    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     12190    /run/systemd/journal/stdout
unix  2      [ ]         STREAM     CONNECTED     16023
unix  3      [ ]         STREAM     CONNECTED     17417
unix  3      [ ]         STREAM     CONNECTED     4898
unix  2      [ ]         DGRAM                    14457
unix  2      [ ]         DGRAM      CONNECTED     15833
unix  3      [ ]         STREAM     CONNECTED     17424
unix  3      [ ]         STREAM     CONNECTED     12657    /run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     17418
unix  2      [ ]         DGRAM      CONNECTED     4938
unix  3      [ ]         STREAM     CONNECTED     15448
unix  3      [ ]         STREAM     CONNECTED     14604
unix  3      [ ]         STREAM     CONNECTED     17530
unix  3      [ ]         STREAM     CONNECTED     5098
unix  2      [ ]         DGRAM      CONNECTED     4377
unix  3      [ ]         STREAM     CONNECTED     4989
unix  3      [ ]         STREAM     CONNECTED     14954    /run/user/1000/bus
unix  3      [ ]         STREAM     CONNECTED     14258
unix  3      [ ]         STREAM     CONNECTED     14600
unix  3      [ ]         STREAM     CONNECTED     17532
unix  3      [ ]         STREAM     CONNECTED     15718    /run/user/1000/bus
unix  3      [ ]         STREAM     CONNECTED     15376
unix  3      [ ]         STREAM     CONNECTED     14605    /run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     16432    /run/user/1000/bus
unix  2      [ ]         DGRAM      CONNECTED     12829
unix  3      [ ]         STREAM     CONNECTED     15378    /run/systemd/journal/stdout
unix  2      [ ]         DGRAM      CONNECTED     12563
unix  3      [ ]         STREAM     CONNECTED     14361    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     14182
unix  3      [ ]         STREAM     CONNECTED     17499
unix  3      [ ]         STREAM     CONNECTED     14381    /run/systemd/journal/stdout
unix  3      [ ]         DGRAM      CONNECTED     12860
unix  3      [ ]         STREAM     CONNECTED     16896    @/dbus-vfs-daemon/socket-hQutFmGx
unix  3      [ ]         STREAM     CONNECTED     14362    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     15377    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     14658    /run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     17575
unix  3      [ ]         STREAM     CONNECTED     15762    /run/user/1000/pulse/native
unix  3      [ ]         STREAM     CONNECTED     4971
unix  3      [ ]         STREAM     CONNECTED     16434    /run/user/1000/pipewire-0
unix  3      [ ]         STREAM     CONNECTED     12864
unix  3      [ ]         STREAM     CONNECTED     12656    /run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     13990
unix  3      [ ]         STREAM     CONNECTED     16575
unix  3      [ ]         STREAM     CONNECTED     17601
unix  3      [ ]         STREAM     CONNECTED     16828
unix  3      [ ]         DGRAM      CONNECTED     12861
unix  3      [ ]         STREAM     CONNECTED     16433    /run/user/1000/pipewire-0
unix  2      [ ]         DGRAM      CONNECTED     5039     /tmp/.vncserver-license/0.533
unix  3      [ ]         DGRAM      CONNECTED     4772
unix  3      [ ]         STREAM     CONNECTED     15694    @/tmp/.X11-unix/X0
unix  3      [ ]         STREAM     CONNECTED     12546
unix  3      [ ]         STREAM     CONNECTED     16829
unix  3      [ ]         STREAM     CONNECTED     14289
unix  2      [ ]         DGRAM      CONNECTED     5037
unix  3      [ ]         STREAM     CONNECTED     17602    /run/dhcpcd.unpriv.sock
unix  3      [ ]         STREAM     CONNECTED     12215    /run/systemd/journal/stdout
unix  3      [ ]         DGRAM      CONNECTED     4773
unix  3      [ ]         STREAM     CONNECTED     15763    /run/user/1000/pulse/native
unix  3      [ ]         STREAM     CONNECTED     16740
unix  3      [ ]         STREAM     CONNECTED     14667    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     4837
unix  3      [ ]         STREAM     CONNECTED     15063    /run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     14601    /run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     13932    /run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     16576    @/tmp/.X11-unix/X0
unix  3      [ ]         DGRAM      CONNECTED     4770
unix  3      [ ]         STREAM     CONNECTED     11816    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     15624    /run/dbus/system_bus_socket
unix  2      [ ]         DGRAM      CONNECTED     4766
unix  3      [ ]         STREAM     CONNECTED     16965    /run/user/1000/menu-cached-:0
unix  2      [ ]         DGRAM      CONNECTED     15411
unix  3      [ ]         STREAM     CONNECTED     14290
unix  2      [ ]         DGRAM      CONNECTED     14103
unix  3      [ ]         STREAM     CONNECTED     17612
unix  3      [ ]         STREAM     CONNECTED     15449
unix  3      [ ]         STREAM     CONNECTED     14183    /run/systemd/journal/stdout
unix  3      [ ]         DGRAM      CONNECTED     4771
unix  3      [ ]         STREAM     CONNECTED     16741
unix  3      [ ]         STREAM     CONNECTED     16756
unix  2      [ ]         DGRAM      CONNECTED     16682
unix  3      [ ]         STREAM     CONNECTED     17603
unix  3      [ ]         STREAM     CONNECTED     5097
unix  2      [ ]         DGRAM                    17143
unix  3      [ ]         STREAM     CONNECTED     17604    /run/dhcpcd.unpriv.sock
unix  3      [ ]         STREAM     CONNECTED     15447
unix  2      [ ]         DGRAM      CONNECTED     12821
unix  3      [ ]         DGRAM      CONNECTED     4309
unix  3      [ ]         DGRAM      CONNECTED     4310
unix  3      [ ]         STREAM     CONNECTED     12202    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     16823    /run/user/1000/bus
unix  3      [ ]         STREAM     CONNECTED     16822    /run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     14283
unix  3      [ ]         STREAM     CONNECTED     13931    /run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     14292    /run/user/1000/bus
unix  3      [ ]         STREAM     CONNECTED     4836
unix  3      [ ]         STREAM     CONNECTED     4724
unix  3      [ ]         STREAM     CONNECTED     17478
unix  2      [ ]         DGRAM      CONNECTED     17607    /tmp/dhcpcd-ryan/libdhcpcd-wpa-884.0
unix  3      [ ]         STREAM     CONNECTED     13681    /run/systemd/journal/stdout
unix  2      [ ]         DGRAM      CONNECTED     17608    /tmp/dhcpcd-ryan/libdhcpcd-wpa-884.1
unix  4      [ ]         DGRAM      CONNECTED     14080    /var/run/wpa_supplicant/wlan0
unix  2      [ ]         DGRAM                    14089    /var/run/wpa_supplicant/p2p-dev-wlan0
unix  3      [ ]         STREAM     CONNECTED     17477
unix  3      [ ]         STREAM     CONNECTED     12902
unix  3      [ ]         STREAM     CONNECTED     15728    /run/user/1000/bus
unix  3      [ ]         STREAM     CONNECTED     14280    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     4796
```
