<div align="center">
  
![maxresdefault](https://raw.githubusercontent.com/igareck/GoldCaviar/refs/heads/main/Files/vpn-configs-for-russia-4.svg)

</div>

# <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNTljeGk4d3lzZnU3Mm1peDBienFpbmEyb3JmaDB5N21tMW9oczIwdyZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/8p1WPEOeDWFCksfe18/giphy.gif" width="45">  کانفیگ‌های VPN رایگان که در روسیه کار می‌کنند

[![Stars](https://img.shields.io/github/stars/igareck/vpn-configs-for-russia?style=flat)](https://github.com/igareck/vpn-configs-for-russia/stargazers)
<img src="https://komarev.com/ghpvc/?username=igareck&label=Visitors&color=0e75b6&style=flat" alt="Visitor Count" /> 
[![Issues](https://img.shields.io/github/issues/igareck/vpn-configs-for-russia?style=flat&color=0e75b6)](https://github.com/igareck/vpn-configs-for-russia/issues)
[![last commit][1]][1]
![Open Source Love](https://badges.frapsoft.com/os/v2/open-source.png?v=103)
[![Email](https://img.shields.io/badge/Email-igareck%40proton.me-0e75b6?logo=gmail&logoColor=white)](mailto:igareck@proton.me)

[1]: https://custom-icon-badges.demolab.com/github/last-commit/igareck/vpn-configs-for-russia?logo=history&logoColor=white&color=0e75b6&style=flat

**🌐 Язык: [Русский](README.md) | 🌐 Language: [English](README-EN-US.md) | 🌐 语言: [中文](README-ZH-CN.md) | 🌐 زبان: [فارسی](README-FA-IR.md)**

<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExa2RkeXZzdDl1Y3g4dW1xcjFxc2xsMHVsZ2RiY243OHJodjd0cHQ1NSZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/qXp82ZL3eZbbTUrLyy/giphy.gif" width="20"> مجموعه‌ای از کانفیگ‌های عمومی و رایگانِ VPN که به‌صورت خودکار به‌روزرسانی و تست می‌شوند و برای کارکرد در خاک فدراسیون روسیه آزمایش شده‌اند (`VLESS` / `VMess` / `Shadowsocks` / `Hysteria2` / `Tuic` / `Trojan` و سایر).

برای دور زدن مسدودسازی‌های Roskomnadzor (RKN).

این مجموعه بر اساس دسته‌بندی به لیست‌های CIDR و SNI «سیاه» و «سفید» فیلتر شده است.

هر کانفیگ یک اشتراک TXT است که می‌توانید آن را در هر کلاینتی که نیاز دارید ایمپورت کنید (`v2rayN`، `Streisand`، `NekoBox`، `Throne` و دیگران).

هر ۱–۲ ساعت، قبل از انتشار، کانفیگ‌ها روی یک سرور داخل روسیه به‌صورت خودکار تست سلامت می‌شوند و موارد کند یا غیرفعال حذف می‌شوند.

اینجا تست‌های واقعیِ دسترسی‌پذیری، تأخیر و سرعت انجام می‌شود — نه صرفاً جمع‌آوری خودکار و حذف تکراری‌ها. از 13 نوامبر تا 28 دسامبر همه‌چیز را دستی انجام می‌دادم؛ 28 دسامبر اسکریپتی را کامل کردم که روند بررسی را خودکار و سریع‌تر کرد، با حفظ همان کیفیت «دستی».

VPNهای کلاسیک (OpenVPN، WireGuard و غیره) مدت‌هاست درست کار نمی‌کنند — و فرقی ندارد اشتراک شما پولی باشد یا نه.

به همین دلیل مهم است از کانفیگ‌هایی استفاده کنید که مشخصاً برای کارکرد در روسیه تأیید شده‌اند تا همیشه آنلاین بمانید.

همچنین به‌روزرسانی مداوم کانفیگ‌های عمومی مهم است، چون معمولاً سریع ظاهر می‌شوند — و به همان سرعت هم از کار می‌افتند. برای همین، به‌روزرسانی خودکار همراه با تست/بررسی خودکار را اضافه کردم تا هر کاربر داخل روسیه در هر زمان، تازه‌ترین لیستِ کانفیگ‌های باکیفیت و بدون «آشغال اضافی» را داشته باشد.

## 🔴 توجه برای کاربران خارج از روسیه!

❗❗❗ اگر خارج از روسیه هستید (چین، ایران یا هر کشور دیگری)، فقط از کانفیگ‌های «لیست سیاه» ("BLACK_SS+All_RUS.txt", "BLACK_VLESS_RUS.txt" و "BLACK_VLESS_RUS_mobile.txt") استفاده کنید.

«لیست سفید» (WHITE) به شما کمکی نمی‌کند، چون «لیست سفید» فقط برای دور زدن محدودیت‌های خاص و شدید داخل روسیه تنظیم شده است! برای سایر کشورها، «لیست سفید» عملاً ناکارآمد، کند و بی‌فایده خواهد بود!

«لیست سیاه» (BLACK LIST) یک «گزینه VPN بین‌المللی» است و سریع‌ترین کانفیگ‌های عمومیِ موجود در اینترنت را شامل می‌شود!

ممنون از توجه شما!

## <img src="https://raw.githubusercontent.com/igareck/GoldCaviar/refs/heads/main/Files/Download-VPN-configs-banner-FA-IR.svg" width="480">

  *در کلاینت VPN خود «به‌روزرسانی خودکار» را فعال کنید!*

<details>

<summary><h3>🧾 لیست سیاه ⚫</h3></summary>

---

### **VLESS برای موبایل (حداکثر 100 کانفیگ در اشتراک):** 

### [BLACK_VLESS_RUS_mobile.txt](https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/main/BLACK_VLESS_RUS_mobile.txt)

  *اشتراک VLESS فشرده و سبک برای موبایل (لیست سیاه). شامل 100 کانفیگِ سریع‌تر از اشتراک کامل VLESS است.*

<details>
<summary> QR code </summary>

  ![BLACK_VLESS_RUS_mobile_QR.png](https://github.com/igareck/vpn-configs-for-russia/blob/main/QR-codes/BLACK_VLESS_RUS_mobile_QR.png)

</details>

### **VLESS کامل (همه کانفیگ‌ها):** 

### [BLACK_VLESS_RUS.txt](https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/main/BLACK_VLESS_RUS.txt)

  *اشتراک کامل VLESS برای لیست سیاه.*

<details>
<summary> QR code </summary>

  ![BLACK_VLESS_RUS-QR](https://github.com/igareck/vpn-configs-for-russia/blob/main/QR-codes/BLACK_VLESS_RUS-QR.png)

</details>

### **SHADOWSOCKS+ALL:** 

### [BLACK_SS+All_RUS.txt](https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/main/BLACK_SS+All_RUS.txt)

  *اشتراک ShadowSocks، Hysteria2، Vmess، Trojan برای لیست سیاه.*

<details>
<summary> QR code </summary>

  ![BLACK_SS+All_RUS-QR](https://github.com/igareck/vpn-configs-for-russia/blob/main/QR-codes/BLACK_SS+All_RUS-QR.png)

</details>


</details>

*[روی فلش کلیک کنید]*

---

<details>

<summary><h3>🧾 لیست سفید ⚪</h3></summary>

---

### اشتراک CIDR برای موبایل (حداکثر 100 کانفیگ در اشتراک) ⚪: 

### [Vless-Reality-White-Lists-Rus-Mobile.txt](https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/main/Vless-Reality-White-Lists-Rus-Mobile.txt)

<details>
<summary> QR code </summary>

  ![WHITE_VLESS_MOBILE_RUS-QR](https://github.com/igareck/vpn-configs-for-russia/blob/main/QR-codes/Vless-Reality-White-Lists-Rus-Mobile-QR.png)

</details>

*اشتراک CIDR فشرده و سبک برای موبایل (لیست سفید). شامل 100 کانفیگِ سریع‌تر از اشتراک کامل CIDR است. دور زدن مسدودسازی‌های CIDR بر اساس IP. پروتکل VLESS.*


### اشتراک CIDR کامل (همه کانفیگ‌ها) ⚪: 

### [WHITE-CIDR-RU-all.txt](https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/main/WHITE-CIDR-RU-all.txt)

<details>
<summary> QR code </summary>

  ![WHITE-CIDR-RU-all-QR](https://github.com/igareck/vpn-configs-for-russia/blob/main/QR-codes/WHITE-CIDR-RU-all-QR.png)

</details>

*اشتراک CIDR کامل برای لیست سفید. شامل همه زیرشبکه‌های «سفید» شناخته‌شده از میزبان‌ها/هاسترهای مختلف. دور زدن مسدودسازی‌های CIDR بر اساس IP. پروتکل VLESS.*


### اشتراک CIDR فقط برای هاسترها: VK, YANDEX, CDNVIDEO, Beeline ⚪:

### [WHITE-CIDR-RU-checked.txt](https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/main/WHITE-CIDR-RU-checked.txt)

<details>
<summary> QR code </summary>

  ![WHITE-CIDR-RU-checked-QR](https://github.com/igareck/vpn-configs-for-russia/blob/main/QR-codes/WHITE-CIDR-RU-checked-QR.png)

</details>

*نسخه فیلترشده‌ی اشتراک CIDR کامل بر اساس هاسترهای مشخص (کوچک‌تر از نسخه کامل). در این اشتراک فقط زیرشبکه‌های «سفید» و امتحان‌پس‌داده از هاسترهای روسی وجود دارد: VK، YANDEX، CDNVIDEO و Beeline. دور زدن مسدودسازی‌های CIDR بر اساس IP. پروتکل VLESS.*


### اشتراک SNI ⚪: 

### [WHITE-SNI-RU-all.txt](https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/main/WHITE-SNI-RU-all.txt)

<details>
<summary> QR code </summary>

  ![WHITE-SNI-RU-all-QR](https://github.com/igareck/vpn-configs-for-russia/blob/main/QR-codes/WHITE-SNI-RU-all-QR.png)

</details>

*فقط مسدودسازی‌های مبتنی بر SNI را با استفاده از نام دامنه‌ی SNI جعلی دور می‌زند. مسدودسازی‌های CIDR را دور نمی‌زند. پروتکل VLESS.*

</details>

*[روی فلش کلیک کنید]*

---

## <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3bjF5NnEyM21vMjJhd2UxdWphYnQxZGh6bjc1bjBzMG44eDB0Ym03eCZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/dyX9ixfxMpOUGawfdK/giphy.gif" width="50"> تفاوت لیست سیاه و لیست سفید چیست و کدام اشتراک را انتخاب کنیم

**لیست‌های سیاه** یعنی **«هر چیزی که ممنوع نشده، مجاز است»**. *در 90% مواقع اینترنت همین‌طور کار می‌کند.*

**لیست‌های سفید** یعنی **«همه‌چیز ممنوع است مگر اینکه صراحتاً مجاز باشد»**. یعنی جز Yandex، VK و سایت‌های مورد تأیید RKN تقریباً هیچ‌چیز باز نمی‌شود — حتی Google.com و Gmail هم باز نمی‌شود.

*اینترنت در حالت لیست سفید بیشترین محدودیت را دارد. شما فقط به چیزهایی دسترسی دارید که رگولاتور با «لیست‌های سفید» خودش تأیید کرده باشد. مثلاً اگر فقط Yandex و Ozon تأیید شوند، فقط همان‌ها باز می‌شوند و هیچ چیز دیگر. این محدودیت‌ها الان به‌طور گسترده توسط اپراتورهای موبایل تست و در عمل اجرا می‌شود.*

`⬇   ترتیب اقدامات   ⬇`

`اول بررسی می‌کنیم آیا اینترنت اساساً کار می‌کند یا نه: Yandex.ru، Gosuslugi، VK، Rutube.ru، Sberbank، Mail.ru، Ozon را باز کنید. اگر هیچ‌کدام باز نشود، یعنی اینترنت شما اصولاً کار نمی‌کند (هیچ اتصالی وجود ندارد) و هیچ کانفیگی کمکی نمی‌کند! در این حالت اتصال شبکه روی دستگاهتان را بررسی کنید!"`

`اگر ناگهان «هیچ‌جوری لود نمی‌کند»، معمولاً ریست‌کردن اتصال شبکه کمک می‌کند: حالت «Airplane mode» را 10–15 ثانیه روشن کنید، بعد خاموش کنید، دوباره امتحان کنید — غالباً درست می‌شود!`

### **1)** **اول انتخاب کنید سیاه یا سفید:**  <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3Y3Q4NW94NXo0ZXQwajl1cDRzdHg3ZXFzbWc4aGtzeDA0cGRtNTl2ZSZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/35LH6GkOzEXuw/giphy.gif" width="80">  

a) در حالت معمول، وقتی اینترنت عادی کار می‌کند (Google باز می‌شود)، اما می‌خواهید YouTube مسدودشده را ببینید یا Roblox مسدودشده را بازی کنید — از کانفیگ‌های «لیست سیاه» استفاده کنید.

**کانفیگ‌های «لیست سیاه» در اصل یک VPN معمولی هستند، فقط با پروتکل مدرن!** لیست سیاه معمولاً سریع‌ترین هم هست، چون در شرایط عادی کار می‌کند.

b) **اگر هیچ‌چیزی کار نمی‌کند** به‌جز Yandex.ru، Gosuslugi، VK، Rutube، Sberbank، Mail.ru یا Ozon — یعنی اینترنت به‌شدت محدود شده است؛ در این حالت **از کانفیگ‌های «لیست سفید» استفاده کنید.**

### **2)** **در حالت لیست سیاه معمولی ⚫:** **VLESS** یا **SHADOWSOCKS+ALL**

در لیست سیاه معمولی ⚫ بهتر است سراغ پایدارترین پروتکل یعنی **VLESS** بروید؛ یا به‌عنوان گزینه‌ی جایگزین **SHADOWSOCKS+ALL** را انتخاب کنید (اجباری نیست). فرقی ندارد PC باشد یا موبایل — همه‌جا کار می‌کند.

*نکته: برای من Hysteria2 روی PC با کابل عالی است، اما روی گوشی با Wi‑Fi معمولاً از کار می‌زند (و حتی در تست تأخیر هم بار اول پاسخ نمی‌دهد و باید چند بار تکرار کنید). دلیلش را نفهمیده‌ام. VLESS و Shadowsocks معمولاً روی همه دستگاه‌ها بدون مشکل کار می‌کنند.*

*گاهی حتی VLESS روی PC با کابل کاملاً خوب است، ولی روی Wi‑Fi تست تأخیر ناپایدار می‌شود.*

### **3)** **در حالت لیست سفید ⚪: اشتراک CIDR یا اشتراک SNI**

  **a)** **«CIDR SUBSCRIPTION FULL» یا «CIDR SUBSCRIPTION ONLY WITH HOSTERS: VK, YANDEX, CDNVIDEO»:** 
  
  شدیدترین مسدودسازی CIDR «white IP» در حال حاضر بیشتر روی اپراتورهای موبایل دیده می‌شود (Megafon، Beeline، MTS، T2، Yota و غیره). برای همین، `کانفیگ‌های CIDR که لیست‌های white IP را در اینترنت موبایل دور می‌زنند داخل اشتراک TXT با نام “CIDR SUBSCRIPTION” قرار داده شده‌اند` و در توضیحات هر کانفیگ با `[*CIDR]` علامت‌گذاری شده‌اند.
  
  این کانفیگ‌ها طبیعتاً در شرایط عادی هم کار می‌کنند (همراه با لیست سیاه)، اما بهتر است این کار را نکنید! چرا؟ برای اینکه فشار روی منابع بالا نرود و کسانی که واقعاً نیاز دارند (و شاید ماه‌ها با اینترنت محدود زندگی می‌کنند) بتوانند از آن استفاده کنند. فقط وقتی واقعاً لازم شد از CIDR استفاده کنید.

اگر یک کانفیگ ناگهان کار نکرد، ممکن است بعد از مدتی دوباره زنده شود (دلیل: سرورها تحت فشارند (چون رایگان و عمومی‌اند) یا موقتاً خاموش شده‌اند). فوراً حذفش نکنید!
  
  **b)** **اشتراک SNI:**
  
  کانفیگ‌هایی که مسدودسازی‌های ساده‌تر را با «white SNI lists» (صرفاً با نام دامنه) دور می‌زنند در اشتراک TXT با نام **SNI SUBSCRIPTION** قرار دارند. در توضیحات هر کانفیگ با `[SNI-RU]` مشخص شده‌اند و همه مقادیر SNI هم برای راحتی برچسب‌گذاری شده‌اند.

## <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3Yml0MndhcDZ6dzFuYjY3aG0yNWowN2Rqbnp1aTV2cXNvb3FvMnluMiZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/MxryCOQuSYVVD0SPyp/giphy.gif" width="40"> چطور این کانفیگ‌ها را روی دستگاه خود استفاده کنم؟

1) راحت‌ترین روش اضافه‌کردن کانفیگ‌های VPN روی دستگاه، استفاده از *«subscription»* یا *«subscription group»* در v2rayN، Throne، v2rayNG، NekoBox، Streisand یا Karing است.

2) URL فایل txt در GitHub را کپی کنید. بعد از کپی لینک، داخل اپ باید «Add from clipboard» را بزنید، یا از دکمه‌ی معمولی «Add» -> «Configure manually» -> نوع «Subscription» را انتخاب کنید -> لینک فایل txt را Paste کنید و یک نام برای اشتراک بگذارید.

3) QR اشتراک را از بخش بعدی اسکن کنید. QR حتی راحت‌تر است: «Add» -> «Scan QR code» را بزنید و اپ به‌صورت خودکار یک اشتراک می‌سازد؛ فقط کافی است روی گوشی نامش را عوض کنید و اگر لیست فوراً لود نشد «Update» را بزنید.
   
   QRها زیر لینک اشتراک هستند — روی فلشِ «QR code» کلیک کنید.
   
4) چطور بفهمیم الان کدام کانفیگ/سرور واقعاً کار می‌کند؟

   روی کل اشتراک (نام اشتراک در بالا) یا روی یک کانفیگ کلیک کنید؛ معمولاً باید لمس طولانی کنید تا منو باز شود. گزینه‌ی — *توجه!* — *«Test real latency»* یا *«Latency»* را انتخاب کنید! «TCP Ping» یا «ICMP Ping» را انتخاب نکنید، چون دسترسی واقعی سرور VPN را نشان نمی‌دهند. هر موردی که عدد سبز برگرداند قابل استفاده است. عدد کوچک‌تر یعنی تأخیر کمتر و پاسخ‌گویی سریع‌تر.

5) شدیداً توصیه می‌شود حداقل روزی 2 بار (هر 12 ساعت) «به‌روزرسانی خودکار» را فعال کنید؛ در تعطیلات طولانی می‌تواند بیشتر هم باشد. کانفیگ‌ها هر ساعت آپدیت می‌شوند چون با گذر زمان از کار می‌افتند. با فعال‌بودن آپدیت، همیشه تازه‌ترین نسخه‌ی اشتراک را با کانفیگ‌های سالم و بدون «زباله» دارید.

7) کانفیگ‌ها (خصوصاً از لیست سفید) ممکن است در تست «real latency» فوراً سبز نشوند؛ خیلی وقت‌ها باید 2–3–4 بار تست را تکرار کنید تا سرورهای تازه‌فعال سبز شوند.

8) چند کلاینت مختلف روی گوشی نصب کنید — گاهی کلاینت‌های مختلف سرورهای متفاوتی را «قابل استفاده» تشخیص می‌دهند. این به تفاوت تنظیمات کلاینت‌ها در زمان تست کانفیگ‌ها برمی‌گردد.

می‌توانید محتوای هر فایل txt را هم یکی‌یکی دستی وارد v2rayN و غیره کنید، اما مزیت اشتراک این است که بعد از آپدیت در GitHub، روی دستگاه شما هم خودکار آپدیت می‌شود — بدون نیاز به حذف و کپی دوباره — و روند را ساده‌تر می‌کند.

## 🧩 اپ‌ها برای استفاده از کانفیگ‌ها روی PC و موبایل:

###  <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3amtqMmQxOGh0aG0waGk5OGhhNG5odmdob2k1bWc4ejNyZ3E3N2Y2bCZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/xUS4Fp5i6iIn2Y1EYT/giphy.gif" width="25"> Windows/Linux/MacOS

کلاینت رسمی v2rayN یا Throne (جانشین Nekoray) را نصب کنید، با دسترسی «Administrator» اجرا کنید، کانفیگ/اشتراک را اضافه کنید و Update بزنید، لیست که آمد «real latency» را اجرا کنید، بعد بر اساس Ping مرتب کنید، یک مورد سبز با کمترین عدد را انتخاب کنید (Enter)، و در نهایت «VPN mode / TUN mode» را فعال کنید.

**1)** **v2rayN:**
  
   *v2rayN را توصیه می‌کنم چون پایدار است و ثابت کرده می‌تواند هزاران کانفیگ با پروتکل‌های مختلف را هم‌زمان مدیریت کند (حداکثر شخصی من 150,000 بوده). عمومی‌ترین کلاینت است و می‌تواند Xray، Sing-Box و Mihomo را در یک محیط استفاده کند.*

   https://github.com/2dust/v2rayN/releases
  
   `v2rayN-windows-64.zip` برای Windows
  
   `v2rayN-linux-64.deb` برای Linux (Ubuntu)
  
   `v2rayN-macos-64.dmg` برای MacOS

**2)** **Throne (جانشین Nekoray که از 2024 دیگر به‌روزرسانی نمی‌شود):**

*به‌عنوان جایگزینِ قابل استفاده بعد از v2rayN پیشنهاد می‌شود.*

   https://github.com/throneproj/Throne/releases

   `Throne-1.0.8-windows64-installer.exe` برای Windows
  
   `Throne-1.0.8-debian-x64.deb` برای Linux (Ubuntu)
  
   `Throne-1.0.8-macos-arm64.zip` برای MacOS

**3)** **Karing:**

   https://github.com/KaringX/karing/releases

   `karing_1.2.10.1300_windows_x64.exe` برای Windows
  
   `karing_1.2.10.1300_linux_amd64.deb` برای Linux (Ubuntu)
  
   `karing_1.2.10.1300_macos_universal.dmg` برای MacOS
   

### <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3aGcxcG8yMGNzOTNmZDE1Z3hob3V3ajU4dmhkdnhsY2doMXFrNXowMyZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/oFSDc1Oq12Ie5NJnmA/giphy.gif" width="20"> iOS — از Streisand، Shadowrocket، Karing، V2Box یا v2RayTun از App Store استفاده کنید.

  Streisand را توصیه می‌کنم: در App Store اعلام کرده داده جمع‌آوری نمی‌کند و همه قابلیت‌ها (از جمله تغییر DNS) برخلاف بسیاری از کلاینت‌های مشابه درست کار می‌کند؛ لود و کار با کانفیگ‌ها پایدار است.

  کاربران Happ را به دلیل ناپایداری عملکرد/تأخیر توصیه نمی‌کنند.

   **1)** `Streisand` https://apps.apple.com/us/app/streisand/id6450534064 
   
   *بهترین کلاینت رایگان iOS بدون جمع‌آوری داده*

   **2)** `Shadowrocket` https://apps.apple.com/us/app/shadowrocket/id932747118 
   
   *حتی بعد از زمان طولانی Idle اتصال را قطع نمی‌کند، داده جمع‌آوری نمی‌کند، اما پولی است*

   **3)** `Karing` https://apps.apple.com/us/app/karing/id6472431552
     
   *نظرها درباره Karing متفاوت است: بعضی دوستش دارند، بعضی مشکل اتصال دارند*

   **4)** `V2Box` https://apps.apple.com/us/app/v2box-v2ray-client/id6446814690

   **5)** `v2RayTun` https://apps.apple.com/us/app/v2raytun/id6476628951
  
