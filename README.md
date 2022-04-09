# Ansible4RaspberryPi
Ansible scripts to manage Raspberry Pis

The roles install a LAMP-Server and Samba on a Raspberry Pi.

# Real Time Clock

The installation of a Real Time Clock (RTC) is supported.

# GPS

With a GPS USB dongle you can convert the Rasberry Pi to a local Stratum 1 time server. To work as a Stratum 1 time server with GPS you have to calibrate the GPS dongle. You must adjust the value for *time1* in */etc/ntp.conf* to a specific value depending on your Pi and your dongle. Every combination Pi dongle has a different value.

# Rolls

  * ansible-compatible
  * common
  * dhcpserver
  * firewall
  * gps
  * ip-forward
  * jitsi
  * lightdm
  * mailserver
  * minimalsystem
  * morefacts
  * ntpserver
  * realtimeclock
  * reboot
  * samba
  * test
  * timezone
  * update
  * virtualbox
  * webserver
  * wlan