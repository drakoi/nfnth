
<p align="center">
<img src="https://github.com/nfnth/res/raw/main/site/chimi_hi.png" width="200" height="240" />
</p>

## bitOS, simplistic speed

bitOS (*version 1.04*) is a minimal site/browser-based stack based on being easy to use. 

### Installation steps

1. Use [Arch Linux](https://archlinux.org/), or download the [ISO](http://mirror.rackspace.com/archlinux/iso/2021.06.01/archlinux-2021.06.01-x86_64.iso): 

   ```
   wget http://mirror.rackspace.com/archlinux/iso/2021.06.01/archlinux-2021.06.01-x86_64.iso
   dd if=archlinux-2021.06.01-x86_64.iso of=/dev/sda status=progress #fdisk -l #show drives
   #launch BIOS (use Esc, Del, or F1..F12 on restart), then boot to USB/ISO drive
   ```

1. Download *build.sh*, adjust parameters, then run:

   ```
   pacman -S git --noconfirm #scp...? wget...?
   git clone https://github.com/nfnth/nfnth
   nano nfnth/build.sh 
   chmod +x nfnth/build.sh
   nfnth/build.sh
   ```

That's it. Enjoy!

<p align="center"><img src="https://github.com/nfnth/res/raw/main/site/chimi_cards.png" width="200" height="200" /></p>

### Additional info

- For site changes, edit *run.py* and *index.htm*, then run:

   ```
   nfnth/build.sh deploy
   ```

- Script parameters:

   |Parameter|Default|Description|
   |-|-|-|
   |**source**|on|online or offline installation|
   |**boot**|disk|disk or iso installation|
   |**drive**|`/dev/sda`|Installation drive|
   |**drived**|(empty)|Drive part, eg. `/dev/mmcblk0p1` has diskpart of `p`|
   |**host**|bitos|Hostname|
   |**password**|`temp1234`|root password|
   |**user_name**|`bit`|Default user|
   |**user_password**|`temp1234`|user password|
   |**mode**||client or server deployment|
   |**domain**|bit.com|Default site|
   |**ip**|`192.168.1.111`|IP used to assign(client) or deploy(server)|
   |**wifi_id**|||
   |**wifi_password**|||
   |**mail_server**|||
   |**mail_id**|||
   |**mail_password**|||

- Ensure the following ports are open:

   |Port|Function|
   |-|-|
   |80|http *(site)*|
   |443|https *(seure socket layer)*|
   |587|tls *(mail)*|

- How to build hardware and install from scratch... *video coming soon*

   [![fish](https://img.youtube.com/vi/-xMR_x3lYAA/0.jpg)](https://www.youtube.com/watch?v=-xMR_x3lYAA)

- Helpful commands

   ```
   vim <file> #press (i) to insert and make changes, (Esc) to escape, then either :wq (write quit) or :q (quit)
   df, ls -a, du -xhS | sort -h | tail -n15 #file/folder info
   lscpu #hardware info
   grep -R "term" #search
   iwctl #wifi
   ip addr #network
   ping google.com -c 2 #network test
   find /home/username/ -name "*.err"
   #sed 's/.*six.*/fault/' file     # check all lines
   ```


## New features


 🧦🧦.ws Get Whois Privacy16 Dec 2021 On
 🧤🧤.ws Get Whois Privacy16 Dec 2021 On
 👣👣.ws Get Whois Privacy16 Dec 2021 On
 🙂🙂.ws Get Whois Privacy16 Dec 2021 On
 👖👖.ws Get Whois Privacy16 Dec 2021 On
 👓👓.ws Get Whois Privacy16 Dec 2021 On
 🌳🌳.ws Private 27 May 2022 On
 📚📚.ws Private 12 Jul 2022 On
 ⚙⚙.ws Private 16 Nov 2022 On
 ♠♠.ws Private 16 Nov 2022 On
 🖱🖱.ws Private 16 Feb 2023 On
 🐁🐁.ws Private 16 Feb 2023 On
 🏴🏳.ws Private 15 Apr 2023 On
 🏴🏴.ws Private 15 Apr 2023 On
 🏳🏳.ws Private 15 Apr 2023 On
 🏳🏴.ws Private 15 Apr 2023 On
https://www.name.com/account/domain/details/xn--wv9ha.ws
https://www.name.com/account/domain/details/xn--uv9ha.ws
https://www.name.com/account/domain/details/xn--lq8ha.ws
https://www.name.com/account/domain/details/xn--938ha.ws
https://www.name.com/account/domain/details/xn--7p8ha.ws
https://www.name.com/account/domain/details/xn--4p8ha.ws
https://www.name.com/account/domain/details/xn--wh8ha.ws
https://www.name.com/account/domain/details/xn--zt8ha.ws
https://www.name.com/account/domain/details/xn--x7ha.ws
https://www.name.com/account/domain/details/xn--b6ha.ws
https://www.name.com/account/domain/details/xn--4z8ha.ws
https://www.name.com/account/domain/details/xn--sn8ha.ws
https://www.name.com/account/domain/details/xn--en8hb.ws
https://www.name.com/account/domain/details/xn--fn8ha.ws
https://www.name.com/account/domain/details/xn--en8ha.ws
https://www.name.com/account/domain/details/xn--en8hc.ws

abbv.us
mq1.us