### <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExODUzYWRwNzNpa3doMDd1bXo4NTlzanJsaTcya3dlNXA4d3c5cnVzNCZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/UQJlZ2OcaCA2RLfGiZ/giphy.gif" width="20"> Android — از v2rayNG و NekoBox از GitHub، یا v2Box و v2RayTun از Google Play استفاده کنید.

 v2rayNG را توصیه می‌کنم، چون معادل اندرویدیِ کلاینت محبوب PC من یعنی v2rayN است (از همان توسعه‌دهنده «2dust»).

 NekoBox را هم امتحان کنید — کاربران از آن تعریف می‌کنند.

 کاربران Happ را به دلیل ناپایداری عملکرد/تأخیر توصیه نمی‌کنند.

  **1)** `NekoBox` https://github.com/MatsuriDayo/NekoBoxForAndroid/releases

  **2)** `v2rayNG`  https://github.com/2dust/v2rayNG/releases

  **3)** `v2Box` https://play.google.com/store/apps/details?id=dev.hexasoftware.v2box

  **4)** `v2RayTun` https://play.google.com/store/apps/details?id=com.v2raytun.android&hl=en&pli=1


## <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3ZDhxeG02NHlucTdqZGhtejBnb2V5dGpwaDBmcHhobWlsOHQxdWpoYSZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/8L0hXHQkY4o7eyQHJB/giphy.gif" width="30"> اطلاعات مفید

