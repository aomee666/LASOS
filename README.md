# LASOS COMPATIBILITY
rn x86_64 we will add 32bit soon and arm 
no gnu busybox
no systemd we use epoch (look it up)
16MIB of ram on idle unlike someone who sucks up 4.5gb 
like 6mib tarball sorry its supposed to be 3mib but im to lazy so cry about it
# WHY WE ARE BETTER THAN MICROSOFT
anyone is better than them 
# WHY USE LASOS INSTEAD OF ALPINE 
smaller and use less ram
# PACKAGE SYSTEM
apk alpine package manager
# FIWI
copy 1-1 to get e1000 eth0 working mostly for myself qemu testing

ip link set lo up
udhcpc -i eth0
or if udhcpc not found:
dhcpcd eth0
or busybox one:
busybox udhcpc -i eth0

ip a
ping 8.8.8.8
