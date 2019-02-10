## Base system

Debian images including firmware:

https://cdimage.debian.org/cdimage/unofficial/non-free/cd-including-firmware/

First time manual network setup:

```shell
# list interfaces
ip link

# enable interface
ip link set [interface] up

# generate wpa_supplicant config
wpa_passphrase [network-name] > /etc/wpa_supplicant.conf

# run wpa_supplicant
wpa_supplicant -i [interface] -c /etc/wpa_supplicant.conf -B

# check interface status
iw dev [interface] link

# obtain IP address
dhclient [interface]
```