⚡ چرا اصلاً کانفیگ‌ها را تست می‌کنم؟ در ابتدای کار، از میان 40,000+ کانفیگ عمومی و رایگان، فقط حدود 700 تا تست سلامت را پاس کردند — یعنی کمتر از 2%. در نهایت حدود 200 کانفیگ باکیفیت با پاسخ‌گویی خوب و سرعت قابل قبول منتشر شد — حدود نیم درصد. همه وقت ندارند با بیلدهای ده‌ها هزار کانفیگی سروکله بزنند که فقط چندصدتایش واقعاً کار می‌کند.

⚡ پروتکل‌ها زیادند، اما **موثرترین** گزینه (در برابر DPI و مسدودسازی‌های Roskomnadzor) **Vless+Reality** است، چون می‌تواند ترافیک را مثل درخواست به یک سایت HTTPS بی‌خطر جا بزند و استفاده از VPN را برای ISP تقریباً نامرئی کند. سایر پروتکل‌ها پایین‌تر قرار می‌گیرند چون راحت‌تر شناسایی می‌شوند.

⚡ پایدارترین ترنسپورت‌ها: XHTTP، GRPC و WS.

⚡ برخی کانفیگ‌ها ممکن است به‌مرور به دلایلی خارج از کنترل من از کار بیفتند، بنابراین لیست‌ها به‌صورت دوره‌ای به‌روزرسانی می‌شوند.

