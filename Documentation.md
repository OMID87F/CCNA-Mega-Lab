>**نکته**:
> ایده و فایل خام`pka.`این سناریو از [Jeremy's IT Lab](https://youtu.be/2p7-MluKAgE?si=PZIXJnTveFXlKFq1) برداشته شده‼️

# 🔻سناریوی CCNA Mega Lab

## 🔹محیط کار و توپولوژی

![Topology](Topology.png)
Cisco Packet Tracer`9.0.1`⬆️




## 🔹هدف

- انجام دستورالعمل‌های داخل فایل`CCNA Mega Lab (Jeremy's IT Lab).pka`یا`Instructions.pdf`که نوشتم.
    
- **هدف** از این سناریو اینه که تمامی مباحث داخل CCNA رو به صورت یک جا تمرین/مرور/یادآوری کنیم!




## 🔹اقدامات و کانفیگ‌ها

### 🔸چک‌لیست
1. Part 1:
	- [x] Step 1
	- [x] Step 2
	- [x] Step 3
	- [x] Step 4
	
2. Part 2:
	- [x] Step 1
	- [x] Step 2
	- [x] Step 3
	- [x] Step 4
	- [x] Step 5
	- [x] Step 6
	- [x] Step 7
	- [x] Step 8
	- [x] Step 9
	
3. Part 3:
	- [x] Step 1
	- [x] Step 2
	- [x] Step 3
	- [x] Step 4
	- [x] Step 5
	- [x] Step 6
	- [x] Step 7
	- [x] Step 8
	- [x] Step 9
	- [x] Step 10
	- [x] Step 11
	- [x] Step 12
	- [x] Step 13
	- [x] Step 14
	- [x] Step 15
	- [x] Step 16
	- [x] Step 17
	- [x] Step 18
	- [x] Step 19
	
4. Part 4:
	- [x] Step 1
	- [x] Step 2
	
5. Part 5:
	- [x] Step 1
	- [x] Step 2
	
6. Part 6:
	- [x] Step 1
	- [x] Step 2
	- [x] Step 3
	- [x] Step 4
	- [x] Step 5
	- [x] Step 6
	- [x] Step 7
	- [x] Step 8
	- [x] Step 9
	- [x] Step 10
	- [x] Step 11
	- [x] Step 12
	- [x] Step 13
	
7. Part 7:
	- [x] Step 1
	- [x] Step 2
	- [x] Step 3
	- [x] Step 4
	
8. Part 8:
	- [x] Step 1
	- [x] Step 2
	
9. Part 9:
	- [x] Step 1
	- [x] Step 2
	- [x] Step 3
	- [x] Step 4
***
### 🔸کانفیگ‌ها
>**نکته**:
>از اول دستورات رو یه جایی ذخیره نکردم که **اشتباه** بود؛ و بخاطر حجم زیاد کانفیگ‌ها، الان صرفا میتونم Export نهایی هر دستگاه رو بذارم‼️

###### R1
[R1_running-config.txt](Final%20Config%20Files/R1_running-config.txt)

###### CSWs
[CSW1_running-config.txt](Final%20Config%20Files/CSW1_running-config.txt)  
[CSW2_running-config.txt](Final%20Config%20Files/CSW2_running-config.txt)

###### DSWs
[DSW-A1_running-config.txt](Final%20Config%20Files/DSW-A1_running-config.txt)  
[DSW-A2_running-config.txt](Final%20Config%20Files/DSW-A2_running-config.txt)  
[DSW-B1_running-config.txt](Final%20Config%20Files/DSW-B1_running-config.txt)  
[DSW-B2_running-config.txt](Final%20Config%20Files/DSW-B2_running-config.txt)

###### ASWs
[ASW-A1_running-config.txt](Final%20Config%20Files/ASW-A1_running-config.txt)  
[ASW-A2_running-config.txt](Final%20Config%20Files/ASW-A2_running-config.txt)  
[ASW-A3_running-config.txt](Final%20Config%20Files/ASW-A3_running-config.txt)  
[ASW-B1_running-config.txt](Final%20Config%20Files/ASW-B1_running-config.txt)  
[ASW-B2_running-config.txt](Final%20Config%20Files/ASW-B2_running-config.txt)  
[ASW-B3_running-config.txt](Final%20Config%20Files/ASW-B3_running-config.txt)



## 🔹راستی آزمایی
### 🔸پارت 1 - Initial Setup

بررسی اطلاعات اولیه هر دستگاه⬇️
![Verification - Part 1](Verifications/Verification%20-%20Part%201.png)

### 🔸پارت 2 - VLANs & Layer-2 EtherChannel

بررسی`VTP`و`VLAN`ها⬇️
![Verification - Part 2.1](Verifications/Verification%20-%20Part%202.1.png)


بررسی L2 EtherChannelها⬇️
![Verification - Part 2.2](Verifications/Verification%20-%20Part%202.2.png)


بررسی Trunk Portها⬇️
![Verification - Part 2.3](Verifications/Verification%20-%20Part%202.3.png)

### 🔸پارت 3 - IP Addressing, Layer-3 EtherChannel & HSRP

بررسی IP Addressها و وضعیت Interfaceها⬇️
![Verification - Part 3.1](Verifications/Verification%20-%20Part%203.1.png)


بررسی L3 EtherChannel⬇️
![Verification - Part 3.2](Verifications/Verification%20-%20Part%203.2.png)


بررسی وضعیت`HSRP`⬇️
![Verification - Part 3.3](Verifications/Verification%20-%20Part%203.3.png)
- همه چیز مطابق دستورالعمل ها انجام شده.


بررسی ارتباط بین شبکه‌ها⬇️
![Verification - Part 3.4](Verifications/Verification%20-%20Part%203.4.png)

### 🔸پارت 4 - Rapid Spanning Tree Protocol

بررسی همپوشانی Root Bridge با Active HSRP هر VLAN⬇️
![Verification - Part 4.1](Verifications/Verification%20-%20Part%204.1.png)


بررسی`Port Fast`و`BPDU Guard`روی Access Portها⬇️
![Verification - Part 4.2](Verifications/Verification%20-%20Part%204.2.png)

### 🔸پارت 5 - Static & Dynamic Routing

بررسی عملکرد`OSPF`⬇️
![Verification - Part 5.1](Verifications/Verification%20-%20Part%205.1.png)


بررسی ارتباط بین کلاینت و سرور⬇️
![Verification - Part 5.2](Verifications/Verification%20-%20Part%205.2.png)

### 🔸پارت 6 - Network Services

بررسی آدرس‌‎دهی درست DHCP Server و کارکرد DHCP Relay (Helper Address)⬇️
![Verification - Part 6.1](Verifications/Verification%20-%20Part%206.1.png)


بررسی عملکرد`DNS`⬇️
![Verification - Part 6.2](Verifications/Verification%20-%20Part%206.2.png)

بررسی عملکرد`NTP`⬇️
![Verification - Part 6.3](Verifications/Verification%20-%20Part%206.3.png)
>**نکته**:
>در دستورالعمل‌ها صریحا گفته شده که "`NTP`داخل Packet Tracer **کلی** زمان میبره"؛
>به همین خاطر، **نمیدونم** اینکه`R1`داره از زمان Local استفاده میکنه یا `DSW-B2`داره از`CSW2`زمان میگیره رو اشتباه بدونم یا Bug‼️


بررسی`SNMP`(مجاز بودن`GET`و غیرمجاز بودن`SET`)⬇️
![Verification - Part 6.4](Verifications/Verification%20-%20Part%206.4.png)


بررسی ثبت لاگ‌ها بر`Syslog`روی`SRV1`⬇️
![Verification - Part 6.5](Verifications/Verification%20-%20Part%206.5.png)
>**نکته**:
>اول کار هیچی Log ثبت **نمیشد** و وقتی پی‌ش رو گرفتم، فهمیدم که بخش دستورات مربوط به Logging رو جا انداختم؛ خلاصه که برای همه کانفیگ زدم و **درست** شد‼️


بررسی انتقال فایل IOS به Flash، و Boot شدن R1 با نسخه جدید⬇️
![Verification - Part 6.6](Verifications/Verification%20-%20Part%206.6.png)


بررسی عملکرد`SSH`و رد شدن درخواست از PC در Office B⬇️
![Verification - Part 6.7](Verifications/Verification%20-%20Part%206.7.png)
>**نکته**:
>اون اول`PC3`میتونست SSH بزنه، درنتیجه رفتم`sh acc 1`زدم و دیدم هست؛ یه چک کردم و دیدم به`line vty 0 15`**اعمال** نکردم این ACL رو، پس اعمال کردم و **درست** شد‼️


بررسی عملکرد`NAT/PAT`⬇️
![Verification - Part 6.8](Verifications/Verification%20-%20Part%206.8.png)


بررسی Failover⬇️
![Verification - Part 6.9](Verifications/Verification%20-%20Part%206.9.png)


بررسی وضعیت`CDP`و`LLDP`⬇️
![Verification - Part 6.10](Verifications/Verification%20-%20Part%206.10.png)

### 🔸پارت 7 - Security

بررسی Extended ACL که روی DSW-A1 و DSW-A2 گذاشتیم⬇️
![Verification - Part 7.1](Verifications/Verification%20-%20Part%207.1.png)


بررسی`Port Security`و`DHCP Snooping`و`DAI`⬇️
![Verification - Part 7.2](Verifications/Verification%20-%20Part%207.2.png)
>**نکته**:
>داخل Packet Tracer حمله ARP Spoofing عملا قابل راه‌اندازی **نیست**؛ پس خیلی نمیشه تست کرد`DAI`رو‼️

### 🔸پارت 8 - IPv6

بررسی IPv6 Addressها و Routeها⬇️
![Verification - Part 8](Verifications/Verification%20-%20Part%208.png)

### 🔸پارت 9 - Wireless

بررسی تنظیمات`WLC1`⬇️
![Verification - Part 9](Verifications/Verification%20-%20Part%209.png)
>**نکته**:
>طبق گفته دستورالعمل ها، "دستگاه‌های`LWAP`داخل Packet Tracer آدرس IP که از`WLC1`'گرفتن رو نشون **نمیدن**"؛ ولی درواقع مشکلی روی **عملکرد** کار نداره‼️




## 🔹مشکل

- **مشکل**م این بود که بعد از اتمام هر 9 پارت، درصدم شد`95%`و به`100%`نرسیدم‼️ 
    
- **راه‌حل**‌ش اینه که ببینم **چرا** از دستوراتم ایراد گرفته شده؛ و ببینم که آیا **تاثیر**ی روی عملکرد شبکه دارن یا نه✅ 




## 🔹نتیجه

>

