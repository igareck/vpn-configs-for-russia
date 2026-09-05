<div align="center">
  
![maxresdefault](https://cdn.jsdelivr.net/gh/igareck/GoldCaviar@refs/heads/main/Files/vpn-configs-for-russia-4.svg)

</div>

# <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNTljeGk4d3lzZnU3Mm1peDBienFpbmEyb3JmaDB5N21tMW9oczIwdyZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/8p1WPEOeDWFCksfe18/giphy.gif" width="45">  کانفیگ‌های رایگان VPN که در فدراسیون روسیه کار می‌کنند

[![تعداد بازدیدکنندگان](https://komarev.com/ghpvc/?username=igareck&label=Visitors&color=0e75b6&style=flat)](https://github.com/igareck)
[![ستاره‌ها](https://img.shields.io/github/stars/igareck/vpn-configs-for-russia?style=flat)](https://github.com/igareck/vpn-configs-for-russia/stargazers)
[![Issues](https://img.shields.io/github/issues/igareck/vpn-configs-for-russia?style=flat&color=0e75b6)](https://github.com/igareck/vpn-configs-for-russia/issues)
[![آخرین کامیت](https://img.shields.io/github/last-commit/igareck/vpn-configs-for-russia?style=flat&color=0e75b6)](https://github.com/igareck/vpn-configs-for-russia/commits/main/)
![عشق به متن‌باز](https://img.shields.io/badge/Open%20Source-%E2%9D%A4-0e75b6)
[![ایمیل](https://img.shields.io/badge/Email-igareck%40proton.me-0e75b6?logo=gmail&logoColor=white)](mailto:igareck@proton.me)

[![حمایت از من در Patreon](https://img.shields.io/badge/Support_me_on-Patreon-f96854?style=for-the-badge&logo=patreon&logoColor=white)](https://www.patreon.com/igareck/shop)
[![Telegram](https://img.shields.io/badge/Join_me_on-Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/igareq)

**🌐 Язык: [Русский](README.md) | 🌐 Language: [English](README-EN-US.md) | 🌐 语言: [中文](README-ZH-CN.md) | 🌐 زبان: [فارسی](README-FA-IR.md)**

<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExa2RkeXZzdDl1Y3g4dW1xcjFxc2xsMHVsZ2RiY243OHJodjd0cHQ1NSZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/qXp82ZL3eZbbTUrLyy/giphy.gif" width="20"> مجموعه‌ای از کانفیگ‌های عمومی و رایگان VPN که به‌صورت خودکار به‌روزرسانی و بررسی می‌شوند و کارکرد آن‌ها در فدراسیون روسیه آزمایش شده است (`VLESS` / `Trojan` / `Shadowsocks` / `Hysteria2` / `VMess` / `TUIC` و سایر پروتکل‌ها).

**برای دور زدن مسدودسازی‌های اینترنتی اعمال‌شده توسط Roskomnadzor (RKN).**

این مجموعه بر پایه CIDR و SNI به «لیست‌های سیاه» و «لیست‌های سفید» تقسیم شده است.

هر فهرست کانفیگ به‌صورت یک اشتراک TXT/YAML/JSON ارائه می‌شود که می‌توانید آن را در کلاینت دلخواه خود وارد کنید (`Karing`، `Clash Verge Rev`، `Clash Mi`، `v2rayN`، `Happ`، `Streisand`، `Throne` و سایر کلاینت‌ها).

پیش از انتشار، کانفیگ‌ها هر ۲ تا ۴ ساعت به‌صورت خودکار روی سروری در روسیه آزمایش می‌شوند. کانفیگ‌های کند و ازکارافتاده حذف می‌شوند؛ فاصله دقیق بررسی‌ها به نوع اشتراک بستگی دارد.

این بررسی‌ها دسترسی واقعی، تأخیر و سرعت را اندازه‌گیری می‌کنند؛ بنابراین صرفاً گردآوری و حذف خودکار موارد تکراری نیستند. از ۱۳ نوامبر تا ۲۸ دسامبر ۲۰۲۵، تمام این فرایند را به‌صورت دستی انجام می‌دادم. در ۲۸ دسامبر، اسکریپتی را تکمیل کردم که بررسی‌ها را خودکار و سریع‌تر کرد و در عین حال همان کیفیت بالای نتایج دستی را حفظ کرد.

این اسکریپت به‌طور منظم بازبینی می‌شود تا کیفیت اشتراک‌ها پیوسته بهتر شود.

پروتکل‌های سنتی VPN مانند OpenVPN و WireGuard مدت‌هاست که، چه در سرویس‌های رایگان و چه پولی، عملکرد قابل‌اعتمادی ندارند.

به همین دلیل، اگر می‌خواهید به اینترنت متصل بمانید، استفاده از کانفیگ‌هایی که مشخصاً از داخل روسیه آزمایش شده‌اند اهمیت دارد.

کانفیگ‌های عمومی نیز باید مرتب به‌روزرسانی شوند، زیرا معمولاً به‌سرعت منتشر می‌شوند و به همان سرعت از کار می‌افتند. به‌روزرسانی و بررسی خودکار باعث می‌شود کاربران در روسیه همیشه به فهرستی به‌روز و باکیفیت از کانفیگ‌های VPN، بدون موارد اضافی، دسترسی داشته باشند.

## 🔴 توجه کاربران خارج از روسیه!

<details>
<summary><em><code> روی فلش کلیک کنید </code></em></summary>

❗❗❗ اگر خارج از روسیه هستید (چین، ایران یا هر کشور دیگری)، فقط از کانفیگ‌های «لیست سیاه» استفاده کنید.

«لیست سفید» (WHITE) به شما کمکی نمی‌کند، چون «لیست سفید» فقط برای دور زدن محدودیت‌های خاص و شدید داخل روسیه تنظیم شده است! برای سایر کشورها، «لیست سفید» عملاً ناکارآمد، کند و بی‌فایده خواهد بود!

«لیست سیاه» (BLACK LIST) یک «گزینه VPN بین‌المللی» است و سریع‌ترین کانفیگ‌های عمومیِ موجود در اینترنت را شامل می‌شود!

ممنون از توجه شما!

</details>

---

<h2><code> موضوع شماره ۱ </code></h2>

### کانال Telegram را دنبال کنید: https://t.me/igareq <img src="https://thumb.wikimedia.org/wikipedia/commons/thumb/8/83/Telegram_2019_Logo.svg/960px-Telegram_2019_Logo.svg.png" width="25" align="absmiddle">

---

<h2><code> موضوع شماره ۲ </code></h2>

### دوستان عزیز!
### با توجه به احتمال مسدود شدن GitHub در روسیه، لطفاً لینک‌های آینه را ذخیره کنید! 

<details>
<summary><em><code> برای جزئیات روی فلش کلیک کنید </code></em></summary>

㋡

آینه‌ها به‌صورت همزمان با کانال اصلی به‌روزرسانی خواهند شد. 

**مسدودسازی تاثیری بر خود GitHub نخواهد داشت؛ مخزن اصلی تحت هر شرایطی به کار خود ادامه خواهد داد!**

اکیداً توصیه می‌کنم همین حالا در کلاینت‌های خود لینک‌های RAW اصلی `https://raw.githubusercontent.com/` را با لینک‌های RAW یکی از آینه‌ها جایگزین کنید؛ به `table` یا بخش `MIRRORS 🪞` مراجعه کنید! 

**چگونه یک فایل RAW را از یک آینه دریافت کنیم؟** در آنجا txt اشتراکی که به آن علاقه دارید را با همان نام پیدا کنید، روی لینک آن بروید و در بالای آن یک دکمه با نوشته `RAW`، `Open Raw`، `View Raw` یا `Source` پیدا کنید، روی این دکمه کلیک کنید و سپس لینک را از نوار آدرس کپی کنید. **یا لینک‌های آماده را از بخش `MIRRORS 🪞` بگیرید.**

**اشتراک‌ها و کدهای QR در توضیحات README در GitHub اصلی قبلاً با `GitHub-RAW` در یک پروکسی `GitHack-RAW` و `CDN.jsDelivr` جایگزین شده‌اند**.

لیست آینه‌ها:

| | | |
|---:|---|---|
| **GitLab** | https://gitlab.com/igareck/vpn-configs-for-russia/ | آینه Git / open-core SaaS |
| **Codeberg** | https://codeberg.org/igareck/vpn-configs-for-russia | آینه Git/FOSS |
| **Gitea** | https://gitea.com/igareck/vpn-configs-for-russia | آینه Git / مبتنی بر FOSS |
| **SourceHut** | https://git.sr.ht/~igareck/vpn-configs-for-russia | آینه Git/FOSS |
| **Bitbucket** | https://bitbucket.org/igareck/vpn-configs-for-russia/ | آینه Git / تجاری |
| **GitHack** | https://raw.githack.com/| پروکسی زنده RAW |
| **Yandex+BB** | https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/WHITE-CIDR-RU-all.txt&lang=de-de | پروکسی سفیدلیستی RAW Yandex+Bitbucket |
| | | |

✦ **GitLab/Codeberg/Gitea/SourceHut/Bitbucket** - این‌ها نسخه‌های کامل GitHub هستند، تمام اطلاعات موجود است (README و اشتراک‌ها) مشابه نسخه اصلی و بیشتر آن‌ها **بدون VPN کار می‌کنند**. 

✦ **GitLab** - بهترین آینه از همه.

✦ **آینه GitHack** برای لینک‌های RAW - حتی برای کسانی که هنگام تلاش برای دسترسی به دیگر آینه‌ها پیام “شما هم‌اکنون از یک آدرس IP یا کشور مسدود شده مشاهده می‌کنید” را دریافت می‌کنند، کار می‌کند.

✦ **آینه Yandex+Bitbucket** برای لینک‌های RAW **در حالت لیست سفید**. 

**لطفاً توجه داشته باشید که ترکیب Yandex+Bitbucket است که کار می‌کند**، هر اتصال دیگری با Yandex کانفیگ‌ها را خراب می‌کند!

**عملکرد کانفیگ‌هایی که از طریق Yandex+Bitbucket دانلود شده‌اند، توسط مشترکین در محدودیت‌های تهدید پهپاد در Karing، Clash Mi و v2rayN/v2rayNG آزمایش شده است.** 

> سوالات زیادی درباره ارسال یک نسخه از مخزن روی معادل‌های روسی GitHub مطرح شد.
> 
> اجازه دهید روشن کنم: سایت‌هایی که به‌طور مستقیم یا غیرمستقیم سانسور را در فدراسیون روسیه ترویج می‌کنند و/یا زیرمجموعه Roskomnadzor هستند، به دلایل عینی برای درج در فهرست رسمی آینه‌های این مخزن بسیار نامطلوب هستند. اگر می‌خواهید کانفیگ‌ها را در حالت لیست سفید دریافت کنید، از لینک پروکسی کارآمد Yandex+Bitbucket (فصل `MIRRORS 🪞`) استفاده کنید. Yandex+Bitbucket دقیقاً استثنای قاعده است، که به شما اجازه می‌دهد منابع مخزن را مستقیماً روی سایت‌های ناخواسته قرار ندهید، اما حتی در محدودیت‌های تهدید پهپادی آن‌ها را دانلود کنید!

</details>

---

<h2><code> موضوع شماره ۳ </code></h2>

### برای کسانی که برای اولین بار اینجا هستند و در ابتدا نمی‌دانند کدام کلاینت و اشتراک VPN را انتخاب کنند

<details>
<summary><em><code> برای جزئیات روی فلش کلیک کنید </code></em></summary>

㋡

```diff
توجه داشته باشید!

اوج بار و مسدودسازی‌ها در طول روز رخ می‌دهد.
در ساعات روز، دو اشتراک بیشترین مقاومت را در برابر مسدودسازی نشان داده‌اند:
BLACK_SS+All_RUS (در قالب استاندارد یا Clash) و به‌ویژه TOR BRIDGES!
به‌دلیل افزایش بار و تشدید مسدودسازی‌های گسترده،
سایر اشتراک‌ها از ۱ سپتامبر بسیار ناپایدار شده‌اند.
برای سایر موارد (و به‌طور کلی برای VPN)، اکنون بهترین زمان استفاده
از ساعت ۲۳:۰۰ تا ۱۱:۰۰ صبح به‌وقت مسکو است. طبق مشاهدات شخصی،
کانفیگ‌های عمومی در این بازه رفتار پایدارتر و قابل‌پیش‌بینی‌تری دارند.
```

**فقط ترکیب‌های کلاینت/اشتراک با بررسی سلامت خودکار توصیه می‌شوند!**

در این مخزن، تمام فرمت‌های اشتراک به دو دسته تقسیم شده‌اند: «عمومی» (فقط لیست پروکسی) و «مرتبط با کلاینت‌های خاص» (با بررسی سلامت خودکار و مسیریابی از قبل ساخته شده).

✦ **`فرمت عمومی/استاندارد (فقط فهرست پروکسی‌ها):`** 

**با Karing، Shadowrocket، Exclave و V2Box (iOS) پایدار کار می‌کند؛ قابلیت بررسی خودکار سلامت در خود این کلاینت‌ها تنظیم می‌شود.**

✦ **`فرمت Clash با بررسی سلامت خودکار داخلی (من آن را به عنوان پایدارترین گزینه توصیه می‌کنم):`** 

**با همه کلاینت‌های Clash/Mihomo کار می‌کند (Clash Verge Rev، Clash Mi، ClashMetaForAndroid و سایر کلاینت‌ها).**

✦ **`فرمت ویژه برای یک کلاینت جداگانه با بررسی سلامت خودکار داخلی:`**

**با v2rayN، v2rayNG، Streisand، Happ و v2RayTun کار می‌کند.** 

*اشتراک‌های ویژه v2rayNG، Streisand، Happ، v2RayTun و V2Box گزینه‌های تک‌دکمه‌ای هستند و سرور را به‌صورت خودکار انتخاب می‌کنند؛ برخلاف اشتراک‌های معمولی، فهرست کانفیگ‌ها نمایش داده نمی‌شود. در v2rayN، کانفیگ خودکار PolicyGroup همراه با فهرست کامل سرورها ارائه می‌شود.* 

*اگر اتصال اشتراکی با بررسی خودکار سلامت ناگهان قطع شد—که گاهی هنگام خطای کانفیگ رخ می‌دهد—برای منتظر نماندن، اتصال را دوباره راه‌اندازی کنید و ۵ تا ۲۰ ثانیه صبر کنید؛ برنامه دوباره بهترین پروکسی را انتخاب می‌کند. در کلاینت‌های Mihomo نیز می‌توانید بدون انتظار برای انتخاب خودکار یا اتصال مجدد کامل، یک پروکسی را به‌صورت دستی از فهرست انتخاب کنید.*

| | |
|:---|:---|
| **برای لیست سیاه** | **برای لیست سفید (White List)** |
| **فرمت استاندارد** **[BLACK_VLESS_RUS_mobile.txt](https://raw.githack.com/igareck/vpn-configs-for-russia/main/BLACK_VLESS_RUS_mobile.txt)** (لیست سیاه موبایل، ۱۵۰ کانفیگ) + **Karing (PC/iOS/Android), Exclave (Android), Shadowrocket (iOS) یا V2Box (iOS)** | **فرمت عمومی/استاندارد** **[Vless-Reality-White-Lists-Rus-Mobile.txt](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Vless-Reality-White-Lists-Rus-Mobile.txt&lang=de-de)** (لیست سفید موبایل، ۱۵۰ کانفیگ) یا **[WHITE-CIDR-RU-all.txt](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/WHITE-CIDR-RU-all.txt&lang=de-de)** (لیست سفید کامل) + **Karing (PC/iOS/Android), Shadowrocket (iOS) یا V2Box (iOS)** |
| یا | یا |
| **فرمت کلش** **[BLACK_VLESS_RUS_mobile_clash_global.yaml](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/Clash/GLOBAL/BLACK_VLESS_RUS_mobile_clash_global.yaml)** (لیست سیاه موبایل، ۱۵۰ کانفیگ) + **کلاینت‌های Clash/Mihomo** | **فرمت Clash** **[Vless-Reality-White-Lists-Rus-Mobile-clash-global.yaml](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/Clash/GLOBAL/Vless-Reality-White-Lists-Rus-Mobile-clash-global.yaml&lang=de-de)** (لیست سفید موبایل، ۱۵۰ کانفیگ) یا **[WHITE-CIDR-RU-all-clash-global.yaml](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/Clash/GLOBAL/WHITE-CIDR-RU-all-clash-global.yaml&lang=de-de)** (لیست سفید کامل) + **کلاینت‌های Clash/Mihomo** |
| | |

اشتراک‌های TOP 150 لیست سیاه و لیست سفید سبک، بهینه و با بیشتر کلاینت‌ها سازگارند؛ بنابراین برای دستگاه‌های همراه یا استفاده نخست بهترین انتخاب هستند.

**اگر اشتراک‌های موبایل لیست سیاه ناپایدارند، اشتراک‌های کامل را امتحان کنید (تقریباً از ساعت ۱۱ صبح تا ۲۳، اشتراک BLACK_SS+All_RUS بهترین عملکرد را دارد):**


 **[BLACK_SS+All_RUS.txt](https://raw.githack.com/igareck/vpn-configs-for-russia/main/BLACK_SS%2BAll_RUS.txt) یا [BLACK_SS+All_RUS_clash_global.yaml](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/Clash/GLOBAL/BLACK_SS%2BAll_RUS_clash_global.yaml)** 

**[BLACK_VLESS_RUS.txt](https://raw.githack.com/igareck/vpn-configs-for-russia/main/BLACK_VLESS_RUS.txt) یا [BLACK_VLESS_RUS_clash_global.yaml](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/Clash/GLOBAL/BLACK_VLESS_RUS_clash_global.yaml)**

**برای کلاینت‌های Karing یا Mihomo.**

در ادامه، لینک و کد QR همه اشتراک‌ها و همچنین فهرست کامل کلاینت‌های PC، روتر، iOS و Android را همراه با راهنمای دقیق خواهید یافت.

</details>

---

<h2><code> موضوع شماره ۴ </code></h2>

**توجه به کاربرانی که لیست‌های سفید ندارند (اینترنت کابلی و موبایل بدون محدودیت)، و نیاز به جایگزین رایگان VPN Blacklist در خانه یا محل کار دارند - از بسته** <img src="https://upload.wikimedia.org/wikipedia/commons/d/df/Tor_Browser_icon_%28New%29.png" width="20" align="absmiddle"> `Tor Bridges` **+** `کلاینت Tor OnionHop V3` یا `OnionFruit کلاینت Tor` یا `Tor Browser` **(جزئیات در بخش** `تفاوت بین لیست‌های سیاه و سفید چیست` ➞ `با لیست‌های سیاه معمولی` ➞ `TOR BRIDGES`).

**اگر ناگهان لیست سیاه VPN ناپایدار شد، از این روش استفاده کنید. همیشه در لحظات کاهش کارایی کمک می‌کند. بنا بر مشاهدات، TOR چندین برابر پایدارتر از VPN است؛ اتصال برای چندین روز برقرار می‌ماند.**

**تمام [پل‌های TOR](https://github.com/igareck/vpn-configs-for-russia/tree/main/TOR-BRIDGES) در این مخزن، هر ۴ ساعت یک‌بار تست می‌شوند تا به‌طور خاص در روسیه کار کنند و تأخیر، سرعت و دسترسی کامل آن‌ها بررسی می‌شود.** آن را با پینگ معمولی اشتباه نگیرید؛ پینگ عملکرد واقعی را نشان نمی‌دهد.

از ۱ سپتامبر، اتصال‌های VPN در طول روز بسیار ناپایدار شده‌اند؛ تقریباً از ساعت ۱۱ صبح تا ۱۱ شب به‌وقت مسکو. بدترین وضعیت معمولاً حوالی ساعت ۱ بعدازظهر است؛ در آن ساعت، تعداد زیادی از نودهای عمومی VPN هم‌زمان از دسترس خارج می‌شوند و اختلال در نودهای VLESS از همه شدیدتر است. اوضاع تازه بعد از ساعت ۷ تا ۸ شب کم‌کم بهتر می‌شود. فعلاً VPN فقط در طول شب، تقریباً از ساعت ۱۱ شب تا ۱۱ صبح، نسبتاً پایدار است.

بنابراین، در طول روز از TOR استفاده کنید؛ TOR در هر ساعتی از شبانه‌روز پایدار و قابل‌اعتماد است!

---

<h2><code> موضوع شماره ۵ </code></h2>

### نکات مهم درباره DNS

<details>
<summary><em><code> برای جزئیات روی فلش کلیک کنید </code></em></summary>

㋡

**DNS در کلاینت**

اخیراً با کانفیگ‌هایی مواجه شده‌ام که آزمایش را پشت سر می‌گذارند، وصل می‌شوند، اما بعداً از کار کردن امتناع می‌کنند.

یعنی پینگ آن‌ها موفق است، اما با گذشت زمان ترافیک متوقف می‌شود.

تمام این موارد از طریق تنظیمات DNS در کلاینت حل شد.

بگذارید برایتان مثال بیاورم:

<details>
<summary><strong><code> Karing </code></strong> ⬅ برای باز کردن کلیک کنید </summary>

㋡

```diff
   Path: "Settings" ⚙️ → "DNS" → "Server" → Click on "Traffic Proxy" → Uncheck all boxes except:

   https://doh.pub/dns-query
   https://dns.alidns.com/dns-query
   https://cloudflare-dns.com/dns-query
   https://dns.google/dns-query

   Or, alternatively, try one, for example: https://dns.google/dns-query.

   Other items in the "DNS" menu → There is no need to touch the "Server".
```

</details>

<details>
<summary><strong><code> v2rayN </code></strong> ⬅ برای باز کردن کلیک کنید </summary>

㋡

```diff
Path: "Settings" -> "DNS Settings" -> "Basic DNS Settings"

Replace the contents of "Remote DNS" (Remote DNS) per line:

https://dns.google/dns-query,https://dns.quad9.net/dns-query,https://dns.adguard-dns.com/dns-query,https://freedns.controld.com/p0,https://dns.mullvad.net/dns-query,https://cloudflare-dns.com/dns-query,https://doh.opendns.com/dns-query
```

</details>

<details>
<summary><strong><code> Exclave </code></strong> ⬅ برای باز کردن کلیک کنید </summary>

㋡

```diff
In the section "☰" → "Settings" find the line/item called "Remote DNS".
Instead of the default value, put: https://dns.google/dns-query
```

</details>

▷ برای **`Shadowrocket`** فایل کانفیگ را در بخش **دستورالعمل‌ها برای هر کلاینت به‌صورت جداگانه** دانلود کنید.

▷ برای اشتراک‌های کلاینت ویژه **`Clash-Mihomo / v2rayNG / Happ / Streisand / V2rayTun / V2Box`** نیازی به پیکربندی چیزی نیست، **همه چیز با اشتراک‌های خودکار ارائه می‌شود**.

━━━

**DNS روی دستگاه (روتر، PC یا گوشی)**

ارائه‌دهنده / DNS خودکار روی دستگاه را با DNS-over-HTTPS رمزگذاری‌شده (DoH) جایگزین کنید. 

**موارد واقعی وجود دارند (و تعداد آن‌ها روز به‌روز بیشتر می‌شود)، زمانی که DoH روی یک دستگاه/روتر نصب می‌شود، مسائل مربوط به عملکرد کانفیگ‌ها حل می‌شود، قطع ارتباطات به مراتب کمتر اتفاق می‌افتد، ترافیک پایدارتر و قابل پیش‌بینی‌تر می‌شود.**

فهرست‌های DNS-over-HTTPS (DoH) توصیه‌شده را در پایین‌ترین بخش README **DNS-over-HTTPS** ببینید.

**پس از موج بزرگی از مسدود شدن‌های Roskomnadzor از 17 تا 23 آگوست 2026، محدودیت‌های DNS-over-HTTPS در روسیه آغاز شد (DoH)**. اما این به این معنا نیست که اکنون هیچ DoH خارجی به‌طور کامل کار نمی‌کند. آن‌ها کار می‌کنند، فقط اکنون هر اپراتور به صورت انتخابی با DoHهای خودش کار می‌کند و نه همه به‌صورت پشت سر هم، مانند قبل. 

برای مثال، یک ارائه‌دهنده ممکن است فقط Google DoH داشته باشد، در حالی که ارائه‌دهنده دیگر ممکن است Cloudflare و OpenDNS DoH داشته باشد، در حالی که Quad9 DoH در همه جا برای من کار نکرد. فقط با بررسی از طریق اپراتور خود می‌توانید مطمئن شوید. ما DoH را وصل کردیم - شبکه را روشن کردیم: مرورگر سایت‌ها را بارگذاری می‌کند - این به این معنی است که DoH کار می‌کند، بارگذاری نمی‌شود - یعنی ما DoH بعدی را گرفته و بیشتر بررسی می‌کنیم.

زمانی صرف کنید و یک DoH کارآمد پیدا کنید، این اتصال شما را پایدارتر خواهد کرد.

━━━

**در دوره رژیم لیست سفید (محدودیت‌های تهدید پهپاد) هیچ ارائه‌دهنده خارجی DNS کار نمی‌کند (نه گوگل، نه Cloudflare، نه Quad9، نه علی‌بابا، نه OpenDNS، نه). در این صورت، از یا DNS خودکار از ارائه‌دهنده خود استفاده کنید یا DNS/DNS-over-HTTPS از Yandex. در غیر این صورت، کانفیگ‌های VPN برای لیست سفید به‌سادگی کار نخواهند کرد.**

━━━

**DoH یک درمان شگفت‌انگیز یا معجزه‌آسا برای تمام مشکلات نیست، اما جزئیات بسیار مهمی هنگام راه‌اندازی شبکه و کلاینت‌های شماست.**

</details>

---

<h2><code> موضوع شماره ۶ </code></h2>

### این اخبار مهمی برای همه کسانی است که VPN را روی گوشی هوشمند خود استفاده می‌کنند

**یک تحلیل بسیار مهم از آسیب‌پذیری بحرانی کلاینت‌های موبایل بر اساس xray/sing-box در سایت Habr منتشر شد و یک رده‌بندی کوچک از ایمن‌ترین آنها تهیه شد.** 

**تحلیلی از روش‌های شناسایی شده نظارت در برنامه‌های روسی انجام شد.**

**همچنین یک برنامه حداقل-حداکثر برای امنیت دستگاه‌های شما تدوین کرده‌ایم تا VPN به درستی کار کند.**

<details>
<summary><em><code> برای جزئیات روی فلش کلیک کنید </code></em></summary>

㋡

یک تحلیل بسیار مهم از یک آسیب‌پذیری بحرانی بر روی کلاینت‌های **موبایل** Habr مبتنی بر xray/sing-box منتشر شده است. اصل مشکل این است که کلاینت یک پروکسی محلی SOCKS5 بدون احراز هویت ایجاد می‌کند و برنامه مخرب (یعنی هر برنامه روسی: MAX، Yandex، Wildberries، Ozon، Gosuslugi، Rzd، هر نرم‌افزار بانکی (Sber، T-Bank)، Kaspersky و سایر شرکت‌های بزرگ فناوری اطلاعات روسیه) روی **همان دستگاه** می‌تواند بدون عبور از آن `VpnService` به آن متصل شود، IP خروجی شما را تعیین کند و در نتیجه پروکسی/سرور شما را در اختیار گیرد. نویسنده به طور جداگانه می‌نویسد که `private space`، `Shelter`، `Island` و تونل‌زنی تقسیم‌شده اختصاصی برای هر برنامه در اینجا کمکی نمی‌کند.

مقاله: https://habr.com/ru/articles/1020080/

آینه: https://web.archive.org/web/https://habr.com/ru/articles/1020080/

یک فایل PDF به صورت آنلاین منتشر شد که روش‌های نظارتی شناسایی شده در برنامه‌های روسی را توضیح می‌دهد:

فایل PDF: **[Russian_apps_spy_for_vpn.pdf](https://github.com/igareck/GoldCaviar/blob/main/Files/Russian_apps_spy_for_vpn.pdf)**

**کدام کلاینت‌ها مشکل اشاره‌شده توسط نویسنده مقاله را حل کرده‌اند؟** @runetfreedom **در Habré (تأیید شده):** 

1. **Karing** ✅ - اضافه کردن **مجوز دستی** (افزودن تنظیمات مجوز برای اتصالات ورودی نوع ترکیبی (Settings-Mixed))، همانطور که نویسنده در مقاله در Habré اشاره کرده بود. یک اصلاح برای Android در GitHub، برای iOS در AppStore منتشر شده است. بر روی تمام کلاینت‌ها تست شده! **توسعه‌دهنده مشکل را حل کرده است!**

2. **Throne** ✅ - **افزودن پشتیبانی مجوز ورودی** در به‌روزرسانی. نسخه‌ها فقط برای PC هستند. بررسی کردم که در تنظیمات «نام کاربری/رمز عبور مجوز ورودی» وجود دارد. **توسعه‌دهنده مشکل را حل کرده است!**

3. **Happ** ✅ - **حذف HandlerService در Android؛ در Android، در iOS، در نسخه PC، «مجوز ورودی» ساخته شده است**.

4. **v2rayNG** ✅ - **"کاربر/رمز عبور پروکسی محلی" در تنظیمات** نسخه‌ها برای Android. در **نسخه‌های PC** (**v2rayN**❌) مشکل حل نشده است.

۵. **v2raytun** - در **Android** ✅ ورود/رمز عبور برای پروکسی محلی socks5 اضافه شد، برای **iOS** ❌ هیچ کاری انجام نشده است.

۶. **Exclave** ✅ - نسخه‌های **"کاربر/رمز عبور پروکسی محلی" در تنظیمات** برای Android (Exclave پلتفرم دیگری ندارد).

۷. **Hiddify** ❌ - آخرین به‌روزرسانی در ۵ مارس بود. **مشکل اجازه‌نامه پورت localhost حل نشده است.**

۸. **Streisand, NekoBox, V2Box** ❌ - من نیز در دفترچه تغییرات یا در تنظیمات خود برنامه‌ها راه‌حلی برای مشکل ذکر شده توسط نویسنده ندیدم. **مشکل اجازه‌نامه پورت localhost حل نشده است.**


**پیامدهای عملی این موضوع:**

✦ دیگر نمی‌توانید خروجی IP پروکسی خود را به‌عنوان «به‌طور پیش‌فرض محافظت‌شده» در نظر بگیرید اگر نرم‌افزار غیرقابل اعتماد/مخرب روی دستگاه وجود داشته باشد (یعنی هر برنامه RU: MAX، Yandex، Wildberries، Ozon، Gosuslugi، Rzd، VK، هر نرم‌افزار بانکی (Sber، T-Bank)، Kaspersky و سایر شرکت‌های بزرگ IT روسیه);

✦ فضای خصوصی و تونل زدن تقسیم‌شده امنیتی که بسیاری انتظار داشتند را فراهم نمی‌کنند;

✦ اگر یک کلاینت VPN داشته باشید و تعدادی نرم‌افزار روسی روی گوشی شما ترکیب شده باشد، این مدل امنیتی بدی است;

✦ اگر شما هیچ نرم‌افزار RU روی گوشی هوشمند خود یا PC ندارید، نگران نباشید، این آسیب‌پذیری‌ها بر شما تأثیری نخواهند داشت.

**کارهایی که اکنون باید انجام دهید**

**برنامه حداقل:**

✦ اگر هر نرم‌افزار RU روی گوشی هوشمند خود یا PC دارید - **فقط از Karing (Android+iOS+PC)، Throne (PC)، v2rayNG (Android)، v2rayTun (Android)، Happ (Android+iOS) استفاده کنید و حتماً یک نام کاربری/رمز عبور** برای "Settings-Mixed" (Karing)، برای "Inbound Authorization" (Throne, Happ)، و "Local proxy user/password" (v2rayNG، v2rayTun) در تنظیمات تعیین کنید;

✦ بروزرسانی‌ها از کلاینت‌ها دیگر را مانیتور کرده و بلافاصله نصب کنید؛

✦ از مسیریابی تقسیم‌شده `geoip:ru -> direct` استفاده کنید، `other -> proxy`؛

✦ گزینه برای Android: یک پروفایل دوم کامل و امکان جابجایی بین آنها. 

دستورالعمل‌های رسمی گوگل: https://support.google.com/android/answer/2865483?hl=ru

`Main profile` — VPN/Tor، مرورگر، GitHub، Telegram، ایمیل، رمزهای عبور؛

`پروفایل دوم RU` - بانک‌ها، خدمات دولتی، Yandex، اوزون، WB، راه‌آهن روسیه و دیگر نرم‌افزارهای روسی.

اما این تضمین محافظت در برابر نشت‌های لوکال‌هاست نیست. این تفکیک داده‌ها بهتر از ایزوله کردن برنامه در یک حساب کاربری است، اما هنوز حلقه بازگشت/لوکال‌هاست بین کاربران را جدا نمی‌کند. یک کاربر غیرفعال می‌تواند در پس‌زمینه به کار خود ادامه دهد در حالی که کاربر دیگری فعال است. در یک دستگاه واحد، این بهترین محافظت تا به امروز است.

✦ شما باید درک کنید که این «محافظت کامل» نیست، بلکه تنها کاهش «خسارت» است.

**برنامه حداکثر (در این‌جا تضمین ایزولاسیون به 100% نزدیک‌تر است):**

✦ **دستگاه موبایل اصلی**: هر برنامه غیر RU، VPN، Tor و وظایف حساس؛

✦ **دستگاه موبایل اضافی**: برای نرم‌افزارهای روسی، ارزان‌ترین گوشی دست‌دوم برای برنامه‌های RU بخرید.

✦ **کامپیوتر**: هیچ‌گاه برنامه‌های روسی را نصب نکنید، یا فقط در یک ماشین مجازی (VirtualBox) نصب کنید. 

اکنون هر برنامه RU باید به‌عنوان بالقوه مخرب در نظر گرفته شود و باید جدا نگه داشته شود!

✦ **مرورگرها در PC**: برای سایت‌های روسی، یک مرورگر جداگانه با افزونه uBlock Origin و فیلتر «Block Outsider Intrusion into LAN» فعال انتخاب کنید، یا آن را در یک ماشین مجازی اجرا کنید.

**نتیجه‌گیری اصلی:**
اگر از کانفیگ‌ها عمومی یا سرور خود استفاده می‌کنید، فرض کنید که در بدترین حالت، آدرس IP خروجی شما مشخص خواهد شد. اکنون زیرساخت و عادات باید با دقت بیشتری ساخته شوند: به‌روزرسانی‌ها، دستگاه خالص/جداگانه، مسیریابی جداگانه، جداسازی IP ورودی و خروجی (برای صاحبان سرور)، ایزوله کردن نرم‌افزار مخرب.

</details>

---

## `حتماً بخوانید!`

**اگر می‌خواهید کانفیگ‌ها را به‌طور موفقیت‌آمیز راه‌اندازی کنید، اشتراک صحیح را دانلود کنید و بفهمید چه چیزی چیست، بخش‌های زیر را با دقت بخوانید!** 

**در ادامه خواهید فهمید:** 

`1. تفاوت بین لیست‌های سیاه و سفید؛`

`۲. چه نوع اشتراک‌هایی وجود دارد و چگونه با یکدیگر تفاوت دارند.`

`لطفاً توجه داشته باشید که لینک‌های جایگزین در فایل Readme (آینه‌ها) وجود دارند که حتی در حالت White List نیز کار می‌کنند;`

`۳. چه برنامه‌هایی را دانلود کنیم، از کجا دانلود کنیم و چگونه استفاده کنیم;`

`۴. چه ترکیبی از برنامه‌ها و اشتراک‌ها باید استفاده شود تا کانفیگ‌ها به روان‌ترین و خودکارترین شکل عمل کنند;`

`۵. دیگر اطلاعات مفید درباره نحوه کار اینترنت به زبان ساده، اینکه ارائه‌دهنده چه چیزی را وقتی آنلاین هستید می‌بیند، کدام مرورگرها بهتر هستند، و غیره;`

**علاوه بر این، بخش «مسائل» در بالای مخزن را بخوانید، سوال بپرسید، نظر دهید و تجربیات خود را به اشتراک بگذارید.**

**کانفیگ‌هایی که در اینجا منتشر می‌شوند پس از بررسی‌های واقعی منتشر شده‌اند، یعنی بیشتر آن‌ها در زمان انتشار فعال خواهند بود!**

**هر اشتراک تقریباً هر ۲ تا ۴ ساعت به‌روزرسانی می‌شود تا از دست دادن مرتبط بودن آن جلوگیری شود!**

---

## <img src="https://raw.githubusercontent.com/igareck/GoldCaviar/refs/heads/main/Files/Download-VPN-configs-banner-FA-IR.svg" width="480">

 ✦ *نام‌های اشتراک (به رنگ آبی برجسته شده) قابل کلیک هستند و شامل لینک به فرمت اشتراک RAW می‌باشند!*

 ✦ *مخزن شامل **Standard**، **Base64**، **Clash/Mihomo و فرمت‌های ویژه** برای کلاینت‌ها اختصاصی (پوشه Export) می‌باشد.*

 ✦ *فعال‌سازی به‌روزرسانی خودکار در کلاینت VPN شما هر ۱ ساعت یک بار!*

 ✦ *برای Black Lists: اگر در روسیه هستید و به مسیریابی RU-DIRECT نیاز دارید (که در آن سایت‌های روسی مستقیماً و بدون VPN باز می‌شوند):*

 * *یا به نسخه روسی README و بخش مربوطه "Download VPN-configs" بروید؛ لینک‌های دارای مسیریابی RU-DIRECT در آنجا قرار دارند.*

 * *یا پیکربندی‌های RU-DIRECT را در پوشه Export پیدا کنید.*

---

<details>

<summary><h2> 🧾 <code> لیست سیاه ⚫ </code></h2></summary>

---

### TOP 150 برای تلفن (بهترین 150 کانفیگ در اشتراک، ترکیبی از پروتکل‌ها):

<details>
<summary><strong><code> باز کردن </code></strong></summary>

㋡

| | | | | | | | | | | |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **فرمت اشتراک** | **عمومی (فرمت استاندارد)** | **عمومی (فرمت Base64)** | **Clash/Mihomo (PC/iOS/Android)** | **v2rayN (PC)** | **v2rayNG (Android)** | **Streisand (iOS)** | **Happ (PC/iOS/Android)** | **V2Box (Android)** | **v2RayTun (Android)** | **v2RayTun (iOS)** |
| **لینک** | [BLACK_VLESS_RUS_mobile](https://raw.githack.com/igareck/vpn-configs-for-russia/main/BLACK_VLESS_RUS_mobile.txt) | [BLACK_VLESS_RUS_mobile](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/Base64/PROXIES_ONLY/BLACK_VLESS_RUS_mobile_base64.txt) | [BLACK_VLESS_RUS_mobile](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/Clash/GLOBAL/BLACK_VLESS_RUS_mobile_clash_global.yaml) | [BLACK_VLESS_RUS_mobile](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/v2rayN_PC/BLACK_VLESS_RUS_mobile_v2rayN.txt) | [BLACK_VLESS_RUS_mobile](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/v2rayNG_Android/GLOBAL/BLACK_VLESS_RUS_mobile_v2rayNG_global.json) | [BLACK_VLESS_RUS_mobile](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/Streisand_iOS/GLOBAL/BLACK_VLESS_RUS_mobile_Streisand_global.json) | [BLACK_VLESS_RUS_mobile](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/Happ/GLOBAL/BLACK_VLESS_RUS_mobile_Happ_global.json) | [BLACK_VLESS_RUS_mobile](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/V2Box_Android/GLOBAL/BLACK_VLESS_RUS_mobile_V2Box_Android_global.json) | [BLACK_VLESS_RUS_mobile](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/v2RayTun_Android/GLOBAL/BLACK_VLESS_RUS_mobile_v2RayTun_Android_global.json) | [BLACK_VLESS_RUS_mobile](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/v2RayTun_iOS/GLOBAL/BLACK_VLESS_RUS_mobile_v2RayTun_iOS_global.json) |
| **کد QR** | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Standard/PROXIES_ONLY/BLACK_VLESS_RUS_mobile_standard_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Base64/PROXIES_ONLY/BLACK_VLESS_RUS_mobile_base64_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Clash/GLOBAL/BLACK_VLESS_RUS_mobile_clash_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2rayN_PC/BLACK_VLESS_RUS_mobile_v2rayN_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2rayNG_Android/GLOBAL/BLACK_VLESS_RUS_mobile_v2rayNG_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Streisand_iOS/GLOBAL/BLACK_VLESS_RUS_mobile_Streisand_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Happ/GLOBAL/BLACK_VLESS_RUS_mobile_Happ_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/V2Box_Android/GLOBAL/BLACK_VLESS_RUS_mobile_V2Box_Android_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2RayTun_Android/GLOBAL/BLACK_VLESS_RUS_mobile_v2RayTun_Android_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2RayTun_iOS/GLOBAL/BLACK_VLESS_RUS_mobile_v2RayTun_iOS_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> |
| **بررسی خودکار سلامت؟** | **بررسی خودکار سلامت ندارد.** در کلاینت تنظیم می‌شود | **بررسی خودکار سلامت ندارد.** در کلاینت تنظیم می‌شود | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** |
| **مسیریابی، GLOBAL** | **مسیریابی GLOBAL ندارد.** در کلاینت تنظیم می‌شود | **مسیریابی GLOBAL ندارد.** در کلاینت تنظیم می‌شود | **بله، GLOBAL در اشتراک تعبیه شده است** | **مسیریابی GLOBAL ندارد.** در v2rayN تنظیم می‌شود | **بله، GLOBAL در اشتراک تعبیه شده است** | **بله، GLOBAL در اشتراک تعبیه شده است** | **بله، GLOBAL در اشتراک تعبیه شده است** | **بله، GLOBAL در اشتراک تعبیه شده است** | **بله، GLOBAL در اشتراک تعبیه شده است** | **بله، GLOBAL در اشتراک تعبیه شده است** |
| **کاربرد** | اشتراک عمومی با فرمت استاندارد، بدون تنظیمات یا مسیریابی مخصوص کلاینت؛ فقط شامل فهرست پروکسی‌هاست. مناسب برای Karing، Exclave، Shadowrocket و V2Box (iOS) | همان اشتراک عمومیِ فقط-پروکسی در فرمت Base64 که به‌عنوان گزینه سازگاری برای سایر کلاینت‌ها ارائه می‌شود | اشتراک Clash/Mihomo با بررسی خودکار سلامت تعبیه‌شده برای کلاینت‌های Mihomo: Clash Verge Rev، Clash Mi، Clash Lite، Stash، Clash Meta for Android و FlClash | اشتراک v2rayN با بررسی خودکار سلامت تعبیه‌شده. برای استفاده از انتخاب خودکار، کانفیگ `PolicyGroup` را در پایین فهرست انتخاب کنید | اشتراک v2rayNG با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای Android | اشتراک Streisand با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای iOS | اشتراک Happ با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای PC، iOS و Android | اشتراک V2Box با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای Android؛ نسخه iOS از اشتراک‌های استاندارد استفاده می‌کند | اشتراک v2RayTun با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای Android | اشتراک v2RayTun با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای iOS |
| | | | | | | | | | | |

</details>

`اشتراک تلفن مختصر و سبک برای لیست‌های سیاه. شامل 150 کانفیگ سریع‌ترین‌ها از اشتراک‌های کامل VLESS و SHADOWSOCKS+ALL (مخلوط پروتکل‌ها).`

---

### VLESS: 

<details>
<summary><strong><code> باز کردن </code></strong></summary>

㋡

| | | | | | | | | | | |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **فرمت اشتراک** | **عمومی (فرمت استاندارد)** | **عمومی (فرمت Base64)** | **Clash/Mihomo (PC/iOS/Android)** | **v2rayN (PC)** | **v2rayNG (Android)** | **Streisand (iOS)** | **Happ (PC/iOS/Android)** | **V2Box (Android)** | **v2RayTun (Android)** | **v2RayTun (iOS)** |
| **لینک** | [BLACK_VLESS_RUS](https://raw.githack.com/igareck/vpn-configs-for-russia/main/BLACK_VLESS_RUS.txt) | [BLACK_VLESS_RUS](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/Base64/PROXIES_ONLY/BLACK_VLESS_RUS_base64.txt) | [BLACK_VLESS_RUS](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/Clash/GLOBAL/BLACK_VLESS_RUS_clash_global.yaml) | [BLACK_VLESS_RUS](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/v2rayN_PC/BLACK_VLESS_RUS_v2rayN.txt) | [BLACK_VLESS_RUS](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/v2rayNG_Android/GLOBAL/BLACK_VLESS_RUS_v2rayNG_global.json) | [BLACK_VLESS_RUS](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/Streisand_iOS/GLOBAL/BLACK_VLESS_RUS_Streisand_global.json) | [BLACK_VLESS_RUS](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/Happ/GLOBAL/BLACK_VLESS_RUS_Happ_global.json) | [BLACK_VLESS_RUS](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/V2Box_Android/GLOBAL/BLACK_VLESS_RUS_V2Box_Android_global.json) | [BLACK_VLESS_RUS](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/v2RayTun_Android/GLOBAL/BLACK_VLESS_RUS_v2RayTun_Android_global.json) | [BLACK_VLESS_RUS](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/v2RayTun_iOS/GLOBAL/BLACK_VLESS_RUS_v2RayTun_iOS_global.json) |
| **کد QR** | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Standard/PROXIES_ONLY/BLACK_VLESS_RUS_standard_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Base64/PROXIES_ONLY/BLACK_VLESS_RUS_base64_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Clash/GLOBAL/BLACK_VLESS_RUS_clash_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2rayN_PC/BLACK_VLESS_RUS_v2rayN_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2rayNG_Android/GLOBAL/BLACK_VLESS_RUS_v2rayNG_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Streisand_iOS/GLOBAL/BLACK_VLESS_RUS_Streisand_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Happ/GLOBAL/BLACK_VLESS_RUS_Happ_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/V2Box_Android/GLOBAL/BLACK_VLESS_RUS_V2Box_Android_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2RayTun_Android/GLOBAL/BLACK_VLESS_RUS_v2RayTun_Android_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2RayTun_iOS/GLOBAL/BLACK_VLESS_RUS_v2RayTun_iOS_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> |
| **بررسی خودکار سلامت؟** | **بررسی خودکار سلامت ندارد.** در کلاینت تنظیم می‌شود | **بررسی خودکار سلامت ندارد.** در کلاینت تنظیم می‌شود | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** |
| **مسیریابی، GLOBAL** | **مسیریابی GLOBAL ندارد.** در کلاینت تنظیم می‌شود | **مسیریابی GLOBAL ندارد.** در کلاینت تنظیم می‌شود | **بله، GLOBAL در اشتراک تعبیه شده است** | **مسیریابی GLOBAL ندارد.** در v2rayN تنظیم می‌شود | **بله، GLOBAL در اشتراک تعبیه شده است** | **بله، GLOBAL در اشتراک تعبیه شده است** | **بله، GLOBAL در اشتراک تعبیه شده است** | **بله، GLOBAL در اشتراک تعبیه شده است** | **بله، GLOBAL در اشتراک تعبیه شده است** | **بله، GLOBAL در اشتراک تعبیه شده است** |
| **کاربرد** | اشتراک عمومی با فرمت استاندارد، بدون تنظیمات یا مسیریابی مخصوص کلاینت؛ فقط شامل فهرست پروکسی‌هاست. مناسب برای Karing، Exclave، Shadowrocket و V2Box (iOS) | همان اشتراک عمومیِ فقط-پروکسی در فرمت Base64 که به‌عنوان گزینه سازگاری برای سایر کلاینت‌ها ارائه می‌شود | اشتراک Clash/Mihomo با بررسی خودکار سلامت تعبیه‌شده برای کلاینت‌های Mihomo: Clash Verge Rev، Clash Mi، Clash Lite، Stash، Clash Meta for Android و FlClash | اشتراک v2rayN با بررسی خودکار سلامت تعبیه‌شده. برای استفاده از انتخاب خودکار، کانفیگ `PolicyGroup` را در پایین فهرست انتخاب کنید | اشتراک v2rayNG با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای Android | اشتراک Streisand با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای iOS | اشتراک Happ با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای PC، iOS و Android | اشتراک V2Box با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای Android؛ نسخه iOS از اشتراک‌های استاندارد استفاده می‌کند | اشتراک v2RayTun با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای Android | اشتراک v2RayTun با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای iOS |
| | | | | | | | | | | |


</details>

  `اشتراک VLESS برای لیست‌های سیاه.`

---

### SHADOWSOCKS+ALL:

<details>
<summary><strong><code> باز کردن </code></strong></summary>

㋡

| | | | | | | | | | | |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **فرمت اشتراک** | **عمومی (فرمت استاندارد)** | **عمومی (فرمت Base64)** | **Clash/Mihomo (PC/iOS/Android)** | **v2rayN (PC)** | **v2rayNG (Android)** | **Streisand (iOS)** | **Happ (PC/iOS/Android)** | **V2Box (Android)** | **v2RayTun (Android)** | **v2RayTun (iOS)** |
| **لینک** | [BLACK_SS+All_RUS](https://raw.githack.com/igareck/vpn-configs-for-russia/main/BLACK_SS%2BAll_RUS.txt) | [BLACK_SS+All_RUS](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/Base64/PROXIES_ONLY/BLACK_SS%2BAll_RUS_base64.txt) | [BLACK_SS+All_RUS](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/Clash/GLOBAL/BLACK_SS%2BAll_RUS_clash_global.yaml) | [BLACK_SS+All_RUS](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/v2rayN_PC/BLACK_SS%2BAll_RUS_v2rayN.txt) | [BLACK_SS+All_RUS](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/v2rayNG_Android/GLOBAL/BLACK_SS%2BAll_RUS_v2rayNG_global.json) | [BLACK_SS+All_RUS](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/Streisand_iOS/GLOBAL/BLACK_SS%2BAll_RUS_Streisand_global.json) | [BLACK_SS+All_RUS](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/Happ/GLOBAL/BLACK_SS%2BAll_RUS_Happ_global.json) | [BLACK_SS+All_RUS](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/V2Box_Android/GLOBAL/BLACK_SS%2BAll_RUS_V2Box_Android_global.json) | [BLACK_SS+All_RUS](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/v2RayTun_Android/GLOBAL/BLACK_SS%2BAll_RUS_v2RayTun_Android_global.json) | [BLACK_SS+All_RUS](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/v2RayTun_iOS/GLOBAL/BLACK_SS%2BAll_RUS_v2RayTun_iOS_global.json) |
| **کد QR** | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Standard/PROXIES_ONLY/BLACK_SS%2BAll_RUS_standard_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Base64/PROXIES_ONLY/BLACK_SS%2BAll_RUS_base64_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Clash/GLOBAL/BLACK_SS%2BAll_RUS_clash_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2rayN_PC/BLACK_SS%2BAll_RUS_v2rayN_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2rayNG_Android/GLOBAL/BLACK_SS%2BAll_RUS_v2rayNG_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Streisand_iOS/GLOBAL/BLACK_SS%2BAll_RUS_Streisand_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Happ/GLOBAL/BLACK_SS%2BAll_RUS_Happ_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/V2Box_Android/GLOBAL/BLACK_SS%2BAll_RUS_V2Box_Android_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2RayTun_Android/GLOBAL/BLACK_SS%2BAll_RUS_v2RayTun_Android_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2RayTun_iOS/GLOBAL/BLACK_SS%2BAll_RUS_v2RayTun_iOS_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> |
| **بررسی خودکار سلامت؟** | **بررسی خودکار سلامت ندارد.** در کلاینت تنظیم می‌شود | **بررسی خودکار سلامت ندارد.** در کلاینت تنظیم می‌شود | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** |
| **مسیریابی، GLOBAL** | **مسیریابی GLOBAL ندارد.** در کلاینت تنظیم می‌شود | **مسیریابی GLOBAL ندارد.** در کلاینت تنظیم می‌شود | **بله، GLOBAL در اشتراک تعبیه شده است** | **مسیریابی GLOBAL ندارد.** در v2rayN تنظیم می‌شود | **بله، GLOBAL در اشتراک تعبیه شده است** | **بله، GLOBAL در اشتراک تعبیه شده است** | **بله، GLOBAL در اشتراک تعبیه شده است** | **بله، GLOBAL در اشتراک تعبیه شده است** | **بله، GLOBAL در اشتراک تعبیه شده است** | **بله، GLOBAL در اشتراک تعبیه شده است** |
| **کاربرد** | اشتراک عمومی با فرمت استاندارد، بدون تنظیمات یا مسیریابی مخصوص کلاینت؛ فقط شامل فهرست پروکسی‌هاست. مناسب برای Karing، Exclave، Shadowrocket و V2Box (iOS) | همان اشتراک عمومیِ فقط-پروکسی در فرمت Base64 که به‌عنوان گزینه سازگاری برای سایر کلاینت‌ها ارائه می‌شود | اشتراک Clash/Mihomo با بررسی خودکار سلامت تعبیه‌شده برای کلاینت‌های Mihomo: Clash Verge Rev، Clash Mi، Clash Lite، Stash، Clash Meta for Android و FlClash | اشتراک v2rayN با بررسی خودکار سلامت تعبیه‌شده. برای استفاده از انتخاب خودکار، کانفیگ `PolicyGroup` را در پایین فهرست انتخاب کنید | اشتراک v2rayNG با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای Android | اشتراک Streisand با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای iOS | اشتراک Happ با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای PC، iOS و Android | اشتراک V2Box با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای Android؛ نسخه iOS از اشتراک‌های استاندارد استفاده می‌کند | اشتراک v2RayTun با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای Android | اشتراک v2RayTun با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای iOS |
| | | | | | | | | | | |

</details>

  `اشتراک ShadowSocks، Hysteria2، Vmess، Trojan برای لیست‌های سیاه.`

</details>


*اشتراک‌هایی که لیست‌های سیاه RKN را دور می‌زنند.*

---
---

<details>

 <summary><h2> 🧾 <code> پل‌های TOR <img src="https://upload.wikimedia.org/wikipedia/commons/d/df/Tor_Browser_icon_%28New%29.png" width="35" align="absmiddle"> </code></h2></summary>

### TOR BRIDGES — TOP 100: 

### [TOR_BRIDGES_TOP100.txt](https://raw.githack.com/igareck/vpn-configs-for-russia/main/TOR-BRIDGES/TOR_BRIDGES_TOP100.txt)

<details>
<summary> کد QR </summary>

![TOR_BRIDGES_TOP100_GitHack_QR.png](https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/GitHack-proxy/TOR_BRIDGES_TOP100_GitHack_QR.png)

</details>

 `فهرست پل‌ها برای دسترسی به شبکه تور. 100 پل برتر.`

---

### TOR BRIDGES — کامل: 

### [TOR_BRIDGES_ALL.txt](https://raw.githack.com/igareck/vpn-configs-for-russia/main/TOR-BRIDGES/TOR_BRIDGES_ALL.txt)

<details>
<summary> کد QR </summary>

![TOR_BRIDGES_ALL_GitHack_QR.png](https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/GitHack-proxy/TOR_BRIDGES_ALL_GitHack_QR.png)

</details>

 `فهرست پل‌ها برای دسترسی به شبکه تور. فهرست کامل.`

---

### TOR BRIDGES — VANILLA: 

### [TOR_BRIDGES_VANILLA.txt](https://raw.githack.com/igareck/vpn-configs-for-russia/main/TOR-BRIDGES/TOR_BRIDGES_VANILLA.txt)

<details>
<summary> کد QR </summary>

![TOR_BRIDGES_VANILLA_GitHack_QR.png](https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/GitHack-proxy/TOR_BRIDGES_VANILLA_GitHack_QR.png)

</details>

 `فهرست پل‌ها برای دسترسی به شبکه تور. تایپ کنید VANILLA.`

---

### TOR BRIDGES — OBFS4: 

### [TOR_BRIDGES_OBFS4.txt](https://raw.githack.com/igareck/vpn-configs-for-russia/main/TOR-BRIDGES/TOR_BRIDGES_OBFS4.txt)

<details>
<summary> کد QR </summary>

![TOR_BRIDGES_OBFS4_GitHack_QR.png](https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/GitHack-proxy/TOR_BRIDGES_OBFS4_GitHack_QR.png)

</details>

 `فهرست پل‌ها برای دسترسی به شبکه تور. تایپ کنید OBFS4.`

---

### TOR BRIDGES — WEBTUNNEL: 

### [TOR_BRIDGES_WEBTUNNEL.txt](https://raw.githack.com/igareck/vpn-configs-for-russia/main/TOR-BRIDGES/TOR_BRIDGES_WEBTUNNEL.txt)

<details>
<summary> کد QR </summary>

![TOR_BRIDGES_WEBTUNNEL_GitHack_QR.png](https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/GitHack-proxy/TOR_BRIDGES_WEBTUNNEL_GitHack_QR.png)

</details>

 `فهرست پل‌ها برای دسترسی به شبکه تور. تایپ کنید WEBTUNNEL.`

</details>

*فهرست پل‌ها برای دسترسی به شبکه تور. مشابه لیست سیاه.*

---
---

<details>

<summary><h2> 🧾 <code> لیست سفید ⚪ </code></h2></summary>

---

### اشتراک CIDR برای تلفن (۱۵۰ کانفیگ برتر نخست در اشتراک) ⚪: 

<details>
<summary><strong><code> باز کردن </code></strong></summary>

㋡

| | | | | | | | | | | |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **فرمت اشتراک** | **عمومی (فرمت استاندارد)** | **عمومی (فرمت Base64)** | **Clash/Mihomo (PC/iOS/Android)** | **v2rayN (PC)** | **v2rayNG (Android)** | **Streisand (iOS)** | **Happ (PC/iOS/Android)** | **V2Box (Android)** | **v2RayTun (Android)** | **v2RayTun (iOS)** |
| **لینک** | [Vless-Reality-White-Lists-Rus-Mobile](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Vless-Reality-White-Lists-Rus-Mobile.txt&lang=de-de) | [Vless-Reality-White-Lists-Rus-Mobile](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/Base64/PROXIES_ONLY/Vless-Reality-White-Lists-Rus-Mobile-base64.txt&lang=de-de) | [Vless-Reality-White-Lists-Rus-Mobile](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/Clash/GLOBAL/Vless-Reality-White-Lists-Rus-Mobile-clash-global.yaml&lang=de-de) | [Vless-Reality-White-Lists-Rus-Mobile](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/v2rayN_PC/Vless-Reality-White-Lists-Rus-Mobile-v2rayN.txt&lang=de-de) | [Vless-Reality-White-Lists-Rus-Mobile](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/v2rayNG_Android/GLOBAL/Vless-Reality-White-Lists-Rus-Mobile-v2rayNG-global.json&lang=de-de) | [Vless-Reality-White-Lists-Rus-Mobile](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/Streisand_iOS/GLOBAL/Vless-Reality-White-Lists-Rus-Mobile-Streisand-global.json&lang=de-de) | [Vless-Reality-White-Lists-Rus-Mobile](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/Happ/GLOBAL/Vless-Reality-White-Lists-Rus-Mobile-Happ-global.json&lang=de-de) | [Vless-Reality-White-Lists-Rus-Mobile](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/V2Box_Android/GLOBAL/Vless-Reality-White-Lists-Rus-Mobile-V2Box-Android-global.json&lang=de-de) | [Vless-Reality-White-Lists-Rus-Mobile](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/v2RayTun_Android/GLOBAL/Vless-Reality-White-Lists-Rus-Mobile-v2RayTun-Android-global.json&lang=de-de) | [Vless-Reality-White-Lists-Rus-Mobile](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/v2RayTun_iOS/GLOBAL/Vless-Reality-White-Lists-Rus-Mobile-v2RayTun-iOS-global.json&lang=de-de) |
| **کد QR** | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Standard/PROXIES_ONLY/Vless-Reality-White-Lists-Rus-Mobile-standard-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Base64/PROXIES_ONLY/Vless-Reality-White-Lists-Rus-Mobile-base64-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Clash/GLOBAL/Vless-Reality-White-Lists-Rus-Mobile-clash-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2rayN_PC/Vless-Reality-White-Lists-Rus-Mobile-v2rayN-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2rayNG_Android/GLOBAL/Vless-Reality-White-Lists-Rus-Mobile-v2rayNG-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Streisand_iOS/GLOBAL/Vless-Reality-White-Lists-Rus-Mobile-Streisand-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Happ/GLOBAL/Vless-Reality-White-Lists-Rus-Mobile-Happ-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/V2Box_Android/GLOBAL/Vless-Reality-White-Lists-Rus-Mobile-V2Box-Android-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2RayTun_Android/GLOBAL/Vless-Reality-White-Lists-Rus-Mobile-v2RayTun-Android-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2RayTun_iOS/GLOBAL/Vless-Reality-White-Lists-Rus-Mobile-v2RayTun-iOS-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> |
| **بررسی خودکار سلامت؟** | **بررسی خودکار سلامت ندارد.** در کلاینت تنظیم می‌شود | **بررسی خودکار سلامت ندارد.** در کلاینت تنظیم می‌شود | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** |
| **مسیریابی، GLOBAL** | **مسیریابی GLOBAL ندارد.** در کلاینت تنظیم می‌شود | **مسیریابی GLOBAL ندارد.** در کلاینت تنظیم می‌شود | **بله، GLOBAL در اشتراک تعبیه شده است** | **مسیریابی GLOBAL ندارد.** در v2rayN تنظیم می‌شود | **بله، GLOBAL در اشتراک تعبیه شده است** | **بله، GLOBAL در اشتراک تعبیه شده است** | **بله، GLOBAL در اشتراک تعبیه شده است** | **بله، GLOBAL در اشتراک تعبیه شده است** | **بله، GLOBAL در اشتراک تعبیه شده است** | **بله، GLOBAL در اشتراک تعبیه شده است** |
| **کاربرد** | اشتراک عمومی با فرمت استاندارد، بدون تنظیمات یا مسیریابی مخصوص کلاینت؛ فقط شامل فهرست پروکسی‌هاست. مناسب برای Karing، Exclave، Shadowrocket و V2Box (iOS) | همان اشتراک عمومیِ فقط-پروکسی در فرمت Base64 که به‌عنوان گزینه سازگاری برای سایر کلاینت‌ها ارائه می‌شود | اشتراک Clash/Mihomo با بررسی خودکار سلامت تعبیه‌شده برای کلاینت‌های Mihomo: Clash Verge Rev، Clash Mi، Clash Lite، Stash، Clash Meta for Android و FlClash | اشتراک v2rayN با بررسی خودکار سلامت تعبیه‌شده. برای استفاده از انتخاب خودکار، کانفیگ `PolicyGroup` را در پایین فهرست انتخاب کنید | اشتراک v2rayNG با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای Android | اشتراک Streisand با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای iOS | اشتراک Happ با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای PC، iOS و Android | اشتراک V2Box با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای Android؛ نسخه iOS از اشتراک‌های استاندارد استفاده می‌کند | اشتراک v2RayTun با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای Android | اشتراک v2RayTun با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای iOS |
| | | | | | | | | | | |

</details>

`اشتراک سبک و مختصر CIDR برای تلفن و لیست‌های سفید. شامل ۱۵۰ کانفیگ نخست از اشتراک کامل CIDR است؛ اگر اشتراک کامل کمتر از ۱۵۰ کانفیگ داشته باشد، همه آن‌ها را شامل می‌شود. مسدودسازی مبتنی بر IP/CIDR را دور می‌زند. پروتکل VLESS.`

---

### اشتراک کامل CIDR (همه کانفیگ‌ها) ⚪: 

<details>
<summary><strong><code> باز کردن </code></strong></summary>

㋡

| | | | | | | | | | | |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **فرمت اشتراک** | **عمومی (فرمت استاندارد)** | **عمومی (فرمت Base64)** | **Clash/Mihomo (PC/iOS/Android)** | **v2rayN (PC)** | **v2rayNG (Android)** | **Streisand (iOS)** | **Happ (PC/iOS/Android)** | **V2Box (Android)** | **v2RayTun (Android)** | **v2RayTun (iOS)** |
| **لینک** | [WHITE-CIDR-RU-all](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/WHITE-CIDR-RU-all.txt&lang=de-de) | [WHITE-CIDR-RU-all](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/Base64/PROXIES_ONLY/WHITE-CIDR-RU-all-base64.txt&lang=de-de) | [WHITE-CIDR-RU-all](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/Clash/GLOBAL/WHITE-CIDR-RU-all-clash-global.yaml&lang=de-de) | [WHITE-CIDR-RU-all](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/v2rayN_PC/WHITE-CIDR-RU-all-v2rayN.txt&lang=de-de) | [WHITE-CIDR-RU-all](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/v2rayNG_Android/GLOBAL/WHITE-CIDR-RU-all-v2rayNG-global.json&lang=de-de) | [WHITE-CIDR-RU-all](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/Streisand_iOS/GLOBAL/WHITE-CIDR-RU-all-Streisand-global.json&lang=de-de) | [WHITE-CIDR-RU-all](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/Happ/GLOBAL/WHITE-CIDR-RU-all-Happ-global.json&lang=de-de) | [WHITE-CIDR-RU-all](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/V2Box_Android/GLOBAL/WHITE-CIDR-RU-all-V2Box-Android-global.json&lang=de-de) | [WHITE-CIDR-RU-all](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/v2RayTun_Android/GLOBAL/WHITE-CIDR-RU-all-v2RayTun-Android-global.json&lang=de-de) | [WHITE-CIDR-RU-all](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/v2RayTun_iOS/GLOBAL/WHITE-CIDR-RU-all-v2RayTun-iOS-global.json&lang=de-de) |
| **کد QR** | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Standard/PROXIES_ONLY/WHITE-CIDR-RU-all-standard-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Base64/PROXIES_ONLY/WHITE-CIDR-RU-all-base64-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Clash/GLOBAL/WHITE-CIDR-RU-all-clash-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2rayN_PC/WHITE-CIDR-RU-all-v2rayN-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2rayNG_Android/GLOBAL/WHITE-CIDR-RU-all-v2rayNG-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Streisand_iOS/GLOBAL/WHITE-CIDR-RU-all-Streisand-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Happ/GLOBAL/WHITE-CIDR-RU-all-Happ-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/V2Box_Android/GLOBAL/WHITE-CIDR-RU-all-V2Box-Android-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2RayTun_Android/GLOBAL/WHITE-CIDR-RU-all-v2RayTun-Android-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2RayTun_iOS/GLOBAL/WHITE-CIDR-RU-all-v2RayTun-iOS-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> |
| **بررسی خودکار سلامت؟** | **بررسی خودکار سلامت ندارد.** در کلاینت تنظیم می‌شود | **بررسی خودکار سلامت ندارد.** در کلاینت تنظیم می‌شود | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** |
| **مسیریابی، GLOBAL** | **مسیریابی GLOBAL ندارد.** در کلاینت تنظیم می‌شود | **مسیریابی GLOBAL ندارد.** در کلاینت تنظیم می‌شود | **بله، GLOBAL در اشتراک تعبیه شده است** | **مسیریابی GLOBAL ندارد.** در v2rayN تنظیم می‌شود | **بله، GLOBAL در اشتراک تعبیه شده است** | **بله، GLOBAL در اشتراک تعبیه شده است** | **بله، GLOBAL در اشتراک تعبیه شده است** | **بله، GLOBAL در اشتراک تعبیه شده است** | **بله، GLOBAL در اشتراک تعبیه شده است** | **بله، GLOBAL در اشتراک تعبیه شده است** |
| **کاربرد** | اشتراک عمومی با فرمت استاندارد، بدون تنظیمات یا مسیریابی مخصوص کلاینت؛ فقط شامل فهرست پروکسی‌هاست. مناسب برای Karing، Exclave، Shadowrocket و V2Box (iOS) | همان اشتراک عمومیِ فقط-پروکسی در فرمت Base64 که به‌عنوان گزینه سازگاری برای سایر کلاینت‌ها ارائه می‌شود | اشتراک Clash/Mihomo با بررسی خودکار سلامت تعبیه‌شده برای کلاینت‌های Mihomo: Clash Verge Rev، Clash Mi، Clash Lite، Stash، Clash Meta for Android و FlClash | اشتراک v2rayN با بررسی خودکار سلامت تعبیه‌شده. برای استفاده از انتخاب خودکار، کانفیگ `PolicyGroup` را در پایین فهرست انتخاب کنید | اشتراک v2rayNG با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای Android | اشتراک Streisand با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای iOS | اشتراک Happ با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای PC، iOS و Android | اشتراک V2Box با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای Android؛ نسخه iOS از اشتراک‌های استاندارد استفاده می‌کند | اشتراک v2RayTun با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای Android | اشتراک v2RayTun با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای iOS |
| | | | | | | | | | | |

</details>

`اشتراک کامل CIDR برای لیست‌های سفید. شامل همه زیرشبکه‌های سفید شناخته‌شده از ارائه‌دهندگان میزبانی مختلف است. مسدودسازی مبتنی بر IP/CIDR را دور می‌زند. پروتکل VLESS.`

*توجه! گاهی به دلیل حجم، ممکن است برای دستگاه‌های ضعیف سنگین باشد!*

---

### اشتراک CIDR فقط با ارائه‌دهندگان میزبانی: VK، YANDEX، CDNVIDEO، Beeline ⚪:

<details>
<summary><strong><code> باز کردن </code></strong></summary>

㋡

| | | | | | | | | | | |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **فرمت اشتراک** | **عمومی (فرمت استاندارد)** | **عمومی (فرمت Base64)** | **Clash/Mihomo (PC/iOS/Android)** | **v2rayN (PC)** | **v2rayNG (Android)** | **Streisand (iOS)** | **Happ (PC/iOS/Android)** | **V2Box (Android)** | **v2RayTun (Android)** | **v2RayTun (iOS)** |
| **لینک** | [WHITE-CIDR-RU-checked](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/WHITE-CIDR-RU-checked.txt&lang=de-de) | [WHITE-CIDR-RU-checked](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/Base64/PROXIES_ONLY/WHITE-CIDR-RU-checked-base64.txt&lang=de-de) | [WHITE-CIDR-RU-checked](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/Clash/GLOBAL/WHITE-CIDR-RU-checked-clash-global.yaml&lang=de-de) | [WHITE-CIDR-RU-checked](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/v2rayN_PC/WHITE-CIDR-RU-checked-v2rayN.txt&lang=de-de) | [WHITE-CIDR-RU-checked](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/v2rayNG_Android/GLOBAL/WHITE-CIDR-RU-checked-v2rayNG-global.json&lang=de-de) | [WHITE-CIDR-RU-checked](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/Streisand_iOS/GLOBAL/WHITE-CIDR-RU-checked-Streisand-global.json&lang=de-de) | [WHITE-CIDR-RU-checked](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/Happ/GLOBAL/WHITE-CIDR-RU-checked-Happ-global.json&lang=de-de) | [WHITE-CIDR-RU-checked](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/V2Box_Android/GLOBAL/WHITE-CIDR-RU-checked-V2Box-Android-global.json&lang=de-de) | [WHITE-CIDR-RU-checked](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/v2RayTun_Android/GLOBAL/WHITE-CIDR-RU-checked-v2RayTun-Android-global.json&lang=de-de) | [WHITE-CIDR-RU-checked](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/v2RayTun_iOS/GLOBAL/WHITE-CIDR-RU-checked-v2RayTun-iOS-global.json&lang=de-de) |
| **کد QR** | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Standard/PROXIES_ONLY/WHITE-CIDR-RU-checked-standard-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Base64/PROXIES_ONLY/WHITE-CIDR-RU-checked-base64-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Clash/GLOBAL/WHITE-CIDR-RU-checked-clash-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2rayN_PC/WHITE-CIDR-RU-checked-v2rayN-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2rayNG_Android/GLOBAL/WHITE-CIDR-RU-checked-v2rayNG-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Streisand_iOS/GLOBAL/WHITE-CIDR-RU-checked-Streisand-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Happ/GLOBAL/WHITE-CIDR-RU-checked-Happ-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/V2Box_Android/GLOBAL/WHITE-CIDR-RU-checked-V2Box-Android-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2RayTun_Android/GLOBAL/WHITE-CIDR-RU-checked-v2RayTun-Android-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2RayTun_iOS/GLOBAL/WHITE-CIDR-RU-checked-v2RayTun-iOS-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> |
| **بررسی خودکار سلامت؟** | **بررسی خودکار سلامت ندارد.** در کلاینت تنظیم می‌شود | **بررسی خودکار سلامت ندارد.** در کلاینت تنظیم می‌شود | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** |
| **مسیریابی، GLOBAL** | **مسیریابی GLOBAL ندارد.** در کلاینت تنظیم می‌شود | **مسیریابی GLOBAL ندارد.** در کلاینت تنظیم می‌شود | **بله، GLOBAL در اشتراک تعبیه شده است** | **مسیریابی GLOBAL ندارد.** در v2rayN تنظیم می‌شود | **بله، GLOBAL در اشتراک تعبیه شده است** | **بله، GLOBAL در اشتراک تعبیه شده است** | **بله، GLOBAL در اشتراک تعبیه شده است** | **بله، GLOBAL در اشتراک تعبیه شده است** | **بله، GLOBAL در اشتراک تعبیه شده است** | **بله، GLOBAL در اشتراک تعبیه شده است** |
| **کاربرد** | اشتراک عمومی با فرمت استاندارد، بدون تنظیمات یا مسیریابی مخصوص کلاینت؛ فقط شامل فهرست پروکسی‌هاست. مناسب برای Karing، Exclave، Shadowrocket و V2Box (iOS) | همان اشتراک عمومیِ فقط-پروکسی در فرمت Base64 که به‌عنوان گزینه سازگاری برای سایر کلاینت‌ها ارائه می‌شود | اشتراک Clash/Mihomo با بررسی خودکار سلامت تعبیه‌شده برای کلاینت‌های Mihomo: Clash Verge Rev، Clash Mi، Clash Lite، Stash، Clash Meta for Android و FlClash | اشتراک v2rayN با بررسی خودکار سلامت تعبیه‌شده. برای استفاده از انتخاب خودکار، کانفیگ `PolicyGroup` را در پایین فهرست انتخاب کنید | اشتراک v2rayNG با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای Android | اشتراک Streisand با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای iOS | اشتراک Happ با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای PC، iOS و Android | اشتراک V2Box با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای Android؛ نسخه iOS از اشتراک‌های استاندارد استفاده می‌کند | اشتراک v2RayTun با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای Android | اشتراک v2RayTun با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای iOS |
| | | | | | | | | | | |

</details>

`نسخه فیلتر شده از اشتراک کامل CIDR برای ارائه‌دهندگان میزبانی خاص. نسخه کامل کمتر. در این اشتراک کوتاه شده، زیرشبکه‌های سفید فقط از این ارائه‌دهندگان میزبانی روسی: VK، YANDEX، CDNVIDEO و Beeline هستند، و در اشتراک کامل - همه ارائه‌دهندگان میزبانی! مانع مسدودسازی IP توسط CIDR می‌شود. پروتکل VLESS.`

---

### اشتراک SNI ⚪: 

<details>
<summary><strong><code> باز کردن </code></strong></summary>

㋡

| | | | | | | | | | | |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **فرمت اشتراک** | **عمومی (فرمت استاندارد)** | **عمومی (فرمت Base64)** | **Clash/Mihomo (PC/iOS/Android)** | **v2rayN (PC)** | **v2rayNG (Android)** | **Streisand (iOS)** | **Happ (PC/iOS/Android)** | **V2Box (Android)** | **v2RayTun (Android)** | **v2RayTun (iOS)** |
| **لینک** | [WHITE-SNI-RU-all](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/WHITE-SNI-RU-all.txt&lang=de-de) | [WHITE-SNI-RU-all](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/Base64/PROXIES_ONLY/WHITE-SNI-RU-all-base64.txt&lang=de-de) | [WHITE-SNI-RU-all](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/Clash/GLOBAL/WHITE-SNI-RU-all-clash-global.yaml&lang=de-de) | [WHITE-SNI-RU-all](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/v2rayN_PC/WHITE-SNI-RU-all-v2rayN.txt&lang=de-de) | [WHITE-SNI-RU-all](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/v2rayNG_Android/GLOBAL/WHITE-SNI-RU-all-v2rayNG-global.json&lang=de-de) | [WHITE-SNI-RU-all](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/Streisand_iOS/GLOBAL/WHITE-SNI-RU-all-Streisand-global.json&lang=de-de) | [WHITE-SNI-RU-all](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/Happ/GLOBAL/WHITE-SNI-RU-all-Happ-global.json&lang=de-de) | [WHITE-SNI-RU-all](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/V2Box_Android/GLOBAL/WHITE-SNI-RU-all-V2Box-Android-global.json&lang=de-de) | [WHITE-SNI-RU-all](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/v2RayTun_Android/GLOBAL/WHITE-SNI-RU-all-v2RayTun-Android-global.json&lang=de-de) | [WHITE-SNI-RU-all](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/v2RayTun_iOS/GLOBAL/WHITE-SNI-RU-all-v2RayTun-iOS-global.json&lang=de-de) |
| **کد QR** | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Standard/PROXIES_ONLY/WHITE-SNI-RU-all-standard-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Base64/PROXIES_ONLY/WHITE-SNI-RU-all-base64-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Clash/GLOBAL/WHITE-SNI-RU-all-clash-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2rayN_PC/WHITE-SNI-RU-all-v2rayN-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2rayNG_Android/GLOBAL/WHITE-SNI-RU-all-v2rayNG-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Streisand_iOS/GLOBAL/WHITE-SNI-RU-all-Streisand-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Happ/GLOBAL/WHITE-SNI-RU-all-Happ-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/V2Box_Android/GLOBAL/WHITE-SNI-RU-all-V2Box-Android-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2RayTun_Android/GLOBAL/WHITE-SNI-RU-all-v2RayTun-Android-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2RayTun_iOS/GLOBAL/WHITE-SNI-RU-all-v2RayTun-iOS-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> |
| **بررسی خودکار سلامت؟** | **بررسی خودکار سلامت ندارد.** در کلاینت تنظیم می‌شود | **بررسی خودکار سلامت ندارد.** در کلاینت تنظیم می‌شود | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** | **بله، در اشتراک تعبیه شده است** |
| **مسیریابی، GLOBAL** | **مسیریابی GLOBAL ندارد.** در کلاینت تنظیم می‌شود | **مسیریابی GLOBAL ندارد.** در کلاینت تنظیم می‌شود | **بله، GLOBAL در اشتراک تعبیه شده است** | **مسیریابی GLOBAL ندارد.** در v2rayN تنظیم می‌شود | **بله، GLOBAL در اشتراک تعبیه شده است** | **بله، GLOBAL در اشتراک تعبیه شده است** | **بله، GLOBAL در اشتراک تعبیه شده است** | **بله، GLOBAL در اشتراک تعبیه شده است** | **بله، GLOBAL در اشتراک تعبیه شده است** | **بله، GLOBAL در اشتراک تعبیه شده است** |
| **کاربرد** | اشتراک عمومی با فرمت استاندارد، بدون تنظیمات یا مسیریابی مخصوص کلاینت؛ فقط شامل فهرست پروکسی‌هاست. مناسب برای Karing، Exclave، Shadowrocket و V2Box (iOS) | همان اشتراک عمومیِ فقط-پروکسی در فرمت Base64 که به‌عنوان گزینه سازگاری برای سایر کلاینت‌ها ارائه می‌شود | اشتراک Clash/Mihomo با بررسی خودکار سلامت تعبیه‌شده برای کلاینت‌های Mihomo: Clash Verge Rev، Clash Mi، Clash Lite، Stash، Clash Meta for Android و FlClash | اشتراک v2rayN با بررسی خودکار سلامت تعبیه‌شده. برای استفاده از انتخاب خودکار، کانفیگ `PolicyGroup` را در پایین فهرست انتخاب کنید | اشتراک v2rayNG با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای Android | اشتراک Streisand با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای iOS | اشتراک Happ با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای PC، iOS و Android | اشتراک V2Box با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای Android؛ نسخه iOS از اشتراک‌های استاندارد استفاده می‌کند | اشتراک v2RayTun با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای Android | اشتراک v2RayTun با بررسی خودکار سلامت و مسیریابی تعبیه‌شده برای iOS |
| | | | | | | | | | | |

</details>

`فقط مسدودیت SNI را بر اساس یک نام دامنه جعلی SNI دور می‌زند. قفل‌های CIDR دور زده نمی‌شوند. پروتکل VLESS.`

---

</details>


*اشتراک‌هایی که لیست‌های سفید RKN را دور می‌زنند.*

`اشتراک CIDR برای تلفن شماره ۲ Vless-Reality-White-Lists-Rus-Mobile-2.txt به دلیل منسوخ‌شدن از مخزن حذف شد!`

---
---

<details>

<summary><h2> 🧾 <code> آینه‌ها 🪞 </code></h2></summary>

**گزینه‌های متعددی با آینه‌ها برای دسترسی جایگزین به اشتراک‌ها وجود دارد.**

### `روش ۱. مترجم Yandex` 

این در حالت لیست سفید کمک خواهد کرد، زیرا... زیرشبکه‌های Yandex پایدارترین و قابل استفاده‌ترین در حالت لیست سفید هستند. 

*این روش یا با اضافه کردن لینک مستقیماً به کلاینت (Yandex+Bitbucket) کار می‌کند، یا از طریق کپی دستی کانفیگ‌ها از پنجره مرورگر (اتصالات دیگر)!* 

**مترجم Yandex به عنوان یک "پروکسی" در حین حالت لیست سفید عمل می‌کند.**

اگر شما در حالت لیست سفید هستید و GitHub شما مسدود شده است، گزینه‌ای برای به‌روزرسانی هر اشتراک از طریق مترجم Yandex در ۲ روش وجود دارد:

**1. به‌طور خودکار از طریق کلاینت.** **اما توجه! تنها یک آینه Bitbucket از طریق مترجم به‌درستی کار می‌کند:** **Yandex+Bitbucket**! 

**عملکرد کانفیگ‌ها هنگام وارد کردن از طریق Yandex+Bitbucket توسط مشترکین تحت محدودیت‌های تهدید پهپاد در Karing، Clash Mi و v2rayN/v2rayNG آزمایش شده است.**

آینه‌های باقیمانده GitLab/Codeberg/Gitea/SourceHut/Githack، همراه با مترجم Yandex، هنگام بروز رسانی خودکار از طریق کلاینت، کانفیگ‌ها را خراب می‌کنند؛ در این موارد، پارامترهای “sni/security/type/pbk/sid/fp/mode” همیشه ریست می‌شوند. این به طور عمدی توسط توسعه‌دهندگان خود Yandex خراب شده است، زیرا قبل از آن همه چیز کار می‌کرد.

**2. استفاده دستی از روش کپی‌پیست در مرورگر**. در حالت دستی، لینک‌ها از هر منبع GitHub/GitLab/Codeberg/Gitea/SourceHut/Bitbucket/Githack برای Yandex مناسب هستند.

**چگونه خودتان یک لینک Yandex بسازید؟**

✦ **در وب‌سایت** "https://translate.yandex.ru/translate" می‌توانید لینک مورد نظر برای اشتراک RAW را در فیلد «وارد کردن آدرس سایت» درج کنید؛

✦ با استفاده از یک آینه Bitbucket (یا جایگزین‌ها)، **لینک را برای اشتراک وارد کنید** **به جای عبارت "SUBSCRIPTION"** در اینجا:

https://translate.yandex.ru/translate?url=SUBSCRIPTION&lang=de-de و سپس این لینک را در کلاینت (برای حالت خودکار) یا مرورگر (برای حالت دستی) جای‌گذاری کنید!

✦ **از لینک‌های آماده‌ Yandex (Yandex+Bitbucket) زیر استفاده کنید**، که می‌توانید آن‌ها را در یادداشت‌های گوشی یا PC خود ذخیره کرده و در صورت نیاز استفاده کنید. لینک‌ها به Bitbucket در مترجم Yandex قبلاً جایگزین شده‌اند.

از کاربران @AmiFox و @HenonBank برای اشاره اولیه به روش ترجمه Yandex سپاسگزاریم.

---

### `روش ۲. GitLab/Codeberg/Gitea/SourceHut/Bitbucket`

| | | |
|---:|---|---|
| **GitLab** | https://gitlab.com/igareck/vpn-configs-for-russia/ | آینه Git / open-core SaaS |
| **Codeberg** | https://codeberg.org/igareck/vpn-configs-for-russia | آینه Git/FOSS |
| **Gitea** | https://gitea.com/igareck/vpn-configs-for-russia | آینه Git / مبتنی بر FOSS |
| **SourceHut** | https://git.sr.ht/~igareck/vpn-configs-for-russia | آینه Git/FOSS |
| **Bitbucket** | https://bitbucket.org/igareck/vpn-configs-for-russia/ | آینه Git / تجاری |
| | | |

*آینه‌های کامل گیت. پروکسی نیست. یک نسخه از مخزن اصلی روی ۵ سرور جداگانه قرار دارد.*

---

### `روش ۳. GitHack RAW`

| | | |
|---:|---|---|
| **GitHack** | https://raw.githack.com/| پروکسی زنده RAW |
| | | |

*ذخیره‌سازی کش پروکسی زنده برای فایل‌های RAW از GitHub/GitLab/Bitbucket/Gitea/Codeberg.*

برخلاف آینه‌های روش شماره ۲ که نسخه‌های کامل مخزن را روی سرورهای جداگانه خود نگه می‌دارند، گیت‌هک RAW متفاوت است زیرا همیشه هنگام درخواست به مخزن اصلی (در این مورد GitHub) دسترسی پیدا می‌کند و به عنوان پروکسی برای فایل‌های RAW عمل می‌کند.

این روش حتی برای کسانی که هنگام تلاش برای دسترسی به آینه‌های دیگر پیام «شما در حال حاضر از یک آدرس IP یا کشور مسدود شده مشاهده می‌کنید» را دریافت می‌کنند نیز کار می‌کند.

---

**روش ۱ در محدودیت‌های لیست سفید/تهدید پهپاد کمک خواهد کرد.**

**روش‌های ۲ و ۳ تنها در صورت وجود لیست سیاه کمک خواهند کرد. مرتبط است اگر Roskomnadzor جلوی GitHub را بگیرد.**

JSDelivr CDN (https://cdn.jsdelivr.net از طریق CDN) و Githack CDN (https://rawcdn.githack.com از طریق Cloudflare) باید حذف شوند به دلیل اینکه داده‌ها آنجا با تأخیر زیادی کش می‌شوند. 

JSDelivr CDN - طی ۵ تا ۲۴ ساعت. Githack CDN - شکست در زمان می‌تواند تا ۲ هفته طول بکشد.

GitLab/Codeberg/Gitea/SourceHut/Bitbucket/Githack RAW - اطلاعات همیشه به‌روز و بدون تأخیر است.

---

**چه کاری باید انجام داد؟** لینک‌های اصلی RAW را با اشتراک‌های `https://raw.githubusercontent.com/` در کلاینت‌های خود به لینک‌های RAW یکی از آینه‌ها در فهرست زیر (فهرست درست پایین این پست است) جایگزین کنید یا لینک RAW را در وب‌سایت خود آینه‌ها کپی کنید. 

**چگونه یک اشتراک را از آینه دانلود کنیم؟** برای دریافت فایل RAW از آینه، کافی است در آنجا اشتراک txt که به آن علاقه دارید را با همان نام موجود در نسخه اصلی پیدا کنید، روی لینک آن کلیک کنید و در بالای آن دکمه‌ای با برچسب RAW (باز کردن به صورت خام، مشاهده خام، منبع) پیدا کنید، روی دکمه کلیک کرده و لینک را از نوار آدرس کپی کنید. 

---

### `در زیر لینک‌های آماده برای اشتراک‌ها از طریق آینه آمده است.` 

### آنها را در دستگاه خود ذخیره کنید تا در صورت مسدود شدن GitHub یا فعال بودن محدودیت‌های لیست سفید، قابل استفاده باشند.

لینک‌های مترجم Yandex **Yandex+Bitbucket برای حالت لیست سفید** از طریق کلاینت‌ها به‌درستی کار می‌کنند. عملکرد کانفیگ‌های دانلود شده توسط مشترکین تحت محدودیت‌های تهدید پهپاد در Karing و v2rayN/v2rayNG آزمایش شده است. لطفاً توجه داشته باشید که ترکیب Yandex+Bitbucket است که کار می‌کند؛ تمام اتصالات دیگر با Yandex کانفیگ را خراب می‌کنند!

قبل از افزودن، ابتدا در مرورگر خود در دسترس بودن آن را بررسی کنید.

**اگر پیام «شما در حال حاضر از یک آدرس یا کشور مسدود شده مشاهده می‌کنید» را دریافت کردید** - این بدان معنا است که GeoBlock خود آینه کار کرده، بنابراین آینه بعدی را امتحان کنید. 

**گزینه کاری حداکثر** - این **GitHack** (raw.githack.com)، برای تقریبا همه کار می‌کند، زیرا این یک پروکسی است، نه یک شرکت بزرگ؛ و همچنین **SourceHut** (git.sr.ht)، زیرا این یک پروژه کوچک خصوصی است.

**[MIRRORS_LINKS_FULL.txt](https://raw.githack.com/igareck/GoldCaviar/main/Files/MIRRORS_LINKS_FULL.txt)** - **دانلود لیست کامل آینه‌ها در یک فایل TXT** 

فهرست کامل آینه‌ها برای همه قالب‌های اشتراک، در صفحه‌ای جداگانه نیز قرار گرفته است:

#### [⬅️ باز کردن فهرست کامل آینه‌ها](./MIRRORS.md)

</details>

*لینک‌های جایگزین برای دسترسی به اشتراک‌ها در حالت لیست سفید یا در صورت مسدود شدن GitHub.*

---

## <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3bjF5NnEyM21vMjJhd2UxdWphYnQxZGh6bjc1bjBzMG44eDB0Ym03eCZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/dyX9ixfxMpOUGawfdK/giphy.gif" width="50"> `تفاوت بین لیست سیاه و لیست سفید چیست و کدام اشتراک را باید انتخاب کنید؟`


`⬇   PROCEDURE   ⬇`

`ابتدا بیایید بررسی کنیم که آیا اینترنت اصلاً کار می‌کند یا نه: Yandex.ru، خدمات دولتی، VK، Rutube.ru، Sberbank، Mail.ru، Ozon را باز کنید. اگر هیچ‌کدام از این‌ها باز نشد، اینترنت شما اصلاً کار نمی‌کند. (هیچ اتصال وجود ندارد) و هیچ کانفیگ‌ای در اینجا کمک نخواهد کرد! در این صورت، اتصال دستگاه خود را بررسی کنید!`

`اگر ناگهان «اصلاً بارگذاری نمی‌شود»، معمولاً ریست کردن اتصال شبکه کمک می‌کند (راه‌اندازی مجدد): حالت «پرواز» را به مدت ۱۰-۱۵ ثانیه روشن کنید، سپس خاموشش کنید و دوباره تلاش کنید تا متصل شوید - به نتیجه خواهید رسید!`

`توجه داشته باشید که هنگام قطع کامل اینترنت همراه (حتی غیرفعال یا محدود شدن سایت‌های «لیست سفید»)، راه‌اندازی مجدد شبکه کمکی نمی‌کند؛ باید صبر کنید تا دست‌کم سایت‌های «لیست سفید» دوباره در دسترس قرار گیرند، یا از اینترنت سیمی یا Wi-Fi عمومی استفاده کنید.`

### ① `سیاه یا سفید را انتخاب کنید:`  <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3Y3Q4NW94NXo0ZXQwajl1cDRzdHg3ZXFzbWc4aGtzeDA0cGRtNTl2ZSZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/35LH6GkOzEXuw/giphy.gif" width="80">  

| | لیست سیاه / پل‌های TOR (اینترنت استاندارد) | لیست سفید (حداکثر محدود شده) |
|--|--|--|
| **به طور خلاصه** | لیست‌های سیاه زمانی هستند که «هر چیزی که ممنوع نشده باشد، مجاز است» | لیست‌های سفید زمانی هستند که «هر چیزی که مجاز نشده باشد، ممنوع است» |
| **چه نوع اینترنتی؟** | هر کابل + موبایل بدون محدودیت‌های شدید | گوشی همراه با شدیدترین محدودیت‌ها |
| **چه چیزهایی کار می‌کند؟** | اینترنت طبق معمول کار می‌کند: گوگل، App Store، Telegram یا هر سایت/خدمت عادی خارجی که به طور رسمی در روسیه مسدود نشده باشد باز می‌شود | شما اینترنت موبایل دارید و هیچ چیزی کار نمی‌کند جز Yandex.ru، خدمات دولتی، VK، Rutube، Sberbank، Mail.ru، Ozon و سایر سایت‌هایی که توسط RKN تأیید شده‌اند. نه Google.com باز می‌شود، نه GMail، نه App Store، نه Telegram و نه هیچ سایت خارجی دیگری. شما فقط می‌توانید به آن سایت‌های روسی که توسط نهاد نظارتی تأیید شده‌اند، دسترسی داشته باشید و از «لیست‌های سفید» آن‌ها استفاده کنید. یعنی، برای مثال، RKN فقط Yandex و Ozone را تأیید کرده است - شما فقط می‌توانید به Yandex و Ozone بروید و به هیچ جای دیگری دسترسی ندارید. |
| **هدف VPN چیست؟** | به سرویس‌هایی که به طور رسمی در روسیه مسدود شده‌اند مراجعه کنید: مشاهده YouTube با کیفیت 4K، تماس/چت در WhatsApp، وایبر، سیگنال، FaceTime، Facebook، Discord، ارسال پست در Instagram، X(توییتر)، استفاده از LinkedIn، بازی کردن Roblox (بله، Roblox رفع مسدود شده است، اما چه کسی می‌داند فردا چه اتفاقی خواهد افتاد)، استفاده از Telegram، Grok، ChatGPT، Gemini و غیره. | فقط به جایی غیر از Yandex، اسبربانک، خدمات دولتی و VK در طول محدودیت‌ها بروید. از سرویسی استفاده کنید که نیاز چندانی به پینگ و پهنای باند شبکه نداشته باشد: WhatsApp، Telegram، گوگل، هر ایمیل، ویدیوهای YouTube از گوشی شما. برای ترافیک سنگین و بازی‌های آنلاین طراحی نشده است (می‌توانید امتحان کنید، اما نتیجه تضمین‌شده نیست) |
| **توجه** | کانفیگ‌های «لیست سیاه» - در واقع این رایج‌ترین/عمومی‌ترین/بین‌المللی‌ترین گزینه VPN است، فقط با یک پروتکل مدرن! لیست سیاه همچنین سریع‌ترین است، زیرا در شرایط استاندارد کار می‌کند. | کانفیگ‌های «لیست سفید» اساساً یک VPN تخصصی هستند که محدودیت‌های شدید خاص در شرایط فعلی روسیه را دور می‌زند. |
| **چه چیزی را باید انتخاب کنم؟** | اگر اینترنت کابلی دارید، یا اینترنت تلفن همراه بدون محدودیت و وضعیت شما با توضیح در این ستون «چپ» مطابقت دارد، پس نیاز به اشتراک «لیست سیاه» یا «پل‌های TOR» دارید. | اگر اینترنت موبایل دارید، همه چیز محدود است و وضعیت شما با توضیحات ستون «راست» مطابقت دارد، در این صورت به اشتراک «لیست سفید» نیاز دارید |
| **چه پروتکل‌ها و اشتراک‌هایی وجود دارد؟** | مجموعه لیست‌های سیاه بر اساس پروتکل تقسیم‌بندی شده است: **اشتراک Shadowsocks+Hysteria2+Vmess+Trojan** **[BLACK_SS+All_RUS.txt](https://raw.githack.com/igareck/vpn-configs-for-russia/main/BLACK_SS+All_RUS.txt)**، **اشتراک VLESS** **[BLACK_VLESS_RUS.txt](https://raw.githack.com/igareck/vpn-configs-for-russia/main/BLACK_VLESS_RUS.txt)**، همچنین یک اشتراک فشرده TOP 150 برای تلفن‌ها **[BLACK_VLESS_RUS_mobile.txt](https://raw.githack.com/igareck/vpn-configs-for-russia/main/BLACK_VLESS_RUS_mobile.txt)** (VLESS در نام صرفاً اصلی است، در واقع ترکیبی TOP 150 از تمام کانفیگ‌های موجود است) |  پروتکل اینجا اساساً **VLESS** است، که به وسیله **4 اشتراک CIDR** تقسیم شده است: 1 **[WHITE-CIDR-RU-all.txt](https://raw.githack.com/igareck/vpn-configs-for-russia/main/WHITE-CIDR-RU-all.txt)** کامل + 1 فشرده برای تلفن‌ها **[Vless-Reality-White-Lists-Rus-Mobile.txt](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Vless-Reality-White-Lists-Rus-Mobile.txt)** + 1 اضافی **[WHITE-CIDR-RU-checked.txt](https://raw.githack.com/igareck/vpn-configs-for-russia/main/WHITE-CIDR-RU-checked.txt)** (محدودیت‌های CIDR روی محدوده‌های IP اکنون برای 100٪ اپراتورهای موبایل روسیه که لیست سفید را معرفی می‌کنند، اعمال می‌شود)؛ و همچنین **1 اشتراک SNI** **[WHITE-SNI-RU-all.txt](https://raw.githack.com/igareck/vpn-configs-for-russia/main/WHITE-SNI-RU-all.txt)** (محدودیت‌ها روی دامنه‌های جعلی سفید SNI، که دیگر برای دور زدن لیست سفید کار نمی‌کند، بلکه تنها در مواقع اضطراری) |

---

### ② `زیر شرایط معمول لیست سیاه ⚫:` 

**[VLESS موبایل] • [VLESS کامل] • [SHADOWSOCKS+ALL کامل] • [Shadowsocks ضعیف DPI]**

**[پل‌های TOR کامل] • TOP 100 • VANILLA • OBFS4 • WEBTUNNEL**

<details>
<summary><em><code> برای جزئیات روی فلش کلیک کنید </code></em></summary>

㋡

#### `الف) VLESS موبایل • VLESS • SHADOWSOCKS+ALL`

برای لیست‌های سیاه معمولی، اشتراک موبایل سبک‌شده **[BLACK VLESS Mobile](#---black-list--)** را انتخاب کنید؛ این اشتراک ترکیبی TOP 150 از دو اشتراک **VLESS** و **SHADOWSOCKS+ALL** است. همچنین می‌توانید اشتراک‌های کامل تفکیک‌شده بر اساس پروتکل، یعنی **[BLACK VLESS](#---black-list--)** یا **[BLACK SHADOWSOCKS+ALL](#---black-list--)** را انتخاب کنید؛ این اشتراک‌ها شامل Shadowsocks، Hysteria2، Trojan و Vmess هستند. 

**بسته به کلاینت، فرمت اشتراک را انتخاب می‌کنیم: استاندارد، Clash یا فرمت ویژه برای یک کلاینت خاص**.

**BLACK VLESS** و **BLACK SHADOWSOCKS+ALL** ممکن است بیش از ۱۵۰ کانفیگ از اشتراک موبایل داشته باشد (مثل **BLACK VLESS Mobile**). تعداد زیادی می تواند هنگام بررسی فشار زیادی روی دستگاه شما وارد کند. و گزینه TOP 150 موبایل همیشه سبک است، دستگاه را با پینگ سنگین بیش از حد بارگذاری نمی کند، که بهترین گزینه برای گوشی هاست.

در اشتراک تلفنی سال TOP 150 **BLACK VLESS Mobile** - کلمه «VLESS» در عنوان نمادین است (از زمان ایجاد مخزن وجود دارد)، در واقع این ترکیبی TOP 150 از تمام کانفیگ‌ها/پروتکل های موجود برای لیست‌های سیاه است.

————

#### `ب) Shadowsocks Weak DPI`

اشتراک جدید ShadowSocks بدون مخفی‌سازی و افزونه‌ها برای لیست‌های سیاه **[BLACK_SS_WEAK_DPI_RUS.txt](https://raw.githack.com/igareck/vpn-configs-for-russia/main/BLACK_SS_WEAK_DPI_RUS.txt)**

طراحی شده برای استفاده در شبکه‌هایی با امنیت ضعیف DPI یا سطوح فیلترینگ کاهش یافته.

شبکه‌های اپراتورهای منطقه‌ای کوچک، عمدتاً کابلی، توصیه می‌شود. اپراتورهای موبایل بزرگ سراسر روسیه، مانند مگافون، MTS، بی‌لین، احتمالا کار نخواهد کرد: یعنی آنها می‌توانند ShadowSocks را بدون مخفی‌سازی پینگ کنند، اما ترافیک عبور نخواهد کرد و سایت‌ها بارگذاری نمی‌شوند. اپراتورهای منطقه‌ای کابلی در این زمینه ساده‌تر هستند؛ هر گونه اشتراک برای آنها بهتر کار می‌کند.

شما نیاز دارید DNS-over-HTTPS را در روتر یا در تنظیمات کارت شبکه PC کانفیگ کنید. بدون DoH، ترافیک ممکن است مسدود شود حتی اگر پینگ‌های کانفیگ با موفقیت تایید شوند.

عملکرد تضمین نمی‌شود و ممکن است بسته به اپراتور متفاوت باشد.

————

#### `ج) TOR BRIDGES کامل  •  TOP 100  •  VANILLA • OBFS4 • WEBTUNNEL`

یک جایگزین عملی برای لیست‌های سیاه VPN - پل‌ها **[پل‌های TOR](#---tor-bridges--)**. 

عملکرد مشابه با لیست سیاه VPN دارد، با تنها یک تفاوت - دسترسی به شبکه از طریق شبکه جهانی استاندارد (به اصطلاح Clearnet) انجام نمی‌شود، بلکه از طریق شبکه Tor انجام می‌شود. بریج‌ها پروکسی هستند، زیرا اتصالات IP استاندارد ساخته‌شده در Tor Browser توسط Roskomnadzor (RKN) مسدود شده‌اند.

می‌توانید از بریج‌های Tor از طریق Tor Browser، کلاینت Tor OnionHop V3 (PC/لپ‌تاپ)، کلاینت Tor OnionFruit (PC/لپ‌تاپ)، همچنین Orbot (تلفن) یا Invizible Pro (تلفن) استفاده کنید، که به عنوان کلاینت روی دستگاه Windows/macOS/iOS/Android عمل می‌کنند.

توضیح، نکات ظریف وجود دارد: اگر از پل‌های Tor استفاده کنید و ترافیک خود را از طریق کلاینت‌ها به تونل Tor تبدیل کنید، تنها جریان‌های TCP کار خواهند کرد، اتصال‌های UDP تحت هیچ شرایطی کار نخواهند کرد، زیرا معماری خود Tor اجازه عبور UDP را نمی‌دهد. 

برخی برنامه‌ها حتی در صورت نبود UDP نیز 100٪ کار خواهند کرد، اگر کاهش سطح TCP را فراهم کند. به عنوان مثال، این دقیقاً نحوه کار Telegram است. (تا اخیراً کاهش سطح TCP کار می‌کرد، اکنون نیاز به بررسی داریم).

**این چگونه بر عملکرد تأثیر خواهد گذاشت؟** 

a) **مرورگرها** - تقریباً هیچ تاثیری نخواهند داشت، زیرا در بیشتر موارد به جریان‌های TCP متصل هستند و همه چیزهایی که در آن‌ها اتفاق می‌افتد به طور عادی و معمولی بارگذاری خواهد شد.

b) **برنامه‌ها**، که به اتصالات UDP متصل هستند، مانند Discord یا Steam، بخشی از عملکرد خود را از دست خواهند داد. کدام یک؟ 

c) متون/تصاویر/ویدئوها/فایل‌های **Discord** در پیام‌ها ارسال خواهند شد، همه چیز مانند یک پیام‌رسان معمولی است، اما صدا/ویدئو/پخش زنده و تماس‌ها ممکن است انجام نشوند، زیرا «آنلاین» به ترافیک UDP متصل است. اما دوباره - همه چیز توسط جایگزین TCP تصمیم‌گیری می‌شود اگر کار کند.

**Telegram** - همه چیز مانند یک VPN معمولی کار خواهد کرد اگر P2P را برای تماس‌ها در تنظیمات پیکربندی کنید. قابلیت بازگشت به TCP در تماس‌ها اینجا به‌طور عادی کار می‌کند. گفت‌وگوها، پیام‌رسانی (متن/تصویر/ویدئو/فایل‌ها) بدون تنظیمات اضافی به‌خوبی کار می‌کنند. 

> نکته‌ای در مورد تماس‌ها وجود دارد!
> 
> اگر تماس از طریق سرورهای Telegram انجام شود (معمولاً با تنظیمات استاندارد)،
> در این صورت تماس یک جریان آنلاین UDP خواهد بود و برقرار نخواهد شد.
> 
> اما اگر P2P را در تنظیمات Telegram فعال کنید: `Privacy - Calls - use peer-to-peer`
> برای همه یا مخاطبین انتخاب شده،
> سپس TCP-fallback کار خواهد کرد و تماس‌ها از طریق Tor انجام خواهند شد! بررسی شد!
> 
> به‌روزرسانی: ممکن است این روش با P2P در تنظیمات دیگر کار نکند، بنابراین آن را به‌صورت محلی بررسی کنید.

**Steam**، به‌طور خاص، باز خواهد شد و بازی اجرا می‌شود، اما در خود بازی سرورهای آنلاین بارگذاری نخواهند شد، زیرا همه چیز مرتبط با «آنلاین» به UDP متصل است. 

> فقط خرید/دانلود یک بازی و بازی کردن آفلاین روی یک PC مشکلی ندارد، زیرا... این اتفاق به‌صورت محلی روی PC شما رخ می‌دهد.

اما این به این معنا نیست که این در مورد همه برنامه‌ها صدق می‌کند. برنامه‌هایی وجود دارند که فقط برای ترافیک TCP هستند، مانند کلاینت‌های ایمیل، کلاینت‌های SSH (ابزارهای Git در حالت SSH)، کلاینت‌های SQL، کلاینت‌های FTP/FTPS، کلاینت‌های پایگاه داده و غیره.

### `ترکیب «پل‌های Tor» + کلاینت Tor «OnionHop V3» یا «OnionFruit»`

<details>

<summary><em><code> باز کردن </code></em></summary> 

㋡

یک VPN، به‌ویژه یک VPN عمومی، همیشه در ترافیک محدود است و علاوه بر آن در معرض حملات توسط Roskomnadzor نیز قرار دارد. نتیجه این است که کانفیگ‌ها باید به‌طور مداوم به‌روزرسانی شوند و اغلب اتصال تغییر کند. برای تغییر خودکار کانفیگ‌ها بدون تغییر دستی، از Karing یا کلاینت‌هایی برای اشتراک‌های Clash استفاده کنید.

#### آیا جایگزینی وجود دارد، چیزی پایدار به غیر از VPN؟ - بله!

#### من یک راه‌حل عملی برای شما دارم: «پل‌های تور» + «OnionHop V3» یا «OnionFruit».
#### من یک راهنمای گام‌به‌گام برای شما آماده کرده‌ام، همه لینک‌های دانلود کلاینت موجود است (راهنما بر اساس نسخه V2 ساخته شده است، بعداً به V3 به‌روزرسانی می‌کنم، اما در کل همه چیز مشابه است).

| | |
|---:|---|
|**پل‌های تور، برای کارگران فدراسیون روسیه**|https://github.com/igareck/vpn-configs-for-russia/tree/main/TOR-BRIDGES|
|**کلاینت تور OnionHop V3**|https://github.com/center2055/OnionHop/releases|
|**کلاینت تور OnionFruit**|https://github.com/dragonfruitnetwork/onionfruit/releases|
|**راهنمای تلگراف (اصلی)**|**[OnionHop V2 - مرور کوتاه کلاینت تور برای PC](https://telegra.ph/OnionHop-V2--kratkij-obzor-Tor-klienta-dlya-PK-04-04)**|
|**راهنمای ماشین زمان WayBack (آینه)**|**[OnionHop V2 - مرور کوتاه کلاینت تور برای PC](https://web.archive.org/web/https://graph.org/OnionHop-V2--kratkij-obzor-Tor-klienta-dlya-PK-04-04)**|
| | |

*هنگام استفاده از یک آینه برای خواندن یک راهنما، از دنبال کردن لینک‌های خودکار خودداری کنید و متن را به صورت دستی کپی کرده و در تب بعدی جای‌گذاری کنید، زیرا لینک‌ها در آینه به لینک‌های همان آینه منتهی می‌شوند و نه مستقیماً به گیت‌هاب.*

**این به طور مشابه با طرح عمل می‌کند: «کانفیگ‌ها VPN» + «کلاینت VPN».**

**تا چه مدت فعال می‌ماند؟ اتصال برای چندین روز قطع نمی‌شود یا تا زمانی که خودتان آن را قطع کنید.** 

حداکثر زمانی که بدون وقفه داشتم ۷ روز بود و آن را خاموش کردم فقط به این دلیل که نیاز داشتم PC را ریستارت کنم. 

برخی پل‌های جداگانه برای چندین سال در حال کار بوده‌اند! این است ثبات!

همه چیز همانند یک VPN معمولی کار می‌کند، فقط این است که تمام ترافیک روی PC شما به شبکه تور تبدیل می‌شود. 

**تفاوت با مدل استاندارد Tor Browser** این است که نه تنها Tor Browser به‌صورت جداگانه، بلکه **کل PC از طریق Tor اجرا می‌شود**: همه مرورگرها و برنامه‌ها، از جمله پیام‌رسان‌ها (WhatsApp، Telegram) پیام‌ها و فایل‌ها را ارسال/دریافت می‌کنند.

در فایل Readme نوشتم که یک نکته در معماری Tor وجود دارد: اتصالات TCP کار می‌کنند، اما اتصالات UDP کار نمی‌کنند. 

**`این نکات ظریف چیست و چه تأثیری خواهند داشت؟`**

```diff

> Using any messenger as an example:
Messages, files, text, video, audio are all sent, everything works as usual. 

But there is a nuance with calls!

If the call goes through WhatsApp/Telegram servers (usually this is with standard settings),
then the call in this case is a UDP online stream and will not go through.

But if you enable P2P in Telegram settings: `Privacy - Calls - use peer-to-peer`
for all or selected contacts,
then TCP-fallback will work and calls will work through Tor! Checked!

- UPD: this method with P2P in the Telegram settings may no longer work, so check it locally.

> Using Steam as an example:
The application itself is updated, the game starts, but the list of online servers will not load,
because any online activity is an UDP stream.
Just buying/downloading a game and playing offline on a PC is fine, because... this happens locally on your PC.

```

**بیشتر ویژگی‌ها**: هر مرورگری، YouTube، Instagram، Facebook، شبکه‌های اجتماعی، مکاتبات، تبادل فایل، چت‌ها، پیام‌رسان‌های فوری (WhatsApp، Telegram، Signal، Viber، Facetime، Discord)، هوش مصنوعی (Google Gemini، ChatGPT، Grok) **آن‌ها به همان روش با کانفیگ‌های VPN کار می‌کنند و اتصال به‌طور کامل قطع نمی‌شود.**

**نتیجه‌گیری: اگر به یک VPN پایدار روی PC نیاز دارید، پس «Tor Bridges» + «OnionHop V3» یا «OnionFruit» راه‌حل شما است.**

**در حال حاضر راه‌حل رایگان پایدارتر و ساده‌تر پیدا نخواهید کرد.** 

برای دستگاه‌های موبایل از **Orbot** یا **Invizible Pro** استفاده کنید. اطلاعات دقیق در بخش «برنامه‌ها» موجود است.

---

</details>

### آیا خود TOR امن است؟

<details>
<summary><em><code> باز کردن </code></em></summary> 

㋡

TOR ایمن‌تر از حتی پیچیده‌ترین VPN پولی است، به این دلیل که اتصال شما از طریق ۳ سرور عبور می‌کند: 

**`کامپیوتر شما در شبکه شماست`** ➞ **`اتصال از طریق پل‌های Tor (سرور شماره ۱)`** ➞ **`Server #2`** ➞ **`Server #3`** ➞ **`دسترسی به شبکه Tor (اینترنت)`**

سرور اول IP سرور سوم را نمی‌بیند و سرور سوم IP سرور اول را نمی‌بیند. امنیت شبکه Tor بر اساس همین معماری ساخته شده است، تا کاربران در کشورهایی با سانسور شدید مجبور نباشند نگران نظارت دیجیتال باشند.

**فقط TOR را روی کامپیوتر خود فعال کنید و فراموش کنید که Roskomnadzor و محدودیت‌ها وجود دارند!**

</details>

</details>

---

### ③ `تحت محدودیت‌های لیست سفید ⚪: اشتراک CIDR یا اشتراک SNI`

**[اشتراک کامل CIDR] • [TOP 150 برای تلفن]**

**[فقط با ارائه‌دهندگان میزبانی: VK، YANDEX، CDNVIDEO، Beeline] • اشتراک SNI**

<details>
<summary><em><code> برای جزئیات روی فلش کلیک کنید </code></em></summary>

㋡

#### `الف) اشتراک کامل CIDR • TOP 150 برای تلفن • فقط با ارائه‌دهندگان میزبانی: VK، YANDEX، CDNVIDEO، Beeline`
  
  سخت‌ترین مسدودسازی روی آی‌پی‌های سفید (باندهای CIDR) حالا فقط روی اپراتورهای موبایل Megafon، Beeline، MTS، T2، Yota و غیره، بنابراین `کانفیگ‌های دارای IP سفید/روسی (از محدوده‌های CIDR سفید/روسی) را که از شدیدترین محدودیت‌های اینترنت همراه عبور می‌کنند، در اشتراک‌های TXT قرار داده‌ام که نامشان با` **[اشتراک CIDR](#---white-list--)** و در یادداشت‌ها برای هر کانفیگ با `[*CIDR]` علامت‌گذاری شده است.

**بسته به کلاینت، فرمت اشتراک را انتخاب کنید: استاندارد یا کلاش**.
  
  این کانفیگ‌ها، البته، در شرایط عادی همراه با لیست‌های سیاه کار خواهند کرد، اما نباید این کار را انجام دهید! چرا؟ فقط به این دلیل که آنها را به خاطر افرادی که واقعاً به آنها نیاز دارند و ماه‌ها در مناطقی با اینترنت محدود زندگی می‌کنند، بارگذاری نکنید! از کانفیگ‌ها CIDR فقط زمانی استفاده کنید که واقعاً به آنها نیاز دارید!

⚡ اشتراک CIDR یک راه‌حل عمومی (نه ۱۰۰٪ فردی) برای دور زدن محدودیت‌ها است. یک قسمت از کانفیگ‌ها ممکن است کار کند، قسمت دوم ممکن است بخش دیگری داشته باشد و قسمت سوم ممکن است بخش سومی داشته باشد. چرا؟ از اپراتوری به اپراتور دیگر، از منطقه‌ای به منطقه دیگر، مسدودسازی متفاوت است، «ساب‌نت‌های سفید» واقعاً کارآمد نیز برای هر کس متفاوت است و همه چنین ساب‌نت‌هایی را ندارند، و فقط خود شما می‌توانید بررسی کنید چه چیزی به‌طور خاص برای شما مناسب است. گاهی پیش می‌آید که در برخی مناطق حتی «ساب‌نت‌های سفید» اثبات‌شده و کارآمد پس از شناسایی فعالیت غیرعادی روی آدرس‌های آی‌پی فردی، غیرفعال می‌شوند. امتحان کنید، بررسی کنید، تجربه خود را به اشتراک بگذارید.

⚡ گاهی اوقات، علاوه بر VLESS، اشتراک کامل CIDR شامل پروتکل‌هایی مانند Trojan، Shadowsocks، Hysteria2 می‌شود. بررسی کنید - آنها در انتهای لیست قرار دارند.

⚡ در حالت «لیست سفید»، سعی کنید از سایت‌های موجود در «لیست سفید Roskomnadzor» از طریق کانفیگ‌ها اشتراک CIDR دسترسی پیدا نکنید، این می‌تواند یکی از دلایل ممنوعیت آینده آنها باشد! اگر نیاز به ورود دارید، برای مثال در VKontakte، VPN را خاموش کرده و فقط سپس وارد شوید!
  
#### `ب) اشتراک SNI`
  
  کانفیگ‌هایی که از مسدودسازی لیست سفید سبک SNI عبور می‌کنند (فقط با نام دامنه)، من آن را در اشتراک TXT **[اشتراک SNI](#---white-list--)** قرار داده‌ام. این‌ها در یادداشت‌های هر کانفیگ به عنوان `[SNI-RU]` علامت‌گذاری شده‌اند، همه SNIها نیز برای راحتی امضا شده‌اند.

  در حال حاضر، بلوک‌های SNI توسط اپراتورهای تلفن همراه استفاده نمی‌شوند به دلیل سهولت عبور از آن‌ها، زیرا تقریباً هر کسی می‌تواند سرور خود را در خارج با دامنه فیک در لیست سفید اجاره و راه‌اندازی کند.

  **اشتراک SNI** در حال حاضر **می‌تواند به‌طور ایمن به عنوان لیست سیاه استفاده شود**، زیرا تحت شرایط فعلی از رژیم لیست سفید عبور نمی‌کند.

  *به‌روزرسانی: اکنون اشتراک SNI به طور خودکار به لیست سیاه اضافه می‌شود تا قابلیت استفاده بیشتری داشته باشد.*

  </details>

---

## <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3Yml0MndhcDZ6dzFuYjY3aG0yNWowN2Rqbnp1aTV2cXNvb3FvMnluMiZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/MxryCOQuSYVVD0SPyp/giphy.gif" width="40"> `چگونه می‌توانم از این کانفیگ‌ها روی دستگاه خود استفاده کنم؟` 

### `دستورالعمل‌ها و توصیه‌های عمومی:`

1) **ابتدا گزینه اشتراک لیست سیاه یا لیست سفید `➞` را انتخاب کنید، سپس نوع آن (موبایل، کامل، و غیره) `➞` را انتخاب کنید. سپس، بسته به کلاینت، فرمت اشتراک را انتخاب کنید: عمومی (استاندارد)، Clash یا فرمت ویژه برای یک کلاینت خاص (v2rayN، v2rayNG، Happ، Streisand، v2rayTun، V2Box).**

۲) **به شدت توصیه می‌شود از ترکیب اشتراک‌ها/کلاینت‌هایی استفاده کنید که دارای عملکرد بررسی سلامت خودکار در پس‌زمینه باشند.** برای چه هدفی؟ همه کانفیگ‌های عمومی تمایل دارند در غیرمنتظره‌ترین لحظه از کار بیفتند، گاهی کمتر و گاهی بیشتر. برای اینکه مجبور نباشید کل فهرست را بی‌پایان پینگ کنید و دائم دنبال بهترین کانفیگ بگردید، باید اشتراک‌ها/کلاینت‌های مناسبی در دست داشته باشید که این کار را به صورت خودکار برای شما انجام دهند. در بیشتر موارد این از طریق چیزی به نام بالانسر انجام می‌شود، اما نام آن ممکن است متفاوت باشد.

### `ترکیب‌های توصیه شده «اشتراک + کلاینت» با بررسی سلامت خودکار:`

| | | |
|:---:|:---:|:---:|
| **①** | **②** | **③** |
| **`فرمت عمومی (استاندارد)` (از رشته‌های معمولی vless://، ss://، trojan:// و غیره با پسوند .TXT)** | **`فرمت اشتراک Clash` (اشتراک با پسوند .YAML)** | **`فرمت برای یک برنامه کلاینت جداگانه` (اشتراک با پسوند .JSON)** |
| **➕** | **➕** | **➕** |
| **`کلاینت Karing (PC/iOS/Android), Shadowrocket(iOS), V2Box(iOS), Exclave(Android)`** | **`کلاینت‌های سازگار با Mihomo/Clash`: Clash Verge Rev، Clash Mi، Clash Lite، Stash - پروکسی مبتنی بر قوانین، ClashMetaForAndroid، FlClash** | **`خود کلاینت: v2rayN(txt)، v2rayNG، Happ، Streisand، v2rayTun، V2Box(Android)`** |
| *اتوماسیون در خود کلاینت تنظیم می‌شود، یعنی V **Karing**، Shadowrocket، Exclave یا V2Box(iOS)* | *اتوماسیون می‌تواند یا در خود کلاینت تنظیم شود (که برای کاربر متوسط دشوارتر است)، یا با اشتراک ارائه می‌شود (توصیه شده و نیازی به اقدام ندارد). در مخزن Igareck، تمام بررسی سلامت خودکار و تنظیمات مسیریابی از قبل با اشتراک‌های Clash برای راحتی ارائه شده‌اند* | *در مخزن Igareck، همه تنظیمات خودکار تأیید و مسیریابی قبلاً در چنین اشتراک‌هایی قرار داده شده‌اند. این اشتراک‌ها یک گزینه «یک دکمه‌ای» خودکار هستند: وارد شده، به‌روزرسانی خودکار هر ساعت یک بار تنظیم شده، راه‌اندازی شده، سرورها خودشان در پس‌زمینه تغییر یافته و بررسی می‌شوند. مشکل حل شد - آن‌ها فقط دوباره متصل شدند، همین. یک دکمه بدون فهرست‌های بلند و بالا* |
| | | |

### `پایدارترین ترکیب‌ها عبارت‌اند از اشتراک‌های Clash/YAML همراه با کلاینت‌های Mihomo، و اشتراک‌های استاندارد همراه با Karing.`

3) راحت‌ترین روش برای افزودن کانفیگ‌های VPN روی دستگاه شما از طریق `new profile`، `add profile`، `subscription` یا `subscription group` در Karing، Clash Verge Rev، Clash Mi، ClashMetaForAndroid، v2rayN، Throne، v2rayNG، Streisand، Happ و دیگران است.

۴) URL فایل TXT/YAML را از GitHub کپی کنید. مطمئن شوید که این یک لینک RAW باشد و نه لینک معمولی! پس از کپی کردن لینک، در برنامه باید روی `Add from clipboard` کلیک کنید یا از دکمه معمولی `Add` ➞ `Configure manually` ➞ نوع `Subscription` را وارد کنید ➞ یک لینک RAW به فایل TXT/YAML قرار دهید و به اشتراک‌گذاری یک نام بدهید.

۵) **اگر راحت‌تر است، کد QR اشتراک را اسکن کنید**. کد QR حتی ساده‌تر است: روی دکمه‌ای در گوشی خود فشار دهید `Add` ➞ `Scan QR code` ➞ برنامه/کلاینت با استفاده از دوربین، کد QR را اسکن کرده و خود به خود یک اشتراک ایجاد می‌کند، شما فقط باید نام آن را در گوشی تغییر داده و اگر لیست کانفیگ‌ها بلافاصله بارگذاری نشد، روی دکمه "Update" کلیک کنید.
   
   کدهای QR برای کانفیگ‌های VPN درست زیر لینک اشتراک قرار دارند (بخش "دانلود کانفیگ‌های VPN").

   کدهای QR برای پل‌های Tor نیز زیر لینک اشتراک قرار دارند، اما شما باید روی فلش با برچسب "کد QR" کلیک کنید.
   
6) **چگونه بررسی کنیم که کدام کانفیگ‌ها/سرورها در حال حاضر فعال و در حال کار هستند؟**

   روی همه اشتراک‌ها (روی نام گروه) یا یک تنظیم جداگانه کلیک کنید، معمولاً باید فشار داده و نگه دارید - یک منو ظاهر می‌شود، انتخاب کنید **توجه!** **`آزمون تأخیر واقعی`**، **`Delay`** یا **`Url Test`**! نه "TCP Ping" و نه "ICMP Ping" - آن‌ها در دسترس بودن واقعی سرور VPN را نشان نمی‌دهند. آن‌هایی که با اعداد سبز پاسخ دادند - آن‌ها را انتخاب کنید. اعدادی با کمترین مقدار را انتخاب کنید، زیرا... هر چه عدد کمتر باشد، تأخیر کمتر است و سرور سریع‌تر به درخواست‌های شما «پاسخ» می‌دهد.

۷) **به شدت توصیه می‌شود به‌روزرسانی خودکار اشتراک‌ها را هر ۱-۲ ساعت فعال کنید**. کانفیگ‌ها به طور مکرر به‌روزرسانی می‌شوند زیرا... با گذشت زمان ممکن است دیگر کار نکنند. بنابراین با فعال کردن این به‌روزرسانی، نسخه جدید اشتراک با کانفیگ‌های کارآمد بدون «زباله»های غیرضروری در اختیار شما خواهد بود.

۸) کانفیگ‌ها، به ویژه آن‌هایی که از لیست‌های سفید هستند، ممکن است هنگام بررسی «زمان پاسخ واقعی» فوراً سبز نشوند؛ بسیار اوقات پینگ‌ها ۲-۳-۴ بار سرورهای جدید موجود را نشان می‌دهند.

۹) چند کلاینت مختلف را روی گوشی خود دانلود کنید - ممکن است اتفاق بیفتد که کلاینت‌های مختلف سرورهای موجود متفاوتی را نشان دهند. این به دلیل تفاوت در کانفیگ‌ها کلاینت هنگام بررسی کانفیگ‌ها است.

۱۰) شما همچنین می‌توانید همه چیز را به صورت دستی و جداگانه اضافه کنید، فقط با کپی کردن محتوای فایل TXT/YAML به کلاینت‌های Karing/Throne/v2rayN، اما اشتراک‌ها راحت‌تر هستند زیرا پس از به‌روزرسانی در گیت‌هاب، به‌طور خودکار روی دستگاه شما به‌روزرسانی می‌شوند، بدون نیاز به حذف و کپی دوباره، که روند را ساده‌تر می‌کند.

---

## 🧾 `دستورالعمل برای هر کلاینت به صورت جداگانه`


<details>
<summary><strong><code> راهنمای OnionHop V3 </code></strong> ⬅ برای باز کردن کلیک کنید </summary>

---

### `OnionHop V3`

راهنما مطابق نسخه V2 ساخته شده است، من بعداً به V3 به‌روزرسانی خواهم کرد، اما به طور کلی همه چیز مشابه است.

**[OnionHop V2 - مرور کوتاه بر کلاینت Tor برای PC (اصلی، قابل دسترسی از طریق VPN یا Tor)](https://telegra.ph/OnionHop-V2--kratkij-obzor-Tor-klienta-dlya-PK-04-04)**

**[OnionHop V2 - مرور کوتاه بر کلاینت Tor برای PC (آینه)](https://web.archive.org/web/https://graph.org/OnionHop-V2--kratkij-obzor-Tor-klienta-dlya-PK-04-04)**

---

</details>


<details>
<summary><strong><code> راهنمای Karing </code></strong> ⬅ برای باز کردن کلیک کنید </summary>

---

### `Karing` 

https://github.com/KaringX/karing/blob/main/README_ru.md

**[Karing – شروع سریع بخش ۱ (اصلی، قابل دسترسی از طریق VPN یا Tor)](https://telegra.ph/Karing-Part1-02-16)**

**[Karing – شروع سریع بخش ۱ (آینه)](https://web.archive.org/web/https://graph.org/Karing-Part1-02-16)**

**[Karing – شروع سریع قسمت 2 (نسخه اصلی، قابل دسترسی از طریق VPN یا Tor)](https://telegra.ph/Karing-Part2-02-15)**

**[Karing – شروع سریع قسمت 2 (آینه)](https://web.archive.org/web/https://graph.org/Karing-Part2-02-15)**

*از کاربر @Pupkin Vasya برای راهنمای مفصل روسی شده ارائه‌شده تشکر می‌کنیم.*

<details>
<summary><strong><code> حل مشکل «پینگ هست، اما سرعت نیست» یا «بارگذاری بی‌پایان» در Karing </code></strong> ⬅ برای باز کردن کلیک کنید </summary>

㋡

```diff
به مسیر "Settings" ⚙️ → "DNS" → "Server" بروید، سپس روی "Traffic Proxy" کلیک کنید و تیک همه گزینه‌ها را بردارید، به‌جز:

https://doh.pub/dns-query
https://dns.alidns.com/dns-query
https://cloudflare-dns.com/dns-query
https://dns.google/dns-query

یا به‌عنوان جایگزین، فقط یکی از آن‌ها را امتحان کنید؛ برای مثال: https://dns.google/dns-query.

سایر گزینه‌های منوی "DNS" → "Server" نیازی به تغییر ندارند، مگر در صورت ضرورت.
```

</details>

<details>
<summary><strong><code> راهنمای دور زدن مسدودسازی در Karing </code></strong> ⬅ برای باز کردن کلیک کنید </summary>

---

از کاربر @999ivan33

**کانفیگ برای عملکرد پایدار در اینترنت موبایل و وای‌فای**

**1. وارد کردن کانفیگ‌ها و مدیریت پروفایل‌ها**

· اشتراک: اضافه کردن از طریق “افزودن لینک به کانفیگ” → وارد کردن URL خام اشتراک (توصیه شده BLACK_VLESS_RUS_mobile.txt برای تلفن یا BLACK_VLESS_RUS.txt برای PC). به‌روزرسانی خودکار را فعال کنید.

· کلیدهای فردی: وارد کردن از کلیپ‌بورد. هر کلید یا اشتراک یک پروفایل جداگانه ایجاد می‌کند. چندین کلید می‌توانند با انتخاب چندگانه هنگام وارد کردن به یک پروفایل اضافه شوند.

· انتخاب یک سرور: در صفحه اصلی، روی نام سرور کلیک کنید → «تست تأخیر». از «انتخاب خودکار» برای جابجایی خودکار به سریع‌ترین سرور استفاده کنید.

**۲. قوانین مسیریابی (تونل‌زنی جداگانه)**

قوانین از بالا به پایین پردازش می‌شوند تا اولین مطابقت پیدا شود. مورد نهایی یک تله برای ترافیک مفقود است.

· روش کلی: برای انواع مختلف ترافیک گروه‌های جداگانه ایجاد کنید. در هر گروه مجموعه قوانین داخلی (build-in) را فعال می‌کنیم و در صورت نیاز، domain_suffix و شناسه بسته برنامه (فقط Android) را اضافه می‌کنیم.

· خدمات روسیه (خدمات دولتی، بانک‌ها، بازارها):

  · عملیات منطقی: OR.
  
  · مجموعه قوانین (سازگار با سیستم): geosite:ru (اساسی) + geoip:ru (اگر تماس‌ها را مختل نکند).
  
  · اقدام: "مستقیم" (Direct).
  
  · دلیل: تمام ترافیک از منطقه .ru/.su/.рф و آی‌پی‌های روسی برای حداکثر سرعت و عدم مسدود شدن توسط تحریم‌های آی‌پی از VPN عبور نمی‌کند.
  
· مسنجرها (Telegram/AyuGram, WhatsApp):

  · مشکل: حملات مسدودکننده، پروتکل‌های تماس را هدف قرار می‌دهند. مسیریابی GeoIP باعث آسیب‌پذیری ترافیک در برابر DPI می‌شود.
  
  · راه‌حل: برای هر برنامه قوانین جداگانه ایجاد کنید.
  
  · برای AyuGram:
  
    · مجموعه قوانین (ساخته‌شده): geosite:telegram، acl:Telegram. مطمئن شوید geoip:telegram غیرفعال است.
    · domain_suffix (اختیاری، برای اطمینان بیشتر): t.me، telegram.org.
    · شناسه بسته: com.radolyn.ayugram.
    · اقدام: «انتخاب خودکار» یا «سرور فعلی».
    
  · برای WhatsApp:
  
    · مجموعه قوانین (ساخته شده): geosite:whatsapp.
    · پسوند دامنه: whatsapp.net, whatsapp.com (هر دو مورد لازم است به دلیل مسدودسازی NDIS).
    · شناسه بسته: com.whatsapp.
    · عملیات: "سرور فعلی".
    
· خدمات هوش مصنوعی (ChatGPT، Claude، Gemini، Grok و غیره):

  · هیچ دسته واحدی برای geosite:ai وجود ندارد. ما از اجزا جمع‌آوری می‌کنیم:
  
  · مجموعه قوانین (ساخته شده در): geosite:openai، geosite:anthropic، geosite:google-gemini، geosite:microsoft (برای Copilot)، geosite:meta، geosite:xai.
  
  · پسوند دامنه (برای کسانی که در لیست‌ها نیستند): deepseek.com، midjourney.com، x.ai، grok.com.
  
  · شناسه بسته (Android): com.openai.chatgpt، com.anthropic.claude، com.microsoft.copilot، و غیره.
  
  · عملیات: "سرور فعلی".
  
· سایر مسدود شده‌ها (YouTube، Discord، Instagram، GitHub):

  · قوانین داخلی مربوطه را فعال کنید (geosite:youtube، geosite:discord و غیره) یا یک گروه کلی “مسدود شده” ایجاد کنید که دسته‌های مورد نیاز را فهرست کند. اقدام: "سرور فعلی".
  
· نهایی:

  · اقدام: "سرور فعلی". تمام ترافیکی که در قوانین گنجانده نشده است به طور پیش‌فرض از طریق یک پروکسی عبور می‌کند.
  

**3. DNS: جداسازی جریان**

هدف: حل درخواست‌ها به سرورهای روسیه به سرعت از طریق DNS محلی، و به سرورهای مسدود شده - از طریق یک تونل رمزگذاری شده.

· پروتکل‌ها: استفاده انحصاری از DNS-over-HTTPS (DoH) (https://). UDP (udp://) حریم خصوصی فراهم نمی‌کند، TLS (tls://) به راحتی در پورت 853 مسدود می‌شود، محلی/dhcp://auto - کنترل ندارد.

· "سرور DNS" (برای افزایش VPN): قرار دادن https://223.5.5.5/dns-query (AliDNS).

· «سرور پروکسی» (اضافی، ترافیک نهایی): https://1.1.1.1/dns-query (Cloudflare)، https://8.8.8.8/dns-query (گوگل). هر دو را برای تحمل خطا انتخاب کنید.

· «پخش مستقیم» (برای سرویس‌های روسی):

  · پایه: https://common.dot.dns.yandex.net/dns-query. به صورت فیزیکی در فدراسیون روسیه، پینگ حداقلی.
  
  · رزرو شده: https://1.1.1.1/dns-query و https://8.8.8.8/dns-query. را اضافه کنید
  
  · اضافه کردن دستی: از طریق «+» → فیلد ISP (نام)، فیلد URL (آدرس).
  
· «ترافیک پروکسی» (برای مسدود شده): مشابه «سرور پروکسی» - Cloudflare + گوگل.

· تنظیمات اضافی:

  · TUN HijackDNS: فعال کنید.
  
  · فعال کردن قوانین DNS: فعال (لازم برای جداسازی جریان).
  
  · [جریان مستقیم] فعال کردن ECS: فعال.
  
  · [ترافیک پروکسی] روش حل مشکل: از FakeIP استفاده نکنید. فیلد روش حل مشکل را خالی بگذارید. در عوض، گزینه «[ترافیک پروکسی] حل DNS از طریق پروکسی» را فعال کنید. این باعث می‌شود درخواست‌ها از مسیر استاندارد تونل VPN عبور کنند بدون شبیه‌سازی IP ناپایدار.
  
  · TTL: ۲ ساعت (بهینه برای کش کردن).
  
  · ترجیح برای حل IP ثابت: غیرفعال.
  
  · IP ثابت: زیرمجموعه‌ای در بخش DNS. مشابه فایل hosts سیستم - خالی بگذارید.

**۴. تنظیمات دقیق TUN**

· حالت TUN: فعال.

· MTU: 1400 (برای جلوگیری از قطعه قطعه شدن حیاتی است).

· مسیر سختگیرانه: فعال.

· استک (Stack): gvisor (حداکثر عایق بندی).

· تایم‌اوت UDP: 1 دقیقه.

· نکته: تنظیمات TLS (تکه‌تکه کردن، ترکیبی SNI) در بخش TUN نیست، بلکه در یک بخش منوی جداگانه قرار دارد (به نقطه ۶ مراجعه کنید).

**۵. مدیریت پروفایل و انتخاب خودکار سرور**

· گروه‌های سرور: در بخش «پروفایل‌ها و سرورها» می‌توانید گروه‌های خود را ایجاد کنید (برای مثال، «استریم»، «تورنت‌ها»، «اخبار») و نودها را بین آن‌ها توزیع کنید.

· حالت انتخاب خودکار: وقتی حالت انتخاب خودکار را برای یک گروه انتخاب می‌کنید، Karing به طور مداوم سرور را تغییر نمی‌دهد. تنها در صورتی به نود دیگری منتقل می‌شود که نود فعلی به طور قابل توجهی دچار افت کیفیت شده باشد یا پاسخ نمی‌دهد، یا طبق یک برنامه زمانی (معمولاً هر چند دقیقه یک‌بار).

این مشکل «تغییر بیش از حد» را در صورت صحیح بودن کانفیگ‌ها از بین می‌برد.

· بررسی تأخیر (آدرس بررسی تأخیر): آدرس استاندارد http://www.gstatic.com/generate_204 گاهی روی تعدادی پروکسی ناپایدار است. اگر تغییرات مکرر سرور را مشاهده کردید، آن را با یکی از جایگزین‌ها تعویض کنید:
  
  · http://www.google.com/generate_204
  
  · http://connect.rom.miui.com/generate_204
  
· پیدا کردن تنظیم: تنظیمات → آدرس تشخیص تأخیر (یا تأخیر).

**6. قطعه‌بندی TLS و عبور از DPI**

· این یک بخش جداگانه در منوی اصلی تنظیمات است و به TUN مربوط نمی‌شود.

· همه گزینه‌ها (تکه‌تکه کردن، ترکیبی SNI، پر کردن) خاموش هستند (پیش‌فرض). آن‌ها برای DPI تهاجمی طراحی شده‌اند که سرعت و پایداری را کاهش می‌دهد.

**7. انتقال تنظیمات و چندسکویی**

· پشتیبان‌گیری: تنظیمات → پشتیبان‌گیری → صادرات به فایل .zip. شامل پروفایل‌ها، قوانین، کلیدها در قالب json است.

· انتقال به آیفون (iOS):

  · در Android، یک کد QR در «همگام‌سازی از طریق LAN» ایجاد کنید.
  
  · نصب Karing روی آیفون (iOS 15+)، کد QR را اسکن کنید.
  
  · توجه: قوانین مبتنی بر شناسه بسته برنامه (Android) منتقل می‌شوند، اما روی iOS فعال نیستند. آنها نیاز به جایگزینی دستی با قوانین domain_suffix دارند (برای مثال، برای AyuGram - domain_suffix: telegram.org).

**8. رفع تعارض‌ها با روتر (OpenWrt)**

· علامت: خدمات عمومی (و سایر خدمات روسیه) از طریق Wi-Fi کار نمی‌کنند و خطای «دسترسی به دلایل امنیتی محدود است» را نشان می‌دهند.

· علت: هدایت اجباری DNS روی روتر یا تعارض DNS با ارائه‌دهنده.

· راه حل:
  · در رابط OpenWrt، تغییر مسیر DNS را غیرفعال کنید: شبکه → DHCP و DNS → تیک DNS تغییر مسیر را بردارید.
  
  · پیکربندی DNS ثابت در WAN: شبکه → رابط‌ها → WAN → تنظیمات پیشرفته → استفاده از سرورهای DNS سفارشی اضافه کنید 77.88.8.8، 77.88.8.1.
  
  · روتر را راه‌اندازی مجدد کنید.

  ---

</details>

---

</details>


<details>
<summary><strong><code> راهنمای Clash Verge Rev </code></strong> ⬅ برای باز کردن کلیک کنید </summary>

---

### `Clash Verge Rev`

**https://github.com/clash-verge-rev/clash-verge-rev/releases**

Clash Verge Rev فقط برای پروفایل‌های با فرمت YAML در Clash طراحی شده است.

*هنگام تلاش برای وارد کردن یک اشتراک غیر-YAML، Clash Verge Rev خطاهایی مانند `داده‌های پروفایل راه دور YAML نامعتبر است` یا `پروفایل شامل پروکسی‌ها یا ارائه‌دهندگان پروکسی نیست` را نشان می‌دهد.*

از تمام پروتکل‌های مدرن VLESS، Trojan، VMess، Hysteria2 پشتیبانی می‌کند، فقط باید در قالب کانفیگ Clash توصیف شوند. خود کلاینت روی هسته Mihomo اجرا می‌شود، که قبلاً Clash.Meta نامیده می‌شد.

من خودم شروع به استفاده فعال از Clash Verge Rev کردم و احساس می‌شد که اینترنت با VPN عملاً بدون وقفه است، کانفیگ‌ها به‌طور خودکار در پس‌زمینه بررسی می‌شدند و یکی پس از دیگری به‌قدری روان تغییر می‌کردند که من دیگر متوجه آن نمی‌شدم. شاید این کلاینت حتی کمی بهتر از Karing کار کند، زیرا Karing گاهی اوقات هنوز هنگام اجرای طولانی مدت نیاز به راه‌اندازی مجدد اجباری دارد.

**برای استفاده از این کلاینت، فقط از اشتراک‌های YAML از پوشه مخزن به نام Clash استفاده کنید:** https://github.com/igareck/vpn-configs-for-russia/tree/main/Export/Clash

**Igareck قبلاً بررسی سلامت خودکار کانفیگ‌ها در پس‌زمینه را در تمام اشتراک‌های Clash برای راحتی کاربران ساخته است.**
  
**اشتراک‌های Clash بر اساس منطقه تقسیم شده‌اند:**
  
- **اشتراک‌های Clash برای کاربران از روسیه** (RU-DIRECT تا همه سایت‌های روسیه بدون VPN باز شوند): 

https://github.com/igareck/vpn-configs-for-russia/tree/main/Export/Clash/RU_DIRECT

- **اشتراک‌های Clash برای گزینه بین‌المللی** (برای سایر کشورها که به RU-DIRECT نیاز ندارند): 

https://github.com/igareck/vpn-configs-for-russia/tree/main/Export/Clash/GLOBAL

**تمام تنظیمات پس از وارد کردن توسط کلاینت گرفته خواهد شد.**

**کاربر تنها باید تمدید خودکار اشتراک را درون کلاینت هر یک یا دو ساعت تنظیم کند و کانفیگ را اجرا نماید:** 

1. به بخش «پروفایل‌ها» بروید، روی کانفیگ وارد شده کلیک راست کنید (RMB);
2. در منوی کشویی، روی «تغییر اطلاعات» کلیک کنید;
3. در منویی که ظاهر می‌شود، اهرم «اجازه به‌روزرسانی خودکار» را فعال کنید، فاصله به‌روزرسانی را وارد کنید (عدد به دقیقه، برای مثال 60 یا 120). در صورت تمایل می‌توانید عنوان/توضیحات را ویرایش کنید;
4. در پایان، روی «ذخیره» کلیک کنید;
5. سپس روی کانفیگ وارد شده کلیک راست کنید، روی «به‌روزرسانی» یا «به‌روزرسانی از طریق پروکسی» کلیک کنید تا کانفیگ‌ها از اشتراک بارگذاری شوند؛
۶. سپس به بخش "پروکسی‌ها" بروید;
۷. در گوشهٔ بالا سمت راست بالای فهرست کانفیگ‌ها، روی آیکون فیلتر کلیک کنید (شبیه نماد قیف 🌪️ است)، یک فیلد ورودی در سمت چپ ظاهر خواهد شد;
۸. در فیلد ورودی، عبارت "delay<5000" را وارد کنید تا سرورهای غیر فعال مخفی شوند (لطفاً توجه داشته باشید که آنها بلافاصله ناپدید نمی‌شوند، بلکه ۵ تا ۱۰ دقیقه بعد از تکرار اسکن پس‌زمینه);
۹. سپس دوباره روی آیکون فیلتر کلیک کنید (شبیه آیکون قیف 🌪️) تا فیلد ورودی مخفی شود؛
۱۰. سپس به بخش "تنظیمات" بروید؛
۱۱. در بخش «تنظیمات» در گوشه بالای سمت چپ، «حالت TUN» را پیدا کنید، در سمت راست آن یک آیکون کوچک «آچار آبی» با نوشته «نصب یک سرویس» وجود دارد، روی آن کلیک کنید و منتظر نصب بمانید. بررسی کنید که اهرم‌های «حالت TUN» و «پروکسی سیستم» فعال باشند؛
۱۲. سپس به بخش «خانه» بروید؛
۱۳. در بخش «خانه»، پنل «تنظیمات شبکه» را پیدا کنید، حالت عملکرد مورد نیاز را انتخاب کنید: «پروکسی سیستم» یا «حالت TUN»، آن را با استفاده از دکمه اهرم فعال کنید. معمولاً یکی از حالت‌ها فعال است و کافی است، اما گاهی اوقات هر دو برای عملکرد کامل لازم هستند، به وضعیت توجه کنید؛
۱۴. تمام!
۱۵. بخش «خانه» آمار عملکرد کانفیگ‌ها در کلاینت Clash Verge Rev را نشان می‌دهد: سرعت، حجم آپلود/دانلود، خروجی-IP/ASN و غیره.
۱۶. **پروفایل YAML آماده با بررسی سلامت خودکار برای روسیه (RU-DIRECT، به طوری که تمام سایت‌های RU بدون VPN کار کنند) برای پیکربندی جهانی خود کلاینت Clash Verge Rev.** 

    **ضروری نیست، زیرا همان تنظیمات به‌طور خودکار با اشتراک Igareck شما می‌آید. کاربر معمولی می‌تواند این مورد را نادیده بگیرد و در نقطه ۱۵ متوقف شود.** این کار برای راحتی کاربران طبق اصل انجام شد: اشتراک اضافه کنید و فوراً استفاده کنید.

    **کجا اضافه کنیم؟** **به بخش «پروفایل‌ها» بروید، «کانفیگ ادغام جهانی» را پیدا کنید، روی آن راست‌کلیک کنید - «ویرایش فایل»، همه چیز را حذف کرده و تنظیمات YAML آماده شده از بلوک زیر را وارد کنید، سپس «ذخیره» را کلیک کنید.**

    **برای چه چیزی؟** برای کاربران پیشرفته: اگر نیاز دارید هر گزینه اشتراک‌گذاری Clash را به صورت دستی در خود کلاینت Clash Verge Rev تغییر دهید، و آن‌ها را برای هر اشتراک ورودی به‌صورت جهانی اعمال کنید. تنظیمات ثبت شده در خود کلاینت Clash Verge Rev، اگر با تنظیمات هر اشتراک Clash ورودی مطابقت داشته باشد، آن‌ها را بازنویسی می‌کند.

```diff
# ============================================================
# Igareck Mihomo Client Profile
# Settings profile without built-in proxies.
# Proxies must come from the connected subscription.
#
# Mode:
# - automatic selection of the best proxy;
# - manual proxy selection;
# - RU-DIRECT.
# ============================================================


mode: rule
unified-delay: true
tcp-concurrent: true

keep-alive-idle: 300
keep-alive-interval: 60
disable-keep-alive: false

profile:
  store-selected: true
  store-fake-ip: true

dns:
  enable: true
  prefer-h3: false
  ipv6: false
  use-hosts: true
  use-system-hosts: true
  respect-rules: false

  enhanced-mode: fake-ip
  fake-ip-range: 198.18.0.1/16
  fake-ip-filter-mode: blacklist

  fake-ip-filter:
    - "*.lan"
    - "*.local"
    - "localhost"

    - "time.*.com"
    - "time.*.gov"
    - "time.*.apple.com"
    - "time-ios.apple.com"
    - "time1.*.com"
    - "time2.*.com"
    - "time3.*.com"
    - "time4.*.com"
    - "time5.*.com"
    - "time6.*.com"
    - "time7.*.com"

    - "ntp.*.com"
    - "ntp1.*.com"
    - "ntp2.*.com"
    - "ntp3.*.com"
    - "ntp4.*.com"
    - "ntp5.*.com"
    - "ntp6.*.com"
    - "ntp7.*.com"
    - "*.pool.ntp.org"

    - "+.push.apple.com"

    - "+.stun.*.*"
    - "+.stun.*.*.*"
    - "+.stun.*.*.*.*"
    - "+.stun.*.*.*.*.*"
    - "+.stun.playstation.net"

    - "lens.l.google.com"
    - "*.n.n.srv.nintendo.net"
    - "xbox.*.*.microsoft.com"
    - "*.*.xboxlive.com"

    - "*.msftncsi.com"
    - "*.msftconnecttest.com"

    - "WORKGROUP"

  cache-algorithm: arc

  default-nameserver:
    - 8.8.8.8
    - 8.8.4.4
    - 9.9.9.9
    - 94.140.14.14
    - 76.76.2.0
    - 76.76.10.0
    - 1.0.0.1
    - 1.1.1.1
    - 208.67.220.220
    - 208.67.222.222

  nameserver:
    - https://dns.google/dns-query
    - https://dns.quad9.net/dns-query
    - https://dns.adguard-dns.com/dns-query
    - https://freedns.controld.com/p0
    - https://dns.mullvad.net/dns-query
    - https://cloudflare-dns.com/dns-query
    - https://doh.opendns.com/dns-query
    - https://doh.libredns.gr/dns-query
    - https://doh.dns4all.eu/dns-query
    - https://wikimedia-dns.org/dns-query
    - https://dns.hostux.net/dns-query
    - https://blank.dnsforge.de/dns-query

  proxy-server-nameserver:
    - 8.8.8.8
    - 8.8.4.4
    - 9.9.9.9
    - 94.140.14.14
    - 76.76.2.0
    - 76.76.10.0
    - 1.0.0.1
    - 1.1.1.1
    - 208.67.220.220
    - 208.67.222.222
    - system

  direct-nameserver:
    - 8.8.8.8
    - 8.8.4.4
    - 9.9.9.9
    - 94.140.14.14
    - 76.76.2.0
    - 76.76.10.0
    - 1.0.0.1
    - 1.1.1.1
    - 208.67.220.220
    - 208.67.222.222
    - system

  direct-nameserver-follow-policy: false

sniffer:
  enable: true
  force-dns-mapping: true
  parse-pure-ip: true
  override-destination: false

  sniff:
    HTTP:
      ports: [80, 8080-8880]
      override-destination: true

    TLS:
      ports: [443, 8443]

    QUIC:
      ports: [443, 8443]

proxy-groups:
  - name: "Igareck Auto Select (Auto connect)"
    type: url-test
    include-all: true
    exclude-type: "Direct|Reject|RejectDrop|Compatible|Pass|Dns"
    url: "https://www.gstatic.com/generate_204"
    interval: 300
    tolerance: 150
    lazy: true
    timeout: 5000
    max-failed-times: 2
    expected-status: 204

  - name: "Igareck Manual (Manual Connection)"
    type: select
    proxies:
      - "Igareck Auto Select (Auto connect)"
    include-all: true
    exclude-type: "Direct|Reject|RejectDrop|Compatible|Pass|Dns"
    default-selected: "Igareck Auto Select (Auto connect)"

  - name: "GLOBAL"
    type: select
    proxies:
      - "Igareck Auto Select (Auto connect)"
      - "Igareck Manual (Manual Connection)"
    default-selected: "Igareck Auto Select (Auto connect)"

rules:
  - DOMAIN-SUFFIX,localhost,DIRECT
  - DOMAIN-SUFFIX,local,DIRECT
  - "DOMAIN-REGEX,^[^.]+$,DIRECT"

  - IP-CIDR,127.0.0.0/8,DIRECT,no-resolve
  - IP-CIDR,10.0.0.0/8,DIRECT,no-resolve
  - IP-CIDR,172.16.0.0/12,DIRECT,no-resolve
  - IP-CIDR,192.168.0.0/16,DIRECT,no-resolve
  - IP-CIDR,169.254.0.0/16,DIRECT,no-resolve
  - IP-CIDR,100.64.0.0/10,DIRECT,no-resolve

  - IP-CIDR6,::1/128,DIRECT,no-resolve
  - IP-CIDR6,fc00::/7,DIRECT,no-resolve
  - IP-CIDR6,fe80::/10,DIRECT,no-resolve

  # Remove the following 4 lines for global/Not-RU-Direct mode.
  # Delete the next 4 lines for Global/Not-RU-Direct routing.
  - DOMAIN-SUFFIX,ru,DIRECT
  - DOMAIN-SUFFIX,xn--p1ai,DIRECT
  - GEOSITE,category-ru,DIRECT
  - GEOIP,RU,DIRECT

  - "MATCH,Igareck Manual (Manual Connection)"
```

---

</details>


<details>
<summary><strong><code> راهنمای Exclave </code></strong> ⬅ برای باز کردن کلیک کنید </summary>

## `Exclave`

دستورالعمل‌های راه‌اندازی Exclave در Android

### 1. نصب

دانلود Exclave از [مخزن رسمی](https://github.com/ExclaveNetwork/Exclave/releases).

### ۲. افزودن یک اشتراک

۱. لینک اشتراک را کپی کنید.
۲. Exclave را باز کنید.
۳. منوی کناری در سمت چپ `☰` را باز کنید.
۴. به بخش **Configuration** بروید.
۵. بر روی دکمه در گوشه بالای سمت راست **Add profile** — آیکون برگ با علامت بعلاوه کلیک کنید.
۶. گزینه **Import from clipboard** را انتخاب کنید.
۷. با دکمه **Import a subscription** عمل را تأیید کنید.
۸. منوی کناری در سمت چپ را باز کنید `☰` → **Groups**.
۹. اگر کنار گروه جدید نوشته شده است **هنوز به‌روزرسانی نشده است**، روی دکمه پیکان تازه‌سازی کلیک کنید.
۱۰. کنار گروه جدید، روی آیکون مداد برای ویرایش کلیک کنید.
۱۱. در تنظیمات گروه، **نام گروه** را تنظیم کنید، بر اساس تأخیر **مرتب‌سازی** کنید، در تنظیمات به‌روزرسانی پایین، **به‌روزرسانی خودکار** را فعال کنید و **تاخیر به‌روزرسانی خودکار (به دقیقه)** را روی ۶۰ یا ۱۲۰ قرار دهید.
۱۲. در گوشه بالا سمت راست، روی علامت تیک کلیک کنید تا تغییرات اعمال شود.

بعد از دریافت اشتراک خود، به `☰` → **کانفیگ** بازگردید

روی `⋮` کلیک کنید → **تست اتصال** → **تست URL** برای یک تست دستی اولیه. اما حتماً به تنظیمات زیر در نقاط ۳، ۴، ۵ بروید.


### ۳. تنظیمات پیشنهادی

در بخش `☰` → **تنظیمات** نصب کنید:

| تنظیمات                                             | معنی                                                           |
| ----------------------------------------------------- | ------------------------------------------------------------------ |
| حالت سرویس                                       | `VPN`                                                              |
| TCP/پشته IP                                           | `gVisor`                                                           |
| مسیر IPv6                                          | خاموش                                                          |
| کنار زدن LAN                                             | شامل                                                           |
| استراتژی حل دامنه                          | `AsIs`                                                             |
| فعال کردن تحلیل ترافیک                               | شامل                                                           |
| نادیده گرفتن مقصد                             | خاموش                                                          |
| حالت مسیرها                                       | `rule` برای RU-DIRECT یا `global` برای پروکسی کامل |
| ریموت DNS                                         | `https://dns.google/dns-query`                                     |
| استراتژی ریموت DNS                              | `IPv4 only`                                                      |
| استفاده از DNS محلی به عنوان DNS مستقیم             | شامل                                                           |
| استراتژی DNS مستقیم                                 | `IPv4 only`                                                      |
| از سیستم DNS به عنوان راه‌انداز DNS استفاده کنید | شامل                                                           |
| روتینگ DNS را فعال کنید                            | شامل                                                           |
| FakeDNS را فعال کنید                                      | خاموش                                                          |

برای حالت RU-DIRECT در بخش `☰` → **مسیرها** قوانین باید موجود باشند:

```diff
geosite:category-ru → bypass
geoip:ru            → bypass
geoip:private       → bypass
```

اگر این قوانین وجود دارند، همه چیز درست است.

اگر این قوانین وجود ندارند، باید آنها را به صورت دستی از طریق منوی بالا سمت چپ اضافه کنید `☰` → **مسیرها** → `⋮` → **وارد کردن از کلیپ‌بورد**.

خود قوانین RU-DIRECT را می‌توان از اینجا کپی کرد:

```diff
[
  {
    "locked": false,
    "remarks": "RU-DIRECT: local and private IP",
    "enabled": true,
    "outboundTag": "direct",
    "ip": [
      "geoip:private"
    ]
  },
  {
    "locked": false,
    "remarks": "RU-DIRECT: Russian domains",
    "enabled": true,
    "outboundTag": "direct",
    "domain": [
      "geosite:category-ru"
    ]
  },
  {
    "locked": false,
    "remarks": "RU-DIRECT: Russian IP",
    "enabled": true,
    "outboundTag": "direct",
    "ip": [
      "geoip:ru"
    ]
  }
]
```

اطمینان حاصل کنید که سه قانون ظاهر شده و فعال باشند:
* RU-DIRECT: آی‌پی محلی و خصوصی;
* RU-DIRECT: دامنه‌های روسی;
* RU-DIRECT: آی‌پی روسیه.
در هر قانون، جهت خروجی باید به صورت **عبور** نمایش داده شود.
اگر VPN قبلاً متصل بود، آن را غیرفعال کرده و دوباره فعال کنید.


### ۴. انتخاب خودکار بهترین گره

برای انجام بررسی سلامت خودکار و انتخاب بهترین گره:

1. `☰` را باز کنید → **کانفیگ**.
2. روی دکمه در بالای سمت راست کلیک کنید **افزودن پروفایل** — آیکون برگ با علامت بعلاوه.
3. انتخاب کنید **تنظیمات دستی** → **تراز کننده**.
4. مشخص کنید:

```diff
Profile name: Igareck Auto Select
Type: Groups
Strategy: leastPing
Group: Select imported subscription
Custom Connection Test URL: https://www.gstatic.com/generate_204
Interval between checks: 300
```

5. با دکمه تیک (بالای سمت راست) ذخیره کنید.
6. در بخش `☰` → **کانفیگ** تعادل‌ساز تازه ایجاد شده را انتخاب کنید.

### 5. اتصال

1. در بخش `☰` → **کانفیگ** یک گره جداگانه برای حالت دستی یا یک تعادل‌ساز ایجاد شده `Igareck Auto Select` را به‌عنوان کانفیگ فعال انتخاب کنید (پیشنهاد شده).
2. روی دکمه اتصال (نماد هواپیمای کاغذی) در پایین صفحه کلیک کنید.
3. هنگام شروع برای اولین بار، درخواست سیستم Android برای ایجاد اتصال VPN را تأیید کنید.


---

</details>


<details>
<summary><strong><code> راهنمای Shadowrocket </code></strong> ⬅ برای باز کردن کلیک کنید </summary>

---

### `Shadowrocket`

https://github.com/hiddify/Hiddify-Manager/wiki/Tutorial-for-ShadowRocket-app

**1. فایل کانفیگ RU-DIRECT**

**[دانلود Shadowrocket_RU_DIRECT_ROUTING.conf](https://raw.githack.com/igareck/GoldCaviar/main/Files/Shadowrocket_RU_DIRECT_ROUTING.conf)**

<details>
<summary><code> باز کردن </code></summary>

㋡

```diff
# Shadowrocket RU-DIRECT routing and DNS configuration
#
# ENG
# This file does not contain proxy nodes.
# First add a normal RAW/Base64 subscription to Shadowrocket and configure
# Shadowrocket's native automatic proxy testing/selection. Then import and
# activate this .conf in the Configuration ("Settings") routing mode.
#
# RU-DIRECT means Russian domains and IP addresses use DIRECT. All other external
# Internet traffic uses PROXY. Localhost, private networks, and LAN devices also
# remain DIRECT so the router and local devices stay reachable.
#
# FA
# این فایل شامل هیچ نود پروکسی نیست.
# ابتدا یک اشتراک معمولی RAW/Base64 را به Shadowrocket اضافه کنید و بررسی خودکار
# داخلی و انتخاب پروکسی را تنظیم کنید. سپس این فایل .conf را وارد کرده
# و آن را در حالت مسیریابی «Configuration» فعال کنید.
#
# RU-DIRECT به این معناست که دامنه‌ها و آدرس‌های IP روسیه از طریق DIRECT هدایت می‌شوند.
# سایر ترافیک اینترنت خارجی از طریق PROXY عبور می‌کند. Localhost، شبکه‌های خصوصی و
# دستگاه‌های شبکه محلی نیز در حالت DIRECT باقی می‌مانند.
#
# For more information visit: github.com/igareck/vpn-configs-for-russia


[General]

ipv6 = false
prefer-ipv6 = false
ipv6-only-if-no-ipv4-dns = false

private-ip-answer = true
always-ip-address = false
allow-dns-svcb = false
allow-dns-all = true

dns-server = 8.8.8.8,8.8.4.4,9.9.9.9,94.140.14.14,76.76.2.0,76.76.10.0,1.0.0.1,1.1.1.1,208.67.220.220,208.67.222.222,system

fallback-dns-server = system
dns-fallback-system = true

proxy-dns-server = https://dns.google/dns-query#no-h3,https://dns.quad9.net/dns-query#no-h3,https://dns.adguard-dns.com/dns-query#no-h3,https://freedns.controld.com/p0#no-h3,https://dns.mullvad.net/dns-query#no-h3,https://cloudflare-dns.com/dns-query#no-h3,https://doh.opendns.com/dns-query#no-h3,https://doh.libredns.gr/dns-query#no-h3,https://doh.dns4all.eu/dns-query#no-h3,https://wikimedia-dns.org/dns-query#no-h3,https://dns.hostux.net/dns-query#no-h3,https://blank.dnsforge.de/dns-query#no-h3

dns-direct-system = false
dns-direct-fallback-proxy = false
hijack-dns = *:53

always-real-ip = *.lan,*.local,localhost,time.*.com,time.*.gov,time.*.apple.com,time-ios.apple.com,time1.*.com,time2.*.com,time3.*.com,time4.*.com,time5.*.com,time6.*.com,time7.*.com,ntp.*.com,ntp1.*.com,ntp2.*.com,ntp3.*.com,ntp4.*.com,ntp5.*.com,ntp6.*.com,ntp7.*.com,*.pool.ntp.org,push.apple.com,*.push.apple.com,stun.*.*,*.stun.*.*,stun.*.*.*,*.stun.*.*.*,stun.*.*.*.*,*.stun.*.*.*.*,stun.*.*.*.*.*,*.stun.*.*.*.*.*,stun.playstation.net,*.stun.playstation.net,lens.l.google.com,*.n.n.srv.nintendo.net,xbox.*.*.microsoft.com,*.*.xboxlive.com,*.msftncsi.com,*.msftconnecttest.com,WORKGROUP

skip-proxy = 127.0.0.0/8,10.0.0.0/8,172.16.0.0/12,192.168.0.0/16,169.254.0.0/16,100.64.0.0/10,localhost,*.local,*.lan

tun-excluded-routes = 10.0.0.0/8,100.64.0.0/10,127.0.0.0/8,169.254.0.0/16,172.16.0.0/12,192.0.0.0/24,192.0.2.0/24,192.88.99.0/24,192.168.0.0/16,198.51.100.0/24,203.0.113.0/24,224.0.0.0/4,239.255.255.250/32,255.255.255.255/32

udp-policy-not-supported-behaviour = REJECT
block-quic = always-allow
use-local-host-item-for-proxy = true
icmp-auto-reply = false
always-reject-url-rewrite = false

[Rule]

DOMAIN,localhost,DIRECT
DOMAIN-SUFFIX,local,DIRECT
DOMAIN-SUFFIX,lan,DIRECT

IP-CIDR,127.0.0.0/8,DIRECT,no-resolve
IP-CIDR,10.0.0.0/8,DIRECT,no-resolve
IP-CIDR,172.16.0.0/12,DIRECT,no-resolve
IP-CIDR,192.168.0.0/16,DIRECT,no-resolve
IP-CIDR,169.254.0.0/16,DIRECT,no-resolve
IP-CIDR,100.64.0.0/10,DIRECT,no-resolve

IP-CIDR,::1/128,DIRECT,no-resolve
IP-CIDR,fc00::/7,DIRECT,no-resolve
IP-CIDR,fe80::/10,DIRECT,no-resolve

# Remove the next 3 lines for Global / Not-RU-Direct routing.
DOMAIN-SUFFIX,ru,DIRECT
DOMAIN-SUFFIX,xn--p1ai,DIRECT
GEOIP,RU,DIRECT

FINAL,PROXY

[Host]

localhost = 127.0.0.1
```

</details>


**2. فایل کانفیگ GLOBAL**

**[دانلود Shadowrocket_GLOBAL_ROUTING.conf](https://raw.githack.com/igareck/GoldCaviar/main/Files/Shadowrocket_GLOBAL_ROUTING.conf)**

<details>
<summary><code> باز کردن </code></summary>

㋡

```diff
# Shadowrocket GLOBAL routing and DNS configuration
#
# ENG
# This file does not contain proxy nodes.
# First add a normal RAW/Base64 subscription to Shadowrocket and configure
# Shadowrocket's native automatic proxy testing/selection. Then import and
# activate this .conf in the Configuration ("Settings") routing mode.
#
# GLOBAL means all external Internet traffic uses PROXY. Localhost, private
# networks, and LAN devices remain DIRECT so the router and local devices stay
# reachable.
#
# FA
# این فایل شامل هیچ نود پروکسی نیست.
# ابتدا یک اشتراک معمولی RAW/Base64 را به Shadowrocket اضافه کنید و بررسی خودکار
# داخلی و انتخاب پروکسی را تنظیم کنید. سپس این فایل .conf را وارد کرده
# و آن را در حالت مسیریابی «Configuration» فعال کنید.
#
# GLOBAL به این معناست که تمام ترافیک اینترنت خارجی از طریق PROXY هدایت می‌شود.
# Localhost، شبکه‌های خصوصی و دستگاه‌های شبکه محلی در حالت DIRECT باقی می‌مانند
# تا دسترسی به روتر و سایر دستگاه‌های محلی حفظ شود.
#
# For more information visit: github.com/igareck/vpn-configs-for-russia

[General]

ipv6 = false
prefer-ipv6 = false
ipv6-only-if-no-ipv4-dns = false

private-ip-answer = true
always-ip-address = false
allow-dns-svcb = false
allow-dns-all = true

dns-server = 8.8.8.8,8.8.4.4,9.9.9.9,94.140.14.14,76.76.2.0,76.76.10.0,1.0.0.1,1.1.1.1,208.67.220.220,208.67.222.222,system

fallback-dns-server = system
dns-fallback-system = true

proxy-dns-server = https://dns.google/dns-query#no-h3,https://dns.quad9.net/dns-query#no-h3,https://dns.adguard-dns.com/dns-query#no-h3,https://freedns.controld.com/p0#no-h3,https://dns.mullvad.net/dns-query#no-h3,https://cloudflare-dns.com/dns-query#no-h3,https://doh.opendns.com/dns-query#no-h3,https://doh.libredns.gr/dns-query#no-h3,https://doh.dns4all.eu/dns-query#no-h3,https://wikimedia-dns.org/dns-query#no-h3,https://dns.hostux.net/dns-query#no-h3,https://blank.dnsforge.de/dns-query#no-h3

dns-direct-system = false
dns-direct-fallback-proxy = false
hijack-dns = *:53

always-real-ip = *.lan,*.local,localhost,time.*.com,time.*.gov,time.*.apple.com,time-ios.apple.com,time1.*.com,time2.*.com,time3.*.com,time4.*.com,time5.*.com,time6.*.com,time7.*.com,ntp.*.com,ntp1.*.com,ntp2.*.com,ntp3.*.com,ntp4.*.com,ntp5.*.com,ntp6.*.com,ntp7.*.com,*.pool.ntp.org,push.apple.com,*.push.apple.com,stun.*.*,*.stun.*.*,stun.*.*.*,*.stun.*.*.*,stun.*.*.*.*,*.stun.*.*.*.*,stun.*.*.*.*.*,*.stun.*.*.*.*.*,stun.playstation.net,*.stun.playstation.net,lens.l.google.com,*.n.n.srv.nintendo.net,xbox.*.*.microsoft.com,*.*.xboxlive.com,*.msftncsi.com,*.msftconnecttest.com,WORKGROUP

skip-proxy = 127.0.0.0/8,10.0.0.0/8,172.16.0.0/12,192.168.0.0/16,169.254.0.0/16,100.64.0.0/10,localhost,*.local,*.lan

tun-excluded-routes = 10.0.0.0/8,100.64.0.0/10,127.0.0.0/8,169.254.0.0/16,172.16.0.0/12,192.0.0.0/24,192.0.2.0/24,192.88.99.0/24,192.168.0.0/16,198.51.100.0/24,203.0.113.0/24,224.0.0.0/4,239.255.255.250/32,255.255.255.255/32

udp-policy-not-supported-behaviour = REJECT
block-quic = always-allow
use-local-host-item-for-proxy = true
icmp-auto-reply = false
always-reject-url-rewrite = false

[Rule]

DOMAIN,localhost,DIRECT
DOMAIN-SUFFIX,local,DIRECT
DOMAIN-SUFFIX,lan,DIRECT

IP-CIDR,127.0.0.0/8,DIRECT,no-resolve
IP-CIDR,10.0.0.0/8,DIRECT,no-resolve
IP-CIDR,172.16.0.0/12,DIRECT,no-resolve
IP-CIDR,192.168.0.0/16,DIRECT,no-resolve
IP-CIDR,169.254.0.0/16,DIRECT,no-resolve
IP-CIDR,100.64.0.0/10,DIRECT,no-resolve

IP-CIDR,::1/128,DIRECT,no-resolve
IP-CIDR,fc00::/7,DIRECT,no-resolve
IP-CIDR,fe80::/10,DIRECT,no-resolve

FINAL,PROXY

[Host]

localhost = 127.0.0.1
```

</details>

---

</details>


<details>
<summary><strong><code> راهنمای v2rayN و v2rayNG </code></strong> ⬅ برای باز کردن کلیک کنید </summary>

---

### `v2rayN, v2rayNG`

**[راه‌اندازی V2rayN روی Windows (آینه)](https://web.archive.org/web/https://vpnpanels.com/ru/p/setup-v2ray-windows)**

**[راه‌اندازی V2rayNG روی Android (آینه)](https://web.archive.org/web/https://vpnpanels.com/ru/p/setup-v2ray-android/)**

<details>
<summary><strong><code> v2rayN — تنظیمات کلاینت ۱ </code></strong> ⬅ برای باز کردن کلیک کنید </summary>

---

کلاینت رسمی v2rayN را نصب کنید، در حالت “مدیر” اجرا کنید.

به "تنظیمات" - "تنظیمات منطقه‌ای" بروید، "روسیه" را انتخاب کنید. روی منوی "راه‌اندازی مجدد" کلیک کنید یا برنامه را دوباره راه‌اندازی کنید.

از طریق **گروه اشتراک - تنظیمات گروه اشتراک** یک اشتراک اضافه کنید، اشتراک خود را از طریق **گروه اشتراک - به‌روزرسانی اشتراک فعلی بدون پروکسی** دانلود کنید، یک فهرست ظاهر خواهد شد.

روی گزینه "تاخیر واقعی" (آیکون رعد و برق در بالا سمت راست) کلیک کنید، پس از تکمیل - بر اساس پینگ مرتب کنید، چند کانفیگ سبز بالا با کمترین عدد را انتخاب کنید.

چند سرور با کمترین عدد پینگ را انتخاب کنید، راست‌کلیک کنید، گزینه «آزمایش سرعت بارگذاری سرور» را انتخاب کنید، پس از آزمایش، سریع‌ترین را با فشار دادن Enter انتخاب کنید. اما تست سرعت v2rayN اخیراً حتی روی سرورهای زنده نیز نتایج نادرست نشان می‌دهد، بنابراین من به آرامی روی پینگ تمرکز می‌کنم. در اشتراک‌های من، اگر سرور پینگ دارد، به طور پیش‌فرض باید کار کند.

در نهایت، «حالت VPN/حالت TUN» را اجرا کنید، یا «تنظیم پروکسی سیستم» را فعال کنید. در سمت راست، قوانین مسیریابی «RUv1-همه چیز به جز RF» را انتخاب کنید تا VPN برای کار روی سایت‌های RU استفاده نشود.

---

</details>

<details>
<summary><strong><code> v2rayN — تنظیمات کلاینت ۲ </code></strong> ⬅ برای باز کردن کلیک کنید </summary>

---

**v2rayN — تنظیمات کلاینت**

نسخه رابط برای آن که دستورالعمل‌ها برای آن کامپایل شده‌اند: v2rayN 7.24.4. 

زبان رابط انگلیسی است.

خطوط تکمیل شده زیر در فیلدهای مشخص شده v2rayN کپی می‌شوند و سوئیچ‌ها یک‌بار به‌صورت دستی تنظیم می‌شوند.


**`1. DNS SETTINGS`**

**مسیر: تنظیمات -> تنظیمات DNS -> تنظیمات پایه DNS**

**DNS داخلی**

در یک خط درج کنید:

```diff
8.8.8.8,8.8.4.4,9.9.9.9,94.140.14.14,76.76.2.0,76.76.10.0,1.0.0.1,1.1.1.1,208.67.220.220,208.67.222.222
```

**DNS از راه دور**

در یک خط درج کنید:

```diff
https://dns.google/dns-query,https://dns.quad9.net/dns-query,https://dns.adguard-dns.com/dns-query,https://freedns.controld.com/p0,https://dns.mullvad.net/dns-query,https://cloudflare-dns.com/dns-query,https://doh.opendns.com/dns-query,https://doh.libredns.gr/dns-query,https://doh.dns4all.eu/dns-query,https://wikimedia-dns.org/dns-query,https://dns.hostux.net/dns-query,https://blank.dnsforge.de/dns-query
```

**DNS بوت‌استرپ**

در یک خط درج کنید:

```diff
8.8.8.8,8.8.4.4,9.9.9.9,94.140.14.14,76.76.2.0,76.76.10.0,1.0.0.1,1.1.1.1,208.67.220.220,208.67.222.222
```

پارامترهای دیگر تنظیمات DNS پایه:

```diff
• Direct Target Resolution Strategy: UseIPv4
• Proxy Target Resolution Strategy: UseIPv4
• Proxy Dial Resolution Strategy: AsIs or empty value
• Parallel Query: Off
• Serve Stale: Off
• Enable Happy Eyeballs: Off
```

تنظیم استراتژی حل شماره‌گیری پروکسی را روی UseIPv4 قرار ندهید: رابط v2rayN
هشدار می‌دهد که این استراتژی ممکن است باعث حلقه مسیریابی شود.


**`2. تنظیمات پیشرفته DNS`**

**مسیر: تنظیمات -> تنظیمات DNS -> تنظیمات پیشرفته DNS**

```diff
• Use System Hosts: On
• Add Common DNS Hosts: On
• FakeIP: Off
• Block SVCB and HTTPS Queries: On
• Validate Regional Domain IPs: leave blank
• DNS Hosts: leave blank
```

FakeIP غیرفعال باقی مانده است: رابط v2rayN دارای لیست کاملی از استثناها است
FakeIP برای sing-box در دسترس است و این پروفایل عمومی از Xray استفاده می‌کند.


**`3. CUSTOM DNS`**

**مسیر: تنظیمات -> تنظیمات DNS -> V2ray سفارشی DNS**

غیرفعال رها کنید:

```diff
• V2ray Custom DNS -> HTTP/SOCKS: Enable = Off
• sing-box Custom DNS -> HTTP/SOCKS: Enable = Off
```

دکمه "برای وارد کردن کانفیگ پیش‌فرض DNS کلیک کنید" قالب داخلی v2rayN را بارگیری می‌کند.
JSON سفارشی جدا از دیسک از طریق آن وارد نمی‌شود.


**`4. هسته: تنظیمات پایه`**

**مسیر: تنظیمات -> تنظیم گزینه -> هسته: تنظیمات پایه**

```diff
• Enable UDP: On
• Turn on Sniffing: On
• Sniffing type: http, tls, quic
• Route Only: Off
• Allow connections from the LAN: Off
• Enable fragment: Off
```

اگر شما عمدتاً پروکسی‌ها را به دستگاه‌های دیگر در شبکه محلی توزیع می‌کنید، پارامتر
اجازه اتصال از LAN به صورت جداگانه با در نظر گرفتن امنیت تنظیم می‌شود.


**`5. V2RAYN SETTINGS`**


**مسیر: تنظیمات -> تنظیم گزینه -> تنظیمات v2rayN**

```diff
• Speed Ping Test URL: https://www.gstatic.com/generate_204
• Automatic update interval for Geo files: 24 hours
• Number of concurrent tests during multi-test: 5
```

**`6. تنظیمات گروه اشتراک`**

**مسیر: گروه اشتراک -> تنظیمات گروه اشتراک -> *گروه* -> ویرایش** 

```diff
• Automatic update interval: 60 minutes
```

می‌توان بازه تجدید اشتراک را تا ۱۲۰ دقیقه افزایش داد.


**`7. تنظیمات حالت TUN`**

**مسیر: تنظیمات -> تنظیم گزینه -> تنظیمات حالت TUN**

```diff
• Auto Route: On
• Strict Route: On
• Stack: gvisor
• MTU: 4000
• Enable IPv6 Address: Off
• Legacy TUN Protect: On
```


**`8. مسیریابی RU-DIRECT`**

**مسیر: تنظیمات -> تنظیمات منطقه‌ای -> روسیه**


**`9. UPDATE`**

**مسیر: راهنما -> بررسی به‌روزرسانی**

اجزای کلاینت را به‌روزرسانی کنید.

سپس روی دکمه بارگذاری مجدد در منوی بالا کلیک کنید.


**`10. APPLICATION`**

• در تمام پنجره‌های تغییر یافته روی تأیید کلیک کنید.

• روی بارگذاری مجدد یا اتصال مجدد v2rayN کلیک کنید.

• مسیردهی RU-DIRECT مستقیماً در v2rayN انتخاب شده است.

• RU-DIRECT در سمت راست دکمه فعال‌سازی TUN فعال است: «RUv1-All except RF» را انتخاب کنید.

• برای GLOBAL، «RUv1-All» را انتخاب کنید.

---

</details>

---

</details>
 
**`Throne Instructions:`**

https://wiki.aeza.net/en/guides/throne/

**`دستورالعمل‌ها Streisand، v2Box:`**

**[راه‌اندازی Streisand، v2Box روی iOS (آینه)](https://web.archive.org/web/https://vpnpanels.com/ru/p/setup-v2ray-ios/)**
  
**`Nekobox instructions:`**

https://hiddify.com/manager/client-software-on-android/Tutorial-for-Nekobox-app/
  
**`Hiddify instructions:`**

https://hiddify.com/manager/client-software-on-desktop/Tutorial-for-HiddifyN-software/

https://hiddify.com/app/How-to-use-Hiddify-app/

---

### `راهنمای کلاینت‌های روترهای OpenWrt، دستگاه‌های NAS و سیستم‌های Linux:`

<details>
<summary><code><strong> ShellCrash دستورالعمل‌ها </strong></code></summary>

### `ShellCrash`

**https://github.com/juewuy/ShellCrash**

**`1.`** **یک گزینه عمومی برای انواع پلتفرم‌ها: روترهای OpenWrt و فریمور مشتق، NAS، Docker و سیستم‌های Linux. سازگار با OpenWrt، Padavan، Pandora، ASUS Merlin، Debian، Ubuntu، CentOS، Armbian، Linux/BusyBox، Docker، Synology و PVE.**

**`2.`** **هسته:** Mihomo/Sing-box.

**`3.`** **چه چیزهایی را پشتیبانی می‌کند؟** TUN، REDIRECT، PROXY، nftables/iptables، قوانین مسیریابی، قوانین برای دستگاه‌های شبکه محلی.

**`4.`**  **بررسی سلامت خودکار و انتخاب گره‌ها در پس‌زمینه، مطابق با نمونه Karing، در دسترس است.**

پشتیبانی از به‌روزرسانی خودکار اشتراک‌ها، کانفیگ‌ها و قوانین بر اساس برنامه زمان‌بندی شده. به عنوان یک سیاست محلی در سمت کاربر کانفیگ شده است: از طریق قالب کاربر. بررسی و انتخاب خودکار گره‌ها در پس‌زمینه هنگام استفاده از گروه‌های مناسب Mihomo یا sing-box در دسترس است: برای Mihomo - `url-test` یا `fallback`؛ برای sing-box - `urltest`.

  الف. قالب کاربر، گروه `url-test` Mihomo مشابه Karing Auto Select است.

  ب. قالب کاربر، گروه `urltest` Sing-box با `url-test` Mihomo متفاوت است و نیازمند تنظیمات متفاوت است - اما همچنین مشابه Karing Auto Select است (`urltest` ما در این راهنما درباره Sing-box بحث نمی‌کنیم.).

  اصل عملکرد `url-test` Mihomo و `urltest` Sing-box (نقاط «a» و «b»):

  - به‌طور دوره‌ای درخواست تأیید را از طریق هر گره ارسال می‌کند؛
  - تأخیر را اندازه‌گیری می‌کند؛
  - گره با بهترین نتیجه را انتخاب می‌کند؛
  - آزمایش را در فواصل مشخص تکرار می‌کند؛
  - ارتباطات جدید را به بهترین گره منتقل می‌کند.
  - پارامتر تحمل حداقل تفاوت در تأخیر لازم برای سوئیچ کردن را تعیین می‌کند. این از پرش مداوم بین گره‌ها با نتایج تقریباً یکسان محافظت می‌کند.

  **نتیجه نکات 4-الف و 4-ب: کاربر اشتراک YAML Clash را دانلود می‌کند (هنگامی که هسته Mihomo در ShellCrash انتخاب شده است) و از اشتراک خودکار استفاده می‌کند.** در صورت لزوم (اما نه الزاماً) یک قالب کلاینت محلی `url-test` را در کلاینت ShellCrash اضافه می‌کند، یعنی پروفایل YAML از نکته 10.

  V. قالب کلاینت، گروه `fallback` (رزرو خودکار) همچنین بررسی‌های پس‌زمینه را انجام می‌دهد، اما نه سریع‌ترین نود، بلکه اولین نود موجود در یک ترتیب مشخص را انتخاب می‌کند. `fallback` V **ShellCrash** - این معادل `Auto Switch` در کلاینت **PassWall2** است.

**`5.`** **چه نوع اشتراک‌هایی را قبول می‌کند؟** اشتراک‌های Clash YAML را به‌صورت بومی می‌پذیرد. اشتراک‌های معمولی (از رشته‌های مرسوم vless://، ss://، trojan:// و غیره) و Base64 هنگام وارد کردن به‌صورت خودکار به فرمت Clash تبدیل می‌شوند.

**`6.`** **قوانین GEO.** ShellCrash شامل مجموعه‌ها و قالب‌های آماده از قوانین Geo، به‌روزرسانی‌های خودکار GeoSite/GeoIP و کانفیگ‌های محبوب مانند ACL4SSR است، اما عمدتاً برای چین می‌باشد. هیچ سیاست آماده‌ای برای روسیه یا ایران در نصب استاندارد وجود ندارد؛ شما باید آن را یا از طریق کلاینت یا در خود اشتراک با کانفیگ‌ها کانفیگ کنید. برای فایل کانفیگ نهایی کلاینت ShellCrash برای روسیه، به نکته ۱۰ مراجعه کنید. برای یک کاربر معمولی، ۹ نکته کافی است، زیرا تمام قوانین GEO قبلاً در اشتراک‌های Clash این مخزن Igareck ساخته شده‌اند.

**`۷.`** **اشتراک‌های Clash. برای راحتی کاربران، یک پروفایل آماده YAML با بررسی خودکار سلامت از قبل در اشتراک‌های Clash این مخزن Igareck تعبیه شده است:**

- اشتراک‌های Clash برای کاربران روسیه (RU-DIRECT به‌طوری که تمامی سایت‌های روسیه بدون VPN باز شوند): 

https://github.com/igareck/vpn-configs-for-russia/tree/main/Export/Clash/RU_DIRECT

- اشتراک‌های Clash برای نسخه بین‌المللی (برای کشورهای دیگر که RU-DIRECT نیاز نیست): 

https://github.com/igareck/vpn-configs-for-russia/tree/main/Export/Clash/GLOBAL

**`8.`** **چگونه اشتراک‌های Clash را به ShellCrash اضافه کنیم؟**

<details>
<summary><code> جزئیات را گسترش دهید </code></summary>

ابتدا به روتر متصل شوید:

```diff
ssh root@192.168.1.1
```

سپس ShellCrash را اجرا کنید:

```diff
crash
```

بعد از این، یک منوی متنی با پیام زیر ظاهر خواهد شد:

```diff
Please enter a number >
or
请输入对应数字 >
```

یعنی بعد از وارد کردن `crash` خود را در **منوی تعاملی اصلی ShellCrash** می‌بینیم، ۱۰ نقطه دیجیتال از ۰ تا ۹ در دسترس است:

```diff
1 — Start / Restart Service
    Start or restart ShellCrash

2 — Feature Settings
    Function settings: operating mode, DNS, ports, kernel and other parameters

3 — Stop Service
    Stop ShellCrash

4 — Startup Settings
    Autostart settings when the device boots

5 — Scheduled Tasks
    Task Scheduler: Automatically update subscriptions, core, etc.

6 — Configuration Management
    Manage configurations, subscriptions and providers

7 — Access & Control
    Configure device access, routing, and management rules

8 — Tools & Optimization
    Tools, diagnostics and optimization

9 — Updates & Support
    ShellCrash update, kernels, panels and support section

0 — Exit Script
    Exit ShellCrash menu
```

مدیریت کانفیگ (Configuration Management) در `6` قرار دارد.

بعد، یک شماره وارد کنید و **Enter** را بزنید: شما باید دقیقاً شماره `6` را وارد کنید:

```diff
6
```

بعد در منو **مدیریت کانفیگ / منوی مدیریت کانفیگ**:

```diff
a - add configuration/subscription provider (Add provider);
b — generate local configuration;
c — generate online configuration;
d — clear the list of suppliers;
e — select a custom configuration file.
```

حرف/دستور `a` را وارد کنید:

```diff
a
```

پس از انتخاب `a` منویی باز خواهد شد **افزودن ارائه‌دهنده / ویرایشگر ارائه‌دهنده فردی**:

```diff
1 — set the name of the supplier;
2 — set a link or path;
3 — configure local override;
a — save supplier;
b - generate local configuration only from this provider;
c - generate online configuration only from this provider;
e - load this configuration directly without conversion.
```

یک شماره/دستور `1` را وارد کنید:

```diff
1
```

سپس نام اشتراک را وارد کنید:

```diff
Igareck BLACK VLESS Mobile
```

سپس شماره/دستور `2` را وارد کنید:

```diff
2
```

لینک را الصاق کنید:

```diff
https://raw.githack.com/igareck/vpn-configs-for-russia/main/Clash/BLACK_VLESS_RUS_mobile.yaml
```

بعد از آن، ارائه‌دهنده کانفیگ را ذخیره کنید، نامه/دستور `a` را وارد کنید:

```diff
a
```

بعدی `e` را انتخاب کنید — این کانفیگ را مستقیماً بدون تبدیل بارگذاری کنید. `e` در ویرایشگر فروشنده YAML را دانلود کرده و به‌عنوان کانفیگ آماده بدون تبدیل اعمال خواهد کرد:

```diff
e
```

**دنباله نهایی:**

```diff
6 → a → 1 → Igareck BLACK VLESS Mobile → 2 → Link → a → e
```

اگر به‌طور تصادفی منوی اشتباهی را وارد کردید، `0` را وارد کرده و **Enter** را فشار دهید تا یک سطح به عقب بازگردید:

```diff
0
```

---

</details>

**`9.`** **راه‌اندازی اشتراک ShellCrash برای به‌روزرسانی خودکار هر ساعت یک‌بار:**

<details>
<summary><code> جزئیات را گسترش دهید </code></summary>

ابتدا به روتر متصل شوید:

```diff
ssh root@192.168.1.1
```

سپس ShellCrash را اجرا کنید:

```diff
crash
```

سپس، هر بار یک مقدار وارد کنید و هر بار **Enter** را فشار دهید:

```diff
5 → 1 → 5 → 3 → 1 → 1
```

توضیح:

```diff
5 - open Scheduled Tasks / Task Scheduler.
1 - Add Task / Add a task.
5 — Hot update online subscriptions (without restart) — update your online subscription without restarting ShellCrash.
3 - Every N hours / Every N hours.
1 - perform every 1 hour.
1 — confirm adding the task.
```

**چگونه بررسی کنیم؟**

برای بازگشت به منوی **وظایف زمان‌بندی‌شده**، `2` را فشار دهید:

```diff
2
```

این **مدیریت وظایف / مدیریت کارها** است. وظیفه به‌روزرسانی اشتراک باید در فهرست با فاصله یک ساعته ظاهر شود. برای بازگشت از `0` استفاده کنید:

```diff
0
```

---

</details>

**`10.`** **پروفایل YAML آماده برای ShellCrash با بررسی خودکار سلامت برای روسیه (RU-DIRECT، به طوری که تمام سایت‌های RU بدون VPN اجرا شوند) از طریق قالب کلاینت (url-test Mihomo، نکته ۴-a):**

***توضیح: این پاراگراف 10 اختیاری است**، فقط برای کاربران پیشرفته لازم است اگر بخواهید هر گزینه‌ای از اشتراک‌های Clash را به صورت دستی تغییر دهید یا تنظیمات را به صورت جهانی برای هر اشتراک دریافتی با اضافه کردن آن‌ها به خود کلاینت اعمال کنید. تنظیماتی که در خود کلاینت ShellCrash نوشته می‌شوند، اگر مطابقت داشته باشند، تنظیمات تمام اشتراک‌های دریافتی Clash را بازنویسی می‌کنند. برای کاربران عادی، نقاط 7، 8، 9 و **اشتراک‌های آماده Clash از مخزن Igareck بیش از حد کافی هستند و شامل تمام تنظیمات نقطه 10 نیز می‌شوند.** این کار برای راحتی کاربران طبق اصل انجام شد: یک اشتراک اضافه کنید و بلافاصله از آن استفاده کنید.*

**بلوک تنظیمات برای ShellCrash در سه فایل توزیع شده است:** **`General Settings`** + **`Groups`** + **`Rules`**

<details>
<summary><code> تنظیمات عمومی user.yaml پارامترها </code></summary>

**تنظیمات عمومی** `user.yaml`

انتخاب کنید:

```diff
ssh root@192.168.1.1
→ crash → 6 → e → 5
```

ShellCrash یک فایل user.yaml ایجاد می‌کند و محل آن را نمایش می‌دهد. سپس فایل باید از طریق WinSCP، vi یا nano باز شود:

```diff
$CRASHDIR/yamls/user.yaml
```

چسباندن پارامترهای عمومی:

```diff
mode: rule
unified-delay: true
tcp-concurrent: true

keep-alive-idle: 300
keep-alive-interval: 60
disable-keep-alive: false

profile:
  store-selected: true
  store-fake-ip: true

dns:
  enable: true
  prefer-h3: false
  ipv6: false
  use-hosts: true
  use-system-hosts: true
  respect-rules: false

  enhanced-mode: fake-ip
  fake-ip-range: 198.18.0.1/16
  fake-ip-filter-mode: blacklist

  fake-ip-filter:
    - "*.lan"
    - "*.local"
    - "localhost"

    - "time.*.com"
    - "time.*.gov"
    - "time.*.apple.com"
    - "time-ios.apple.com"
    - "time1.*.com"
    - "time2.*.com"
    - "time3.*.com"
    - "time4.*.com"
    - "time5.*.com"
    - "time6.*.com"
    - "time7.*.com"

    - "ntp.*.com"
    - "ntp1.*.com"
    - "ntp2.*.com"
    - "ntp3.*.com"
    - "ntp4.*.com"
    - "ntp5.*.com"
    - "ntp6.*.com"
    - "ntp7.*.com"
    - "*.pool.ntp.org"

    - "+.push.apple.com"

    - "+.stun.*.*"
    - "+.stun.*.*.*"
    - "+.stun.*.*.*.*"
    - "+.stun.*.*.*.*.*"
    - "+.stun.playstation.net"

    - "lens.l.google.com"
    - "*.n.n.srv.nintendo.net"
    - "xbox.*.*.microsoft.com"
    - "*.*.xboxlive.com"

    - "*.msftncsi.com"
    - "*.msftconnecttest.com"

    - "WORKGROUP"

  cache-algorithm: arc

  default-nameserver:
    - 8.8.8.8
    - 8.8.4.4
    - 9.9.9.9
    - 94.140.14.14
    - 76.76.2.0
    - 76.76.10.0
    - 1.0.0.1
    - 1.1.1.1
    - 208.67.220.220
    - 208.67.222.222

  nameserver:
    - https://dns.google/dns-query
    - https://dns.quad9.net/dns-query
    - https://dns.adguard-dns.com/dns-query
    - https://freedns.controld.com/p0
    - https://dns.mullvad.net/dns-query
    - https://cloudflare-dns.com/dns-query
    - https://doh.opendns.com/dns-query
    - https://doh.libredns.gr/dns-query
    - https://doh.dns4all.eu/dns-query
    - https://wikimedia-dns.org/dns-query
    - https://dns.hostux.net/dns-query
    - https://blank.dnsforge.de/dns-query

  proxy-server-nameserver:
    - 8.8.8.8
    - 8.8.4.4
    - 9.9.9.9
    - 94.140.14.14
    - 76.76.2.0
    - 76.76.10.0
    - 1.0.0.1
    - 1.1.1.1
    - 208.67.220.220
    - 208.67.222.222
    - system

  direct-nameserver:
    - 8.8.8.8
    - 8.8.4.4
    - 9.9.9.9
    - 94.140.14.14
    - 76.76.2.0
    - 76.76.10.0
    - 1.0.0.1
    - 1.1.1.1
    - 208.67.220.220
    - 208.67.222.222
    - system

  direct-nameserver-follow-policy: false

sniffer:
  enable: true
  force-dns-mapping: true
  parse-pure-ip: true
  override-destination: false

  sniff:
    HTTP:
      ports: [80, 8080-8880]
      override-destination: true

    TLS:
      ports: [443, 8443]

    QUIC:
      ports: [443, 8443]
```

</details>

<details>
<summary><code> گروه‌ها proxy-groups.yaml </code></summary>

**گروه‌ها** `proxy-groups.yaml`

انتخاب کنید:

```diff
ssh root@192.168.1.1
→ crash → 6 → e → 4
```

ShellCrash یک فایل proxy-groups.yaml ایجاد خواهد کرد و مکان آن را نشان می‌دهد.

بعدی:

```diff
1 — add a group manually;
2 — view created groups;
3 — clear groups;
0 - back.
```

اما بهتر است آن را مستقیماً باز کنید:

```diff
$CRASHDIR/yamls/proxy-groups.yaml
```

و گروه‌ها را بدون خط `proxy-groups:` وارد کنید. منوی داخلی به شما امکان نمی‌دهد تمام پارامترها را مانند `include-all`، `exclude-type`، `tolerance`، `lazy` و دیگران تنظیم کنید.

محتویات گروه‌ها را بدون خط `proxy-groups:` جای‌گذاری کنید:

```diff
  - name: "Igareck Auto Select (Auto connect)"
    type: url-test
    include-all: true
    exclude-type: "Direct|Reject|RejectDrop|Compatible|Pass|Dns"
    url: "https://www.gstatic.com/generate_204"
    interval: 300
    tolerance: 150
    lazy: true
    timeout: 5000
    max-failed-times: 2
    expected-status: 204

  - name: "Igareck Manual (Manual Connection)"
    type: select
    proxies:
      - "Igareck Auto Select (Auto connect)"
    include-all: true
    exclude-type: "Direct|Reject|RejectDrop|Compatible|Pass|Dns"
    default-selected: "Igareck Auto Select (Auto connect)"

  - name: "GLOBAL"
    type: select
    proxies:
      - "Igareck Auto Select (Auto connect)"
      - "Igareck Manual (Manual Connection)"
    default-selected: "Igareck Auto Select (Auto connect)"
```

</details>

<details>
<summary><code> قوانین rules.yaml </code></summary>

**قوانین** `rules.yaml`

انتخاب کنید:

```diff
ssh root@192.168.1.1
→ crash → 6 → e → 2
```

ShellCrash یک فایل rules.yaml ایجاد خواهد کرد و مکان آن را نشان می‌دهد.

بعدی:

```diff
1 — add one rule manually;
2 — delete the rule;
3 — clear the rules;
0 - back.
```

اما بهتر است آن را مستقیماً باز کنید:

```diff
$CRASHDIR/yamls/rules.yaml
```

و فقط خطوط قاعده را وارد کنید، بدون خط `rules:`:

```diff
  - DOMAIN-SUFFIX,localhost,DIRECT
  - DOMAIN-SUFFIX,local,DIRECT
  - "DOMAIN-REGEX,^[^.]+$,DIRECT"

  - IP-CIDR,127.0.0.0/8,DIRECT,no-resolve
  - IP-CIDR,10.0.0.0/8,DIRECT,no-resolve
  - IP-CIDR,172.16.0.0/12,DIRECT,no-resolve
  - IP-CIDR,192.168.0.0/16,DIRECT,no-resolve
  - IP-CIDR,169.254.0.0/16,DIRECT,no-resolve
  - IP-CIDR,100.64.0.0/10,DIRECT,no-resolve

  - IP-CIDR6,::1/128,DIRECT,no-resolve
  - IP-CIDR6,fc00::/7,DIRECT,no-resolve
  - IP-CIDR6,fe80::/10,DIRECT,no-resolve

  # Remove the following 4 lines for Global/Non-RU-Direct routing
  # Delete the next 4 lines for Global/Not-RU-Direct routing
  - DOMAIN-SUFFIX,ru,DIRECT
  - DOMAIN-SUFFIX,xn--p1ai,DIRECT
  - GEOSITE,category-ru,DIRECT
  - GEOIP,RU,DIRECT

  - "MATCH,Igareck Manual (Manual Connection)"
```

</details>

**بعد از ذخیره فایل‌ها:**

```diff
ssh root@192.168.1.1
→ crash → 6 → b
```

---

</details>



<details>
<summary><code><strong> راهنمای OpenClash </strong></code></summary>

### `OpenClash`

**https://github.com/vernesong/openclash**

**`1.`** **یکی از شناخته‌شده‌ترین کلاینت‌های OpenWrt+LuCI (و مشتقات سازگار با آن) است.**

**`2.`** **هسته:** Mihomo.

**`3.`** **از چه چیزهایی پشتیبانی می‌کند؟** TUN، REDIRECT، PROXY، nftables/iptables، قوانین مسیریابی، آزمایش URL، بازیابی و متعادل‌سازی.

**`4.`** **بررسی سلامت خودکار و انتخاب گره‌ها در پس‌زمینه، با پیروی از نمونه Karing، در دسترس است.**

  توسط هسته Mihomo قدرت گرفته است، بنابراین گروه‌های استاندارد Mihomo در اینجا در دسترس هستند `url-test` و `fallback`. از طریق این گروه‌ها، بررسی و انتخاب خودکار گره‌ها در پس‌زمینه پیکربندی شده است. به‌عنوان یک سیاست محلی در سمت کلاینت پیکربندی شده است: از طریق یک گروه محلی یا ماژول بازنویسی.

  الف. گروه `url-test` Mihomo معادل Karing Auto Select است:

  - به‌طور دوره‌ای درخواست تأیید را از طریق هر گره ارسال می‌کند؛
  - تأخیر را اندازه‌گیری می‌کند؛
  - گره با بهترین نتیجه را انتخاب می‌کند؛
  - آزمایش را در فواصل مشخص تکرار می‌کند؛
  - ارتباطات جدید را به بهترین گره منتقل می‌کند.
  - پارامتر تحمل حداقل تفاوت در تأخیر لازم برای سوئیچ کردن را تعیین می‌کند. این از پرش مداوم بین گره‌ها با نتایج تقریباً یکسان محافظت می‌کند.

  **نتیجه نقطه ۴-الف: کاربر اشتراک YAML کلش را دانلود کرده و از اشتراک خودکار استفاده می‌کند.** در صورت لزوم (اما نه الزامی) یک گروه محلی (ماژول بازنویسی) اضافه می‌کند، سپس گروه `url-test` را در کلاینت OpenClash پیکربندی می‌کند، یعنی پروفایل از نقطه ۱۰.

  ب. گروه `fallback` (پشتیبان خودکار) نیز بررسی‌های پس‌زمینه انجام می‌دهد، اما نه سریع‌ترین نود، بلکه اولین نود در دسترس در یک ترتیب مشخص را انتخاب می‌کند. `fallback` V **OpenClash** - این یک آنالوگ `Auto Switch` در کلاینت **PassWall2** است.

**`5.`** **چه نوع اشتراک‌هایی را قبول می‌کند؟** اشتراک‌های Clash YAML را به‌صورت بومی می‌پذیرد. اشتراک‌های معمولی (از رشته‌های مرسوم vless://، ss://، trojan:// و غیره) و Base64 هنگام وارد کردن به‌صورت خودکار به فرمت Clash تبدیل می‌شوند.

**`6.`** **قوانین GEO.** از GeoIP، GeoSite، MMDB و ارائه‌دهندگان قانون پشتیبانی می‌کند؛ کیت‌های از پیش ساخته شده عمدتاً برای چین طراحی شده‌اند. در نصب استاندارد هیچ سیاست آماده‌ای برای روسیه یا ایران وجود ندارد؛ شما باید آن را یا از طریق کلاینت یا در خود اشتراک با کانفیگ‌ها کانفیگ کنید. برای فایل کانفیگ نهایی برای کلاینت OpenClash برای روسیه، به نکته ۱۰ مراجعه کنید. برای یک کاربر عادی، ۹ نکته کافی خواهد بود، زیرا تمام قوانین GEO قبلاً در اشتراک‌های Clash این مخزن Igareck ساخته شده‌اند.

**`7.`** **یک پروفایل YAML آماده با بررسی سلامت خودکار قبلاً در اشتراک‌های Clash این مخزن Igareck برای راحتی کاربران ساخته شده است:**

- اشتراک‌های Clash برای کاربران روسیه (RU-DIRECT به‌طوری که تمامی سایت‌های روسیه بدون VPN باز شوند): 

https://github.com/igareck/vpn-configs-for-russia/tree/main/Export/Clash/RU_DIRECT

- اشتراک‌های Clash برای نسخه بین‌المللی (برای کشورهای دیگر که RU-DIRECT نیاز نیست): 

https://github.com/igareck/vpn-configs-for-russia/tree/main/Export/Clash/GLOBAL

**`8.`** **چگونه اشتراک‌های Clash را به OpenClash اضافه کنیم؟**

در لوسی آی:

```diff
Services → OpenClash → Config Subscription → Add
```

پر کردن جایگزین:

```diff
Enabled: enabled
Config Alias: Igareck BLACK VLESS Mobile
Subscribe Address: YAML link
User-Agent: Mihomo or Clash.Meta
Subscription Conversion: disabled
```

سپس:

```diff
Save & Apply → Update Subscription
```

**`9.`** **راه‌اندازی تمدید خودکار اشتراک OpenClash:**

در لوسی آی:

```diff
Services → OpenClash → Config Subscription → Auto Update: Enabled
Update Mode: Loop Mode
Update Interval: 1 hour
```
   
**`10.`** **پروفایل YAML آماده برای OpenClash با بررسی خودکار سلامت روسیه (RU-DIRECT، تا همه سایت های RU بدون VPN بمانند) از طریق گروه محلی یا ماژول بازنویسی (url-test Mihomo، نقطه ۴-a):**

***توضیح: این پاراگراف 10 اختیاری است**، فقط برای کاربران پیشرفته لازم است اگر بخواهید هر گزینه‌ای از اشتراک‌های Clash را به صورت دستی تغییر دهید یا تنظیمات را به صورت جهانی برای هر اشتراک دریافتی با اضافه کردن آن‌ها به خود کلاینت اعمال کنید. تنظیماتی که در خود کلاینت OpenClash نوشته می‌شوند، اگر مطابقت داشته باشند، تنظیمات تمام اشتراک‌های دریافتی Clash را بازنویسی می‌کنند. برای کاربران عادی، نقاط 7، 8، 9 و **اشتراک‌های آماده Clash از مخزن Igareck بیش از حد کافی هستند و شامل تمام تنظیمات نقطه 10 نیز می‌شوند.** این کار برای راحتی کاربران طبق اصل انجام شد: یک اشتراک اضافه کنید و بلافاصله از آن استفاده کنید.*

**بلوک تنظیمات برای OpenClash به سه گروه تقسیم شده است:** **`تنظیمات عمومی و Sniffer`** + **`Groups`** + **`Rules`** + **`DNS Settings`**

<details>
<summary><code> تنظیمات عمومی و Sniffer </code></summary>

مسیر به LuCI:

```diff
Services
→ OpenClash
→ Overwrite Settings
→ Meta Settings
```

روشن کردن:

```diff
Enable Tcp Concurrent
Enable Unified Delay
Enable Sniffer
Forced Sniff Pure IP
Custom Sniffer Settings
```

در فیلد تنظیمات سفارشی Sniffer، فقط وارد کنید:

```diff
sniffer:
  enable: true
  force-dns-mapping: true
  parse-pure-ip: true
  override-destination: false
  sniff:
    HTTP:
      ports: [80, 8080-8880]
      override-destination: true
    TLS:
      ports: [443, 8443]
    QUIC:
      ports: [443, 8443]
```

---

</details>


<details>
<summary><code> گروه‌ها </code></summary>

مسیر به LuCI:

```diff
Services
→ OpenClash
→ Config Manage
→ Config File List
→ For active YAML, select Other: Servers Manage
→ Apply
```

در صفحه مدیریت سرورها و گروه‌ها که باز می‌شود، ابتدا روی **خواندن کانفیگ** کلیک کنید

تنها پس از آن گروه‌ها را می‌توان ایجاد کرد از طریق:

```diff
Proxy Groups → Add
```

OpenClash به‌طور صریح هشدار می‌دهد که قبل از تغییر باید کانفیگ فعلی را خواند.

سپس موارد زیر یکی یکی ایجاد می‌شوند: Igareck Auto Select (اتصال خودکار) → Igareck دستی (اتصال دستی) → GLOBAL

**1. Igareck Auto Select**

```diff
Proxy Groups → Add
```

```diff
Group Type:
URL-Test

Group Name:
Igareck Auto Select (Auto connect)

Test URL:
https://www.gstatic.com/generate_204

Test Interval(s):
300

Tolerance(ms):
150

Other Group:
leave blank
```

در قسمت سایر پارامترها وارد کنید:

```diff
    include-all: true
    exclude-type: "Direct|Reject|RejectDrop|Compatible|Pass|Dns"
    lazy: true
    timeout: 5000
    max-failed-times: 2
    expected-status: 204
```

سپس **تأیید تنظیمات**

**2. دفترچه راهنمای Igareck**

```diff
Proxy Groups → Add
```

```diff
Group Type:
Manual-Select

Group Name:
Igareck Manual (Manual Connection)

Other Group:
Igareck Auto Select (Auto connect)
```

در قسمت سایر پارامترها وارد کنید:

```diff
    include-all: true
    exclude-type: "Direct|Reject|RejectDrop|Compatible|Pass|Dns"
    default-selected: "Igareck Auto Select (Auto connect)"
```

سپس **تأیید تنظیمات**

**3. GLOBAL**

```diff
Proxy Groups → Add
```

```diff
Group Type:
Manual-Select

Group Name:
GLOBAL

Other Group:
Igareck Auto Select (Auto connect)
Igareck Manual (Manual Connection)
```

در قسمت سایر پارامترها وارد کنید:

```diff
    default-selected: "Igareck Auto Select (Auto connect)"
```

سپس **تأیید تنظیمات**

پس از ایجاد هر سه گروه، به صفحه مدیریت سرورها و گروه‌ها بازگردید و روی **اعمال تنظیمات** کلیک کنید.

---

</details>


<details>
<summary><code> قوانین </code></summary>

مسیر به LuCI:

```diff
Services
→ OpenClash
→ Overwrite Settings
→ Rules Setting
→ Custom Clash Rules: Enable
→ Priority
```

در فیلد Priority، کل بخش قوانین را وارد کنید:

```diff
rules:
  - DOMAIN-SUFFIX,localhost,DIRECT
  - DOMAIN-SUFFIX,local,DIRECT
  - "DOMAIN-REGEX,^[^.]+$,DIRECT"

  - IP-CIDR,127.0.0.0/8,DIRECT,no-resolve
  - IP-CIDR,10.0.0.0/8,DIRECT,no-resolve
  - IP-CIDR,172.16.0.0/12,DIRECT,no-resolve
  - IP-CIDR,192.168.0.0/16,DIRECT,no-resolve
  - IP-CIDR,169.254.0.0/16,DIRECT,no-resolve
  - IP-CIDR,100.64.0.0/10,DIRECT,no-resolve

  - IP-CIDR6,::1/128,DIRECT,no-resolve
  - IP-CIDR6,fc00::/7,DIRECT,no-resolve
  - IP-CIDR6,fe80::/10,DIRECT,no-resolve

  # Remove the following 4 lines for Global/Non-RU-Direct routing
  # Delete the next 4 lines for Global/Not-RU-Direct routing
  - DOMAIN-SUFFIX,ru,DIRECT
  - DOMAIN-SUFFIX,xn--p1ai,DIRECT
  - GEOSITE,category-ru,DIRECT
  - GEOIP,RU,DIRECT

  - "MATCH,Igareck Manual (Manual Connection)"
```

**بعد از این:**

```diff
Commit Settings → Apply Settings
```

---

</details>

<details>
<summary><code> DNS تنظیمات </code></summary>

در اینجا 2 گزینه وجود دارد: `وقتی DNS قبلاً از اشتراک Igareck می‌آید` و `اگر DNS تنها باید به صورت محلی پیکربندی شود`

**1. وقتی تنظیمات DNS قبلاً از اشتراک Igareck آمده باشد**

مسیر به LuCI:

```diff
Services
→ OpenClash
→ Overwrite Settings
→ DNS Settings
```

نصب:

```diff
Custom DNS Setting: Disable
Respect Rules: Disable
Append Upstream DNS: Disable
Append Default DNS: Disable
Fake-IP Range: 198.18.0.1/16
Persistence Fake-IP: Enable
```

**2. اگر DNS نیاز به پیکربندی محلی داشته باشد**

مسیر به LuCI:

```diff
Services
→ OpenClash
→ Overwrite Settings
→ DNS Settings
→ Custom DNS Setting: Enable
```

بخش زیر ظاهر خواهد شد:

```diff
Add Custom DNS Servers → Add
```

رابط OpenClash فقط به شما اجازه می‌دهد گروه‌ها را اضافه کنید:

```diff
nameserver
fallback
default-nameserver
```

این بسیار غیرکارآمد و زمان‌بر است، بنابراین بهتر است کانفیگ کامل و دقیق DNS را مستقیماً با اشتراک Igareck به دست آورید، نه اینکه آن را از طریق LuCI OpenClash جمع‌آوری کنید.

</details>

---

</details>


<details>
<summary><code><strong> راهنمای Nikki </strong></code></summary>

### `Nikki`

**https://github.com/nikkinikki-org/OpenWrt-nikki**

**`1.`** **یک جایگزین مدرن و جمع‌وجورتر برای OpenClash.**

   **به عنوان یک پروکسی شفاف مدرن برای OpenWrt 24.10+، Linux 5.13+ با firewall4/nftables قرار گرفته است.** 

**`2.`** **هسته:** Mihomo.

**`3.`** **چه چیزی را پشتیبانی می‌کند؟** TUN، REDIRECT، PROXY، firewall4/nftables و قوانین مسیریابی. Nikki از firewall3/iptables قدیمی پشتیبانی نمی‌کند.

**`4.`** **بررسی سلامت خودکار و انتخاب گره‌ها در پس‌زمینه، با پیروی از نمونه Karing، در دسترس است.**

  به عنوان یک سیاست محلی در سمت کلاینت از طریق «Profile Mixin» پیکربندی شده است. 

  Nikki به‌طور خاص ارائه می‌دهد:
   - Profile Mixin;
   - Profile Editor.

  **کاربر اشتراک YAML کلش را دانلود می‌کند و از اشتراک خودکار بهره می‌برد.** در صورت لزوم (اما لزوماً نه) به‌صورت محلی در Nikki در «Profile Mixin» پروفایل آماده از مرحله ۸ اضافه می‌شود.

  نیکی با هر به‌روزرسانی:
   
  `Downloads profile` → `اعمال "Profile Mixin" محلی` → `اجرای کانفیگ نهایی`

**`5.`** **چه اشتراک‌هایی را می‌پذیرد؟** فقط اشتراک‌های Clash YAML را می‌پذیرد. هنگام وارد کردن فرمت‌های دیگر خطا رخ خواهد داد.

**`6.`** **قوانین GEO.** در نصب استاندارد، سیاست آماده‌ای برای روسیه یا ایران وجود ندارد؛ شما باید آن را یا از طریق کلاینت و یا در خود اشتراک با کانفیگ‌ها کانفیگ کنید. برای فایل کانفیگ نهایی کلاینت Nikki برای روسیه، به بند 10 مراجعه کنید. برای یک کاربر عادی، 9 بند کافی است، زیرا تمام قوانین GEO از قبل در اشتراک‌های Clash این مخزن Igareck ساخته شده‌اند.

**`7.`** **یک پروفایل YAML آماده با بررسی سلامت خودکار قبلاً در اشتراک‌های Clash این مخزن Igareck برای راحتی کاربران ساخته شده است:**

- اشتراک‌های Clash برای کاربران روسیه (RU-DIRECT به‌طوری که تمامی سایت‌های روسیه بدون VPN باز شوند): 

https://github.com/igareck/vpn-configs-for-russia/tree/main/Export/Clash/RU_DIRECT

- اشتراک‌های Clash برای نسخه بین‌المللی (برای کشورهای دیگر که RU-DIRECT نیاز نیست): 

https://github.com/igareck/vpn-configs-for-russia/tree/main/Export/Clash/GLOBAL

**`8.`** **چگونه اشتراک‌های Clash را به Nikki اضافه کنیم؟**

در لوسی آی:

```diff
Services → Nikki → Profile → Subscription → Add

In some versions the path is shown as:

Services → Nikki → Configuration Files → Subscriptions
```

پر کردن جایگزین:

```diff
Subscription Name: Igareck BLACK VLESS Mobile
Subscription URL: YAML link
User Agent: clash.meta or mihomo
Prefer: Remote
```

سپس:

```diff
Save & Apply → Update
```

پس از به‌روزرسانی موفق، در تنظیمات اصلی Nikki، یک پروفایل نمایش انتخاب کنید:

```diff
subscription: Igareck BLACK VLESS Mobile
```

**`9.`** **تنظیم تمدید خودکار اشتراک Nikki:**

در لوسی آی:

```diff
Services → Nikki → Profile → Subscription → Edit
Auto Update: Enabled
Update Interval: 1 hour
```

**`10.`** **پروفایل آماده YAML برای نیکی با بررسی خودکار سلامت برای روسیه (RU-DIRECT، به طوری که همه سایت‌های RU بدون VPN کار کنند) از طریق "Profile Mixin":**

***توضیح: این بند ۱۰ اختیاری است**، تنها در صورتی برای کاربران پیشرفته لازم است که بخواهید هرگونه گزینه اشتراک Clash را به صورت دستی تغییر دهید یا تنظیمات را برای هر اشتراک دریافتی به صورت جهانی اعمال کنید با افزودن آن‌ها به خود کلاینت. تنظیماتی که در خود کلاینت Nikki ذخیره می‌شوند، تنظیمات تمام اشتراک‌های دریافتی Clash را در صورت تطابق بازنویسی خواهند کرد. برای کاربران معمولی، بندهای ۷، ۸، ۹ و **اشتراک‌های آماده Clash از مخزن Igareck بیش از کافی هستند و شامل همه تنظیمات بند ۱۰ می‌باشند.** این کار برای راحتی کاربران انجام شده است بر اساس اصل: یک اشتراک اضافه کنید و بلافاصله از آن استفاده کنید.*

<details>
<summary><code> جزئیات را گسترش دهید </code></summary>

در نیکی، راحت‌ترین روش برای وارد کردن یک بلوک از طریق فایل میکسین است.

مسیر:

```diff
Services
→ Nikki
→ Editor
→ Choose File
→ File for Mixin
```

این فایل است:

```diff
/etc/nikki/mixin.yaml
```

بلوک کامل زیر را آنجا بچسبانید:

*نکته: نیکی-YAML با YAML استاندارد متفاوت است به این صورت که بلوک `rules:` به نام `nikki-rules:` نامیده می‌شود.*

```diff
# ============================================================
# Igareck Nikki Client Profile
# Settings profile without built-in proxies.
# Proxies must come from the connected subscription.
#
# Mode:
# - automatic selection of the best proxy;
# - manual proxy selection;
# - RU-DIRECT.
# ============================================================


mode: rule
unified-delay: true
tcp-concurrent: true

keep-alive-idle: 300
keep-alive-interval: 60
disable-keep-alive: false

profile:
  store-selected: true
  store-fake-ip: true

dns:
  enable: true
  prefer-h3: false
  ipv6: false
  use-hosts: true
  use-system-hosts: true
  respect-rules: false

  enhanced-mode: fake-ip
  fake-ip-range: 198.18.0.1/16
  fake-ip-filter-mode: blacklist

  fake-ip-filter:
    - "*.lan"
    - "*.local"
    - "localhost"

    - "time.*.com"
    - "time.*.gov"
    - "time.*.apple.com"
    - "time-ios.apple.com"
    - "time1.*.com"
    - "time2.*.com"
    - "time3.*.com"
    - "time4.*.com"
    - "time5.*.com"
    - "time6.*.com"
    - "time7.*.com"

    - "ntp.*.com"
    - "ntp1.*.com"
    - "ntp2.*.com"
    - "ntp3.*.com"
    - "ntp4.*.com"
    - "ntp5.*.com"
    - "ntp6.*.com"
    - "ntp7.*.com"
    - "*.pool.ntp.org"

    - "+.push.apple.com"

    - "+.stun.*.*"
    - "+.stun.*.*.*"
    - "+.stun.*.*.*.*"
    - "+.stun.*.*.*.*.*"
    - "+.stun.playstation.net"

    - "lens.l.google.com"
    - "*.n.n.srv.nintendo.net"
    - "xbox.*.*.microsoft.com"
    - "*.*.xboxlive.com"

    - "*.msftncsi.com"
    - "*.msftconnecttest.com"

    - "WORKGROUP"

  cache-algorithm: arc

  default-nameserver:
    - 8.8.8.8
    - 8.8.4.4
    - 9.9.9.9
    - 94.140.14.14
    - 76.76.2.0
    - 76.76.10.0
    - 1.0.0.1
    - 1.1.1.1
    - 208.67.220.220
    - 208.67.222.222

  nameserver:
    - https://dns.google/dns-query
    - https://dns.quad9.net/dns-query
    - https://dns.adguard-dns.com/dns-query
    - https://freedns.controld.com/p0
    - https://dns.mullvad.net/dns-query
    - https://cloudflare-dns.com/dns-query
    - https://doh.opendns.com/dns-query
    - https://doh.libredns.gr/dns-query
    - https://doh.dns4all.eu/dns-query
    - https://wikimedia-dns.org/dns-query
    - https://dns.hostux.net/dns-query
    - https://blank.dnsforge.de/dns-query

  proxy-server-nameserver:
    - 8.8.8.8
    - 8.8.4.4
    - 9.9.9.9
    - 94.140.14.14
    - 76.76.2.0
    - 76.76.10.0
    - 1.0.0.1
    - 1.1.1.1
    - 208.67.220.220
    - 208.67.222.222
    - system

  direct-nameserver:
    - 8.8.8.8
    - 8.8.4.4
    - 9.9.9.9
    - 94.140.14.14
    - 76.76.2.0
    - 76.76.10.0
    - 1.0.0.1
    - 1.1.1.1
    - 208.67.220.220
    - 208.67.222.222
    - system

  direct-nameserver-follow-policy: false

sniffer:
  enable: true
  force-dns-mapping: true
  parse-pure-ip: true
  override-destination: false

  sniff:
    HTTP:
      ports: [80, 8080-8880]
      override-destination: true

    TLS:
      ports: [443, 8443]

    QUIC:
      ports: [443, 8443]

proxy-groups:
  - name: "Igareck Auto Select (Auto connect)"
    type: url-test
    include-all: true
    exclude-type: "Direct|Reject|RejectDrop|Compatible|Pass|Dns"
    url: "https://www.gstatic.com/generate_204"
    interval: 300
    tolerance: 150
    lazy: true
    timeout: 5000
    max-failed-times: 2
    expected-status: 204

  - name: "Igareck Manual (Manual Connection)"
    type: select
    proxies:
      - "Igareck Auto Select (Auto connect)"
    include-all: true
    exclude-type: "Direct|Reject|RejectDrop|Compatible|Pass|Dns"
    default-selected: "Igareck Auto Select (Auto connect)"

  - name: "GLOBAL"
    type: select
    proxies:
      - "Igareck Auto Select (Auto connect)"
      - "Igareck Manual (Manual Connection)"
    default-selected: "Igareck Auto Select (Auto connect)"

nikki-rules:
  - DOMAIN-SUFFIX,localhost,DIRECT
  - DOMAIN-SUFFIX,local,DIRECT
  - "DOMAIN-REGEX,^[^.]+$,DIRECT"

  - IP-CIDR,127.0.0.0/8,DIRECT,no-resolve
  - IP-CIDR,10.0.0.0/8,DIRECT,no-resolve
  - IP-CIDR,172.16.0.0/12,DIRECT,no-resolve
  - IP-CIDR,192.168.0.0/16,DIRECT,no-resolve
  - IP-CIDR,169.254.0.0/16,DIRECT,no-resolve
  - IP-CIDR,100.64.0.0/10,DIRECT,no-resolve

  - IP-CIDR6,::1/128,DIRECT,no-resolve
  - IP-CIDR6,fc00::/7,DIRECT,no-resolve
  - IP-CIDR6,fe80::/10,DIRECT,no-resolve

  # Remove the following 4 lines for global/Not-RU-Direct mode.
  # Delete the next 4 lines for Global/Not-RU-Direct routing.
  - DOMAIN-SUFFIX,ru,DIRECT
  - DOMAIN-SUFFIX,xn--p1ai,DIRECT
  - GEOSITE,category-ru,DIRECT
  - GEOIP,RU,DIRECT

  - "MATCH,Igareck Manual (Manual Connection)"
```

سپس:

```diff
Save & Apply
```

یا، اگر راه‌اندازی مجدد معمولی تغییرات را اعمال نکرد:

```diff
Force Apply
```

همچنین بررسی کنید:

```diff
Services
→ Nikki
→ Mixin Config
→ Rule Config
→ Append Rule: disabled
```

</details>

---

</details>



<details>
<summary><code><strong> راهنمای PassWall2 </strong></code></summary>

### `PassWall2`

**https://github.com/Openwrt-Passwall/openwrt-passwall2**

**گزینه عمومی `1.` برای OpenWrt نسخه 21.02+، همراه با LuCI و فرم‌ورهای مشتق شده (مثلاً ImmortalWrt).** 

**`2.`** **هسته:** Xray/Sing-box.

**`3.`** **چه چیزی را پشتیبانی می‌کند؟** REDIRECT، PROXY، nftables/iptables و قوانین مسیریابی. TUN اعلان نشده است.

**`4.`** **بررسی سلامت خودکار، انتخاب و تغییر گره‌ها در پس‌زمینه، پیروی از نمونه Karing، در دسترس است.**

  این از طریق Sing-Box `URLTest` یا از طریق `Auto Switch` اجرا می‌شود، مانند سوئیچ خودکار به یک نود پشتیبان پیش‌پیکربندی شده یا نود بعدی در لیست.

  طرح Sing-Box `URLTest` **PassWall2** همانند `urltest` Sing-box **ShellCrash** است که نزدیک به **Karing Auto Select** است: `به صورت دوره‌ای چند نود را بررسی می‌کند` → `تاخیر آن‌ها را مقایسه می‌کند` → `بهترین را انتخاب می‌کند`.

  طرح `Auto Switch` نزدیک به رفتار `fallback` V **ShellCrash** است و به این صورت عمل می‌کند: `Main node` → `doesn't work` → `Reserve node 1` → `doesn't work` → `Reserve node 2` → `و به همین ترتیب`.

  PassWall2 دو روش برای افزودن نودهای پشتیبان ارائه می‌دهد: دستی (لیست دستی) و گروهی (انتخاب کل گروه نودها). برای اشتراک موبایل TOP 150، گزینه فنی که کار می‌کند، گروهی است.

**`5.`** **چه اشتراک‌هایی را می‌پذیرد؟** اشتراک‌های معمولی (از رشته‌های رایج vless://، ss://، trojan:// و غیره)، و همچنین Base64. Clash YAML اشتراک‌ها را وارد می‌کند اما آنها را به فرمت معمولی تبدیل می‌کند.

**قواعد `6.`** **GEO.** شامل پشتیبانی GeoIP/GeoSite؛ طرح‌ها/الگوهای آماده عمدتاً روی چین تمرکز دارند: دامنه‌ها/آی‌پی‌های چینی مستقیماً ارسال می‌شوند و بقیه از طریق پروکسی ارسال می‌شوند. حالت آماده روسی یا ایرانی وجود ندارد؛ شما باید آن را خودتان در سمت کلاینت پیکربندی کنید - برای تنظیمات آماده قواعد GEO برای روسیه به نکته ۹ مراجعه کنید.

**`7.`** **چگونه اشتراک‌های VPN را به PassWall2 اضافه کنیم؟**

در لوسی آی:

```diff
Services → PassWall2 → Node Subscribe → Add
```

پر کردن جایگزین:

```diff
Remark/Name: Igareck BLACK TOP 150
Subscription URL: link to TXT
```

اگر فیلدی وجود دارد `User-Agent` استفاده/نگه دارید `v2rayN`.

پس از آن، به‌صورت دستی به‌روز کنید:

```diff
Save & Apply → return to Node Subscribe → Manual subscription All (Update All Subscriptions)
```

گره‌ها در فهرست گره‌ها در LuCI ظاهر خواهند شد:

```diff
Services → PassWall2 → Node List
```

**`8.`** **راه‌اندازی تمدید خودکار اشتراک PassWall2:**
   
   **تجدید خودکار به صورت جداگانه برای هر اشتراک در پارامترهای PassWall2 آن تنظیم شده است.**

در لوسی آی:

```diff
Services → PassWall2 → Node Subscribe → edit subscription
```

   موارد زیر وجود دارد:

```diff
Update Once on Boot - update once after booting the router; disabled by default.
 
Auto Update Mode:
   - Disable;
   - Loop Mode - update cyclically;
   - Every day;
   - selected day of the week.
```

حالت به‌روزرسانی خودکار و حالت حلقه را انتخاب کنید.

برای حالت حلقه، بازه زمانی می‌تواند از ۱ تا ۲۴ ساعت تنظیم شود؛ مقدار پیش‌فرض ۲ ساعت است.
   
برای حالت روزانه یا هفتگی، زمان به‌روزرسانی خاصی تنظیم می‌شود.

   **برای اشتراک‌های Igareck BLACK TOP 150:**
   
```diff
Auto Update Mode: Loop Mode
Update Interval: 1 hour
```

**`۹.`** **تنظیمات آماده PassWall2 درون کلاینت:**
  
**Auto Select (بررسی سلامت خودکار) + دسترسی مستقیم به منابع روسی (RU-DIRECT)، پیکربندی شده داخل کلاینت PassWall2**

*توضیح: تنظیمات خودکار YAML در اینجا کار نخواهند کرد، زیرا این یک کلاینت Mihomo/Clash نیست، بلکه یک Xray/Sing-box است.*

الف. در مرحله ۸، ما قبلاً اشتراک را وارد کرده و آن را به گروه جداگانه (توضیح/نام) `Igareck BLACK TOP 150` اختصاص داده‌ایم.

ب. سپس در `لیست گره‌ها → افزودن گره` یک گره ایجاد کنید:

در لوسی آی:

```diff
Services → PassWall2 → Node List → Add Node
```

* توضیحات گره: `Igareck Auto Select`
* نوع/هسته: `Sing-Box`
* پروتکل: `URLTest`
* روش افزودن گره: `Batch`
* انتخاب گروه: `Igareck BLACK TOP 150`
* قوانین تطبیق نود: خالی بگذارید
* آدرس پروب: `https://www.gstatic.com/generate_204`
* فاصله آزمون: `5m`
* تلورانس آزمون: `150`
* زمان انتظار غیرفعال: `30m`
* قطع ارتباطات موجود: غیرفعال

V. در `Rule Manage` قوانین ایجاد کنید:

در لوسی آی:

```diff
Services → PassWall2 → Rule Manage
```

قانون `LOCAL`:

```diff
IP:
127.0.0.0/8
10.0.0.0/8
172.16.0.0/12
192.168.0.0/16
169.254.0.0/16
100.64.0.0/10
::1/128
fc00::/7
fe80::/10
```

قانون `RU-DIRECT`:

```diff
Domain:
geosite:category-ru
domain:ru
domain:xn--p1ai

IP:
geoip:ru
```

d. یک گره `Sing-Box Shunt` ایجاد کنید:

در لوسی آی:

```diff
Services → PassWall2 → Node List → Add Node
→ Type/Core: Sing-Box
→ Protocol: Shunt
```

سپس قوانین `Sing-Box Shunt` را اختصاص دهید و ذخیره کنید:

```diff
LOCAL → Direct Connection
RU-DIRECT → Direct Connection
Default → Igareck Auto Select (node created in step 9-b `Sing-Box URLTest`)
→ Save & Apply
```

e. Shunt را به‌عنوان گره اصلی انتخاب کنید:

```diff
Services → PassWall2 → Basic Settings → Main
→ Node → select the created Sing-Box Shunt
→ Save & Apply
```

در نتیجه، منابع روسی و محلی به‌صورت مستقیم باز خواهند شد و سایر ترافیک از طریق گره‌ای با کمترین تأخیر فعلی از گروه اشتراک انتخاب‌شده باز خواهد شد.

---

</details>



<details>
<summary><code><strong> دستورالعمل‌ها dae/daed </strong></code></summary>

### `dae/daed`

**https://github.com/daeuniverse/dae**

**https://github.com/daeuniverse/daed**

**`1.`** **یک راه‌حل با عملکرد بالا برای سیستم‌های سرور مدرن Linux، مینی‌کامپیوترها و دروازه‌های شبکه مبتنی بر Linux بدون رابط گرافیکی.** 

**`2.`** **هسته:** هسته پروکسی مستقل `dae`. این پروژه از Xray، Sing-box یا Mihomo استفاده نمی‌کند. توسعه‌دهندگان به‌طور مستقیم می‌نویسند که این پروژه، به‌عنوان جانشین v2rayA، از v2ray-core صرف‌نظر کرده است. `dae` یک هسته پروکسی مستقل است و `daed` یک پنل کنترل مبتنی بر مرورگر ارائه می‌دهد.

**`3.`** **چه مواردی را پشتیبانی می‌کند؟** dae معماری متفاوتی در مقایسه با کلاینت‌های کلاسیک روی Xray/Sing-box/Mihomo دارد؛ ترافیک به‌طور مستقیم در Linux از طریق مکانیزم‌های eBPF/PF رهگیری و دسته‌بندی می‌شود. بنابراین، توصیف آن به‌عنوان یک کلاینت معمولی TUN/iptables کاملاً درست نیست. 

**`4.`** **بررسی سلامت خودکار و انتخاب گره‌ها در پس‌زمینه، با پیروی از نمونه Karing، در دسترس است.**

  انتخاب/تعویض خودکار پس‌زمینه بین کانفیگ‌ها وجود دارد. برای dae، این در واقع یک عملکرد داخلی کرنل است.

  کانفیگ گروهی از گره‌ها و یک سیاست را مشخص می‌کند، برای مثال:

  `policy: min_moving_avg`

  dae به صورت دوره‌ای بررسی گره‌ها را انجام می‌دهد. مثال رسمی بازه زمانی را تنظیم می‌کند:

  `check_interval: 30s`

  تفاوت مجاز نیز تنظیم می‌شود:

  `check_tolerance: 150ms`

  این بدان معناست که یک گره جدید فقط زمانی انتخاب خواهد شد که نتیجه آن حداقل به مقدار مشخص شده بهتر از گره فعلی باشد. این آستانه از سوئیچ مداوم بین دو گره تقریباً یکسان جلوگیری می‌کند.

  Auto Select dae از نظر مفهومی مشابه Auto Select در Karing است.

**`5.`** **چه اشتراک‌هایی را می‌پذیرد؟** فقط اشتراک‌های معمولی (از رشته‌های معمولی مانند vless://، ss://، trojan:// و غیره)، همچنین Base64.

**`6.`** **قوانین GEO.** یک مکانیزم برای قوانین جغرافیایی وجود دارد، اما پروفایل آماده‌ای وجود ندارد. در کانفیگ می‌توانید از: geoip:ru، geosite:ru، geoip:cn، geosite:cn استفاده کنید اگر پایگاه‌ داده‌های مناسب در دسترس باشند. برای قوانین category-ru و geoip:ru، باید geosite.dat و geoip.dat فعلی نصب شده باشند. سیاست کشوری پیش‌فرض هنگام نصب اولیه شامل نمی‌شود.

**`7.`** **چگونه اشتراک‌های VPN را اضافه کنیم، همچنین یک کانفیگ آماده در dae؟**

**پروفایل / فایل کانفیگ آماده dae: RU-DIRECT + Auto Select (dae/daed از YAML استفاده نمی‌کند، بلکه از فرمت کانفیگ .dae اختصاصی خود استفاده می‌کند)**

   *توضیح ۱: این پروفایل برای اشتراک موبایل Black List TOP 150 (BLACK_VLESS_RUS_mobile.txt) ساخته شده است، برای اشتراک/آینه دیگر - لینک را در پارامتر "subscription" جایگزین کنید.*

   *`https-file://` یک طرح ویژه dae است. این یک لینک مرورگر نیست.*

   *توضیح ۲: تنظیمات خودکار YAML در اینجا کار نخواهد کرد، زیرا این Mihomo/کلاینت Clash نیست، بلکه dae است.*

```diff

# ============================================================
# Igareck dae/daed Client Profile
# Settings profile without built-in proxies.
# Proxies come from the connected subscription.
#
# Mode:
# - automatic selection of the best proxy;
# - RU-DIRECT.
#
# Requires dae v1.1.0 or later (dns.bind is used).
# ============================================================

global {
  # Replace eth1 with your LAN interface:
  # for example br0, br-lan or eth1.
  lan_interface: eth1
  wan_interface: auto

  log_level: info
  auto_config_kernel_parameter: true
  disable_waiting_network: false

  dial_mode: domain
  sniffing_timeout: 100ms
  allow_insecure: false

  bootstrap_resolver: '8.8.8.8:53'
  fallback_resolver: '1.1.1.1:53'
}

subscription {
  # For another subscription or mirror, replace the link.
  # https-file:// is a special dae scheme, not a browser link.
  igareck_top150: 'https-file://raw.githack.com/igareck/vpn-configs-for-russia/main/BLACK_VLESS_RUS_mobile.txt'
}

dns {
  ipversion_prefer: 4

  # Local DNS dae. Requires dae v1.1.0+.
  bind: 'tcp+udp://127.0.0.1:5353'

  upstream {
    resolver: 'https://dns.google/dns-query'
  }

  routing {
    request {
      sub(igareck_top150) -> resolver
      subnode(subtag: igareck_top150) -> resolver

      fallback: resolver
    }

    response {
      upstream(resolver) -> accept
      fallback: accept
    }
  }
}

group {
  auto_select {
    filter: subtag(igareck_top150)
    policy: min_moving_avg

    tcp_check_url: 'https://www.gstatic.com/generate_204'
    tcp_check_http_method: GET

    udp_check_dns: 'dns.google:53,8.8.8.8'

    check_interval: 300s
    check_tolerance: 150ms
  }
}

routing {
  pname(
    NetworkManager,
    systemd-resolved,
    dnsmasq
  ) -> must_direct

  dip(
    224.0.0.0/3,
    'ff00::/8'
  ) -> direct

  dip(
    127.0.0.0/8,
    10.0.0.0/8,
    172.16.0.0/12,
    192.168.0.0/16,
    169.254.0.0/16,
    100.64.0.0/10,
    '::1/128',
    'fc00::/7',
    'fe80::/10'
  ) -> direct

  domain(
    suffix: localhost,
    suffix: local,
    regex: '^[^.]+$'
  ) -> direct

  domain(
    suffix: ru,
    suffix: xn--p1ai
  ) -> direct

  domain(geosite:category-ru) -> direct
  dip(geoip:ru) -> direct

  fallback: auto_select
}

```

پس از تغییر فایل:

```diff
sudo dae reload
```

اگر فرمان بارگزاری مجدد در یک بسته خاص پشتیبانی نمی‌شود:

```diff
sudo systemctl restart dae
```

برای قوانین category-ru و geoip:ru، فایل‌های geosite.dat و geoip.dat فعلی باید نصب شده باشند.

**`8.`** **تمدید خودکار اشتراک یک بار در ساعت در تایمر systemd خارجی باقی می‌ماند: برنامه‌ریزی نمی‌تواند مستقیماً در config.dae ساخته شود.**

**برای تمدید خودکار اشتراک خود، یک فایل ایجاد کنید:**

```diff
/etc/systemd/system/dae-subscription-refresh.service
```

با محتوا:

```diff
[Unit]
Description=Refresh dae subscriptions
After=network-online.target dae.service
Wants=network-online.target

[Service]
Type=oneshot
ExecStart=/usr/bin/dae reload
```

سپس ایجاد کنید:

```diff
/etc/systemd/system/dae-subscription-refresh.timer
```

با محتوا:

```diff
[Unit]
Description=Refresh dae subscriptions every hour

[Timer]
OnBootSec=5min

OnUnitActiveSec=1h
Persistent=true
Unit=dae-subscription-refresh.service

[Install]
WantedBy=timers.target
```

فعال‌سازی:

```diff
sudo systemctl daemon-reload
sudo systemctl enable --now dae
sudo systemctl enable --now dae-subscription-refresh.timer
```

به‌روزرسانی به‌صورت دستی:

```diff
sudo dae reload
```

</details>

---
---

## <img src="https://upload.wikimedia.org/wikipedia/commons/8/8d/Shadowsocks_logo.png" width="40" align="absmiddle"> `برنامه‌ها (کلاینت‌ها) برای کانفیگ‌های VPN روی PC، دستگاه‌های همراه و روترها`

بسته به کلاینت، سرورهای کاری می‌توانند متفاوت باشند؛ این طبیعی است به دلیل ویژگی‌های عملیاتی هر کلاینت به صورت جداگانه؛ کانفیگ‌ها در زمان به‌روزرسانی عمدتاً کار می‌کنند. بنابراین، ۲-۳ کلاینت مختلف را روی PC خود نصب کنید: Karing، Clash Verge Rev، v2rayN، Throne، Exclave، Happ و غیره. برخی از کانفیگ‌هایی که در Karing کار نمی‌کنند در Clash-Verge-Rev/v2RayN به خوبی کار خواهند کرد، برخی در Throne و کلاینت‌ها دیگر کار خواهند کرد، بنابراین آنچه نزدیک‌تر و راحت‌تر است را انتخاب کنید. به طور کلی، کانفیگ‌های زیادی وجود دارد، بنابراین حتی اگر برخی از آنها اجرا نشوند، مشکلی نیست، ۵۰٪ آن‌ها قطعاً از طریق یک کلاینت کار خواهند کرد.

این ویژگی همچنین برای کلاینت‌ها روی دستگاه‌های موبایل اعمال می‌شود. به‌عنوان مثال، روی iOS، علاوه بر Karing و Clash Mi، می‌توانید Shadowrocket یا Streisand را نصب کنید و مقایسه کنید.

برای به‌روزرسانی‌ها همراه باشید و فراموش نکنید که کلاینت‌ها خود را حداقل هر ۲ هفته یک‌بار به‌روزرسانی کنید. عملکرد کانفیگ‌ها مستقیماً به این بستگی دارد. آخرین نسخه‌ها شامل اصلاحات هستند و سرورهای بیشتری را ارائه می‌دهند.

###  <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3amtqMmQxOGh0aG0waGk5OGhhNG5odmdob2k1bWc4ejNyZ3E3N2Y2bCZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/xUS4Fp5i6iIn2Y1EYT/giphy.gif" width="25"> `Windows/Linux/MacOS`

<details>
<summary><em><code> گسترش </code></em></summary>

㋡

<details>
<summary><strong><em><code> کلاینت شماره ۱ که من توصیه می‌کنم Karing است </code></em></strong></summary>

⇩

**https://github.com/KaringX/karing/releases**

کلاینت رسمی Karing را نصب کنید، در «حالت مدیر» اجرا کنید، یک اشتراک از طریق **افزودن پروفایل - افزودن اشتراک** اضافه کنید، لینک اشتراک را در کادر بالایی بچسبانید، نام را در «یادداشت» بنویسید، فاصله به‌روزرسانی را روی ۱ ساعت تنظیم کنید، «بوت مجدد پس از به‌روزرسانی پروفایل» و «شروع تست تأخیر پس از به‌روزرسانی پروفایل» را فعال کنید، سپس در گوشه بالا سمت راست روی ✅️ کلیک کنید.

در پنجره اصلی، نماد تنظیمات Karing ⚙️ (گوشه بالا سمت چپ) را پیدا کنید، سپس منوی «انتخاب خودکار» را پیدا کنید، فاصله بررسی تأخیر را روی ۱۰ دقیقه، خطای مجاز را روی ۱۵۰ میلی‌ثانیه و فاصله بررسی سلامت سرور فعلی را روی ۳ ثانیه تنظیم کنید.

سرور در پایین وسط منوی اصلی (زیر شیلد 🛡️) ظاهر می شود، سمت راست آن فلش سمت راست است - روی آن کلیک کنید، منوی انتخاب سرور باز می شود. در گوشه بالا سمت راست، روی ⚙️ آن کلیک کنید و همه دکمه ها را فعال کنید. برگردید، روی «Auto Select» کلیک کنید. سپس از طریق فلش در گوشه بالا سمت چپ به منوی اصلی بازگردید. 

روی نماد سپر 🛡️ در مرکز پایین کلیک کنید، صبر کنید تا اشتراک راه‌اندازی مجدد شود، پینگ‌ها گرفته شوند و سریع‌ترین سرور به‌طور خودکار انتخاب شود. اگر سرور رضایت‌بخش نبود، سپر را روشن و خاموش کنید 🛡️. یا به منوی انتخاب سرور بروید، سرور فعلی را انتخاب کرده و روی «رد کردن» کلیک کنید تا دیگر در جستجو شرکت نکند. شما می‌توانید اشتراک خود را به‌صورت دستی با کلیک روی «ابر» در منوی انتخاب سرور راه‌اندازی مجدد کنید.

---

</details>

<details>
<summary><strong><em><code> کلاینت #2 من توصیه می‌کنم Clash Verge Rev </code></em></strong></summary>

⇩

**https://github.com/clash-verge-rev/clash-verge-rev/releases**

Clash Verge Rev فقط برای پروفایل‌های با فرمت YAML در Clash طراحی شده است.

*هنگام تلاش برای وارد کردن یک اشتراک غیر-YAML، Clash Verge Rev خطاهایی مانند `داده‌های پروفایل راه دور YAML نامعتبر است` یا `پروفایل شامل پروکسی‌ها یا ارائه‌دهندگان پروکسی نیست` را نشان می‌دهد.*

از تمام پروتکل‌های مدرن VLESS، Trojan، VMess، Hysteria2 پشتیبانی می‌کند، فقط باید در قالب کانفیگ Clash توصیف شوند. خود کلاینت روی هسته Mihomo اجرا می‌شود، که قبلاً Clash.Meta نامیده می‌شد.

من خودم شروع به استفاده فعال از Clash Verge Rev کردم و احساس می‌شد که اینترنت با VPN عملاً بدون وقفه است، کانفیگ‌ها به‌طور خودکار در پس‌زمینه بررسی می‌شدند و یکی پس از دیگری به‌قدری روان تغییر می‌کردند که من دیگر متوجه آن نمی‌شدم. شاید این کلاینت حتی کمی بهتر از Karing کار کند، زیرا Karing گاهی اوقات هنوز هنگام اجرای طولانی مدت نیاز به راه‌اندازی مجدد اجباری دارد.

**برای استفاده از این کلاینت، فقط از اشتراک‌های YAML از پوشه مخزن به نام Clash استفاده کنید:** https://github.com/igareck/vpn-configs-for-russia/tree/main/Export/Clash

**Igareck قبلاً بررسی سلامت خودکار کانفیگ‌ها در پس‌زمینه را در تمام اشتراک‌های Clash برای راحتی کاربران ساخته است.**
  
**اشتراک‌های Clash بر اساس منطقه تقسیم شده‌اند:**
  
- **اشتراک‌های Clash برای کاربران از روسیه** (RU-DIRECT تا همه سایت‌های روسیه بدون VPN باز شوند): 

https://github.com/igareck/vpn-configs-for-russia/tree/main/Export/Clash/RU_DIRECT

- **اشتراک‌های Clash برای گزینه بین‌المللی** (برای سایر کشورها که به RU-DIRECT نیاز ندارند): 

https://github.com/igareck/vpn-configs-for-russia/tree/main/Export/Clash/GLOBAL

**تمام تنظیمات پس از وارد کردن توسط کلاینت گرفته خواهد شد.**

**کاربر تنها باید تمدید خودکار اشتراک را درون کلاینت هر یک یا دو ساعت تنظیم کند و کانفیگ را اجرا نماید:** 

1. به بخش «پروفایل‌ها» بروید، روی کانفیگ وارد شده کلیک راست کنید (RMB);
2. بعد، روی «تغییر اطلاعات» کلیک کنید;
3. در منویی که ظاهر می‌شود، اهرم «اجازه به‌روزرسانی خودکار» را فعال کنید، فاصله به‌روزرسانی را وارد کنید (عدد به دقیقه، برای مثال 60 یا 120). در صورت تمایل می‌توانید عنوان/توضیحات را ویرایش کنید;
4. در پایان، روی «ذخیره» کلیک کنید;
5. سپس روی کانفیگ وارد شده کلیک راست کنید، روی «به‌روزرسانی» یا «به‌روزرسانی از طریق پروکسی» کلیک کنید تا کانفیگ‌ها از اشتراک بارگذاری شوند؛
۶. سپس به بخش "پروکسی‌ها" بروید;
۷. در گوشهٔ بالا سمت راست بالای فهرست کانفیگ‌ها، روی آیکون فیلتر کلیک کنید (شبیه نماد قیف 🌪️ است)، یک فیلد ورودی در سمت چپ ظاهر خواهد شد;
۸. در فیلد ورودی، عبارت "delay<5000" را وارد کنید تا سرورهای غیر فعال مخفی شوند (لطفاً توجه داشته باشید که آنها بلافاصله ناپدید نمی‌شوند، بلکه ۵ تا ۱۰ دقیقه بعد از تکرار اسکن پس‌زمینه);
۹. سپس دوباره روی آیکون فیلتر کلیک کنید (شبیه آیکون قیف 🌪️) تا فیلد ورودی مخفی شود؛
۱۰. سپس به بخش "تنظیمات" بروید؛
۱۱. در بخش «تنظیمات» در گوشه بالای سمت چپ، «حالت TUN» را پیدا کنید، در سمت راست آن یک آیکون کوچک «آچار آبی» با نوشته «نصب یک سرویس» وجود دارد، روی آن کلیک کنید و منتظر نصب بمانید. بررسی کنید که اهرم‌های «حالت TUN» و «پروکسی سیستم» فعال باشند؛
۱۲. سپس به بخش «خانه» بروید؛
۱۳. در بخش «خانه»، پنل «تنظیمات شبکه» را پیدا کنید، حالت عملکرد مورد نیاز را انتخاب کنید: «پروکسی سیستم» یا «حالت TUN»، آن را با استفاده از دکمه اهرم فعال کنید. معمولاً یکی از حالت‌ها فعال است و کافی است، اما گاهی اوقات هر دو برای عملکرد کامل لازم هستند، به وضعیت توجه کنید؛
۱۴. تمام!
۱۵. بخش «خانه» آمار عملکرد کانفیگ‌ها در کلاینت Clash Verge Rev را نشان می‌دهد: سرعت، حجم آپلود/دانلود، خروجی-IP/ASN و غیره.
۱۶. **پروفایل YAML آماده با بررسی سلامت خودکار برای روسیه (RU-DIRECT، به طوری که تمام سایت‌های RU بدون VPN کار کنند) برای پیکربندی جهانی خود کلاینت Clash Verge Rev.** 

    **ضروری نیست، زیرا همان تنظیمات به‌طور خودکار با اشتراک Igareck شما می‌آید. کاربر معمولی می‌تواند این مورد را نادیده بگیرد و در نقطه ۱۵ متوقف شود.** این کار برای راحتی کاربران طبق اصل انجام شد: اشتراک اضافه کنید و فوراً استفاده کنید.

    **کجا اضافه کنیم؟** **به بخش «پروفایل‌ها» بروید، «کانفیگ ادغام جهانی» را پیدا کنید، روی آن راست‌کلیک کنید - «ویرایش فایل»، همه چیز را حذف کرده و تنظیمات YAML آماده شده از بلوک زیر را وارد کنید، سپس «ذخیره» را کلیک کنید.**

    **برای چه چیزی؟** برای کاربران پیشرفته: اگر نیاز دارید هر گزینه اشتراک‌گذاری Clash را به صورت دستی در خود کلاینت Clash Verge Rev تغییر دهید، و آن‌ها را برای هر اشتراک ورودی به‌صورت جهانی اعمال کنید. تنظیمات ثبت شده در خود کلاینت Clash Verge Rev، اگر با تنظیمات هر اشتراک Clash ورودی مطابقت داشته باشد، آن‌ها را بازنویسی می‌کند. 

```diff
# ============================================================
# Igareck Mihomo Client Profile
# Settings profile without built-in proxies.
# Proxies must come from the connected subscription.
#
# Mode:
# - automatic selection of the best proxy;
# - manual proxy selection;
# - RU-DIRECT.
# ============================================================


mode: rule
unified-delay: true
tcp-concurrent: true

keep-alive-idle: 300
keep-alive-interval: 60
disable-keep-alive: false

profile:
  store-selected: true
  store-fake-ip: true

dns:
  enable: true
  prefer-h3: false
  ipv6: false
  use-hosts: true
  use-system-hosts: true
  respect-rules: false

  enhanced-mode: fake-ip
  fake-ip-range: 198.18.0.1/16
  fake-ip-filter-mode: blacklist

  fake-ip-filter:
    - "*.lan"
    - "*.local"
    - "localhost"

    - "time.*.com"
    - "time.*.gov"
    - "time.*.apple.com"
    - "time-ios.apple.com"
    - "time1.*.com"
    - "time2.*.com"
    - "time3.*.com"
    - "time4.*.com"
    - "time5.*.com"
    - "time6.*.com"
    - "time7.*.com"

    - "ntp.*.com"
    - "ntp1.*.com"
    - "ntp2.*.com"
    - "ntp3.*.com"
    - "ntp4.*.com"
    - "ntp5.*.com"
    - "ntp6.*.com"
    - "ntp7.*.com"
    - "*.pool.ntp.org"

    - "+.push.apple.com"

    - "+.stun.*.*"
    - "+.stun.*.*.*"
    - "+.stun.*.*.*.*"
    - "+.stun.*.*.*.*.*"
    - "+.stun.playstation.net"

    - "lens.l.google.com"
    - "*.n.n.srv.nintendo.net"
    - "xbox.*.*.microsoft.com"
    - "*.*.xboxlive.com"

    - "*.msftncsi.com"
    - "*.msftconnecttest.com"

    - "WORKGROUP"

  cache-algorithm: arc

  default-nameserver:
    - 8.8.8.8
    - 8.8.4.4
    - 9.9.9.9
    - 94.140.14.14
    - 76.76.2.0
    - 76.76.10.0
    - 1.0.0.1
    - 1.1.1.1
    - 208.67.220.220
    - 208.67.222.222

  nameserver:
    - https://dns.google/dns-query
    - https://dns.quad9.net/dns-query
    - https://dns.adguard-dns.com/dns-query
    - https://freedns.controld.com/p0
    - https://dns.mullvad.net/dns-query
    - https://cloudflare-dns.com/dns-query
    - https://doh.opendns.com/dns-query
    - https://doh.libredns.gr/dns-query
    - https://doh.dns4all.eu/dns-query
    - https://wikimedia-dns.org/dns-query
    - https://dns.hostux.net/dns-query
    - https://blank.dnsforge.de/dns-query

  proxy-server-nameserver:
    - 8.8.8.8
    - 8.8.4.4
    - 9.9.9.9
    - 94.140.14.14
    - 76.76.2.0
    - 76.76.10.0
    - 1.0.0.1
    - 1.1.1.1
    - 208.67.220.220
    - 208.67.222.222
    - system

  direct-nameserver:
    - 8.8.8.8
    - 8.8.4.4
    - 9.9.9.9
    - 94.140.14.14
    - 76.76.2.0
    - 76.76.10.0
    - 1.0.0.1
    - 1.1.1.1
    - 208.67.220.220
    - 208.67.222.222
    - system

  direct-nameserver-follow-policy: false

sniffer:
  enable: true
  force-dns-mapping: true
  parse-pure-ip: true
  override-destination: false

  sniff:
    HTTP:
      ports: [80, 8080-8880]
      override-destination: true

    TLS:
      ports: [443, 8443]

    QUIC:
      ports: [443, 8443]

proxy-groups:
  - name: "Igareck Auto Select (Auto connect)"
    type: url-test
    include-all: true
    exclude-type: "Direct|Reject|RejectDrop|Compatible|Pass|Dns"
    url: "https://www.gstatic.com/generate_204"
    interval: 300
    tolerance: 150
    lazy: true
    timeout: 5000
    max-failed-times: 2
    expected-status: 204

  - name: "Igareck Manual (Manual Connection)"
    type: select
    proxies:
      - "Igareck Auto Select (Auto connect)"
    include-all: true
    exclude-type: "Direct|Reject|RejectDrop|Compatible|Pass|Dns"
    default-selected: "Igareck Auto Select (Auto connect)"

  - name: "GLOBAL"
    type: select
    proxies:
      - "Igareck Auto Select (Auto connect)"
      - "Igareck Manual (Manual Connection)"
    default-selected: "Igareck Auto Select (Auto connect)"

rules:
  - DOMAIN-SUFFIX,localhost,DIRECT
  - DOMAIN-SUFFIX,local,DIRECT
  - "DOMAIN-REGEX,^[^.]+$,DIRECT"

  - IP-CIDR,127.0.0.0/8,DIRECT,no-resolve
  - IP-CIDR,10.0.0.0/8,DIRECT,no-resolve
  - IP-CIDR,172.16.0.0/12,DIRECT,no-resolve
  - IP-CIDR,192.168.0.0/16,DIRECT,no-resolve
  - IP-CIDR,169.254.0.0/16,DIRECT,no-resolve
  - IP-CIDR,100.64.0.0/10,DIRECT,no-resolve

  - IP-CIDR6,::1/128,DIRECT,no-resolve
  - IP-CIDR6,fc00::/7,DIRECT,no-resolve
  - IP-CIDR6,fe80::/10,DIRECT,no-resolve

  # Remove the following 4 lines for global/Not-RU-Direct mode.
  # Delete the next 4 lines for Global/Not-RU-Direct routing.
  - DOMAIN-SUFFIX,ru,DIRECT
  - DOMAIN-SUFFIX,xn--p1ai,DIRECT
  - GEOSITE,category-ru,DIRECT
  - GEOIP,RU,DIRECT

  - "MATCH,Igareck Manual (Manual Connection)"
```

---

</details>

<details>
<summary><strong><em><code> کلاینت شماره ۳ که من توصیه می‌کنم v2rayN است </code></em></strong></summary>

⇩

**https://github.com/2dust/v2rayN/releases**

کلاینت رسمی v2rayN را نصب کنید، در حالت “مدیر” اجرا کنید.

به "تنظیمات" - "تنظیمات منطقه‌ای" بروید، "روسیه" را انتخاب کنید. روی منوی "راه‌اندازی مجدد" کلیک کنید یا برنامه را دوباره راه‌اندازی کنید.

از طریق **گروه اشتراک - تنظیمات گروه اشتراک** یک اشتراک اضافه کنید، اشتراک خود را از طریق **گروه اشتراک - به‌روزرسانی اشتراک فعلی بدون پروکسی** دانلود کنید، یک فهرست ظاهر خواهد شد.

روی گزینه "تاخیر واقعی" (آیکون رعد و برق در بالا سمت راست) کلیک کنید، پس از تکمیل - بر اساس پینگ مرتب کنید، چند کانفیگ سبز بالا با کمترین عدد را انتخاب کنید.

چند سرور با کمترین عدد پینگ را انتخاب کنید، راست‌کلیک کنید، گزینه «آزمایش سرعت بارگذاری سرور» را انتخاب کنید، پس از آزمایش، سریع‌ترین را با فشار دادن Enter انتخاب کنید. اما تست سرعت v2rayN اخیراً حتی روی سرورهای زنده نیز نتایج نادرست نشان می‌دهد، بنابراین من به آرامی روی پینگ تمرکز می‌کنم. در اشتراک‌های من، اگر سرور پینگ دارد، به طور پیش‌فرض باید کار کند.

در نهایت، «حالت VPN/حالت TUN» را اجرا کنید، یا «تنظیم پروکسی سیستم» را فعال کنید. در سمت راست، قوانین مسیریابی «RUv1-همه چیز به جز RF» را انتخاب کنید تا VPN برای کار روی سایت‌های RU استفاده نشود.

---

</details>

<details>
<summary><strong><em><code> کلاینت شماره ۴ که من توصیه می‌کنم Throne است </code></em></strong></summary>

⇩

**https://github.com/throneproj/Throne/releases**

کلاینت رسمی Throne را نصب کنید، در حالت «مدیر» اجرا کنید، یک اشتراک اضافه کنید از طریق **تنظیمات - گروه - گروه جدید**.

نام اشتراک را وارد کنید، نوع «اشتراک» را انتخاب کنید و لینک RAW مربوط به اشتراک را در زیر بچسبانید.

شما باید یک گروه با نام مناسب در پنجره اصلی ظاهر شود. روی آن با RMB (دکمه راست ماوس) کلیک کنید و روی «به‌روزرسانی» کلیک کنید. یک لیست از سرورها باید ظاهر شود.

سپس دوباره روی نام گروه راست‌کلیک کرده و «آزمایش تأخیر کل گروه» را انتخاب کنید؛ پس از اتمام آزمایش، سروری با کمترین عدد تأخیر را انتخاب کنید.

سپس به بخش **Routing - Download Profiles** بروید و **Bypass_Russia** را انتخاب کنید، سپس Routing را از **Default** روی **Bypass_Russia** تغییر دهید.

---

</details>

دستورالعمل‌های دقیق‌تر را می‌توان در پاراگراف بالا یافت. (روی فلش کلیک کنید) و در بخش [دستورالعمل‌ها برای هر کلاینت به‌صورت جداگانه](#-%D0%B8%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%86%D0%B8%D0%B8-%D0%BF%D0%BE-%D0%BA%D0%B0%D0%B6%D0%B4%D0%BE%D0%BC%D1%83-%D0%BA%D0%BB%D0%B8%D0%B5%D0%BD%D1%82%D1%83-%D0%BE%D1%82%D0%B4%D0%B5%D0%BB%D1%8C%D0%BD%D0%BE).

**پایدارترین‌ها اشتراک‌های Clash/YAML + کلاینت‌ها Mihomo و Standard + Karing هستند.**

---

## `کلاینت‌های PC برای اشتراک‌های Clash:`

 اشتراک‌های Clash بر اساس منطقه تقسیم‌بندی شده‌اند:
  
- اشتراک‌های Clash برای کاربران روسیه (RU-DIRECT به‌طوری که تمامی سایت‌های روسیه بدون VPN باز شوند): 

https://github.com/igareck/vpn-configs-for-russia/tree/main/Export/Clash/RU_DIRECT

- اشتراک‌های Clash برای نسخه بین‌المللی (برای کشورهای دیگر که RU-DIRECT نیاز نیست): 

https://github.com/igareck/vpn-configs-for-russia/tree/main/Export/Clash/GLOBAL

| | |
|---|---|
| **① Clash Verge Rev (جانشین Clash Verge)** | **② Clash Mi (توسعه‌دهنده Karing)** |
| **[Clash Verge Rev در GitHub](https://github.com/clash-verge-rev/clash-verge-rev/releases)** | **[Clash Mi در GitHub](https://github.com/KaringX/clashmi/releases)** |
| *من آن را به عنوان یک رقیب مستقیم برای Karing توصیه می‌کنم. هسته Mihomo. Clash Verge Rev فقط برای پروفایل‌های قالب YAML کلش طراحی شده است!* | *کلاینت جایگزین قابل کار با بررسی سلامت خودکار پس از Clash Verge Rev. هسته Mihomo.* |
| *من خودم شروع به استفاده فعال از Clash Verge Rev کردم و حس می‌شد که اینترنت با VPN عملاً بدون وقفه است، کانفیگ‌ها به‌طور خودکار در پس‌زمینه بررسی می‌شدند و آن‌قدر روان یکدیگر را تغییر می‌دادند که من متوقف شدم از آن متوجه شوم. شاید این کلاینت حتی بهتر از Karing کار کند، زیرا Karing گاهی اوقات هنوز وقتی برای مدت طولانی اجرا می‌شود نیاز به راه‌اندازی اجباری دارد.* | *عملکرد مشابه است، اما ضعیف‌تر از Clash Verge Rev است. پنل با آمار اتصالات و کانفیگ‌ها دقیق (Panel) در مرورگر باز می‌شود و در خود کلاینت تعبیه نشده است. Clash Verge Rev همه چیز را در خود برنامه دارد. یک جایگزین خوب. با کانفیگ‌ها داخلی اشتراک‌های Igareck Clash، نیاز به کار زیادی نیست جز تغییر زبان رابط و فعال کردن TUN در کانفیگ‌ها هسته.* |
| | |

بررسی خودکار سلامتی کانفیگ‌ها در پس‌زمینه، به منظور راحتی کاربران، قبلاً در تمام اشتراک‌های Clash توسط Igareck ساخته شده است. تنها کاری که باید انجام دهید این است که اشتراک RAW-Clash را دانلود کرده و خودکارسازی تمدید آن را در کلاینت هر ۱-۲ ساعت کانفیگ کنید.
   
---

## `کلاینت‌های PC برای اشتراک‌های استاندارد و تخصصی`

### ① `Karing` **https://github.com/KaringX/karing/releases**

*برای اشتراک‌های استاندارد. من آن را به عنوان بهترین کلاینت رایگان عمومی با بررسی خودکار سرورها در حین عملیات توصیه می‌کنم. یک ابزار عمومی، تطبیقی و قدرتمند برای اطمینان از اینکه کانفیگ‌های شما حتی تحت فشار نیز راه‌اندازی می‌شوند. مناسب برای تست سرعت جمعی نیست، فقط پینگ.*

### ② `v2rayN` **https://github.com/2dust/v2rayN/releases**

*استفاده با اشتراک ویژه برای v2rayN. به طور پایدار کار می‌کند و با هزاران کانفیگ از پروتکل‌های مختلف به طور همزمان تأیید شده است (حداکثر شخصی من ۱۵۰,۰۰۰ کانفیگ است). این یک کلاینت عمومی برای تمام پروتکل‌های مدرن است. مناسب برای بازرسی‌های جمعی (پینگ+سرعت). با استفاده از Xray، Sing-Box یا Mihomo کار می‌کند.*

*بررسی خودکار سلامت کانفیگ‌ها در پس‌زمینه در دسترس است (مستقیماً در اشتراک ساخته شده)، از طریق گروه سیاست محلی با استراتژی کمترین پینگ پیاده‌سازی می‌شود.*

### ③ `Throne` (جانشین Nekoray) **https://github.com/throneproj/Throne/releases**

*برای اشتراک‌های استاندارد. کانفیگ‌هایی که در Karing/v2rayN شروع نشده‌اند، به‌طور جزئی در اینجا شروع می‌شوند. این یک کلاینت عمومی برای همه پروتکل‌های مدرن است. مناسب برای بازرسی‌های انبوه. با استفاده از Xray, Sing-Box, Mihomo در یک بسته کار می‌کند. بررسی سلامت خودکار برای کانفیگ‌ها در پس‌زمینه وجود ندارد.*

</details>
   
---

### <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExODUzYWRwNzNpa3doMDd1bXo4NTlzanJsaTcya3dlNXA4d3c5cnVzNCZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/UQJlZ2OcaCA2RLfGiZ/giphy.gif" width="20" align="absmiddle"> `iOS`

<details>
<summary><em><code> گسترش </code></em></summary>

㋡

* از Karing, Shadowrocket, V2Box با اشتراک‌های استاندارد/عمومی استفاده کنید. مسیریابی و بررسی سلامت خودکار باید ابتدا در خود کلاینت بررسی و/یا پیکربندی شوند; 

* Clash Mi و Clash Lite، Stash - با اشتراک‌های Clash. بررسی سلامت خودکار + مسیریابی به‌طور مستقیم در خود اشتراک‌ها تعبیه شده‌اند; 

* Happ، Streisand، v2RayTun با اشتراک‌های ویژه برای این کلاینت‌ها. بررسی سلامت خودکار + مسیریابی در خود اشتراک‌ها تعبیه شده است. گزینه VPN با یک کلیک؛ 

**پایدارترین‌ها اشتراک‌های Clash/YAML + کلاینت‌ها Mihomo و Standard + Karing هستند.**

---

### `کلاینت‌های iOS برای اشتراک‌های Clash` (Mihomo):

 اشتراک‌های Clash بر اساس منطقه تقسیم‌بندی شده‌اند:
  
- اشتراک‌های Clash برای کاربران روسیه (RU-DIRECT به‌طوری که تمامی سایت‌های روسیه بدون VPN باز شوند): 

https://github.com/igareck/vpn-configs-for-russia/tree/main/Export/Clash/RU_DIRECT

- اشتراک‌های Clash برای نسخه بین‌المللی (برای کشورهای دیگر که RU-DIRECT نیاز نیست): 

https://github.com/igareck/vpn-configs-for-russia/tree/main/Export/Clash/GLOBAL

| | | |
|---|---|---|
| **① `Clash Mi`** | **② `Clash Lite`** | **③ `Stash - پروکسی مبتنی بر قوانین`** |
| **[Clash Mi در AppStore](https://apps.apple.com/us/app/clash-mi/id6744321968)** | **[Clash Lite در AppStore](https://apps.apple.com/us/app/clash-lite/id6761357475)** | **[Stash در AppStore](https://apps.apple.com/us/app/stash-rule-based-proxy/id1596063349)** |
| *کلاینت رایگان برای اشتراک‌های Clash از همان توسعه‌دهنده Karing* | *یک کلاینت رایگان جایگزین برای اشتراک‌های Clash بدون جمع‌آوری داده‌ها* | *کلاینت جایگزین برای اشتراک‌های Clash روی iOS، پرداختی* |
| | | |

ایگارک قبلاً بررسی خودکار سلامت کانفیگ‌ها را در تمام اشتراک‌های Clash برای راحتی کاربران تعبیه کرده است. تمام کاری که باید انجام دهید این است که اشتراک RAW-Clash را دانلود کرده و تمدید خودکار آن را در کلاینت هر ۱-۲ ساعت کانفیگ کنید.

---

### `کلاینت‌های iOS برای اشتراک‌های استاندارد و اشتراک‌های ویژه با بررسی خودکار سلامت:`

   **① `Karing`** **https://apps.apple.com/us/app/karing/id6472431552**
     
   *برای اشتراک‌های استاندارد. بهترین کلاینت رایگان و عمومی در حال حاضر. بررسی سلامت خودکار کانفیگ‌ها در پس‌زمینه. لیست‌های جغرافیایی و مسیریابی نقاط به‌صورت راحت در نصب اولیه کانفیگ می‌شوند. نیازمند مقدار زیادی رم.*

   **② `Shadowrocket`** **https://apps.apple.com/us/app/shadowrocket/id932747118** 
   
   *برای اشتراک‌های استاندارد. پرداختی. مکانیزم داخلی برای بررسی سلامت خودکار وجود دارد که از طریق منوی «تست اتصال - تنظیمات تست URL» پیاده‌سازی شده است. تنظیمات مسیریابی RU-DIRECT را از دستورالعمل‌های Shadowrocket بگیرید. نیازمند مقدار زیادی رم.*

   **③ `V2Box`** **https://apps.apple.com/us/app/v2box-v2ray-client/id6446814690**

   *برای اشتراک‌های استاندارد. به‌طور خودکار کانفیگ‌ها را در پس‌زمینه بررسی کنید (در منوی اصلی باید «اتصال هوشمند» را فعال کنید). فهرست‌های جغرافیایی و مسیرهای نقطه‌ای به‌طور راحت در منوی اصلی کانفیگ می‌شوند.*

   **④ `Happ`** **https://apps.apple.com/us/app/happ-proxy-utility/id6504287215**

   *استفاده با اشتراک ویژه برای Happ. بهترین گزینه با یک دکمه در حال حاضر! کلاینت برای دستگاه‌های ضعیف/قدیمی به‌خوبی بهینه‌سازی شده است. اگر Karing/Shadowrocket/Streisand به دلیل کمبود حافظه رم اتصال را از دست داد، از Happ استفاده کنید.*

   **⑤ `Streisand`** **https://apps.apple.com/us/app/streisand/id6450534064**
   
   *استفاده با اشتراک ویژه برای Streisand. نیازمند مقدار زیادی حافظه رم.*

   **⑥ `v2RayTun`** **https://apps.apple.com/us/app/v2raytun/id6476628951**

   *استفاده با اشتراک ویژه برای v2RayTun.* 


</details>

---
  
### <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExODUzYWRwNzNpa3doMDd1bXo4NTlzanJsaTcya3dlNXA4d3c5cnVzNCZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/UQJlZ2OcaCA2RLfGiZ/giphy.gif" width="20" align="absmiddle"> `Android`

<details>
<summary><em><code> گسترش </code></em></summary>

㋡

* از Karing، Exclave با اشتراک‌های استاندارد/سراسری استفاده کنید. مسیریابی و بررسی سلامت خودکار باید ابتدا در خود کلاینت بررسی و/یا پیکربندی شود؛ 

* Clash Mi، ClashMetaForAndroid و FlClash - با اشتراک‌های Clash. بررسی سلامت خودکار + مسیریابی به‌صورت درونی در خود اشتراک‌ها قرار دارند؛ 

* Happ، v2rayNG، v2RayTun، V2Box با اشتراک‌های ویژه برای این کلاینت‌ها. بررسی سلامت خودکار + مسیریابی به‌صورت درونی در خود اشتراک‌ها قرار دارند. گزینه VPN با یک دکمه؛  

**پایدارترین‌ها اشتراک‌های Clash/YAML + کلاینت‌ها Mihomo و Standard + Karing هستند.**

---

### `کلاینت‌های Android برای اشتراک‌های Clash` (Mihomo):

 اشتراک‌های Clash بر اساس منطقه تقسیم‌بندی شده‌اند:
  
- اشتراک‌های Clash برای کاربران روسیه (RU-DIRECT به‌طوری که تمامی سایت‌های روسیه بدون VPN باز شوند): 

https://github.com/igareck/vpn-configs-for-russia/tree/main/Export/Clash/RU_DIRECT

- اشتراک‌های Clash برای نسخه بین‌المللی (برای کشورهای دیگر که RU-DIRECT نیاز نیست): 

https://github.com/igareck/vpn-configs-for-russia/tree/main/Export/Clash/GLOBAL

| | | |
|---|---|---|
| **① `Clash Mi`** | **② `ClashMetaForAndroid`** | **③ `FlClash`** |
| **[Clash Mi در GitHub](https://github.com/KaringX/clashmi/releases)** | **[ClashMetaForAndroid در GitHub](https://github.com/MetaCubeX/ClashMetaForAndroid/releases)** | **[FlClash در GitHub](https://github.com/chen08209/FlClash/releases)** |
| *کلاینت رایگان برای اشتراک‌های Clash از همان توسعه‌دهنده Karing* | *کلاینت از خالقان هسته Mihomo است، توصیه شده توسط توسعه‌دهندگان بهترین کلاینت رایگان Clash برای دسکتاپ‌ها "Clash Verge Rev"* | *رابط Flutter مدرن تر از ClashMetaForAndroid. برای کسانی که یک وارد ساده YAML و دکمه اتصال می خواهند، FlClash ممکن است بهتر باشد* |
| | | |

ایگارک قبلاً بررسی خودکار سلامت کانفیگ‌ها را در تمام اشتراک‌های Clash برای راحتی کاربران تعبیه کرده است. تمام کاری که باید انجام دهید این است که اشتراک RAW-Clash را دانلود کرده و تمدید خودکار آن را در کلاینت هر ۱-۲ ساعت کانفیگ کنید.

---

### `کلاینت‌های Android برای اشتراک‌های استاندارد و اشتراک‌های ویژه با بررسی خودکار سلامت:`

**① `Karing`** https://github.com/KaringX/karing/releases

*برای اشتراک‌های استاندارد. بهترین کلاینت رایگان و عمومی در حال حاضر. بررسی سلامت خودکار کانفیگ‌ها در پس‌زمینه. لیست‌های جغرافیایی و مسیریابی نقاط به‌صورت راحت در نصب اولیه کانفیگ می‌شوند. نیازمند مقدار زیادی رم.*

**② `Exclave`** https://github.com/dyhkwong/Exclave/releases

*برای اشتراک‌های استاندارد. این پلتفرم منحصرا Android است. مکانیزمی داخلی برای بررسی سلامت خودکار وجود دارد که از طریق "Balancer" (Balancer) با استراتژی "LeastPing" پیاده‌سازی می شود. در خود کلاینت پیکربندی شده است. مسیریابی جغرافیایی RU-DIRECT در کلاینت تعبیه شده است، اما اگر وجود نداشت، دستورالعمل های Exclave را مشاهده کرده و به صورت دستی اضافه کنید. به دقت به تنظیمات دیگر نگاه کنید!*

**③ `Happ`** https://play.google.com/store/apps/details?id=com.happproxy

*استفاده با اشتراک ویژه برای Happ. گزینه تک‌دکمه‌ای. اشتراک دارای مکانیزم داخلی برای بررسی خودکار سلامت و مسیریابی است. کلاینت برای دستگاه‌های ضعیف/قدیمی بهینه شده است. در صورت قطع اتصال Karing به دلیل کمبود رم، از Happ استفاده کنید.*

**④ `v2rayNG`**  https://github.com/2dust/v2rayNG/releases

*استفاده با اشتراک ویژه برای v2rayNG. گزینه تک‌دکمه‌ای. اشتراک دارای مکانیزم داخلی برای بررسی خودکار سلامت است که از طریق «گروه سیاست» / «گروه سیاست» با استراتژی «کمترین پینگ» اجرا می‌شود، و همچنین مسیریابی دارد.*

**⑤ `v2Box`** https://play.google.com/store/apps/details?id=dev.hexasoftware.v2box

*استفاده با اشتراک v2Box ویژه. گزینه تک‌دکمه‌ای. اشتراک دارای مکانیزم داخلی برای بررسی خودکار سلامت و مسیریابی است.*

**⑥ `v2RayTun`** https://play.google.com/store/apps/details?id=com.v2raytun.android&hl=en&pli=1

*استفاده با اشتراک ویژه برای v2RayTun. گزینه‌ی تک‌دکمه‌ای. اشتراک دارای مکانیزم داخلی برای بررسی خودکار سلامت و مسیریابی است. کلاینت به‌طور بهینه برای دستگاه‌های ضعیف/قدیمی طراحی شده است. از v2RayTun استفاده کنید اگر Karing به دلیل کمبود RAM اتصال را از دست بدهد.*

**⑦ `NekoBox`** https://github.com/MatsuriDayo/NekoBoxForAndroid/releases

*برای اشتراک‌های استاندارد. پلتفرم به‌طور انحصاری Android است. NekoBox اصلی مکانیزم داخلی برای بررسی خودکار سلامت ندارد، فقط تست URL دستی دارد.*

</details>

---

### <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExODUzYWRwNzNpa3doMDd1bXo4NTlzanJsaTcya3dlNXA4d3c5cnVzNCZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/UQJlZ2OcaCA2RLfGiZ/giphy.gif" width="20" align="absmiddle"> `روترهای OpenWrt، دستگاه‌های NAS و سیستم‌های Linux`

<details>
<summary><em><code> گسترش </code></em></summary>

### ① `ShellCrash`

**https://github.com/juewuy/ShellCrash**

1. **گزینه‌ای عمومی برای انواع پلتفرم‌ها: روترها و فریمورهای مشتق شده OpenWrt، NAS، Docker و سیستم‌های Linux. سازگار با OpenWrt، Padavan، Pandora، ASUS Merlin، Debian، Ubuntu، CentOS، Armbian، Linux/BusyBox، Docker، Synology و PVE.**

2. **هسته:** Mihomo/Sing-box.

3. **بررسی سلامت خودکار.**

4. **چه اشتراک‌هایی را می‌پذیرد؟** اشتراک‌های Clash YAML را به‌طور بومی می‌پذیرد. اشتراک‌های معمولی (از رشته‌های رایج vless://، ss://، trojan:// و غیره) و Base64 هنگام وارد کردن به‌طور خودکار به فرمت Clash تبدیل می‌شوند.

**برای دستورالعمل‌های دقیق، بخش «دستورالعمل‌ها برای هر کلاینت به‌صورت جداگانه» را ببینید.**

---

### ② `OpenClash`

**https://github.com/vernesong/openclash**

1. **یکی از مشهورترین کلاینت‌ها OpenWrt+LuCI (و مشتقات سازگار آن).**

2. **هسته:** Mihomo.

3. **بررسی سلامت خودکار.**

4. **چه اشتراک‌هایی را می‌پذیرد؟** اشتراک‌های Clash YAML را به‌طور بومی می‌پذیرد. اشتراک‌های معمولی (از رشته‌های رایج vless://، ss://، trojan:// و غیره) و Base64 هنگام وارد کردن به‌طور خودکار به فرمت Clash تبدیل می‌شوند.

**برای دستورالعمل‌های دقیق، بخش «دستورالعمل‌ها برای هر کلاینت به‌صورت جداگانه» را ببینید.**

---

### ③ `Nikki`

**https://github.com/nikkinikki-org/OpenWrt-nikki**

1. **یک جایگزین مدرن‌تر و جمع‌وجورتر برای OpenClash.**

   **به عنوان یک پروکسی شفاف مدرن برای OpenWrt 24.10+، Linux 5.13+ با firewall4/nftables قرار گرفته است.** 

2. **هسته:** Mihomo.

3. **بررسی سلامت خودکار.**

4. **چه اشتراک‌هایی را می‌پذیرد؟** فقط اشتراک‌های Clash YAML را می‌پذیرد. هنگام وارد کردن فرمت‌های دیگر خطا رخ خواهد داد.

**برای دستورالعمل‌های دقیق، بخش «دستورالعمل‌ها برای هر کلاینت به‌صورت جداگانه» را ببینید.**

---

### ④ `PassWall2`

**https://github.com/Openwrt-Passwall/openwrt-passwall2**

1. **گزینه‌ی عمومی برای OpenWrt 21.02+، همراه با LuCI و فریمورهای مشتق شده (برای مثال ImmortalWrt).** 

2. **هسته:** Sing-box/Xray.

3. **بررسی سلامت خودکار.**

4. **چه نوع اشتراک‌هایی را می‌پذیرد؟** اشتراک‌های معمولی (از رشته‌های رایج مانند vless://، ss://، trojan:// و غیره)، همچنین Base64. Clash YAML اشتراک‌ها را وارد می‌کند اما آنها را به فرمت معمولی تبدیل می‌کند.

**برای دستورالعمل‌های دقیق، بخش «دستورالعمل‌ها برای هر کلاینت به‌صورت جداگانه» را ببینید.**

---

### ⑤ `dae/daed`

**https://github.com/daeuniverse/dae**

**https://github.com/daeuniverse/daed**

1. **یک راه‌حل با عملکرد بالا برای سیستم‌های سرور مدرن Linux، مینی‌پی‌سی‌ها و دروازه‌های شبکه مبتنی بر Linux بدون رابط کاربری گرافیکی.** 

۲. **هسته:** هسته پروکسی مستقل `dae`. این پروژه از Xray، Sing-box یا Mihomo استفاده نمی‌کند. توسعه‌دهندگان به‌طور مستقیم می‌نویسند که این پروژه، به‌عنوان جانشین v2rayA، از v2ray-core صرف‌نظر کرده است. `dae` یک هسته پروکسی مستقل است و `daed` یک پنل کنترل مبتنی بر مرورگر ارائه می‌دهد.

3. **بررسی سلامت خودکار.**

۴. **چه اشتراک‌هایی را می‌پذیرد؟** اشتراک‌های معمولی (از رشته‌های رایج vless://، ss://، trojan:// و غیره) و همچنین Base64.

**برای دستورالعمل‌های دقیق، بخش «دستورالعمل‌ها برای هر کلاینت به‌صورت جداگانه» را ببینید.**

</details>

---
---

## <img src="https://upload.wikimedia.org/wikipedia/commons/d/df/Tor_Browser_icon_%28New%29.png" width="38" align="absmiddle"> `برنامه‌ها (کلاینت‌ها) برای Tor Bridges بر روی PC، گوشی، روتر`

**لینک دانلود رسمی** `Tor Browser` (از طریق VPN یا Tor): https://www.torproject.org/fa/download/

**نسخه به‌روز‌شده** `Tor Browser` **را از طریق ربات Telegram دریافت کنید**: @gettor_bot

**نسخه به‌روزشده را دریافت کنید** `Tor Browser` **ممکن است از طریق ایمیل**با ارسال ایمیلی با موضوع «ویندوز»، «مکوس»، «لینوکس» یا «اندروید» - بسته به سیستم عامل شما: gettor@torproject.org

*برای Windows، macOS، Linux، Android موجود است.*

**پل ها**به جز در این مخزن، شما همچنین می توانید به طور رسمی **از پروژه تور، شرکت دریافت کنید** 

اما در این مورد باید آن ها را مرتب و آزمایش کرد، چون... پل هایی که با آن ها روبرو می شوید همیشه برای روسیه کار نمی کنند.

**پل‌ها از طریق ایمیل** (ارسال یک ایمیل از آدرس جیمیل یا رایزآپ خود): bridges@torproject.org

**پل‌ها از طریق ربات Telegram**: @GetBridgesBot 

**پل‌ها در وب‌سایت رسمی پروژه تور**: https://bridges.torproject.org/options

---

###  <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3amtqMmQxOGh0aG0waGk5OGhhNG5odmdob2k1bWc4ejNyZ3E3N2Y2bCZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/xUS4Fp5i6iIn2Y1EYT/giphy.gif" width="25"> `Windows/MacOS/Linux`

<details>
<summary><em><code> گسترش </code></em></summary>

### کلاینت‌ها پل‌های تور در لپ‌تاپ‌ها و رایانه‌های رومیزی.

### ① `OnionHop V3`

*من آن را به‌عنوان بهترین کلاینت رایگان برای استفاده از پل‌های تور در PC توصیه می‌کنم.*

*یک ابزار عمومی، کاربردی و قدرتمند برای اطمینان از اینکه اتصال شما همیشه به طور پایدار کار می‌کند.*

   **https://github.com/center2055/OnionHop/releases**

---

  ### ② `OnionFruit`

*یک کلاینت رایگان جایگزین برای استفاده از پل‌های تور در PC.*

*برای همه نوع پل‌های تور: وانیلا · obfs4 · وب تونل · meek · برفک · conjure*

*آدرس خروجی قابل تنظیم - به جای انتخاب تصادفی کشور خروجی، می‌توانید یک کشور خاص از فهرست انتخاب کنید، برای مثال: آمریکا، آلمان، استرالیا یا ژاپن.*

*به عنوان یک SYSTEM کار می‌کند PROXY، حالت TUN اعلام نشده است.*

   **https://github.com/dragonfruitnetwork/onionfruit/releases**

   **https://dragonfruit.network/onionfruit**

   `install-x64.exe` - نسخه نصبی GUI 2026.301.0 برای Windows 10/11 (فقط پلتفرم Windows، هیچ پلتفرم دیگری)

  با دوبار کلیک روی install-x64.exe فوراً نصب می‌شود. به دنبال OnionFruit نصب‌شده در دسکتاپ و منوی استارت باشید.

</details>

---

### <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExODUzYWRwNzNpa3doMDd1bXo4NTlzanJsaTcya3dlNXA4d3c5cnVzNCZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/UQJlZ2OcaCA2RLfGiZ/giphy.gif" width="20" align="absmiddle"> `iOS/Android`

<details>
<summary><em><code> گسترش </code></em></summary>

###  کلاینت‌ها برای پل‌های Tor بر روی دستگاه‌های موبایل.

**① `Onion Browser` App Store:** https://apps.apple.com/us/app/onion-browser/id519296448

**② `Onion Browser` Google Play:** https://play.google.com/store/apps/details?id=org.torproject.torbrowser

**③ ویکی‌پدیا `Orbot`:** https://fa.wikipedia.org/wiki/%D8%A7%D9%88%D8%B1%D8%A8%D8%A7%D8%AA

**④ `Orbot` App Store:** https://apps.apple.com/us/app/orbot/id1609461599

**⑤ `Orbot` Google Play:** https://play.google.com/store/apps/details?id=org.torproject.android

**⑥ وب‌سایت رسمی `Invizible Pro`:** https://invizible.net/en

**⑦ `Invizible Pro` Google Play:** https://play.google.com/store/apps/details?id=pan.alexander.tordnscrypt.gp

</details>

---

### <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExODUzYWRwNzNpa3doMDd1bXo4NTlzanJsaTcya3dlNXA4d3c5cnVzNCZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/UQJlZ2OcaCA2RLfGiZ/giphy.gif" width="20" align="absmiddle"> `روترها`

<details>
<summary><em><code> گسترش </code></em></summary>

### ① `TorBox`

**https://github.com/radio24/TorBox**

1. **گزینه‌ای برای تبدیل یک Raspberry Pi یا سایر دستگاه‌های Debian/Ubuntu/DietPi Linux به یک روتر مجزای تور. TorBox یک شبکه Wi-Fi جداگانه ایجاد می‌کند یا دستگاه‌های متصل از طریق کابل اترنت را قبول کرده و ترافیک TCP آن‌ها را از طریق Tor هدایت می‌کند.**

2. **چه بریج‌هایی را قبول می‌کند؟** رابط ادعا می‌کند که Vanilla، Obfs4، Snowflake و meek-azure را قبول می‌کند.

---

### ② `Tor Bridges Proxy - OpenWrt LuCI`

**https://github.com/zerolabnet/luci-app-torbp**

1. **یک ماژول پروفایل مفید LuCI برای تور که در داخل OpenWrt اجرا می‌شود.**

2. **چه بریج‌هایی را قبول می‌کند؟** رابط بیان می‌کند که Obfs4 را قبول می‌کند.

</details>

---
---

## <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3ZDhxeG02NHlucTdqZGhtejBnb2V5dGpwaDBmcHhobWlsOHQxdWpoYSZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/8L0hXHQkY4o7eyQHJB/giphy.gif" width="45" align="absmiddle"> `اطلاعات مفید`

⚡ **چرا من اصلاً کانفیگ‌ها VPN را تست می‌کنم؟** در ابتدای کارم روی مخزن (در نوامبر ۲۰۲۵) از بین بیش از ۴۰٬۰۰۰ کانفیگ‌ها عمومی رایگان که برای تست گرفته شده بود، حدود ۷۰۰ مورد تست عملکرد را گذراندند که کمتر از ۲٪ است و در نهایت من حدود ۲۰۰ مورد با بالاترین کیفیت، پاسخ سریع و سرعت قابل قبول در اینجا قرار دادم، که این خود نیم درصد است. همه وقت ندارند که با مجموعه‌ای از ده‌ها هزار کانفیگ‌ها سر و کار داشته باشند، جایی که تنها چند صد مورد واقعاً کار می‌کنند.

⚡ تا سپتامبر ۲۰۲۶، طبق تجزیه و تحلیل خودمان، **درصد کانفیگ‌ها فعال VPN** از کل تعداد بررسی شده به شرح زیر بود: ۱ کانفیگ فعال برای هر ۱۰۰۰-۲۰۰۰. اما، با تشکر از بازرسی‌های منظم اسکریپت، به‌روزرسانی‌ها و بهبودها، کیفیت بررسی و مرتبط بودن اشتراک‌های `igareck/vpn-configs-for-russia` در سطح نسبتاً بالایی حفظ شد، با وجود دشواری‌های فزاینده.

⚡ در شبکه پروتکل‌های زیادی وجود دارد، اما **موثرترین** آن‌ها، محافظت در برابر DPI از Roskomnadzor و مسدود کردن آن است - این **VLESS+Reality** است به دلیل توانایی آن در ماسک کردن ترافیک به‌عنوان دسترسی به یک سایت بی‌خطر HTTPS، که استفاده از VPN را برای ارائه‌دهنده اینترنت شما کاملاً نامرئی می‌کند. پروتکل‌های باقی‌مانده به ترتیب نزولی رتبه‌بندی شده‌اند، زیرا آسان‌تر می‌توان آن‌ها را آشکار کرد. 

⚡ برخی کانفیگ‌ها ممکن است به مرور زمان به دلایل خارج از کنترل من از کار بیفتند، بنابراین **فهرست‌ها به‌صورت دوره‌ای به‌روزرسانی خواهند شد**.

⚡ **اگر اتصال‌ها به‌صورت مکرر و سریع قطع می‌شوند** ۳-۵ دقیقه بعد از شروع کار - سعی کنید **پارامتر MTU** را در کلاینت کاهش دهید، از ۹۰۰۰ به ۳۰۰۰/۱۵۰۰/۱۳۰۰/۱۲۰۰.

⚡ **اگر ISP شما اتصال یا ترافیک VPN شما را مسدود می‌کند** - DNS معمولی خود را در روتر، PC یا گوشی به یک ارتباط رمزگذاری‌شده تغییر دهید: **از DNS-over-HTTPS (DoH) استفاده کنید**. در بعضی موارد این واقعاً مفید است.

مثالی قابل توجه که این کار جواب می‌دهد: در اینترنت کابلی و اپراتورهایی بدون فیلترینگ سنگین، DoH کانفیگ شده به ایجاد کانفیگ‌های Shadowsocks بدون اختفا (SS بدون پلاگین) کمک می‌کند. اشتراک را ببینید **[BLACK_SS_WEAK_DPI_RUS.txt](https://raw.githack.com/igareck/vpn-configs-for-russia/main/BLACK_SS_WEAK_DPI_RUS.txt)**. با ISP/DNS خودکار، Shadowsocks بدون پلاگین به احتمال زیاد اجازه عبور ترافیک را نخواهد داد.

DNS-over-TLS (DoT) احتمالاً برای اکثر افراد کار نخواهد کرد. 

حتی اگر تغییر DNS کمک نکند (این بدان معناست که باید به دنبال دلیل دیگری باشید) - فقط یک DoH برای حفظ حریم خصوصی آنلاین خود تنظیم کنید!

⚡ **اگر پینگ وجود دارد اما ترافیک نیست** - سعی کنید **DNS از راه دور (Remote DNS)** را در تنظیمات کلاینت خود از استاندارد **on DNS-over-HTTPS (DoH)** جایگزین کنید.

⚡ **در طول رژیم لیست سفید (محدودیت‌های تهدید پهپاد) هیچ ارائه‌دهنده خارجی DNS کار نمی‌کند** (نه گوگل، نه Cloudflare، نه Quad9، نه علی‌بابا، نه OpenDNS، نه). در این صورت، از DNS خودکار از ارائه‌دهنده خود یا DNS/DNS-over-HTTPS از Yandex استفاده کنید. در غیر این صورت، کانفیگ‌های VPN برای لیست سفید به سادگی کار نخواهند کرد.

⚡ شاید، **در آینده نزدیک**، به دلیل افزایش مسدودسازی عمومی DNS-over-HTTPS (DoH) به این نتیجه برسیم که **به جای استفاده از ارائه‌دهندگان عمومی DNS مانند Google/Cloudflare/Quad9 و دیگران، ما خودمان DoH خود را روی VPS اجاره‌ای ایجاد کنیم**، که به اصطلاح **DNS-روی-VPS** نامیده می‌شود، و با سرور VPN به طور مشترک کار خواهد کرد.

⚡ **چرا من در حال آزمایش پل‌های تور هستم وقتی که می‌توان آن‌ها را از پروژه تور نیز دریافت کرد؟** بله، شما می‌توانید آن را از پروژه تور دریافت کنید، به همین دلیل است که من انواع مختلفی از راه‌های تماس را ارائه داده‌ام. اما مشکل این است که پروژه تور پل‌ها را بدون تمرکز بر یک منطقه/کشور خاص ارائه می‌دهد، بلکه به صورت جهانی این کار را انجام می‌دهد. یعنی، در آمریکا همان پل تور می‌تواند به‌طور کامل کار کند، اما در روسیه دیگر اتصال را به دلیل مسدودسازی، مشکلات شبکه و دلایل دیگر فراهم نمی‌کند. پل‌های موجود در مخزن من هر ۴ ساعت یک‌بار به طور خاص برای کار در روسیه آزمایش می‌شوند، که پیدا کردن همان گزینه واقعی و کارآمد را برای کاربر نهایی آسان‌تر و سریع‌تر می‌کند. نه تنها پینگ تست می‌شود، بلکه اتصال کامل هر پل نیز، زیرا پینگ معمولی شاخصی برای عملکرد نیست.

⚡ **برای دریافت به‌روزرسانی‌ها، همراه ما باشید و فراموش نکنید که حداقل هر دو هفته یک بار برنامه‌های کلاینت را به‌روزرسانی کنید. عملکرد کانفیگ‌ها به طور مستقیم به این موضوع بستگی دارد. نسخه‌های جدید شامل اصلاحات هستند و سرورهای زنده بیشتری را مشاهده کنید.**

⚡ **برای پایدارترین عملکرد اینترنت، همراه با VPN در روسیه، توصیه می‌شود از شبکه‌های اپراتورهای منطقه‌ای کوچک استفاده کنید**، زیرساخت آن‌ها با ارائه‌دهندگان بزرگ مانند Ростелеком، ER-Telecom (Dom.ru)، Beeline، Megafon، MTS و مشابه آن‌ها متصل نیست. 

اپراتورهای کابل منطقه‌ای فیلترهای ضعیف‌تری دارند. تغییر اپراتورها آسان‌تر از تحمل تأخیرهای بی‌پایان است.

من قصد دارم یک فهرست از ارائه‌دهندگان توصیه شده ایجاد کنم.

##  `DNS-over-HTTPS`

### 🧾 DNS-over-HTTPS (DoH) چیست و چگونه متصل می‌شود؟ 

<details>

<summary><em> برای جزئیات روی فلش کلیک کنید </em></summary>

㋡

***DNS-over-HTTPS (DoH)*** - این همان DNS است، فقط رمزگذاری شده و خصوصی. DNS از طریق HTTPS درخواست‌های DNS از ناظران محلی (ارائه‌دهنده) را رمزگذاری می‌کند و حریم خصوصی را افزایش می‌دهد. 

اما خود مفسر DNS (Cloudflare/گوگل و غیره) هنوز درخواست‌ها را می‌بیند (شما درخواست‌ها را از طریق آن عبور می‌دهید). ارائه‌دهنده فقط اتصال به آدرس مفسر IP‑DoH/DoT (و حجم/زمان ترافیک) + IP نهایی سرور هدف را می‌بیند، یعنی IP نهایی سایت بازدید شده بدون نام دامنه هدف (و در صورت نبود ECH - دامنه از طریق SNI). بر اساس IP نهایی (و در صورت نبود ECH - از طریق SNI) اغلب (ولی نه همیشه) می‌توان سایت را شناسایی کرد. 

ممکن است (ولی نه 100%) DoH به شما اجازه بدهد برخی محدودیت‌های اتصال را دور بزنید، اگر وجود داشته باشند. DoH می‌تواند در دور زدن فیلترهای ساده DNS کمک کند، اما نه در مورد بلاک شدن IP/SNI یا فیلترینگ عمیق.  

این استاندارد توسط IETF به عنوان RFC 8484 (۲۰۱۸) منتشر شده است و ICANN در پیاده‌سازی پروتکل کمک کرده است، و گوگل ابتدا آن را در سال ۲۰۱۶ پیاده‌سازی/آزمایش کرد! هدف افزایش حریم خصوصی و امنیت کاربر است.

㋡

### `چگونه DNS-over-HTTPS را فعال کنیم؟`

### `روی روتر:` 

صحیح‌ترین گزینه اگر دسترسی به روتر دارید.

حذف و غیرفعال کردن ارائه‌دهنده پیش‌فرض DNS و تنظیم DNS-over-HTTPS (DoH)، ابتدا باید کلاینت DoH را در تنظیمات بروز رسانی روتر دانلود کنید. DNS-over-HTTPS (DoH) باید ۱۰۰٪ پایدار کار کند. DNS-over-TLS (DoT) می‌توانید امتحان کنید، اما نتیجه تضمین نشده است، در روسیه به دلیل مسدود شدن‌های مکرر توصیه نمی‌شود، در واقع DoT در حال حاضر برای اکثریت ساکنان فدراسیون روسیه کار نمی‌کند.

### `روی تلفن` سه گزینه وجود دارد:

***۱. برنامه ویژه برای DNS-over-HTTPS.*** 

| | |
|---|---|
| **iOS (اپ استور)** | **Android (فروشگاه Google Play)** | 
| **1.1.1.1: اینترنت سریع‌تر** (Cloudflare): https://apps.apple.com/us/app/1-1-1-1-faster-internet/id1423538627 | **Cloudflare 1.1.1.1 + WARP: اینترنت امن‌تر**: https://play.google.com/store/apps/details?id=com.cloudflare.onedotonedotonedotone&hl=en-US |
| **AdGuard DNS**: https://apps.apple.com/us/app/adguard-dns/id6754605049 | **AdGuard DNS**: https://play.google.com/store/apps/details?id=com.adguard.dnsclient |
| **DNSecure**: https://apps.apple.com/us/app/dnsecure/id1533413232 | **Intra**: https://play.google.com/store/apps/details?hl=en&id=app.intra |
| **راه‌اندازی سریع Control D:** https://apps.apple.com/us/app/control-d-quick-setup/id1518799460 | **نبولو**: https://play.google.com/store/apps/details?hl=en&id=com.frostnerd.smokescreen (آنها می‌نویسند که تبلیغات را به‌خوبی فیلتر می‌کند) |
| | |

علاوه بر DoH، نکته اصلی برنامه Cloudflare حالت WARP است، یعنی یک تونل رمزگذاری‌شده در سراسر سیستم از طریق شبکه Cloudflare. WARP می‌تواند به عنوان یک VPN برای عبور از محدودیت‌ها استفاده شود اگر ارائه‌دهنده اینترنت شما آن را مسدود نکند. اما در روسیه WARP مسدود است، بنابراین فقط DoH. از آنجایی که Cloudflare به‌طور سیستماتیک توسط Roskomnadzor خفه می‌شود، ممکن است در اتصال به DoH از طریق برنامه Cloudflare مشکلاتی وجود داشته باشد. در صورت نیاز از جایگزین‌ها استفاده کنید.

به طور معمول برنامه‌ها از این نقطه از رابط VPN محلی استفاده می‌کنند. بنابراین، احتمالاً نمی‌توانند همزمان با Karing، v2rayNG یا کلاینت دیگری در حالت VPN کار کنند: Android/iOS معمولاً اجازه یک کاربر فعال VPN را می‌دهد.

 برای Karing/Exclave/Throne و دیگران بهتر است: DoH را مستقیماً داخل Karing/Exclave/Throne کانفیگ کنید یا از فایل کانفیگ سیستم iOS (نقطه ۲) یا تنظیمات شبکه Android (نقطه ۳) استفاده کنید.

***۲. iOS (فایل کانفیگ سیستم .mobileconfig).*** 

**برای iOS کانفیگ‌ها شبکه پایه وجود ندارد و کانفیگ‌های DoH به صورت یک فایل جداگانه دانلود می‌شوند**: 

* یا در وب سایت های رسمی Quad9، AdGuard، Dnsforge و غیره. 

* یا از این مخزن Igareck که به طور ویژه توسط من DoH .mobileconfig برای Google/OpenDNS/Cloudflare/Yandex جمع‌آوری شده است (چون این ارائه‌دهندگان به طور رسمی کانفیگ‌ها DoH را برای آیفون ها انجام نمی دهند). 

لینک ها را در بخش «فهرست سرورهای DoH عمومی» در پایین جستجو کنید؛

لینک های کانفیگ‌های DoH تا آیفون بتواند آن ها را به درستی دانلود و نصب کند، فقط در مرورگر سافاری باز می شوند.

***3. Android (تنظیمات شبکه).*** 

برای Android، به **تنظیمات** ➡️ **شبکه و اینترنت** (یا **Wi-Fi و اینترنت**) ➡️ انتخاب **تنظیمات پیشرفته** ➡️ **سرور شخصی DNS (خصوصی DNS)** ➡️ انتخاب **نام میزبان ارائه‌دهنده شخصی DNS** و وارد کردن **نام میزبان** یکی از آدرس‌های عمومی DoH (مطالعه کنید زیر "لیست سرورهای عمومی DoH")، به عنوان مثال `dns.google` / `doh.opendns.com` / `dns.cloudflare.com` / `dns.alidns.com` یا `common.dot.dns.yandex.net`؛

### `در رایانه/لپ‌تاپ:` 

سرور DoH را در تنظیمات DNS مبدل شبکه ثبت کنید، به عنوان مثال `https://dns.google/dns-query` / `https://doh.opendns.com/dns-query` / `https://dns.cloudflare.com/dns-query` / `https://dns.alidns.com/dns-query` یا `https://common.dot.dns.yandex.net/dns-query`.

### `در خود برنامه/کلاینت VPN:`

سرور DoH را در تنظیمات DNS برنامه/کلاینت ثبت کنید، یا از موارد از پیش تعیین‌شده انتخاب کنید.

---

</details>


### 🧾 فهرست سرورهای عمومی DoH (+ دانلود فایل کانفیگ DoH با فرمت .mobileconfig)

<details>

<summary><em> برای جزئیات روی فلش کلیک کنید </em></summary>

㋡

**Yandex**

**`https://common.dot.dns.yandex.net/dns-query`** - *Yandex DNS پایه. توجه! فقط برای حالت لیست سفید توصیه می‌شود، در حالت عادی (برای لیست سیاه) از سرورهای DNS زیر استفاده کنید;*

**`https://safe.dot.dns.yandex.net/dns-query`** - *Yandex DNS حالت ایمن. توجه! فقط برای حالت لیست سفید توصیه می‌شود، در حالت عادی (برای لیست سیاه) از سرورهای DNS زیر استفاده کنید;*

**[Yandex_DoH_iPhone.mobileconfig](https://raw.githack.com/igareck/GoldCaviar/main/Files/Yandex_DoH_iPhone.mobileconfig)**  - *دانلود فایل کانفیگ Yandex DoH (Yandex DNS پایه) برای iOS;*

**گوگل**

**`https://dns.google/dns-query`** یا **`https://8.8.8.8/dns-query`** - *Google Public DNS، مستقر در مانتین ویو، کالیفرنیا، ایالات متحده آمریکا;*

**[Google_DoH_iPhone.mobileconfig](https://raw.githack.com/igareck/GoldCaviar/main/Files/Google_DoH_iPhone.mobileconfig)**  - *دانلود فایل کانفیگ Google DoH برای iOS;*

**Cloudflare**

**`https://dns.cloudflare.com/dns-query`** یا **`https://cloudflare-dns.com/dns-query`** یا **`https://one.one.one.one/dns-query`** - *Cloudflare DNS پایه، مستقر در سان فرانسیسکو، کالیفرنیا، ایالات متحده آمریکا;*

**`https://security.cloudflare-dns.com/dns-query`** - *Cloudflare DNS برای مسدود کردن بدافزار، مستقر در سانفرانسیسکو، کالیفرنیا، ایالات متحده آمریکا؛*

**[Cloudflare_DoH_iPhone.mobileconfig](https://raw.githack.com/igareck/GoldCaviar/main/Files/Cloudflare_DoH_iPhone.mobileconfig)**  - *دانلود فایل کانفیگ Cloudflare DoH (Cloudflare DNS پایه) برای iOS;*

**OpenDNS**

**`https://doh.opendns.com/dns-query`** - *Cisco Umbrella (OpenDNS)، مستقر در سانفرانسیسکو، کالیفرنیا، ایالات متحده آمریکا؛*

**[OpenDNS_DoH_iPhone.mobileconfig](https://raw.githack.com/igareck/GoldCaviar/main/Files/OpenDNS_DoH_iPhone.mobileconfig)** - *دانلود فایل کانفیگ OpenDNS DoH برای iOS؛*

**AdGuard**

**`https://family.adguard-dns.com/dns-query`** یا **`https://dns.adguard-dns.com/dns-query`** - *AdGuard DNS. DNS از بلاک‌کننده معروف ترین تبلیغات و ردیاب رایگان، مستقر در لیماسول، قبرس؛*

**https://adguard-dns.io/ru/public-dns.html** - *دانلود فایل کانفیگ AdGuard DNS برای iOS، + خواندن دستورالعمل‌ها درباره سایر پلتفرم‌ها، به زبان روسی/انگلیسی؛*

**Quad9**

**`https://dns.quad9.net/dns-query`** - *Quad9 DNS پایه. مسدود کردن بدافزار، اعتبارسنجی DNSSEC. سیاست بدون ثبت لاگ. دفتر مرکزی در زوریخ، سوئیس;*

**`https://dns11.quad9.net/dns-query`** - *Quad9 DNS پیشرفته. امن با ECS: مسدود کردن بدافزار، اعتبارسنجی DNSSEC، ECS فعال. سیاست بدون ثبت لاگ. دفتر مرکزی در زوریخ، سوئیس;*

**https://docs.quad9.net/Setup_Guides/iOS/iOS_14_and_later_(Encrypted)** - *دانلود کانفیگ Quad9 DNS برای iOS، + خواندن دستورالعمل‌ها درباره سایر پلتفرم‌ها، زبان - فقط انگلیسی/فرانسوی، بدون روسی;*

**DNSFORGE**
 
**`https://blank.dnsforge.de/dns-query`** یا **`https://dnsforge.de/dns-query`** - *DNS (خالی/معمولی) از تبلیغ‌دهنده و مسدودکننده ردیاب رایگان آلمانی DNSFORGE dnsforge.de. سیاست بدون ثبت لاگ، سرورها در فالکن‌اشتاین، آلمان. تمام اطلاعات و دستورالعمل‌ها به زبان آلمانی هستند؛*

**[dnsforge-doh.mobileconfig](https://dnsforge.de/dnsforge-doh.mobileconfig)**  - *دانلود فایل کانفیگ DNS (معمولی) از DNSFORGE.DE برای iOS؛*

**[blank-dnsforge-doh.mobileconfig](https://dnsforge.de/blank-dnsforge-doh.mobileconfig)**  - *دانلود فایل کانفیگ DNS (خالی) از DNSFORGE.DE برای iOS؛*

**https://dnsforge.de** - *دانلود سایر فایل‌های کانفیگ DNSFORGE، + خواندن دستورالعمل‌های مربوط به سایر پلتفرم‌ها، به زبان آلمانی؛*

**سایر**

**`https://dns.alidns.com/dns-query`** یا **`https://223.5.5.5/dns-query`** - *Alibaba Public DNS/AliDNS، مستقر در هانگژو، چین اصلی.*

**`https://doh.pub/dns-query`** - *شرکت خدماتی Tencent Cloud، مستقر در شنژن، چین اصلی.*

**`https://freedns.controld.com/p0`** یا **`https://freedns.controld.com/p2`** - *Control D Free DNS، مستقر در تورنتو، کانادا;*

**`https://base.dns.mullvad.net/dns-query`** یا **`https://dns.mullvad.net/dns-query`** - *Mullvad رمزگذاری شده DNS، مستقر در گوتنبرگ، سوئد;*

**`https://dns.hostux.net/dns-query`** - *Hostux Network، مستقر در لوکزامبورگ;*

**`https://doh.dns.sb/dns-query`** - *xTom GmbH، سرویس DNS.SB، دفتر مرکزی در دوسلدورف، آلمان؛*

**`https://adl.adfilter.net/dns-query`** - *ADFilter، دفتر مرکزی در آدلاید، استرالیا؛*

**`https://v.recipes/dns-query`** - *PT VRECIPES AMANAH SEMESTA، دفتر مرکزی در جنوب جاکارتا، اندونزی؛*

**`https://wurzn.hagezi.org/dns-query`** - *HaGeZi DNS، پروژه غیرانتفاعی خصوصی؛ میزبانی Hetzner Online GmbH، نورنبرگ، آلمان؛*

**`https://ada.openbld.net/dns-query`** - *OpenBLD، پروژه خصوصی، آلماتی، قزاقستان؛*

**`https://xbox-dns.ru/dns-query`** - *ایکس باکس DNS، یک پروژه خصوصی غیرانتفاعی؛ سرورها توسط Selectel در مسکو، روسیه میزبانی می‌شوند؛*

```diff
توجه:
در حالت White List (محدودیت‌های ناشی از تهدید پهپادی)، هیچ ارائه‌دهنده DNS خارجی کار نمی‌کند.
نه Google، نه Cloudflare، نه Quad9، نه Alibaba، نه OpenDNS و نه هیچ سرویس دیگری.
در این حالت، یا از DNS خودکار ارائه‌شده توسط ارائه‌دهنده اینترنت خود استفاده کنید یا از DNS / DNS-over-HTTPS شرکت Yandex.
در غیر این صورت، کانفیگ‌های VPN مربوط به White List به‌سادگی کار نخواهند کرد.
```

</details>

---

## <img src="https://upload.wikimedia.org/wikipedia/commons/7/77/Psiphon-logo-512.png" width="30" align="absmiddle"> `روش‌های جایگزین برای دور زدن محدودیت‌ها` (Psiphon)

<details>

<summary><code><em> برای جزئیات روی فلش کلیک کنید </em></code></summary>

<h3><code> Psiphon </code></h3>

**Psiphon** - نرم‌افزار رایگان و متن‌باز برای دور زدن سانسور اینترنت. Psiphon به‌طور خاص برای پشتیبانی از کاربران در کشورهایی با سانسور اینترنت طراحی شده است. Psiphon, Inc. در سال ۲۰۰۷ به‌عنوان یک شرکت مستقل در انتاریو، کانادا تأسیس شد. این شرکت با همکاری Citizen Lab در مدرسه Munk امور جهانی، دانشگاه تورنتو فعالیت می‌کند.

**اطلاعات:** https://fa.wikipedia.org/wiki/%D8%B3%D8%A7%DB%8C%D9%81%D9%88%D9%86

**لینک رسمی** برای دانلود روی Windows 10/11 (فقط از طریق VPN یا Tor قابل دسترسی است): https://psiphon.ca/fa/

**نصب‌کننده روی GitHub آپلود شد:** https://github.com/igareck/GoldCaviar/raw/refs/heads/main/Files/Psiphon3_VPN_install.exe

توجه! فقط روی اینترنت کابلی روی PC کار می‌کند (شبکه‌های موبایل نه)! مجموعه متنوعی از موقعیت‌ها!

سیستم بر اساس پروتکل قدیمی SSH است، اتصال سریع نیست، اما مهم‌ترین چیز این است که کار می‌کند. 

**وضعیت تا آگوست 2026:** ممکن است روی بسیاری از ارائه‌دهندگان کار نکند، خودتان بررسی کنید.

**ترکیب با اشتراک‌ها از مخزن (طرح VPN-over-VPN)، Psiphon می‌تواند به عنوان منبعی برای مکان جغرافیایی جایگزین استفاده شود اگر مکان مورد نیاز در اشتراک‌های استاندارد موجود نباشد.**

---

</details>

## 👁️‍🗨️ `ارائه‌دهنده چه چیزی را می‌بیند؟` وقتی در اینترنت هستید، چه چیزی قابل مشاهده است؟

<details>

<summary><code><em> برای جزئیات روی فلش کلیک کنید </em></code></summary>

⇩

**به‌طور کلی.**

**وقتی در اینترنت هستید، ۵ طرف وجود دارند که اقدامات شما را ارزیابی می‌کنند:**

**1.** `You yourself`

**۲.** `ارائه‌دهنده اینترنت شما` 

**3.** `وب‌سایت/موتور جست‌وجویی که از آن بازدید می‌کنید`

**۴.** `مرورگر شما (اگر از Yandex، گوگل و هر شرکت عمومی باشد)` 

**5.** `DNS resolver` 

**برخی افراد فکر می‌کنند که «ارائه‌دهنده همه چیز را می‌بیند.»**

**اما این یک تصور غلط است؛ ارائه‌دهنده چیز کمی می‌بیند اگر شما در شبکه به درستی رفتار کنید.**

بیایید عملکرد استاندارد اینترنت در سایت‌های HTTPS را بدون VPN توضیح دهیم. با HTTP عریان که رمزنگاری نشده اشتباه گرفته نشود. سال ۲۰۲۶ است و تقریباً هیچ سایت HTTP باقی نمانده است.

### `بیایید همه چیز را جداگانه بررسی کنیم`

### `۱. ارائه‌دهنده`

ارائه‌دهنده معمولاً سه چیز را می‌بیند: IP نهایی سایتی که به آن متصل می‌شوید + نام دامنه + بسته‌های رمزگذاری‌شده HTTPS که در مرورگر کاربر می‌رسند. آنچه در خود سایت اتفاق می‌افتد تنها برای دو طرف مشخص است - کاربر و سایت، همین! با تشکر از رمزگذاری HTTPS. فقط شما و گوگل می‌دانید که در گوگل دنبال چه چیزی هستید.

**اجازه دهید با استفاده از YouTube به عنوان مثال توضیح دهم:**

شما به سایت مورد علاقه ما YouTube رفتید، یک آموزش ویدیویی مفید دیدید، این ویدیو را باز کردید و تماشا کردید. ارائه‌دهنده چه چیزی می‌بیند؟ آی‌پی از YouTube + نام دامنه «YouTube» + بسته‌های رمزگذاری‌شده HTTPS که به PC کاربر می‌آیند! همین، هیچ چیز بیشتر! نوع ویدیوهایی که تماشا می‌کنید، آنچه در موتور جستجو جستجو می‌کنید برای ارائه‌دهنده قابل مشاهده نیست، زیرا این اتفاق مستقیماً در سایت رخ می‌دهد و با HTTPS رمزگذاری شده است. به سمت چپ نام سایت «https:» نگاه کنید - این همان رمزگذاری‌ای است که سایت با آن کار می‌کند و به میلیون‌ها نفر در سراسر جهان امنیت دیجیتال می‌دهد و کاربران را از نظارت دیجیتال محافظت می‌کند. 

**اجازه دهید با استفاده از موتور جستجوی گوگل به عنوان مثال توضیح دهم:** 

شما به Google.com رفتید تا تصاویر گربه‌ها را ببینید، عبارت *"cat meme bring cherries"* را در جستجو وارد کردید، و فهرستی از عکس‌ها با یک گربه در پیش‌بند دریافت کردید. ارائه‌دهنده چه چیزی می‌بیند؟ ترسناک؟ هیچ چیزی نمی‌بیند. آی‌پی از گوگل + نام دامنه "Google" + بسته‌های رمزگذاری شده HTTPS که به PC می‌روند را می‌بیند. آنچه شما دقیقاً آنجا نگاه می‌کنید، چه عکس‌هایی از گربه‌ها و در چه ژست‌هایی هستند - ارائه‌دهنده نمی‌بیند. بسته HTTPS، البته، شامل عکس‌های گربه در پیش‌بند است، اما بسته رمزگذاری شده است - بنابراین ارائه‌دهنده خواهد دید که شما "مشاهده چیزی در گوگل" هستید، اما این برای او یک مجموعه اطلاعات خالی است که حتی سوپرکامپیوترها هم نمی‌توانند رمزگشایی کنند، یا ۱۰۰ سال طول خواهد کشید. تصور کنید، آن‌ها در ۱۰۰ سال آن را رمزگشایی کنند، و آنجا "cat meme carry the cherry" یا "Natalia Marine Corps" خواهد بود.

**چه اتفاقی می‌افتد اگر از DNS-over-HTTPS رمزگذاری‌شده به جای DNS معمولی استفاده کنید، برای مثال 1.1.1.1؟ (DoH)؟**

اکنون ارائه‌دهنده حتی قادر نخواهد بود که مستقیماً نام دامنه‌ای که به آن متصل شده‌اید را ببیند. یعنی با DoH، ارائه‌دهنده درخواست‌های DNS باز شده را نمی‌بیند، او فقط می‌بیند که شما یک اتصال به آدرس حل‌کننده IP‑DoH/DoT برقرار کرده‌اید (و حجم/زمان ترافیک) + IP نهایی سایت. ارائه‌دهنده دامنه مقصد را نمی‌شناسد، اما اغلب می‌تواند سایت هدف را بر اساس IP، SNI و رفتار ترافیک حدس بزند؛ برای سایت‌های محبوب این ساده‌تر است، برای سایت‌های کمتر شناخته‌شده دشوارتر است، اما کاملاً منتفی نیست. اگر DoH IP نهایی را مخفی کند، جای VPN را برای ما می‌گیرد، اما IP نهایی بازدید شده بدون VPN قابل مخفی کردن نیست. و ارائه‌دهنده سایت‌ها (برای مثال یوتیوب) را دقیقاً بر اساس IP نهایی مسدود می‌کند. بنابراین، در نهایت، برای دسترسی به سایت‌ها از VPN استفاده می‌شود.

**به‌طور خلاصه درباره DNS:**

نوع عادی DNS 1.1.1.1 (متن ساده) نشان می‌دهد: آی‌پی سایت + نام دامنه/SNI + بسته‌های رمزگذاری‌شده HTTPS;

DoH نشان می‌دهد: تنها آی‌پی نهایی از سایت (+تحلیل) + بسته‌های رمزگذاری‌شده HTTPS.

### `۲. وب‌سایت/موتور جست‌وجو`

**سایت آنچه شما در قلمرو آن انجام می‌دهید را می‌بیند و تابع قوانین کشوری است که دفتر مرکزی آن در آن قرار دارد.**

تمام سایت‌های مدرن، ارتباطات و اطلاعاتی که با شما رد و بدل می‌کنند توسط HTTPS رمزگذاری می‌شوند (با HTTP لخت اشتباه گرفته نشود)، بنابراین تمام درخواست‌های شما در سایت‌ها تنها برای شما و خود سایت قابل مشاهده است، اما برای ارائه‌دهنده خیر. ارائه‌دهنده تنها ترافیک رمزگذاری‌شده HTTPS را می‌بیند که برای او بی‌فایده است و نمی‌تواند آن را رمزگشایی کند.

**از نظر موتورهای جستجو، من دو مورد را توصیه می‌کنم. با آن‌ها جستجو کنید بدون اینکه نگران باشید که ناگهان چیزی بپرسید که سانسور پسند نباشد:** 

> *1. موتور جستجوی گوگل (پرطرفدارترین + دارای بیشترین نتایج جستجو در جهان). دفتر مرکزی در ماونتین ویو، کالیفرنیا، ایالات متحده آمریکا.*
>
> *۲. موتور جستجوی Duckduckgo (محبوب + نتایج جستجوی عالی، جایی که می‌توانید منطقه جستجو را انتخاب کنید + شرکت اعلام می‌کند که جستجوهای شما محرمانه باقی می‌مانند). دفتر مرکزی در پائولی، پنسیلوانیا، ایالات متحده آمریکا.*

متأسفانه، نمی‌توانم موتور جستجوی Yandex را توصیه کنم. دفتر مرکزی در مسکو است. تمام درخواست‌های شما ثبت و بر اساس دستور کار فعلی تحلیل می‌شوند. فقط برای جستجوی اطلاعاتی که در روسیه ایندکس شده‌اند، با احتیاط استفاده کنید. برای همه موارد دیگر، گوگل و Duckduckgo کافی خواهند بود.

### `۳. مرورگر`

شاید کسی نمی‌دانست - مرورگر نیز اقدامات شما را می‌بیند. 

**اکنون مرورگرهای عمومی و محبوب در روسیه کدام‌ها هستند؟** 

> الف) مرورگر Yandex. به شدت توصیه نمی‌شود! اگر نصب شده است، آن را حذف کرده و با هر مرورگر دیگری جایگزین کنید! ترافیک را ثبت می‌کند؛
>
> ب) گوگل کروم. در اینجا نیز حریم خصوصی وجود ندارد و ترافیک ثبت می‌شود. اما برای روسیه امن‌تر از Yandex + اکوسیستم خود گوگل است؛ 
>
> ج) موزیلا فایرفاکس. بر اساس سیاست حفظ حریم خصوصی، بهترین بین مرورگرهای محبوب و عمومی است؛ 

این مرورگرهای اصلی سازندگان خود را دارند و این سازندگان شرکت‌های عمومی هستند که داده‌هایی درباره کاربران خود جمع‌آوری می‌کنند و می‌توانند سابقه جستجو/مرور آنها را ببینند (فرقی نمی‌کند چه می‌گویند) + تابع قوانین و مقررات کشورهایی هستند که دفتر مرکزی آن‌ها در آنجا قرار دارد، پس به آن فکر کنید. برای جلوگیری از اینکه مرورگر به یک «افراد میانجی» («man-in-the-middle») تبدیل شود - یک مرورگر محرمانه و متن‌باز نصب کنید، که توسط شرکت‌های عمومی ساخته نشده است، بلکه توسط توسعه‌دهندگان مستقل که کدشان به‌صورت باز (Open-Source) است ساخته شده و هر کسی که آن را بفهمد می‌تواند مرورگر را از لحاظ امنیت بررسی کند، برای مثال، کد منتشر شده در GitHub.

**چه مرورگرهایی را برای استفاده روزانه و مرور اینترنت توصیه می‌کنم؟**

از پایین به بالا: از محبوب‌ترین تا محرمانه‌ترین.

**الف)** `Mozilla Firefox` - اگر یک گزینه محبوب بدون هیچ مشکلی می‌خواهید + افزونه uBlock Origin را برای آن دانلود کنید (ublockorigin.com) تا ردیاب‌ها و تبلیغات را مسدود کند. یک مرورگر مبتنی بر موتور فایرفاکس از شرکت عمومی موزیلا. بر اساس سیاست حفظ حریم خصوصی، بهترین گزینه بین مرورگرهای پرطرفدار است.

https://www.firefox.com/en-US/?utm_campaign=SET_DEFAULT_BROWSER

https://github.com/mozilla-firefox/firefox

**ب)** `Ungoogled Chromium` - مرورگر متن‌باز بر پایه موتور Chromium با حذف تله‌متری گوگل که توسط توسعه‌دهندگان مستقل ساخته شده است. توسط طیف وسیعی از کاربران آزمایش شده است. برای انجام کارهای روزمره مناسب است، اما هر بار که توسعه‌دهندگان به‌روزرسانی منتشر می‌کنند، باید آن را به‌صورت دستی از GitHub دانلود کنید. افزونه uBlock origin را برای آن دانلود کنید (ublockorigin.com) تا ردیاب‌ها و تبلیغات را مسدود کنید. برای کارهای روزمره و حفظ حریم خصوصی، من Ungoogled Chromium را میانه طلایی می‌دانم. Ungoogled Chromium دقیقاً مانند Google Chrome عمل می‌کند، فقط بدون اکوسیستم گوگل.

https://github.com/ungoogled-software/ungoogled-chromium-windows برای Windows

https://github.com/ungoogled-software/ungoogled-chromium-portablelinux برای Linux (نسخه پرتابل)

https://github.com/ungoogled-software/ungoogled-chromium-macos برای MacOS

**V)** `Librewolf (فایرفاکس سفارشی)` - مرورگر متن‌باز بر پایه موتور فایرفاکس با حذف تلِمتری موزیلا فایرفاکس، از توسعه‌دهندگان مستقل. من آن را «مرورگر فایرفاکس محرمانه آماده استفاده» می‌نامم: دانلود و اجرا می‌کنید. توسط جمعیت وسیعی تست شده. راحت. با به‌روزرسانی خودکار (در هنگام نصب، تیک مربوطه را بزنید). uBlock origin به طور پیش‌فرض در آن تعبیه شده است. Librewolf عالی است، اما گاهی به دلیل تنظیمات نیمه‌تهاجمی، برخی سایت‌های استریم ممکن است خراب شوند یا باز نشوند، هرچند این اتفاق خیلی به ندرت رخ می‌دهد.

https://librewolf.net/

https://codeberg.org/librewolf

**G)** `Cromite` - مرورگر متن‌باز بر پایه موتور Chromium با غیرفعال‌سازی تلِمتری، از توسعه‌دهندگان مستقل. توسط طیف گسترده‌ای از کاربران آزمایش شده است. مناسب برای مشاهده روزمره، اما با یک نکته - مسدودسازی بسیار شدید ردیاب‌ها و سایر تلِمتری‌ها. دارای AdBlock داخلی. برخی سایت‌ها ممکن است خراب شوند. این اتفاق برای من در کریومایت بیشتر از مرورگرهای فوق رخ داد. ورود به گوگل به‌سختی امکان‌پذیر بود. اما بررسی امنیتی مرورگر با کریومایت بهترین بود - حتی سخت‌افزار PC هم شناسایی نشد، چه برسد به سایر اثرانگشت‌های دیجیتال، همه چیز «تمیز» بود. و این همه چیز از همان ابتدا آماده بود.

https://github.com/uazo/cromite

این مرورگرها توجه ارائه‌دهنده را جلب نخواهند کرد، زیرا... ارائه‌دهنده فقط موتورهایی را که این مرورگرها بر روی آن‌ها کار می‌کنند می‌بیند، یعنی مشخص است که این کرومیوم است (گوگل کروم، آنگوگلد کرومیوم، کرومایت) یا فایرفاکس (موزیلا فایرفاکس، لیبروولف). تنها شما می‌توانید ببینید چه نوع مرورگری دارید.

### `۴. حل‌کننده DNS`

با DNS عادی (1.1.1.1) قبل از وصل شدن به سایت، ما با حل‌کننده DNS تماس می‌گیریم و آن می‌بیند کجا می‌رویم. هر اپراتور حل‌کننده DNS تمام پرس‌وجوها و پاسخ‌های DNS را می‌بیند (چه دامنه‌هایی را اجازه می‌دهید). از این سوابق می‌توانید بفهمید به کجا می‌خواهید وصل شوید.

چه اتفاقی می‌افتد اگر به جای DNS معمولی (متن ساده)، DNS-over-HTTPS رمزگذاری‌شده (DoH) 1.1.1.1 را تنظیم کنید؟ 

ارائه‌دهنده اینترنت شما دیگر نمی‌تواند نام دامنه/سایتی که به آن متصل شده‌اید را ببیند. ارائه‌دهنده فقط می‌بیند که شما اتصال به آدرس رزولور IP‑DoH/DoT برقرار کرده‌اید (و حجم/زمان ترافیک).

اما مفسر DNS همچنان نام دامنه + IP را می‌بیند، زیرا شما درخواست‌های DNS را از طریق آن ارسال می‌کنید، حتی درخواست‌های رمزگذاری شده، آن‌ها را دریافت و رمزگشایی می‌کند.

### `نتیجه‌گیری`

**برای احساس آزادی و اطمینان در فضای اینترنت، نکات زیر مفید خواهند بود:**

`DNS-OVER-HTTPS (DoH)` 

➕

 `موتور جستجوی صحیح: گوگل یا داک‌داک‌گو` (به جز Yandex) 
 
➕
  
`مرورگرهای امن/مستقل: حداقل Mozilla Firefox و در سطح بالاتر Librewolf، Ungoogled Chromium یا Cromite` (در هیچ صورت مرورگر Yandex)

---


**اطلاعات به مرور زمان به‌روزرسانی خواهد شد.**

</details>


## <img src="https://cdn.jsdelivr.net/gh/igareck/GoldCaviar@refs/heads/main/Files/NYC_Statue_of_Liberty_2.gif" width="100" align="absmiddle"> اشتراک‌های خود را به اشتراک بگذارید! از اینترنت به‌طور آزاد و مسئولانه استفاده کنید!

## 🔖 مجوز

مجوز GPL-3.0. مجوز را می‌توان در فایل [`LICENSE`](LICENSE) یافت.

## <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExM2wwMmJ3bDZvMWV2b2JraXZ4ZWk2Y2I5ODYyZ2M2aG5mMHc5ZW81ZyZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/ME8P6ce7Mn3gnRbird/giphy.gif" width="30"> `حمایت از نویسنده`

**این پروژه غیرتجاری است و بر اساس علاقه شخصی نویسنده ساخته شده است.**

**اگر می‌خواهید حمایت کنید، می‌توانید این کار را به ۲ روش انجام دهید: از طریق `اهدا در Patreon.com` یا `cryptocurrency transfer`.**

این بودجه‌ها برای ادامه فعالیت‌ها و توسعه آن‌ها استفاده خواهند شد.

با تشکر از همه کسانی که اهمیت می‌دهند!

### 1. اهدا به `Patreon.com/igareck`

[![حمایت از من در Patreon](https://img.shields.io/badge/Support_me_on-Patreon-f96854?style=for-the-badge&logo=patreon&logoColor=white)](https://www.patreon.com/igareck/shop)

Patreon فقط در روسیه از طریق VPN کار می‌کند.

از روسیه می‌توانید از طریق موارد زیر پرداخت کنید:

**`کارت‌های بانکی بین‌المللی`**

**`کارت‌های مجازی از صادرکنندگان خارجی`**

**`App Store و Google Play: پرداخت برای Patreon از طریق خریدهای درون‌برنامه‌ای در تلفن همراه شما`**

**`خدمات پرداخت واسطه‌ای (فهرست زیر)`**

فهرست واسطه‌ها برای پرداخت هر اشتراک Patreon، شارژ موجودی App Store / Google Play، یا ارائه خدمات برای صدور کارت‌های بانکی بین‌المللی ویزا/مسترکارت:

<details>
<summary><code><em> برای مشاهده فهرست واسطه‌ها برای پرداخت/انتقال روی فلش کلیک کنید </em></code></summary>

⇩

```diff

Payment for Patreon subscription:
https://pyyplbot.com/kak-oplatit/patreon/
https://oplata.guru/patreon
https://oplatym.ru/patreon
https://sanpay.ru/instrustions/kak-oplatit-podpisku-na-patreon.html
https://getpayall.com/services/patreon

Registration/replenishment of international bank cards Visa/Mastercard:
https://platipomiru.com/
https://wanttopay.net/
https://pyyplbot.com/bank-cards/
https://oplata.guru/zarubezhnaya-bankovskaya-karta
https://getpayall.com/individual

Apple-ID / Google Play balance replenishment:
https://wanttopay.net/
https://oplata.guru/googleplay
https://oplatym.ru/googleplay

```

</details>

### 2. انتقال رمزارز

<details>
<summary><code><em> برای بزرگ کردن فهرست کیف پول‌های رمزارز روی فلش کلیک کنید </em></code></summary>

⇩

هر رمزارزی که برای شما راحت است انتخاب کرده و آدرس آن را کپی کنید. شما باید فقط به کیف پولی که با کوین مطابقت دارد ارسال کنید، در غیر این صورت وجوه از بین خواهد رفت.

| № | سکه | آدرس |
|--|--|--|
| 1 | `Bitcoin (BTC)` | `18vVz4UzFdxCGnCnAzJtXv6ECsh32ff9VT` |
| 2 | `سکه‌ها روی پایگاه داده اتریوم (ETH): اتریوم (ETH)، USDC (ETH)، USDT (Ethereum ERC-20)، شیبا اینو (SHIB)` | `0xfc668016a823f3EE53d2F3009547666A2BdaBd32` |
| 3 | `سکه‌ها روی پایگاه داده ترون (TRX): ترون (TRX)، USDC (TRX)، USDT (TRX)` | `TLnzF6NYgyqBHJMM2qByMXEHLBWNhBWcJ1` |
| 4 | `سکه‌ها در پایگاه داده تون‌کوین (TON): تون‌کوین (TON)، نات‌کوین (NOT)، نبرد همستر (HMSTR)، یو‌اس‌دی‌تی (USDT-TON)` | `EQAGbSuckE93yiACSENJGo8WuRq474Wba1J4yCF1Q59xsL0k` |
| 5 | `Litecoin (LTC)` | `LcHbh84V5PgWk1gTzjGWeef6NQT4MwE9RK` |
| 6 | `Ripple (XRP)` | `rNaKXrfLGsAVvA8JMr9dApMgCNzFmPbvTR` |
| 7 | `Monero (XMR)` | `47uvnonFqbyHMRrZadCAAvL2q9ed476PKdGtbLxXeUj1fs7gtPZ6mx3BeRBd2JM6Wmc16tN7K3ZcDMfds3cE8NaMCgAbD5Q` |
| 8 | `ZCash (ZEC)` | `t1cjEDjtLxatccB6o1pUPxb3pMByCz1L5Ct` |
| 9 | `Dogecoin (DOGE)` | `DRNBruzYDv5vWEz1ndGDjywqugVhd2Zmbm` |
| 10 | `Solana (SOL)` | `Hxm9MjxfD1LNKaWuiFFLzBDTR5CnJSty7gRnkTfubiWj` |
| 11 | `Stellar (XLM)` | `GDRN4K4VDDGNFIWJ3BAN7KL7576764RN44TBHTXYJIXMLK7RNP4UTSJ6` |
| 12 | `Cardano (ADA)` | `addr1qxpw4m02auvmrfee3suz98tvj82cm4mpfllvyda8fz004j40dpemdcuzntj5ykxwv2x6azyp982stfxegm9zvl9kf74s309qhu` |
| 13 | `سکه NEAR (NEAR)` | `d9cba0ec6233589267f43b91d8c156efb7fcd0a0177d7e8a34f7b791a61e7e35` |

</details>

<details>
<summary><code><em> کجا ارز دیجیتال می‌خرید؟ </em></code></summary>

⇩

```diff

BestChange:
https://www.bestchange.com
https://www.bestchange.net
https://www.bestchange.ru
New version of the BestChange website:
https://bestchange.biz/ru

```

</details>


## <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3ZmJ4anB6YjR3aWJpaTRvYzUzejY1dmwzN2c2M3c2NnV0MXUwM3RrcyZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/acN91ftm1tJX23OOBx/giphy.gif" width="60"> ایمیل تماس: igareck@proton.me

## 👀 تعداد بازدیدکنندگان
<img src="https://komarev.com/ghpvc/?username=igareck&label=Visitors&color=0e75b6&style=flat" alt="Visitor Count" /> <img src="https://visitor-badge.laobi.icu/badge?page_id=igareck.visitor-badge&left_color=black&right_color=green&left_text=Cyber+Hits" alt="Cyber Hits"/>  
</div>

## <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExa2RkeXZzdDl1Y3g4dW1xcjFxc2xsMHVsZ2RiY243OHJodjd0cHQ1NSZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/qXp82ZL3eZbbTUrLyy/giphy.gif" width="30"> <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExa2RkeXZzdDl1Y3g4dW1xcjFxc2xsMHVsZ2RiY243OHJodjd0cHQ1NSZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/qXp82ZL3eZbbTUrLyy/giphy.gif" width="30"> <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExa2RkeXZzdDl1Y3g4dW1xcjFxc2xsMHVsZ2RiY243OHJodjd0cHQ1NSZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/qXp82ZL3eZbbTUrLyy/giphy.gif" width="30">

[![تاریخچه ستاره](https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/star-tracker-data/charts/star-history.svg)](https://github.com/igareck/vpn-configs-for-russia)

## <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3Z25rOXRoeW1xODR1dWh2b3UycTd6YnB0Y2hlMTZtaDluZW1uNnl4ZyZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/CeYEKonyFQyzWhxmvd/giphy.gif" width="40"> سلب مسئولیت

> *نویسنده مالک/توسعه‌دهنده/ارائه‌دهنده کانفیگ‌ها VPN فهرست‌شده نیست. این یک بررسی مستقل اطلاعات و نتایج آزمایش است.*
>
> *این مطلب تبلیغ برای VPN نیست. تمام مطالب صرفاً برای اهداف اطلاعاتی و تنها برای شهروندان کشورهایی که این اطلاعات در آنجا قانونی است، حداقل برای مقاصد علمی، ارائه شده است. اگر نمی‌توانید این را بخوانید، بلافاصله این صفحه را ببندید!* 
>
> *نویسنده هیچ قصدی ندارد، تشویق نمی‌کند، و استفاده از VPN یا هر برنامه دیگری را تحت هیچ شرایطی تأیید نمی‌کند.*
>
> *هرگونه استفاده از این کانفیگ‌های VPN بر عهده کاربر است.*
>
> *سلب مسئولیت: نویسنده مسئول اقدامات اشخاص ثالث نیست و استفاده غیرقانونی از VPN را تشویق نمی‌کند.*
>
> *نویسنده مسئول صحت، کامل بودن و قابل اعتماد بودن اطلاعات منتشر شده نیست. همه تصادفات تصادفی هستند. تمام اطلاعات به صورت «همان‌طور که هست» ارائه می‌شوند و ممکن است دقیق نباشند.*
>
> *استفاده مطابق با قوانین محلی.* 
>
> *VPN را تنها برای اهداف قانونی استفاده کنید: به‌ویژه برای اطمینان از امنیت آنلاین و دسترسی امن از راه دور، و تحت هیچ شرایطی از این فناوری برای دور زدن محدودیت‌ها استفاده نکنید.*
>
> *این پروژه غیرتجاری و رایگان است، تمام اطلاعات ارائه شده «پرداخت» به صورت تصادفی در جایی از اینترنت پیدا شده، «دقیقا به همان صورت» کپی شده تا یک نمونه احتمالی را نشان دهد و به نویسنده تعلق ندارد.*
>
> *توصیه - این صفحه را ببندید، تمام VPNها را از رایانه خود حذف کنید، MAX و Yandex را روی همه دستگاه‌ها نصب کنید تا حتی در پارکینگ هم بتوانند «ردگیری» کنند، و فقط از منابع اینترنتی استفاده کنید که توسط ارائه‌دهنده اینترنت شما مجاز هستند، متوجه منظور هستید.*