⚡ اگر یک کانفیگ ناگهان از کار افتاد — عجله نکنید حذفش کنید. مورد بعدی را امتحان کنید؛ شاید بعداً دوباره زنده شود. اما تضمینی نیست — این برای سرورهای رایگان و عمومی طبیعی است.

⚡ اگر سرویس‌دهنده‌ی شما اتصال‌های VPN را مسدود می‌کند، DNS معمولی روتر/PC/موبایل را با DNS رمزگذاری‌شده DNS-over-HTTPS (DoH) یا DNS-over-TLS (DoT) جایگزین کنید. حتی اگر کمک نکند، استفاده از DoH برای حریم خصوصی شما خوب است.

⚡ هنگام استفاده از لیست سفید، ممکن است بعضی DNS-DoHهای خارجی (مثلاً Google) گاهی در دسترس نباشند. من اول Cloudflare، OpenDNS، Google، Quad9، AdGuard، Dnsforge را تست می‌کنم؛ و اگر هیچ‌کدام کار نکرد، Yandex DoH را انتخاب می‌کنم. اگر هیچ DoHی کار نکرد، غیرفعالش کنید و از DNS خودکار ISP استفاده کنید.

<details>

<summary> 🧾 DNS-over-HTTPS (DoH) چیست و چطور فعالش کنیم؟ </summary>


