# openwrt-mtall
ca6c46b1b5b0a64697e95e055022de6b  openwrt-mtall-xz_00
17aa1d140e3a0fb9c60b011f036a717c  openwrt-mtall-xz_01
cf720526d3fc00026570da780c1f25ea  openwrt-mtall-xz_02
1f40e1f1749ec4e354a080a350f4e1b9  openwrt-mtall-xz_03
3b437e7d0842f438aa65ce9127426a56  openwrt-mtall-xz_04
a652a4f19cfddf052005ae02b024bd91  openwrt-mtall-xz_05
0d69f4a11fa946c4ef3e45729dd88011  openwrt-mtall-xz_06
92a9b016a0eb61492d7282ed966d8141  openwrt-mtall-xz_07
13181f9b4e385f43836efa5ed0fe2171  openwrt-mtall-xz_08
8a9d0fcec0315f9baf00a1698aa08c4f  openwrt-mtall-xz_09
85ae76750dd09ed86b820d7513bc7853  openwrt-mtall-xz_10

-rw-rw-r-- 1  83886080 Apr 20 16:37 openwrt-mtall-xz_00
-rw-rw-r-- 1  83886080 Apr 20 16:37 openwrt-mtall-xz_01
-rw-rw-r-- 1  83886080 Apr 20 16:37 openwrt-mtall-xz_02
-rw-rw-r-- 1  83886080 Apr 20 16:37 openwrt-mtall-xz_03
-rw-rw-r-- 1  83886080 Apr 20 16:37 openwrt-mtall-xz_04
-rw-rw-r-- 1  83886080 Apr 20 16:37 openwrt-mtall-xz_05
-rw-rw-r-- 1  83886080 Apr 20 16:37 openwrt-mtall-xz_06
-rw-rw-r-- 1  83886080 Apr 20 16:37 openwrt-mtall-xz_07
-rw-rw-r-- 1  83886080 Apr 20 16:37 openwrt-mtall-xz_08
-rw-rw-r-- 1  83886080 Apr 20 16:37 openwrt-mtall-xz_09
-rw-rw-r-- 1  14014800 Apr 20 16:37 openwrt-mtall-xz_10

cat small_files* > large_file

In ubuntu18.04, run the following:

apt install libssl1.0-dev

To send mail, follow these steps:

1. wget http://v4.ipv6-test.com/api/myip.php
2. IPADDR=`cat /root/myip.php`
3. mailsend -ehlo -4 -smtp smtp.139.com -port 25 -t mobilephone@139.com -f mobilephone@139.com -sub "$IPADDR 9099(91) 9080(80) 9022(22) 9090(8090)" -starttls -pass "password" -auth -user mobilephone -msg-body /root/myip.php

