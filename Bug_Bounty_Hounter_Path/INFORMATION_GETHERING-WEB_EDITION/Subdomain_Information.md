# Sertifikalar
SSL/TLS sertifikalarını kullanmak, subdomain adreslerini çıkarmak için kullanılan bir başka yöntemdir.

Araçlar:
+ https://censys.io
+ https://crt.sh

# Bazı **Pasif** Subdomain Numaralandırma Araçları:
### [Theharvester](https://github.com/laramies/theHarvester) 
Araç, aşağıdakileri içeren birden fazla genel kaynağı kullanarak adları, e-postaları, IP'leri, alt etki alanlarını ve URL'leri toplar:

+ [Baidu](https://www.baidu.com/) - Baidu arama motoru.
+ Bufferoverun - Rapid7'nin Project Sonar verilerini kullanıyor - https://www.rapid7.com/research/project-sonar/
+ [Crtsh](https://crt.sh/) - Comodo Sertifika arama.
+ [Hackertarget](https://hackertarget.com/) - Kuruluşlara yardımcı olmak için çevrimiçi güvenlik açığı tarayıcıları ve ağ istihbaratı.
+ Otx AlienVault - Açık Tehdit Değişimi - https://otx.alienvault.com
+ [Rapiddns](https://rapiddns.io/) - Aynı IP'yi kullanan alt alan adlarını veya siteleri sorgulamayı kolaylaştıran DNS sorgulama aracı.
+ [Sublist3r](https://github.com/aboul3la/Sublist3r) - Sızma testçileri için hızlı alt alan adları numaralandırma aracı
+ [Threatcrowd](http://ci-www.threatcrowd.org/) - Açık kaynaklı tehdit istihbaratı.
+ [Threatminer](https://www.threatminer.org/) - Tehdit istihbaratı için veri madenciliği.
+ Trello - Arama Trello panoları (Google aramayı kullanır)
+ [Urlscan](https://urlscan.io/) - URL ve web sitesi tarayıcısı olan web için bir sanal alan.
+ Vhost Bing sanal ana bilgisayar araması.
+ [Virustotal](https://www.virustotal.com/gui/home/search) - Etki alanı araması.
+ [Zoomeye](https://www.zoomeye.org/) - Shodan'ın Çince versiyonu.

# Bazı **Aktif** Altyapı Tanımlama Araçları:
### [WhatWeb](https://morningstarsecurity.com/research/whatweb)
> WhatWeb web sitelerini tanımlar. Amacı, "Bu Web Sitesi nedir?" sorusuna cevap vermektir. WhatWeb, içerik yönetim sistemleri (CMS), blog platformları, istatistik/analitik paketleri, JavaScript kütüphaneleri, web sunucuları ve gömülü cihazlar dahil olmak üzere web teknolojilerini tanır. WhatWeb, her biri farklı bir şeyi tanımak için 1700'den fazla eklentiye sahiptir. WhatWeb ayrıca sürüm numaralarını, e-posta adreslerini, hesap kimliklerini, web çerçeve modüllerini, SQL hatalarını ve daha fazlasını tanımlar.

![photo1](https://morningstarsecurity.com/wp-content/uploads/2009/12/whatweb-verbose.png)<br>
![photo2](https://morningstarsecurity.com/wp-content/uploads/2009/12/whatweb-verbose2.png)

### [WafW00f](https://github.com/EnableSecurity/wafw00f)
![photo3](https://camo.githubusercontent.com/a0dc92ab1f09ea71a40f228789adf69bde8c707a0313036214c9c714d9b72b4d/68747470733a2f2f692e696d6775722e636f6d2f7541677034396f2e706e67)
> Normal bir HTTP isteği gönderir ve yanıtı analiz eder; bu, bir dizi WAF çözümünü tanımlar.
Bu başarılı olmazsa, bir dizi (potansiyel olarak kötü amaçlı) HTTP isteği gönderir ve hangi WAF olduğunu anlamak için basit bir mantık kullanır.
Bu da başarılı olmazsa, daha önce döndürülen yanıtları analiz eder ve bir WAF veya güvenlik çözümünün saldırılarımıza aktif olarak yanıt verip vermediğini tahmin etmek için başka bir basit algoritma kullanır.

### [Aquatone](https://github.com/michenriksen/aquatone)
>Aquatone is a tool for automatic and visual inspection of websites across many hosts and is convenient for quickly gaining an overview of HTTP-based attack surfaces by scanning a list of configurable ports, visiting the website with a headless Chrome browser, and taking a screenshot. This is helpful, especially when dealing with huge subdomain lists. Aquatone is not installed by default in Parrot Linux, so we will need to install via the following commands.