> *روی روتر: DNS پیش‌فرض ISP را حذف/غیرفعال کنید و DNS-over-HTTPS (DoH) را فعال کنید. ممکن است لازم باشد ابتدا کلاینت DoH را از بخش Firmware/Update روتر دانلود/فعال کنید. می‌توانید از DNS-over-TLS (DoT) هم استفاده کنید، اما در روسیه به‌خاطر مسدودسازی‌های زیاد توصیه نمی‌شود. DNS-over-HTTPS (DoH) باید 100% پایدار کار کند.*

> *روی گوشی چند گزینه دارید:*
> 
> - اپ «Cloudflare 1.1.1.1 + WARP: Safer Internet» برای Android (Google Play Store) / اپ «1.1.1.1: Faster Internet App» برای iOS (App Store) را نصب کنید؛
> 
> - در iOS تنظیمات شبکه‌ی داخلی برای DoH وجود ندارد؛ کانفیگ‌های DoH به‌صورت فایل جداگانه از سایت‌های رسمی Quad9، AdGuard، Dnsforge و غیره دانلود می‌شود (بخش پایین «فهرست سرورهای عمومی DoH» را ببینید)؛
> 
> - برای Android: Settings ➡️ Network & internet (یا Wi‑Fi & internet) ➡️ “Advanced” ➡️ “Private DNS” ➡️ گزینه “Private DNS provider hostname” را انتخاب کنید و یکی از آدرس‌های لیست DoH عمومیِ پایین را وارد کنید (بخش پایین «فهرست سرورهای عمومی DoH» را ببینید)؛*

> *روی PC: سرور DoH را در تنظیمات DNS آداپتور شبکه تنظیم کنید.*

> *داخل اپ VPN: سرور DoH را در تنظیمات DNS برنامه وارد کنید یا از گزینه‌های از پیش‌تعریف‌شده انتخاب کنید. در Streisand روی iOS یک DNS درست و پایدار پیدا شده است.*

DNS-over-HTTPS (DoH) همان DNS است، اما رمزگذاری‌شده و خصوصی‌تر؛ یعنی DNS از طریق HTTPS: درخواست‌های DNS را از ناظران محلی (ISP) مخفی می‌کند و حریم خصوصی را بالاتر می‌برد، اما Resolverِ DNS (Cloudflare/Google و …) همچنان درخواست‌ها را می‌بیند (چون شما درخواست‌ها را از طریق او عبور می‌دهید). ISP فقط اتصال شما به IPِ Resolverِ DoH/DoT (و حجم/زمان ترافیک) + IP نهایی سرور مقصد را می‌بیند؛ یعنی IPِ سایتِ بازدیدشده بدون نام دامنهٔ مقصد (و اگر ECH نباشد — دامنه از طریق SNI هم لو می‌رود). با IP نهایی (و در نبود ECH — با SNI) اغلب می‌توان سایت را شناسایی کرد.

ممکن است (اما نه 100%) DoH به دور زدن بعضی محدودیت‌های اتصال کمک کند. DoH می‌تواند DNS‑block ساده را دور بزند، اما مسدودسازی بر اساس IP/SNI یا فیلترینگ عمیق را دور نمی‌زند.

این استاندارد توسط IETF به‌عنوان RFC 8484 (2018) منتشر شده و ICANN هم در پیاده‌سازی آن نقش داشته؛ و Google اولین بار آن را در سال 2016 پیاده‌سازی/تست کرد. هدف: افزایش محرمانگی و امنیت کاربران.

</details>

> *برای مشاهده توضیحات روی فلش کلیک کنید*

<details>

<summary> 🧾 فهرست سرورهای عمومی DoH (+ دانلود فایل‌های پیکربندی DoH DNS): </summary>

`https://common.dot.dns.yandex.net/dns-query` - *Yandex DNS Basic. توجه! فقط وقتی پیشنهاد می‌شود که سایر DNSها در حالت White List کار نمی‌کنند؛ در حالت عادی از DNSهای پایین استفاده کنید؛*

`https://safe.dot.dns.yandex.net/dns-query` - *Yandex DNS Safe Mode. توجه! فقط وقتی پیشنهاد می‌شود که سایر DNSها در حالت White List کار نمی‌کنند؛ در حالت عادی از DNSهای پایین استفاده کنید؛*

`https://dns.adguard-dns.com/dns-query` - *AdGuard DNS. DNSِ یکی از معروف‌ترین و بهترین مسدودکننده‌های رایگان تبلیغات و ردیاب‌ها (HQ: Cyprus)؛*

`https://adguard-dns.io/ru/public-dns.html` - *دانلود فایل کانفیگ AdGuard DNS برای iOS (+ راهنما برای پلتفرم‌های دیگر؛ به زبان روسی)؛*

`https://dns.quad9.net/dns-query` - *Quad9 DNS Basic. Malware Blocking, DNSSEC Validation. سیاست بدون لاگ، HQ: Switzerland؛*

`https://dns11.quad9.net/dns-query` - *Quad9 DNS Extended. Secured w/ECS: Malware blocking, DNSSEC Validation, ECS enabled. سیاست بدون لاگ، HQ: Switzerland؛*

`https://docs.quad9.net/Setup_Guides/iOS/iOS_14_and_later_(Encrypted)/` - *دانلود فایل کانفیگ Quad9 DNS برای iOS (+ راهنما برای پلتفرم‌های دیگر؛ فقط انگلیسی)؛*
 
`https://dnsforge.de/dns-query` - *DNS عالی از DNSFORGE (dnsforge.de) — بلاکر رایگان تبلیغات و ردیاب‌ها. سیاست بدون لاگ، سرورها در Germany؛ اطلاعات/راهنماها به زبان German؛*

`https://dnsforge.de/dnsforge-doh.mobileconfig`  - *دانلود فایل کانفیگ DNSFORGE.DE برای iOS؛*

`https://dns.cloudflare.com/dns-query` - *Cloudflare DNS Basic؛*

`https://security.cloudflare-dns.com/dns-query` - *Cloudflare DNS برای مسدودسازی بدافزار؛*

`https://dns.google/dns-query` - *Google Public DNS (برای بعضی‌ها هنگام White List ممکن است در دسترس نباشد)؛*

`https://doh.opendns.com/dns-query` - *Cisco Umbrella (OpenDNS).*

</details>

> *برای دیدن لیست روی فلش کلیک کنید*


## 👁️‍🗨️ ISP شما چه چیزی می‌بیند و چه کسی چه چیزهایی را هنگام آنلاین‌بودن می‌تواند ببیند؟

<details>

<summary> برای یادگیری روی فلش کلیک کنید </summary>

**به‌طور کلی.**

**وقتی آنلاین هستید، 5 طرف می‌توانند رفتار شما را ارزیابی کنند:**

**1.** `شما`

**2.** `ISP شما`

**3.** `سایت/موتور جستجویی که باز می‌کنید`

**4.** `مرورگر شما (اگر متعلق به Yandex، Google یا هر شرکت عمومی باشد)`

**5.** `DNS resolver`

