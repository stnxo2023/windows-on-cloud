![Visitors](https://api.visitorbadge.io/api/visitors?path=amjiddader%2Fwindows-on-cloud&label=VISITORS&labelColor=%232ccce4&countColor=%23f47373&style=flat&labelStyle=upper)




# Windows on Cloud.

>> Not maintaining anymore..

Install Windows on any Cloud VM including Digitalocean , vultr... \
3 files are included with different versions and size. choose one based on your needs.

:: THIS CODE IS HOSTED ON [GITHUB](https://github.com/amjiddader/windows-on-cloud) - [SOURCEFORGE](https://sourceforge.net/projects/windows-on-cloud/)  \
:: FILES ARE HOSTED ON MULTIPLE PROVIDERS - \
:: FOR DMCA or REMOVAL CONTACT RESPECTIVE PROVIDER.. 


# UPDATE 
## New Mirror Fast with 30MBs speed

```
https://windows-on-cloud.wansaw.com
```
Also if your provider supports you can install from ISO
```
wget -O- 'https://releases.ubuntu.com/20.04.6/ubuntu-20.04.6-desktop-amd64.iso' |  dd of=/dev/vda bs=4M status=progress
```
### Install win(debolted)  (Recommended)
1 Command Install (change disk var)
```
wget -O- 'https://bit.ly/win11-on-cloud_gz' | gunzip | dd of=/dev/vda bs=4M
```
## Auto Install 
You can now use below command to auto install Windows.
- Reboot your server in Recovery Mode.
- Mount your disk (on DigitalOcean press 1.
- Important: make sure to check where windows will be installed script will dedect your disk if not..
- Check your install by running..  df -h
- It will give you list of disks (example: /dev/vda)
- In shell choose Intractive mode or press 6 - On some hosts it may differ..
 
``` curl -o install.sh -fsSL https://github.com/amjiddader/windows-on-cloud/raw/main/install  && bash install.sh ```

- Once Windows is installed - Boot from Disk and access RDP using browser consol.
- At this point your windows will not have Internet so login and change Internet setting.
- On Windows 11 debolted , You need to open Brave or Trash on desktop to restart explorer ( on boot task bar is not showing...)


## SUPPORT 
You can help by uploading images on some good ad-free cloud providers and make sure files will remain online for lone time. \
If someone can host below files on DropxBox i will appericate. \
Such persons can send me dropox invite link. and i will upload files to his account. \
For more: create an issue at github :

## Getting Started... 
I have tried on multiple provider all of them are good. \
**UpCloud** *is very good in terms of bandwidith and Internet Spped of server* \
[Get UPCLOUD 75$](https://upcloud.com/signup/?promo=EE875F) \
**DigitalOcean** *is cheap and has lot ok options to go with But network is very slow.* \
Use my referal link to get 200$ on digitalocean \
[GET 200$](https://m.do.co/c/f5028642478c) \
**VULTR** *Is also good if you are looking for more locations to spin your server.* \
But vultr servers and network is not that good.

:: Using my referral link for Digitalocean will give 100$ credits and i iwll get 25$. \
:: Using my referral link for upcloud will give you 50$ and i will get 25$ 

I recommend not to install on windows on VM  \
Get a windows instance from valid provider. \

---------------------------------------------------------------
# 1. WIN11 (do not use)
This one is pure windows 11 default windows settings and apps.
- For now do not use this, It takes lot of resources...
- It may not boot properly...
```
Username: Administrator
Password: Thuonghai001
```
Download Links (FAST MIRROR)
```
https://windows-on-cloud.wansaw.com/0:/win11
```
Alternative Mirrors
```
https://archive.org/download/windows11-tiny11-cloudvm/win11
https://master.dl.sourceforge.net/project/windows-on-cloud/win11?viasf=1
```
MIRROR: https://www.multiup.org/en/mirror/12ca28b33f010c41889b8fd8b715d1e9/win11

Tested on : Digitalocean : 4GB ram and is not smooth..

==========

# 2.  WIN11 (debolted) 
This version is extreamly debolted and removed all microsoft apps. \
- Updates are disabled.
- Tightvnc installed with same password 
- Installed some vc++
- Installed MalwareBytes (To make sure no bugs)
- Installed Brave Browser
- Uninstalled all windows app
- Uninstalled Edge and other win Softwares

NOTE: After installation it may take few seconds as this is debolted version so microsoft will look for its apps. \
Also you may not see task bar - Open Brave Browser on desktop and all background processes will exit.
Setup Network from web console... 

```
Username : Amjad 
Password: amjiddader
TightVNC PASS: amjiddader
```
Download Links (FAST MIRROR)
```
https://windows-on-cloud.wansaw.com/0:/win_11_ami.gz
```


Alternative Links
```
https://archive.org/download/windows11-tiny11-cloudvm/win_11.gz
https://master.dl.sourceforge.net/project/windows-on-cloud/win_11.gz?viasf=1
```
MIRROR: https://www.multiup.org/en/mirror/f55f3a6957d984fe3811cc39d0e701e2/win_11.gz

Tested on: Digitalocean Regular 4Gb - 2CPU -- it uses very less RAM and runs very smooth.

==========
# 3. Windows 10 ( bonus)
This is just a copy of whatuptime ... credits to them.
```
Username : Administrator
Password: P@ssword64
```
Download Link (FAST MIRROR)
```
https://windows-on-cloud.wansaw.com/0:/win10_en.gz
```
Alternative Mirros.
```
https://archive.org/download/windows11-tiny11-cloudvm/win10_en.gz
https://master.dl.sourceforge.net/project/windows-on-cloud/win10_en.gz?viasf=1
```
MIRROR: https://www.multiup.org/en/mirror/97dc02190298a64454e556b4579e8781/win10_en.gz


# 4. Windows11 Tiny [(by Diep)](https://github.com/diepnt90)
Provided by [Diep](https://github.com/diepnt90) \
_I have not tested this myself so try on your_ \
For more details [read this issue ](https://github.com/amjiddader/windows-on-cloud/issues/9#issuecomment-3067028142)

```
Username: DiepNguyen
Password: 431990
```

Download Link (10GB)
```
https://windows-on-cloud.wansaw.com/0:/win11_tiny.gz
```

------------------------
## Installation
```
Installation :
wget O url | gunzip | dd of=/dev/vda bs=1M
Alternative you can download image file using aria2c exampele you downloaded win11_gz file in /temp folder 
In below command first dd= /dev/vda is your disk where you want to install os.
In below command gzip -c /win_11.gz if os file.
dd if=/dev/vda | gzip -c >/temp/win_11.gz bs=1M
Using wget ...
wget -O- 'https.............' | gunzip | dd of=/dev/vda bs=1M
Using Aria2
aria2c -s 16 -x 16 "https.........." -o | gunzip | dd of=/dev/vda bs=1M
```

## Guide. 

#### Disks 
To install windows OS on your linux server. \
Check which disk you are using in case you have 2 disks you can install eaith on one and then use windows Disk manager to play with disks. \
to check disk run: df -h \
you will get something like /dev/sda or /dev/vda  for multiple disks it will show /dev/vda0 - /dev/vda1

#### Downloads. 
You can use wget to download based on your server your speed maybe slow, \
You can then use Aria2 using 2 methods. \
1. Download & run gunzip command.. aria2c -s 16 -x 16 "https.........." -o | gunzip | dd of=/dev/vda bs=1M \
2. First download then run gunzip .. aria2c -s 16 -x 16 "https.........." -o os.gz .... \
Also make sure you add download url between braces '' or "" (if url has ? or some other string cli takes that as a break

#### Create your own. 
Get ISO file from windows or use below windows 11 (english)x64 iso \
https://master.dl.sourceforge.net/project/windows-on-cloud/win_11en.iso?viasf=1

 ## macOS (MAC) on linux
For MAC os it is not possible to run MAC on all VM and ARCH \
I have build MAC OS (12) image and successfully installed on DigitalOcean VM. \
But it took me 10 days to make things work and trust me nothing on internet helped me. \
Modified few macos source to ignore on error - usually MAC OS is very strict on unknown errors and i saw about 100 HLAT values for erros. \

Problem: Lot of things are not working including keyboard but i managed to use keyboard using Virtual Keyboard. \
Most of the useful i.e: browser, wifi etc are working..

Problem2 . You need Intel Server AMD does not work. \
You need to have atleast 8GB ram (it never used over 4GB but) \
You need to have atleast 40GB ssd (About 26GB was used by OS) \
You need have atleast 4 Cores to run MacOS


I have created MacOS raw(16GB) gz(13) and i can not find any way to upload. \
Nor i have too much space on my persoanl Drive, Not Sourceforge allow too much space. \
And archive.org is slow and never tried to upload such big file.

You are always welcome to create an ISSUE for help, how-to. \
Do not ask for MAC_12.gz image as it is 13GB + Needs lot of passion & CPU.
