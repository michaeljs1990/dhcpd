# dhcpd

This dhcpd config requires a slightly special setup in order to boot servers using iPXE.
http://ipxe.org/howto/chainloading contains an overview of what is needed. I prefer to use
http://chschneider.eu/linux/server/tftpd-hpa.shtml since it's stupid easy to setup. None of
the setup in the guide is needed unless you want to change something. After it's intalled
drop your undionly.kpxe file in /var/lib/tftpboot.