**بعضی‌ها فکر می‌کنند «پرووایدر همه‌چیز را می‌بیند».**

**اما این یک سوءبرداشت است. اگر درست رفتار کنید، ISP خیلی کم می‌بیند.**

بیایید کارکرد استاندارد اینترنت روی سایت‌های HTTPS بدون VPN را توضیح دهیم. این را با HTTP ساده اشتباه نگیرید که رمزگذاری ندارد. تقریباً 2026 است و دیگر به‌سختی سایت HTTP پیدا می‌شود.

**بیایید همه‌چیز را جزءبه‌جزء باز کنیم.**

### 1. ISP.

در حالت عادی، ISP سه چیز را می‌بیند: IP نهاییِ سایتی که به آن وصل می‌شوید + نام دامنه + بسته‌های HTTPS رمزگذاری‌شده‌ای که به مرورگر کاربر می‌آیند. اینکه داخل خود سایت چه اتفاقی می‌افتد فقط برای 2 طرف معلوم است — کاربر و سایت. به لطف رمزگذاری HTTPS. چیزی که در Google جستجو می‌کنید فقط برای شما و Google معلوم است.

**مثال: YouTube**

YouTube را باز می‌کنید، یک آموزش مفید می‌بینید، یک ویدیو را باز می‌کنید و تماشا می‌کنید. ISP چه می‌بیند؟ IP مربوط به YouTube + نام دامنه «YouTube» + بسته‌های HTTPS رمزگذاری‌شده به سمت PC کاربر. همین. ISP نمی‌تواند ببیند چه ویدیوهایی می‌بینید یا چه چیزهایی جستجو می‌کنید — این داخل سایت رخ می‌دهد و با HTTPS محافظت می‌شود. به سمت چپ نام سایت نگاه کنید «https:» — همین رمزگذاری است که به میلیون‌ها نفر امنیت دیجیتال می‌دهد و در برابر نظارت محافظت می‌کند.

**مثال: Google Search**

به Google.com می‌روید برای دیدن میم گربه، عبارت *"кот мем неси черешню"* را جستجو می‌کنید و تصاویر گربه با پیش‌بند را می‌بینید. ISP چه می‌بیند؟ چیز ترسناکی؟ نه. هیچ چیز معناداری نمی‌بیند. IP Google + نام دامنه «Google» + بسته‌های HTTPS رمزگذاری‌شده به سمت PC شما. دقیقاً چه چیزی می‌بینید — عکس‌ها و کوئری‌ها — ISP نمی‌تواند ببیند. بسته HTTPS حاوی عکس‌هاست، اما رمزگذاری شده، بنابراین ISP فقط می‌فهمد «شما دارید یک کاری داخل Google انجام می‌دهید»، که اطلاعات بی‌فایده‌ای است؛ رمزگشایی‌اش عملاً غیرممکن است.

**اگر به جای DNS معمولی از DNS-over-HTTPS (DoH) رمزگذاری‌شده استفاده کنید (مثلاً 1.1.1.1) چه می‌شود؟**

حالا ISP حتی نام دامنه‌ای که درخواست کرده‌اید را هم مستقیم نمی‌بیند. با DoH، ISP درخواست‌های DNS را به صورت متن ساده نمی‌بیند؛ فقط می‌بیند شما به IP مربوط به Resolverِ DoH/DoT وصل شده‌اید (و حجم/زمان ترافیک) + IP نهایی سایت. نام دامنه نهایی را نمی‌فهمد، اما اغلب می‌تواند با IP، SNI و الگوی ترافیک حدس بزند هدف کدام سایت است؛ برای سایت‌های معروف آسان‌تر و برای سایت‌های کمترشناخته سخت‌تر است — اما کاملاً حذف نمی‌شود. اگر DoH می‌توانست IP نهایی را هم پنهان کند، جای VPN را می‌گرفت — اما بدون VPN نمی‌توانید IP مقصد نهایی را پنهان کنید. و ISPها دقیقاً با IP مقصد، سایت‌ها (مثلاً YouTube) را مسدود می‌کنند. پس در نهایت برای دسترسی به سایت‌های مسدود همچنان VPN لازم است.

**DNS به‌اختصار:**

DNS معمولی مثل 1.1.1.1 (متن ساده) نشان می‌دهد: IP سایت + نام دامنه/SNI + بسته‌های HTTPS رمزگذاری‌شده.

DoH نشان می‌دهد: IP مقصد سایت (+تحلیل) + بسته‌های HTTPS رمزگذاری‌شده.

### 2. سایت/موتور جستجو.

**سایت می‌بیند شما در سمت خودش چه کار می‌کنید و تابع قوانین کشوری است که دفتر مرکزی‌اش آنجاست.**

همه سایت‌های مدرن و داده‌هایی که با شما رد و بدل می‌کنند با HTTPS محافظت می‌شوند (نه HTTP ساده). بنابراین کارهای شما در یک سایت فقط برای شما و خود سایت قابل مشاهده است، نه برای ISP. ISP فقط ترافیک HTTPS رمزگذاری‌شده را می‌بیند.

**برای موتورهای جستجو دو مورد را پیشنهاد می‌کنم. می‌توانید بدون نگرانی از سانسور با آن‌ها جستجو کنید:**

> *1. Google search (محبوب‌ترین + بزرگ‌ترین ایندکس جهان). HQ: Mountain View, California, USA.*

> *2. Duckduckgo search (محبوب + نتیجه‌های خوب، امکان انتخاب منطقه + ادعای حریم خصوصی برای کوئری‌ها). HQ: Paoli, Pennsylvania, USA.*

متأسفانه Yandex Search را توصیه نمی‌کنم. HQ در Moscow است. با توجه به شرایط فعلی، تمام کوئری‌های شما می‌تواند لاگ و تحلیل شود. برای اطلاعات خاصِ روسیه با احتیاط از آن استفاده کنید. برای بقیه موارد، Google و Duckduckgo کافی هستند.

### 3. مرورگر.

خیلی‌ها نمی‌دانند، اما مرورگر هم می‌تواند رفتار شما را ببیند.

**کدام مرورگرها در روسیه رایج و محبوب‌اند؟**

> a) Yandex Browser. شدیداً توصیه نمی‌شود! اگر نصب است — حذفش کنید و هر چیز دیگری جایگزین کنید. ترافیک را لاگ می‌کند.

> b) Google Chrome. خصوصی نیست؛ ترافیک را لاگ می‌کند. اما در روسیه از Yandex امن‌تر است + اکوسیستم خودش از Google.

> c) Mozilla Firefox. از نظر سیاست حریم خصوصی، بین مرورگرهای محبوب و عمومی بهترین است.

این مرورگرهای عمومی سازنده دارند و سازندگانشان شرکت‌های عمومی‌اند که داده‌های کاربر جمع می‌کنند و می‌توانند تاریخچه درخواست‌های شما — یعنی ترافیک‌تان — را ببینند (هر چه هم بگویند) و تابع قوانین/حوزه قضاییِ دفتر مرکزی خودشان‌اند. اگر نمی‌خواهید مرورگر «man-in-the-middle» باشد، یک مرورگر متن‌بازِ حریم‌خصوصی‌محور انتخاب کنید که توسط توسعه‌دهندگان مستقل ساخته شده و کدش عمومی است و می‌شود حسابرسی‌اش کرد (مثلاً در GitHub).

