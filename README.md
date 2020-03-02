## Penetration_Testing_POC
搜集有关渗透测试中用到的POC、脚本、工具、文章等姿势分享，作为笔记吧，欢迎补充。

## 请善用搜索[`Ctrl+F`]查找

- - [Penetration_Testing_POC_With_Python](#PenetrationTestingPOCWithPython)
  - [IOT Device](#IOT-Device)
  - [Web APP](#Web-APP)
  - [提权辅助相关](#提权辅助相关)
  - [PC](#PC)
  - [tools](#tools-小工具集合)
  - [books](#书籍相关)
  - [说明](#%E8%AF%B4%E6%98%8E)

## IOT Device

- [天翼创维awifi路由器存在多处未授权访问漏洞](天翼创维awifi路由器存在多处未授权访问漏洞.md)
- [华为WS331a产品管理页面存在CSRF漏洞](华为WS331a产品管理页面存在CSRF漏洞.md)
- [CVE-2019-16313 蜂网互联企业级路由器v4.31密码泄露漏洞](./CVE-2019-16313%20蜂网互联企业级路由器v4.31密码泄露漏洞.md)
- [D-Link路由器RCE漏洞](./CVE-2019-16920-D-Link-rce.md)
- [CVE-2019-13051-Pi-Hole路由端去广告软件的命令注入&权限提升](./CVE-2019-13051)
- [D-Link DIR-859 - RCE UnAutenticated (CVE-2019–17621)](https://github.com/s1kr10s/D-Link-DIR-859-RCE)
- [Huawei HG255 Directory Traversal[目录穿越]](https://packetstormsecurity.com/files/155954/huaweihg255-traversal.rb.txt)|[本地备份文件](./tools/huaweihg255-traversal.rb)
- [D-Link Devices - Unauthenticated Remote Command Execution in ssdpcgi (Metasploit)CVE-2019-20215(Metasploit)](./POC_Details/D-Link%20Devices%20-%20Unauthenticated%20Remote%20Command%20Execution%20in%20ssdpcgi%20(Metasploit)%20CVE-2019-20215.rb)
- [从 Interfaces.d 到 RCE：Mozilla WebThings IoT 网关漏洞挖掘](https://research.nccgroup.com/2020/02/10/interfaces-d-to-rce/)
- [小米系列路由器远程命令执行漏洞（CVE-2019-18370，CVE-2019-18371）](https://github.com/UltramanGaia/Xiaomi_Mi_WiFi_R3G_Vulnerability_POC/blob/master/report/report.md)
- [Intelbras Wireless N 150Mbps WRN240 - Authentication Bypass (Config Upload-未经验证即可替换固件)](https://www.exploit-db.com/exploits/48158)

## Web APP

- [致远OA_A8_getshell_0day](致远OA_A8_getshell_0day.md)
- [Couch through 2.0存在路径泄露漏洞 ](Couch%20through%202.0存在路径泄露漏洞.md)
- [Cobub Razor 0.7.2存在跨站请求伪造漏洞](Cobub%20Razor%200.7.2存在跨站请求伪造漏洞.md)
- [joyplus-cms 1.6.0存在CSRF漏洞可增加管理员账户](joyplus-cms%201.6.0存在CSRF漏洞可增加管理员账户.md)
- [MiniCMS 1.10存在CSRF漏洞可增加管理员账户](MiniCMS%201.10存在CSRF漏洞可增加管理员账户.md)
- [Z-Blog 1.5.1.1740存在XSS漏洞](Z-Blog%201.5.1.1740存在XSS漏洞.md)
- [YzmCMS 3.6存在XSS漏洞](YzmCMS%203.6存在XSS漏洞.md)
- [Cobub Razor 0.7.2越权增加管理员账户](Cobub%20Razor%200.7.2越权增加管理员账户.md)
- [Cobub Razor 0.8.0存在SQL注入漏洞](Cobub%20Razor%200.8.0存在SQL注入漏洞.md)
- [Cobub Razor 0.8.0存在物理路径泄露漏洞](Cobub%20Razor%200.8.0存在物理路径泄露漏洞.md)
- [五指CMS 4.1.0存在CSRF漏洞可增加管理员账户](五指CMS%204.1.0存在CSRF漏洞可增加管理员账户.md)
- [DomainMod的XSS集合](DomainMod的XSS集合.md)
- [GreenCMS v2.3.0603存在CSRF漏洞可获取webshell&增加管理员账户](GreenCMS%20v2.3.0603存在CSRF漏洞可获取webshell&增加管理员账户.md)
- [yii2-statemachine v2.x.x存在XSS漏洞](yii2-statemachine%20v2.x.x存在XSS漏洞.md)
- [maccms_v10存在CSRF漏洞可增加任意账号](maccms_v10存在CSRF漏洞可增加任意账号.md)
- [LFCMS 3.7.0存在CSRF漏洞可添加任意用户账户或任意管理员账户](LFCMS%203.7.0存在CSRF漏洞可添加任意用户账户或任意管理员账户.md)
- [Finecms_v5.4存在CSRF漏洞可修改管理员账户密码](Finecms_v5.4存在CSRF漏洞可修改管理员账户密码.md)
- [Amazon Kindle Fire HD (3rd Generation)内核驱动拒绝服务漏洞](Amazon%20Kindle%20Fire%20HD%20\(3rd%20Generation\)内核驱动拒绝服务漏洞.md)
- [Metinfo-6.1.2版本存在XSS漏洞&SQL注入漏洞](Metinfo-6.1.2版本存在XSS漏洞&SQL注入漏洞.md)
- [Hucart cms v5.7.4 CSRF漏洞可任意增加管理员账号](Hucart%20cms%20v5.7.4%20CSRF漏洞可任意增加管理员账号.md)
- [indexhibit cms v2.1.5 直接编辑php文件getshell](indexhibit%20cms%20v2.1.5%20直接编辑php文件getshell.md)
- [S-CMS企业建站系统PHP版v3.0后台存在CSRF可添加管理员权限账号](S-CMS企业建站系统PHP版v3.0后台存在CSRF可添加管理员权限账号.md)
- [S-CMS PHP v3.0存在SQL注入漏洞](S-CMS%20PHP%20v3.0存在SQL注入漏洞.md)
- [MetInfoCMS 5.X版本GETSHELL漏洞合集](MetInfoCMS%205.X版本GETSHELL漏洞合集.md)
- [discuz ml RCE 漏洞检测工具](discuz-ml-rce/README.md)
- [thinkphp5框架缺陷导致远程代码执行](thinkphp5框架缺陷导致远程代码执行.md)
- [FineCMS_v5.0.8两处getshell](FineCMS_v5.0.8两处getshell.md)
- [Struts2_045漏洞批量检测|搜索引擎采集扫描](Struts2_045-Poc)
- [thinkphp5命令执行](thinkphp5命令执行.md)
- [typecho反序列化漏洞](typecho反序列化漏洞.md)
- [CVE-2019-10173 Xstream 1.4.10版本远程代码执行](CVE-2019-10173%20Xstream%201.4.10版本远程代码执行漏洞.md)
- [IIS/CVE-2017-7269-Echo-PoC](./IIS/CVE-2017-7269-Echo-PoC)
- [CVE-2019-15107 Webmin RCE](./CVE-2019-15107)
- [thinkphp5 rce漏洞检测工具](./tp5-getshell)
- [thinkphp5_RCE合集](./tp5-getshell/TP5_RCE合集.md)
- [thinkphp3.X-thinkphp5.x](./tp5-getshell/ThinkPHP.md)
- [关于ThinkPHP框架的历史漏洞分析集合](https://github.com/Mochazz/ThinkPHP-Vuln)
- [CVE-2019-11510](./CVE-2019-11510)
- [Redis(<=5.0.5) RCE](./redis-rogue-server)
- [WeblogicScanLot系列，Weblogic漏洞批量检测工具](./WeblogicScanLot)
- [jboss_CVE-2017-12149](./jboss_CVE-2017-12149)
- [Wordpress的拒绝服务（DoS）-CVE-2018-6389](./CVE-2018-6389)
- [Webmin Remote Code Execution (authenticated)-CVE-2019-15642](https://github.com/jas502n/CVE-2019-15642)
- [CVE-2019-16131 OKLite v1.2.25 任意文件上传漏洞](./CVE-2019-16131%20OKLite%20v1.2.25%20任意文件上传漏洞.md)
- [CVE-2019-16132 OKLite v1.2.25 存在任意文件删除漏洞](./CVE-2019-16132%20OKLite%20v1.2.25%20存在任意文件删除漏洞.md)
- [CVE-2019-16309 FlameCMS 3.3.5 后台登录处存在sql注入漏洞](./CVE-2019-16309%20FlameCMS%203.3.5%20后台登录处存在sql注入漏洞.md)
- [CVE-2019-16314 indexhibit cms v2.1.5 存在重装并导致getshell](./CVE-2019-16314%20indexhibit%20cms%20v2.1.5%20存在重装并导致getshell.md)
- [泛微OA管理系统RCE漏洞利用脚本](./泛微OA管理系统RCE漏洞利用脚本.md)
- [CVE-2019-16759 vBulletin 5.x 0day pre-auth RCE exploit](./CVE-2019-16759%20vBulletin%205.x%200day%20pre-auth%20RCE%20exploit.md)
- [zentao-getshell 禅道8.2 - 9.2.1前台Getshell](./zentao-getshell)
- [泛微 e-cology OA 前台SQL注入漏洞](./泛微%20e-cology%20OA%20前台SQL注入漏洞.md)
- [Joomla-3.4.6-RCE](./Joomla-3.4.6-RCE.md)
- [Easy File Sharing Web Server 7.2 - GET 缓冲区溢出 (SEH)](./Easy%20File%20Sharing%20Web%20Server%207.2%20-%20GET%20缓冲区溢出%20(SEH).md)
- [构建ASMX绕过限制WAF达到命令执行(适用于ASP.NET环境)](./构建ASMX绕过限制WAF达到命令执行.md)
- [CVE-2019-17662-ThinVNC 1.0b1 - Authentication Bypass](./CVE-2019-17662-ThinVNC%201.0b1%20-%20Authentication%20Bypass.md)
- [CVE-2019-16278andCVE-2019-16279-about-nostromo-nhttpd](./CVE-2019-16278andCVE-2019-16279-about-nostromo-nhttpd.md)
- [CVE-2019-11043-PHP远程代码执行漏](./CVE-2019-11043)
- [ThinkCMF漏洞全集和](./ThinkCMF漏洞全集和.md)
- [CVE-2019-7609-kibana低于6.6.0未授权远程代码命令执行](./CVE-2019-7609-kibana低于6.6.0未授权远程代码命令执行.md)
- [ecologyExp.jar-泛微ecology OA系统数据库配置文件读取](./tools/ecologyExp.jar)
- [freeFTP1.0.8-'PASS'远程缓冲区溢出](./freeFTP1.0.8-'PASS'远程缓冲区溢出.md)
- [rConfig v3.9.2 RCE漏洞](./rConfig%20v3.9.2%20RCE漏洞.md)
- [apache_solr_rce](./solr_rce.md)
- [CVE-2019-7580 thinkcmf-5.0.190111后台任意文件写入导致的代码执行](CVE-2019-7580%20thinkcmf-5.0.190111后台任意文件写入导致的代码执行.md)
- [Apache Flink任意Jar包上传导致远程代码执行](https://github.com/LandGrey/flink-unauth-rce)
- [用于检测JSON接口令牌安全性测试](https://github.com/ticarpi/jwt_tool)
- [cve-2019-17424 nipper-ng_0.11.10-Remote_Buffer_Overflow远程缓冲区溢出附PoC](cve-2019-17424%20nipper-ng_0.11.10-Remote_Buffer_Overflow远程缓冲区溢出附PoC.md)
- [CVE-2019-12409_Apache_Solr RCE](https://github.com/jas502n/CVE-2019-12409)
- [Shiro RCE (Padding Oracle Attack)](https://github.com/wuppp/shiro_rce_exp)
- [CVE-2019-19634-class.upload.php <= 2.0.4任意文件上传](https://github.com/jra89/CVE-2019-19634)
- [Apache Solr RCE via Velocity Template Injection](./Apache%20Solr%20RCE%20via%20Velocity%20Template%20Injection.md)
- [CVE-2019-10758-mongo-express before 0.54.0 is vulnerable to Remote Code Execution ](https://github.com/masahiro331/CVE-2019-10758/)
- [CVE-2019-2107-Android播放视频-RCE-POC(Android 7.0版本，7.1.1版本，7.1.2版本，8.0版本，8.1版本，9.0版本)](https://github.com/marcinguy/CVE-2019-2107)
- [CVE-2019-19844-Django重置密码漏洞(受影响版本:Django master branch,Django 3.0,Django 2.2,Django 1.11)](https://github.com/ryu22e/django_cve_2019_19844_poc/)
- [CVE-2019-17556-unsafe-deserialization-in-apache-olingo(Apache Olingo反序列化漏洞，影响: 4.0.0版本至4.6.0版本)](https://medium.com/bugbountywriteup/cve-2019-17556-unsafe-deserialization-in-apache-olingo-8ebb41b66817)
- [ZZCMS201910 SQL Injections](./ZZCMS201910%20SQL%20Injections.md)
- [WDJACMS1.5.2模板注入漏洞](./WDJACMS1.5.2模板注入漏洞.md)
- [CVE-2019-19781-Remote Code Execution Exploit for Citrix Application Delivery Controller and Citrix Gateway](https://github.com/projectzeroindia/CVE-2019-19781)
- [CVE-2019-19781.nse---use Nmap check  Citrix ADC Remote Code Execution](https://github.com/cyberstruggle/DeltaGroup/tree/master/CVE-2019-19781)
- [Mysql Client 任意文件读取攻击链拓展](https://paper.seebug.org/1112/)
- [CVE-2020-5504-phpMyAdmin注入(需要登录)](https://xz.aliyun.com/t/7092)
- [CVE-2020-5509-Car Rental Project 1.0版本中存在远程代码执行漏洞](https://github.com/FULLSHADE/CVE-2020-5509-POC)
- [CryptoAPI PoC CVE-2020-0601](https://github.com/kudelskisecurity/chainoffools/blob/master/README.md)|[另一个PoC for CVE-2020-0601](https://github.com/ollypwn/CVE-2020-0601)
- [New Weblogic RCE  (CVE-2020-2546、CVE-2020-2551) CVE-2020-2546](https://mp.weixin.qq.com/s/Q-ZtX-7vt0JnjNbBmyuG0w)|[WebLogic WLS核心组件RCE分析（CVE-2020-2551）](https://www.anquanke.com/post/id/199695)|[CVE-2020-2551-Weblogic IIOP 反序列化EXP](https://github.com/Y4er/CVE-2020-2551)
- [CVE-2020-5398 - RFD(Reflected File Download) Attack for Spring MVC](https://github.com/motikan2010/CVE-2020-5398/)
- [PHPOK v5.3&v5.4getshell](https://www.anquanke.com/post/id/194453) | [phpok V5.4.137前台getshell分析](https://forum.90sec.com/t/topic/728) | [PHPOK 4.7从注入到getshell](https://xz.aliyun.com/t/1569)
- [thinkphp6 session 任意文件创建漏洞复现 含POC](./books/thinkphp6%20session%20任意文件创建漏洞复现%20含POC.pdf) --- 原文在漏洞推送公众号上
- [WordPress InfiniteWP - Client Authentication Bypass (Metasploit)](https://www.exploit-db.com/exploits/48047)
- [【Linux提权/RCE】OpenSMTPD 6.4.0 < 6.6.1 - Local Privilege Escalation + Remote Code Execution](https://www.exploit-db.com/exploits/48051)
- [CVE-2020-7471-django1.11-1.11.282.2-2.2.103.0-3.0.3 StringAgg(delimiter)使用了不安全的数据会造成SQL注入漏洞环境和POC](https://github.com/Saferman/CVE-2020-7471)
- [CVE-2019-17564 : Apache Dubbo反序列化漏洞](https://www.anquanke.com/post/id/198747)
- [CVE-2019-2725(CNVD-C-2019-48814、WebLogic wls9-async)](https://github.com/lufeirider/CVE-2019-2725)
- [YzmCMS 5.4 后台getshell](https://xz.aliyun.com/t/7231)
- 关于Ghostcat(幽灵猫CVE-2020-1938漏洞)：[CNVD-2020-10487(CVE-2020-1938), tomcat ajp 文件读取漏洞poc](https://github.com/nibiwodong/CNVD-2020-10487-Tomcat-ajp-POC)|[Java版本POC](https://github.com/0nise/CVE-2020-1938)|[Tomcat-Ajp协议文件读取漏洞](https://github.com/YDHCUI/CNVD-2020-10487-Tomcat-Ajp-lfi/)|[又一个python版本CVE-2020-1938漏洞检测](https://github.com/xindongzhuaizhuai/CVE-2020-1938)|[CVE-2020-1938-漏洞复现环境及EXP](https://github.com/laolisafe/CVE-2020-1938)
- [CVE-2020-8840：Jackson-databind远程命令执行漏洞（或影响fastjson）](https://github.com/jas502n/CVE-2020-8840)
- [CVE-2020-8813-Cacti v1.2.8 RCE远程代码执行 EXP以及分析（需要认证/或开启访客即可不需要登录）(一款Linux是基于PHP,MySQL,SNMP及RRDTool开发的网络流量监测图形分析工具)](https://shells.systems/cacti-v1-2-8-authenticated-remote-code-execution-cve-2020-8813/)|[EXP](./CVE-2020-8813%20-%20Cacti%20v1.2.8%20RCE.md)
- [CVE-2020-7246-PHP项目管理系统qdPM< 9.1 RCE](https://www.exploit-db.com/exploits/48146)

## 提权辅助相关

- [windows-kernel-exploits Windows平台提权漏洞集合](https://github.com/SecWiki/windows-kernel-exploits)
- [windows 溢出提权小记](https://klionsec.github.io/2017/04/22/win-0day-privilege/)/[本地保存了一份+Linux&Windows提取脑图](./tools/Local%20Privilege%20Escalation.md)
- [Windows常见持久控制脑图](./tools/Windows常见持久控制.png)
- [CVE-2019-0803 Win32k漏洞提权工具](./CVE-2019-0803)
- [脏牛Linux提权漏洞](https://github.com/Brucetg/DirtyCow-EXP)
- [远控免杀系列](https://github.com/TideSec/BypassAntiVirus)
- [Linux提权-CVE-2019-13272  A linux kernel Local Root Privilege Escalation vulnerability with PTRACE_TRACEME](https://github.com/jiayy/android_vuln_poc-exp/tree/master/EXP-CVE-2019-13272-aarch64)
- [Linux权限提升辅助一键检测工具](https://github.com/mzet-/linux-exploit-suggester)
- [将powershell脚本直接注入到进程中执行来绕过对powershell.exe的限制](https://github.com/EmpireProject/PSInject)
- [CVE-2020-2696 – Local privilege escalation via CDE dtsession](https://github.com/0xdea/exploits/blob/master/solaris/raptor_dtsession_ipa.c)
- [CVE-2020-0683-利用Windows MSI “Installer service”提权](https://github.com/padovah4ck/CVE-2020-0683/)
- [Linux sudo提权辅助工具—查找sudo权限配置漏洞](https://github.com/TH3xACE/SUDO_KILLER)
- [Windows提权-CVE-2020-0668：Windows Service Tracing本地提权漏洞](https://github.com/RedCursorSecurityConsulting/CVE-2020-0668)
- [Linux提取-Linux kernel XFRM UAF poc (3.x - 5.x kernels)2020年1月前没打补丁可测试](https://github.com/duasynt/xfrm_poc)

## PC

- [ 微软RDP远程代码执行漏洞（CVE-2019-0708）](./BlueKeep)
- [CVE-2019-0708-python版](./BlueKeep/bluekeep-CVE-2019-0708-python)
- [MS17-010-微软永恒之蓝漏洞](https://github.com/Mr-xn/MS17-010)
- [macOS-Kernel-Exploit](./macOS-Kernel-Exploit)
- [CVE-2019-1388 UAC提权 (nt authority\system)](https://github.com/jas502n/CVE-2019-1388)
- [CVE-2019-1405和CVE-2019-1322：通过组合漏洞进行权限提升 Microsoft Windows 10 Build 1803 < 1903 - 'COMahawk' Local Privilege Escalation](https://github.com/apt69/COMahawk)
- [CVE-2019-11708](https://github.com/0vercl0k/CVE-2019-11708)
- [Telegram(macOS v4.9.155353) 代码执行漏洞](https://github.com/Metnew/telegram-links-nsworkspace-open)
- [Remote Desktop Gateway RCE bugs CVE-2020-0609 & CVE-2020-0610](https://www.kryptoslogic.com/blog/2020/01/rdp-to-rce-when-fragmentation-goes-wrong/)
- [Microsoft SharePoint - Deserialization Remote Code Execution](https://github.com/Voulnet/desharialize/blob/master/desharialize.py)
- [CVE-2020-0728-Windows Modules Installer Service 信息泄露漏洞](https://github.com/irsl/CVE-2020-0728/)
- [CVE-2020-0618: 微软 SQL Server Reporting Services远程代码执行（RCE）漏洞](https://www.mdsec.co.uk/2020/02/cve-2020-0618-rce-in-sql-server-reporting-services-ssrs/)|[GitHub验证POC(其实前文的分析文章也有)](https://github.com/euphrat1ca/CVE-2020-0618)
- [CVE-2020-0767Microsoft ChakraCore脚本引擎【Edge浏览器中的一个开源的ChakraJavaScript脚本引擎的核心部分】安全漏洞](https://github.com/phoenhex/files/blob/master/pocs/cve-2020-0767.js)
- [CVE-2020-0688：微软EXCHANGE服务的远程代码执行漏洞](https://github.com/random-robbie/cve-2020-0688)|[CVE-2020-0688_EXP---另一个漏洞检测利用脚本](https://github.com/Yt1g3r/CVE-2020-0688_EXP)|[又一个cve-2020-0688利用脚本](https://github.com/Ridter/cve-2020-0688)


## tools-[小工具集合](./tools)

- [java环境下任意文件下载情况自动化读取源码的小工具](https://github.com/Artemis1029/Java_xmlhack)
- [Linux登录日志清除/伪造](./tools/ssh)
- [python2的socks代理](./tools/s5.py)
- [dede_burp_admin_path-dedecms后台路径爆破(Windows环境)](./tools/dede_burp_admin_path.md)
- [PHP 7.1-7.3 disable_functions bypass](./tools/PHP%207.1-7.3%20disable_functions%20bypass.md)
- [一个各种方式突破Disable_functions达到命令执行的shell](https://github.com/l3m0n/Bypass_Disable_functions_Shell)
- [cmd下查询3389远程桌面端口](./tools/cmd下查询3389远程桌面端口.md)
- [伪装成企业微信名片的钓鱼代码](./tools/伪装成企业微信名片的钓鱼代码.txt)
- [vbulletin5-rce利用工具(批量检测/getshell)](https://github.com/theLSA/vbulletin5-rce)/[保存了一份源码:vbulletin5-rce.py](./tools/vbulletin5-rce.py)
- [CVE-2017-12615](./tools/CVE-2017-12615.py)
- [通过Shodan和favicon icon发现真实IP地址](https://github.com/pielco11/fav-up)
- [Cobalt_Strike扩展插件](./tools/Cobalt_Strike扩展插件.md)
- [Windows命令行cmd的空格替换](./tools/Windows命令行cmd的空格替换.md)
- [绕过disable_function汇总](./tools/绕过disable_function汇总.md)
- [WAF Bypass](https://chybeta.gitbooks.io/waf-bypass/content/)
- [命令注入总结](./tools/命令注入总结.md)
- [隐藏wifi-ssid获取 · theKingOfNight's Blog](./books/隐藏wifi-ssid获取%20·%20theKingOfNight's%20Blog.pdf)
- [crt.sh证书/域名收集](./tools/crt.sh证书收集.py)
- [TP漏洞集合利用工具py3版本-来自奇安信大佬Lucifer1993](https://github.com/Mr-xn/TPscan)
- [Python2编写的struts2漏洞全版本检测和利用工具-来自奇安信大佬Lucifer1993](https://github.com/Mr-xn/struts-scan)
- [sqlmap_bypass_D盾_tamper](./tools/sqlmap_bypass_D盾_tamper.py)
- [sqlmap_bypass_安全狗_tamper](./tools/sqlmap_bypass_安全狗_tamper.py)
- [sqlmap_bypass_空格替换成换行符-某企业建站程序过滤_tamper](./tools/sqlmap_bypass_空格替换成换行符-某企业建站程序过滤_tamper.py)
- [sqlmap_bypass_云锁_tamper](./tools/sqlmap_bypass_云锁_tamper.py)
- [masscan+nmap扫描脚本](./tools/masscan%2Bnmap.py)
- [PHP解密扩展](https://github.com/Albert-Zhan/php-decrypt)
- [linux信息收集/应急响应/常见后门检测脚本](https://github.com/al0ne/LinuxCheck)
- [RdpThief-从远程桌面客户端提取明文凭据辅助工具](https://github.com/0x09AL/RdpThief)
- [织梦(DEDECMS)全版本漏洞扫描](https://github.com/lengjibo/dedecmscan)
- [使用powershell或CMD直接运行命令反弹shell](https://github.com/ZHacker13/ReverseTCPShell)
- [FTP/SSH/SNMP/MSSQL/MYSQL/PostGreSQL/REDIS/ElasticSearch/MONGODB弱口令检测](https://github.com/netxfly/x-crack)
- [GitHack-.git泄露利用脚本](https://github.com/lijiejie/GitHack)
- [GitHacker---比GitHack更好用的git泄露利用脚本](https://github.com/WangYihang/GitHacker)
- [SVN源代码泄露全版本Dump源码](https://github.com/admintony/svnExploit)
- [多进程批量网站备份文件扫描](https://github.com/sry309/ihoneyBakFileScan)
- [Empire](https://github.com/BC-SECURITY/Empire/)|相关文章:[后渗透测试神器Empire详解](https://mp.weixin.qq.com/s/xCtkoIwVomx5f8hVSoGKpA)
- [FOFA Pro view 是一款FOFA Pro 资产展示浏览器插件，目前兼容 Chrome、Firefox、Opera](https://github.com/0nise/fofa_view)
- [Zoomeye Tools-一款利用Zoomeye 获取有关当前网页IP地址的各种信息(需要登录)](https://chrome.google.com/webstore/detail/zoomeye-tools/bdoaeiibkccgkbjbmmmoemghacnkbklj)
- [360 0Kee-Team 的 crawlergo动态爬虫 结合 长亭XRAY扫描器的被动扫描功能](https://github.com/timwhitez/crawlergo_x_XRAY)
- [内网神器Xerosploit-娱乐性质(端口扫描|DoS攻击|HTML代码注入|JavaScript代码注入|下载拦截和替换|嗅探攻击|DNS欺骗|图片替换|Web页面篡改|Drifnet)](https://github.com/LionSec/xerosploit)
- [一个包含php,java,python,C#等各种语言版本的XXE漏洞Demo](https://github.com/c0ny1/xxe-lab)
- [内网常见渗透工具包](https://github.com/yuxiaokui/Intranet-Penetration)
- [从内存中加载 SHELLCODE bypass AV查杀](https://github.com/brimstone/go-shellcode)|[twitter示例](https://twitter.com/jas502n/status/1213847002947051521)
- [流量转发工具-pingtunnel是把tcp/udp/sock5流量伪装成icmp流量进行转发的工具](https://github.com/esrrhs/pingtunnel)
- [内网渗透-创建Windows用户(当net net1 等常见命令被过滤时,一个文件执行直接添加一个管理员【需要shell具有管理员权限l】](https://github.com/newsoft/adduser)|[adduser使用方法](./adduser添加用户.md) 
- [pypykatz-通过python3实现完整的Mimikatz功能(python3.6+)](https://github.com/skelsec/pypykatz)
- [【windows】Bypassing AV via in-memory PE execution-通过在内存中加载多次XOR后的payload来bypass杀软](https://blog.dylan.codes/bypassing-av-via/)|[作者自建gitlab地址](https://git.dylan.codes/batman/darkarmour)
- [wafw00f-帮助你快速识别web应用是否使用何种WAF(扫描之前很有用)](https://github.com/EnableSecurity/wafw00f)
- [Linux提取其他用户密码的工具(需要root权限)](https://github.com/huntergregal/mimipenguin)
- [apache2_BackdoorMod-apache后门模块](https://github.com/VladRico/apache2_BackdoorMod)
- [对密码已保存在 Windwos 系统上的部分程序进行解析,包括：Navicat,TeamViewer,FileZilla,WinSCP,Xmangager系列产品（Xshell,Xftp)](https://github.com/uknowsec/SharpDecryptPwd)
- [一个简单探测jboss漏洞的工具](https://github.com/GGyao/jbossScan)
- [一款lcx在golang下的实现-适合内网代理流量到公网,比如阿里云的机器代理到你的公网机器](https://github.com/cw1997/NATBypass)
- [Cobalt Strike Aggressor 插件包](https://github.com/timwhitez/Cobalt-Strike-Aggressor-Scripts)
- [IP/IP段资产扫描-->扫描开放端口识别运行服务部署网站-->自动化整理扫描结果-->输出可视化报表+整理结果](https://github.com/LangziFun/LangNetworkTopology3)
- [A script to scan for unsecured Laravel .env files](https://github.com/tismayil/laravelN00b)
- [Struts2漏洞扫描Golang版-【特点:单文件、全平台支持、可在webshell下使用】](https://github.com/x51/STS2G)
- [Shiro<=1.2.4反序列化，一键检测工具](https://github.com/sv3nbeast/ShiroScan)
- [完整weblogic 漏洞扫描工具修复版](https://github.com/0xn0ne/weblogicScanner)
- [GitHub敏感信息泄露监控](https://github.com/FeeiCN/GSIL)
- [Java安全相关的漏洞和技术demo](https://github.com/threedr3am/learnjavabug)
- [在线扫描-网站基础信息获取|旁站|端口扫描|信息泄露](https://scan.top15.cn/web/)
- [bayonet是一款src资产管理系统，从子域名、端口服务、漏洞、爬虫等一体化的资产管理系统](https://github.com/CTF-MissFeng/bayonet)
- [内网渗透中常用的c#程序整合成cs脚本，直接内存加载](https://github.com/uknowsec/SharpToolsAggressor)
- [又一个各种漏洞poc、Exp的收集或编写](https://github.com/coffeehb/Some-PoC-oR-ExP)
- [内网渗透代理转发利器reGeorg](https://github.com/sensepost/reGeorg)|**相关文章:**[配置reGeorg+Proxifier渗透内网](https://www.k0rz3n.com/2018/07/06/如何使用reGeorg+Proxifier渗透内网)|[reGeorg+Proxifier实现内网sock5代理](http://jean.ink/2018/04/26/reGeorg/)|[内网渗透之reGeorg+Proxifier](https://sky666sec.github.io/2017/12/16/内网渗透之reGeorg-Proxifier)|[reGeorg+Proxifier使用](https://xz.aliyun.com/t/228)
- [get_Team_Pass-获取目标机器上的teamviewerID和密码(你需要具有有效的目标机器账号密码且目标机器445端口可以被访问(开放445端口))](https://github.com/kr1shn4murt1/get_Team_Pass/)
- [chromepass-获取chrome保存的账号密码/cookies-nirsoft出品在win10+chrome 80测试OK](./tools/chromepass/)|[SharpChrome-基于.NET 2.0的开源获取chrome保存过的账号密码/cookies/history](https://github.com/djhohnstein/SharpChrome)|[ChromePasswords-开源获取chrome密码/cookies工具](https://github.com/malcomvetter/ChromePasswords)

## 书籍相关

- [windwos权限维持系列12篇PDF](./books/Window权限维持)
- [Linux 权限维持之进程注入(需要关闭ptrace)](./books/Linux%E6%9D%83%E9%99%90%E7%BB%B4%E6%8C%81%E4%B9%8B%E8%BF%9B%E7%A8%8B%E6%B3%A8%E5%85%A5%20%C2%AB%20%E5%80%BE%E6%97%8B%E7%9A%84%E5%8D%9A%E5%AE%A2.pdf) | [在不使用ptrace的情况下，将共享库（即任意代码）注入实时Linux进程中。(不需要关闭ptrace)](https://github.com/DavidBuchanan314/dlinject)
- [44139-mysql-udf-exploitation](./books/44139-mysql-udf-exploitation.pdf)
- [emlog CMS的代码审计_越权到后台getshell](./books/emlog%20CMS的代码审计_越权到后台getshell%20-%20先知社区.pdf)
- [PHPOK 5.3 最新版前台注入](./books/PHPOK%205.3%20最新版前台注入%20-%20先知社区.pdf)
- [PHPOK 5.3 最新版前台无限制注入（二）](./books/PHPOK%205.3%20最新版前台无限制注入（二）%20-%20先知社区.pdf)
- [Thinkphp5 RCE总结](./books/Thinkphp5%20RCE总结%20_%20ChaBug安全.pdf)
- [rConfig v3.9.2 RCE漏洞分析](./books/rConfig%20v3.9.2%20RCE漏洞分析.pdf)
- [weiphp5.0 cms审计之exp表达式注入](./books/weiphp5.0%20cms审计之exp表达式注入%20-%20先知社区.pdf)
- [zzzphp1.7.4&1.7.5到处都是sql注入](./books/zzzphp1.7.4%261.7.5到处都是sql注入.pdf)
- [FCKeditor文件上传漏洞及利用-File-Upload-Vulnerability-in-FCKEditor](./books/FCKeditor文件上传漏洞及利用-File-Upload-Vulnerability-in-FCKEditor.pdf)
- [zzcms 2019 版本代码审计](./books/zzcms%202019%E7%89%88%E6%9C%AC%E4%BB%A3%E7%A0%81%E5%AE%A1%E8%AE%A1%20-%20%E5%85%88%E7%9F%A5%E7%A4%BE%E5%8C%BA.pdf)
- [利用SQLmap 结合 OOB 技术实现音速盲注](./books/手把手带你利用SQLmap结合OOB技术实现音速盲注.pdf)
- [特权提升技术总结之Windows文件服务内核篇(主要是在webshell命令行执行各种命令搜集信息)](https://xz.aliyun.com/t/7261)|[(项目留存PDF版本)](./books/特权提升技术总结之Windows文件服务内核篇%20-%20先知社区.pdf)

## 说明

> 此项目所有文章、代码部分来源于互联网，版权归原作者所有，此项目仅供学习参考使用，严禁用于任何非法行为！使用即代表你同意自负责任！
