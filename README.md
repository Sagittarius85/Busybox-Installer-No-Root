# Busybox-Installer-No-Root

Busybox Installer (no root) is an app designed to bring busybox to android device without root access.



We compiled the busybox binary statically by using command below

> make clean && make defconfig && make CROSS_COMPILE="/path/to/cross/compiler" LDFLAGS="--static"



### Supported architecture:

arm, arm64, x86, x86_64 mips, mips64


### Current version of busybox:

1.30.0


### Included applet:

[, [[, acpid, add-shell, addgroup, adduser, adjtimex, arp, arping, ash,
	awk, base64, basename, beep, blkdiscard, blkid, blockdev, bootchartd,
	brctl, bunzip2, bzcat, bzip2, cal, cat, chat, chattr, chgrp, chmod,
	chown, chpasswd, chpst, chroot, chrt, chvt, cksum, clear, cmp, comm,
	conspy, cp, cpio, crond, crontab, cryptpw, cttyhack, cut, date, dc, dd,
	deallocvt, delgroup, deluser, depmod, devmem, df, dhcprelay, diff,
	dirname, dmesg, dnsd, dnsdomainname, dos2unix, dpkg, dpkg-deb, du,
	dumpkmap, dumpleases, echo, ed, egrep, eject, env, envdir, envuidgid,
	ether-wake, expand, expr, factor, fakeidentd, fallocate, false,
	fatattr, fbset, fbsplash, fdflush, fdformat, fdisk, fgconsole, fgrep,
	find, findfs, flock, fold, free, freeramdisk, fsck, fsck.minix,
	fsfreeze, fstrim, fsync, ftpd, ftpget, ftpput, fuser, getopt, getty,
	grep, groups, gunzip, gzip, halt, hd, hdparm, head, hexdump, hostid,
	hostname, httpd, hush, hwclock, i2cdetect, i2cdump, i2cget, i2cset, id,
	ifconfig, ifdown, ifenslave, ifplugd, ifup, inetd, init, insmod,
	install, ionice, iostat, ip, ipaddr, ipcalc, ipcrm, ipcs, iplink,
	ipneigh, iproute, iprule, iptunnel, kbd_mode, kill, killall, killall5,
	klogd, last, less, link, linux32, linux64, linuxrc, ln, loadfont,
	loadkmap, logger, login, logname, logread, losetup, lpd, lpq, lpr, ls,
	lsattr, lsmod, lsof, lspci, lsscsi, lsusb, lzcat, lzma, lzop, makedevs,
	makemime, man, md5sum, mdev, mesg, microcom, mkdir, mkdosfs, mke2fs,
	mkfifo, mkfs.ext2, mkfs.minix, mkfs.vfat, mknod, mkpasswd, mkswap,
	mktemp, modinfo, modprobe, more, mount, mountpoint, mpstat, mt, mv,
	nameif, nanddump, nandwrite, nbd-client, nc, netstat, nice, nl, nmeter,
	nohup, nproc, nsenter, nslookup, ntpd, od, openvt, partprobe, passwd,
	paste, patch, pgrep, pidof, ping, ping6, pipe_progress, pivot_root,
	pkill, pmap, popmaildir, poweroff, powertop, printenv, printf, ps,
	pscan, pstree, pwd, pwdx, raidautorun, rdate, rdev, readahead,
	readlink, readprofile, realpath, reboot, reformime, remove-shell,
	renice, reset, resize, rev, rm, rmdir, rmmod, route, rpm, rpm2cpio,
	rtcwake, run-parts, runlevel, runsv, runsvdir, rx, script,
	scriptreplay, sed, sendmail, seq, setarch, setconsole, setfont,
	setkeycodes, setlogcons, setpriv, setserial, setsid, setuidgid, sh,
	sha1sum, sha256sum, sha3sum, sha512sum, showkey, shred, shuf, slattach,
	sleep, smemcap, softlimit, sort, split, ssl_client, start-stop-daemon,
	stat, strings, stty, su, sulogin, sum, sv, svc, svlogd, swapoff,
	swapon, switch_root, sync, sysctl, syslogd, tac, tail, tar, taskset,
	tcpsvd, tee, telnet, telnetd, test, tftp, tftpd, time, timeout, top,
	touch, tr, traceroute, traceroute6, true, truncate, tty, ttysize,
	tunctl, ubiattach, ubidetach, ubimkvol, ubirename, ubirmvol, ubirsvol,
	ubiupdatevol, udhcpc, udhcpd, udpsvd, uevent, umount, uname, unexpand,
	uniq, unix2dos, unlink, unlzma, unshare, unxz, unzip, uptime, users,
	usleep, uudecode, uuencode, vconfig, vi, vlock, volname, w, wall,
	watch, watchdog, wc, wget, which, who, whoami, whois, xargs, xxd, xz,
	xzcat, yes, zcat, zcip