**مرورگرهایی که برای استفاده روزمره و وب‌گردی پیشنهاد می‌کنم:**

از پایین به بالا: از محبوب‌ترین تا خصوصی‌ترین.

**a)** `Mozilla Firefox` — اگر یک گزینه محبوب و بی‌دردسر می‌خواهید. همچنین uBlock origin (ublockorigin.com) را نصب کنید تا ترَکرها و تبلیغات را مسدود کند. موتور Firefox متعلق به شرکت عمومی Mozilla است. از نظر سیاست حریم خصوصی بین مرورگرهای عمومی بهترین است.

https://www.firefox.com/en-US/?utm_campaign=SET_DEFAULT_BROWSER

https://github.com/mozilla-firefox/firefox

**b)** `Ungoogled Chromium` — مرورگر متن‌باز مبتنی بر Chromium با حذف تله‌متری Google، توسط توسعه‌دهندگان مستقل. به‌طور گسترده حسابرسی شده. برای کارهای روزمره خوب است، اما باید آپدیت‌ها را دستی از GitHub بگیرید. uBlock origin (ublockorigin.com) را هم نصب کنید. برای تعادل بین راحتی و حریم خصوصی، Ungoogled Chromium یک انتخاب عالی است: دقیقاً مثل Google Chrome رفتار می‌کند، اما بدون اکوسیستم Google.

https://github.com/ungoogled-software/ungoogled-chromium-windows برای Windows.

https://github.com/ungoogled-software/ungoogled-chromium-debian برای Linux (Ubuntu).

**c)** `Librewolf (customized Firefox)` — مرورگر متن‌باز مبتنی بر Firefox با حذف تله‌متری Mozilla Firefox، توسط توسعه‌دهندگان مستقل. «Firefox خصوصیِ آماده استفاده»: دانلود کنید و اجرا. به‌طور گسترده حسابرسی شده. راحت. از Auto-update پشتیبانی می‌کند (در نصب تیکش را بزنید). uBlock origin به‌صورت داخلی دارد. Librewolf عالی است، اما گاهی به‌خاطر تنظیمات نیمه‌تهاجمی ممکن است بعضی سایت‌های استریمینگ خراب شوند یا باز نشوند (کم پیش می‌آید، ولی می‌شود).

https://librewolf.net/

https://codeberg.org/librewolf

**d)** `Cromite` — مرورگر متن‌باز مبتنی بر Chromium با حذف تله‌متری، توسط توسعه‌دهندگان مستقل. به‌طور گسترده حسابرسی شده. مناسب وب‌گردی روزمره، اما توجه کنید: مسدودسازی بسیار تهاجمیِ ترَکرها و تله‌متری. AdBlock داخلی. بعضی سایت‌ها ممکن است خراب شوند. برای من این موضوع در Cromite بیشتر از مرورگرهای بالا رخ داد. ورود به Google دردسرساز بود. اما Cromite بهترین نتیجه را در تست «browser fingerprint» به من داد: حتی سخت‌افزار PC من هم شناسایی نشد — همه‌چیز از ابتدا «تمیز» بود.

https://github.com/uazo/cromite

این مرورگرها توجه ISP را جلب نمی‌کنند چون ISP فقط موتورِ استفاده‌شده را می‌بیند: Chromium (Google Chrome، Ungoogled Chromium، Cromite) یا Firefox (Mozilla Firefox، Librewolf). فقط خود شما می‌دانید دقیقاً از کدام مرورگر استفاده می‌کنید.

### 4. DNS resolver.

با DNS معمولی (1.1.1.1)، قبل از بازکردن سایت با DNS resolver تماس می‌گیریم و او می‌بیند کجا می‌خواهیم برویم. اپراتور هر DNS resolver می‌تواند همه درخواست‌ها و پاسخ‌های DNS را ببیند (چه دامنه‌هایی را resolve می‌کنید). از این لاگ‌ها می‌شود فهمید قصد اتصال به چه چیزی را دارید.

اگر به جای DNS معمولیِ 1.1.1.1 (متن ساده) از DNS-over-HTTPS (DoH) رمزگذاری‌شده استفاده کنید چه می‌شود؟

حالا ISP نام دامنه/سایتی که وصل شده‌اید را نمی‌بیند. ISP فقط می‌بیند شما به IP Resolverِ DoH/DoT وصل شده‌اید (به‌علاوه حجم/زمان ترافیک).

اما خود DNS resolver همچنان نام دامنه + IP را می‌بیند، چون درخواست‌های DNS را از طریق آن می‌فرستید؛ حتی اگر رمزگذاری باشد، در نهایت آن را دریافت و رمزگشایی می‌کند.

### نتیجه‌گیری.

**برای اینکه آنلاین راحت و مطمئن باشید، این‌ها کمک می‌کنند:**

`DNS-OVER-HTTPS (DoH)`

➕

`موتور جستجوی درست: Google یا Duckduckgo` (نه Yandex)
 
➕

`مرورگرهای امن/مستقل: حداقل Mozilla Firefox؛ حداکثر Librewolf، Ungoogled Chromium، Cromite` (هرگز Yandex Browser)

---


**این بخش به‌مرور گسترش و دقیق‌تر خواهد شد.**

</details>

##  

## <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExZXJoeTEzZ3FtcGNrdmo2ZnFocDUwOTVvYmdjNWRnaWMwNHozMWN1YiZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/ZcdZ7ldgeIhfesqA6E/giphy.gif" width="25"> اشتراک‌ها را به اشتراک بگذارید!

## از اینترنت آزادانه و مسئولانه استفاده کنید!

## 🔖 License

GPL-3.0 License. می‌توانید آن را در فایل [`LICENSE`](LICENSE) بخوانید.

## <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExM2wwMmJ3bDZvMWV2b2JraXZ4ZWk2Y2I5ODYyZ2M2aG5mMHc5ZW81ZyZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/ME8P6ce7Mn3gnRbird/giphy.gif" width="30"> حمایت از نویسنده

**این پروژه غیرتجاری است و بر پایه علاقه شخصی نویسنده جلو می‌رود.**

**اگر دوست دارید حمایت کنید — می‌توانید از طریق انتقال رمزارز این کار را انجام دهید.**

**این کمک‌ها صرف ادامه و توسعه این کار خواهد شد.**

**از همه کسانی که اهمیت می‌دهند از پیش ممنونم!**

<details>
<summary><h3> 💳 آدرس‌های کیف پول 💳 <h3></summary>

هر رمزارزی که دوست دارید را انتخاب کنید و آدرسش را کپی کنید. فقط به کیف پولِ مربوط به همان کوین ارسال کنید؛ در غیر این صورت دارایی از دست می‌رود.

| № | Coin | Address |
|--|--|--|
| 1 | `Bitcoin (BTC)` | `18vVz4UzFdxCGnCnAzJtXv6ECsh32ff9VT` |
| 2 | `Ethereum-based_coins(ETH): Ethereum (ETH), USDC (ETH), USDT (Ethereum ERC-20), Shiba Inu (SHIB)` | `0xfc668016a823f3EE53d2F3009547666A2BdaBd32` |
| 3 | `Tron-based_coins_(TRX): Tron (TRX), USDC (TRX), USDT (TRX)` | `TLnzF6NYgyqBHJMM2qByMXEHLBWNhBWcJ1` |
| 4 | `Toncoin-based_coins_(TON): Toncoin (TON), Notcoin (NOT), Hamster Combat (HMSTR), USDT (USDT-TON)` | `EQAGbSuckE93yiACSENJGo8WuRq474Wba1J4yCF1Q59xsL0k` |
| 5 | `Litecoin (LTC)` | `LcHbh84V5PgWk1gTzjGWeef6NQT4MwE9RK` |
| 6 | `Ripple (XRP)` | `rNaKXrfLGsAVvA8JMr9dApMgCNzFmPbvTR` |
| 7 | `Monero (XMR)` | `47uvnonFqbyHMRrZadCAAvL2q9ed476PKdGtbLxXeUj1fs7gtPZ6mx3BeRBd2JM6Wmc16tN7K3ZcDMfds3cE8NaMCgAbD5Q` |
| 8 | `ZCash (ZEC)` | `t1cjEDjtLxatccB6o1pUPxb3pMByCz1L5Ct` |
| 9 | `Dogecoin (DOGE)` | `DRNBruzYDv5vWEz1ndGDjywqugVhd2Zmbm` |
| 10 | `Solana (SOL)` | `Hxm9MjxfD1LNKaWuiFFLzBDTR5CnJSty7gRnkTfubiWj` |
| 11 | `Stellar (XLM)` | `GDRN4K4VDDGNFIWJ3BAN7KL7576764RN44TBHTXYJIXMLK7RNP4UTSJ6` |
| 12 | `Cardano (ADA)` | `addr1qxpw4m02auvmrfee3suz98tvj82cm4mpfllvyda8fz004j40dpemdcuzntj5ykxwv2x6azyp982stfxegm9zvl9kf74s309qhu` |
| 13 | `NEAR Coin (NEAR)` | `d9cba0ec6233589267f43b91d8c156efb7fcd0a0177d7e8a34f7b791a61e7e35` |


</details>

> *برای باز کردن لیست روی فلش کلیک کنید*

##  <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3ZmJ4anB6YjR3aWJpaTRvYzUzejY1dmwzN2c2M3c2NnV0MXUwM3RrcyZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/acN91ftm1tJX23OOBx/giphy.gif" width="60"> ایمیل برای ارتباط: igareck@proton.me

## 👀 شمارنده بازدید
<img src="https://komarev.com/ghpvc/?username=igareck&label=Visitors&color=0e75b6&style=flat" alt="Visitor Count" /> <img src="https://visitor-badge.laobi.icu/badge?page_id=igareck.visitor-badge&left_color=black&right_color=green&left_text=Cyber+Hits" alt="Cyber Hits"/>  
</div>

## <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExa2RkeXZzdDl1Y3g4dW1xcjFxc2xsMHVsZ2RiY243OHJodjd0cHQ1NSZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/qXp82ZL3eZbbTUrLyy/giphy.gif" width="30"> <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExa2RkeXZzdDl1Y3g4dW1xcjFxc2xsMHVsZ2RiY243OHJodjd0cHQ1NSZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/qXp82ZL3eZbbTUrLyy/giphy.gif" width="30"> <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExa2RkeXZzdDl1Y3g4dW1xcjFxc2xsMHVsZ2RiY243OHJodjd0cHQ1NSZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/qXp82ZL3eZbbTUrLyy/giphy.gif" width="30">
<a href="https://star-history.dera.page/#igareck/vpn-configs-for-russia&type=date&legend=top-left"><picture><source media="(prefers-color-scheme: dark)" srcset="https://star-history.dera.page/svg?repos=igareck/vpn-configs-for-russia&type=date&theme=dark&legend=top-left" /><source media="(prefers-color-scheme: light)" srcset="https://star-history.dera.page/svg?repos=igareck/vpn-configs-for-russia&type=date&legend=top-left" /><img alt="Star History Chart" src="https://star-history.dera.page/svg?repos=igareck/vpn-configs-for-russia&type=date&legend=top-left" /></picture></a>

## <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3Z25rOXRoeW1xODR1dWh2b3UycTd6YnB0Y2hlMTZtaDluZW1uNnl4ZyZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/CeYEKonyFQyzWhxmvd/giphy.gif" width="40"> DISCLAIMER

> *نویسنده مالک/توسعه‌دهنده/ارائه‌دهنده کانفیگ‌های VPN فهرست‌شده نیست. این یک مرور اطلاعاتی مستقل و نتایج تست‌ها است.*
>
> *این نوشته تبلیغ VPN نیست. تمام مطالب صرفاً برای اطلاع‌رسانی ارائه شده‌اند و فقط برای شهروندان کشورهایی که این اطلاعات در آن‌ها قانونی است — دست‌کم برای اهداف علمی. اگر اجازه ندارید این را بخوانید — همین حالا صفحه را ببندید!* 
>
> *نویسنده هیچ قصدی ندارد و تحت هیچ شرایطی استفاده از VPN یا هر برنامه دیگری را تشویق/تبلیغ/توجیه نمی‌کند.*
>
> *مسئولیت هرگونه استفاده از این کانفیگ‌های VPN بر عهده کاربر است.*
>
> *رفع مسئولیت: نویسنده مسئول اقدامات اشخاص ثالث نیست و استفاده غیرقانونی از VPN را تشویق نمی‌کند.*
>
> *نویسنده مسئول صحت، کامل‌بودن یا قابل‌اعتمادبودن داده‌های منتشرشده نیست. هرگونه شباهت/مصادفه تصادفی است. تمام اطلاعات «همان‌طور که هست» ارائه می‌شود و ممکن است بازتاب واقعیت نباشد.*
>
> *مطابق قوانین محلی استفاده کنید.* 
>
> *فقط برای اهداف قانونی از VPN استفاده کنید: به‌ویژه برای امنیت آنلاین و دسترسی امن از راه دور؛ و تحت هیچ شرایطی از این فناوری برای دور زدن مسدودسازی‌ها استفاده نکنید.*
>
> *این پروژه غیرتجاری و رایگان است؛ تمام اطلاعات مربوط به «پرداخت» که اینجا آمده صرفاً به‌طور اتفاقی جایی در اینترنت پیدا شده، «همان‌طور که هست» کپی شده و فقط به‌عنوان یک نمونه ممکن ارائه شده است و متعلق به نویسنده نیست.*
>
> *نکته: این صفحه را ببندید، همه VPNها را از کامپیوترتان پاک کنید، MAX و Yandex را روی همه دستگاه‌ها نصب کنید تا «حتی در پارکینگ هم کار کند»، و فقط از منابع اینترنتی‌ای استفاده کنید که ISP اجازه می‌دهد — متوجه شدید.*
