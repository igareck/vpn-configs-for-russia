<div align="center">
  
![maxresdefault](https://raw.githubusercontent.com/igareck/GoldCaviar/refs/heads/main/Files/vpn-configs-for-russia-4.svg)

</div>

# <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNTljeGk4d3lzZnU3Mm1peDBienFpbmEyb3JmaDB5N21tMW9oczIwdyZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/8p1WPEOeDWFCksfe18/giphy.gif" width="45">  Бесплатные VPN-конфигурации, работающие в РФ 

[![Stars](https://img.shields.io/github/stars/igareck/vpn-configs-for-russia?style=flat)](https://github.com/igareck/vpn-configs-for-russia/stargazers)
<img src="https://komarev.com/ghpvc/?username=igareck&label=Visitors&color=0e75b6&style=flat" alt="Visitor Count" /> 
[![Issues](https://img.shields.io/github/issues/igareck/vpn-configs-for-russia?style=flat&color=0e75b6)](https://github.com/igareck/vpn-configs-for-russia/issues)
[![last commit][1]][1]
![Open Source Love](https://badges.frapsoft.com/os/v2/open-source.png?v=103)
[![Email](https://img.shields.io/badge/Email-igareck%40proton.me-0e75b6?logo=gmail&logoColor=white)](mailto:igareck@proton.me)


[1]: https://custom-icon-badges.demolab.com/github/last-commit/igareck/vpn-configs-for-russia?logo=history&logoColor=white&color=0e75b6&style=flat

**🌐 Язык: [Русский](README.md) | 🌐 Language: [English](README-EN-US.md) | 🌐 语言: [中文](README-ZH-CN.md) | 🌐 زبان: [فارسی](README-FA-IR.md)**

<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExa2RkeXZzdDl1Y3g4dW1xcjFxc2xsMHVsZ2RiY243OHJodjd0cHQ1NSZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/qXp82ZL3eZbbTUrLyy/giphy.gif" width="20"> Коллекция публичных и бесплатных, автообновляемых и автопроверяемых VPN-конфигураций, протестированных для работы на территории Российской Федерации  (`VLESS` / `VMess` / `Shadowsocks` /`Hysteria2` / `Tuic`/ `Trojan` и другие).

Для обхода блокировок Роскомнадзора (РКН).

Коллекция отфильтрована по категориям на черные и белые CIDR и SNI списки.

Каждая конфигурация — это TXT-подписка, которую можно импортировать в любой необходимый вам клиент (`v2rayN`, `Streisand`, `Throne`, `Karing`, `NekoBox` и другие).

Раз в 2 часа перед опубликованием конфиги проходят автоматические тесты на работоспособность на сервере в России, медленные и нерабочие отсеиваются. 

Проводятся реальные тесты на доступность, задержку, скорость, а не просто обычная автосборка и дедупликация. С 13 ноября по 28 декабря делал все вручную - 28 декабря доделал скрипт, который автоматизировал и ускорил процесс проверки, поддерживая такой же качественный "ручной" результат.

Обычные VPN (OpenVPN, WireGuard и прочее) не работают уже давно, и не влияет - платная у вас подписка или нет. 

Поэтому важно использовать конфигурации, проверенные для работы именно в России, чтобы всегда оставаться онлайн.

Также важно частое обновление публичных конфигов, поскольку они имеют свойство как быстро появляться - так и быстро переставать работать. Поэтому прикрутил автообновление с автопроверкой/автотестами, чтобы у каждого пользователя из России в любое время был самый свежий список с качественными VPN-конфигурациями без лишнего мусора.


---

## TOPIC №1
### Внимание тем пользователям, у кого НЕ белые списки (кабельный и мобильный интернет без ограничений), и вам дома или на работе, на вашем ПК/ноутбуке нужно стабильное бесплатное подключение к сети, стабильно работающий обход - используйте связку "Tor Bridges" + "Tor-клиент OnionHop V2" (подробности в разделе "В чем разница между черными и белыми списками" - "TOR BRIDGES").

---

## TOPIC №2

### ЭТО ВАЖНАЯ НОВОСТЬ ДЛЯ ВСЕХ, КТО ПОЛЬЗУЕТСЯ VPN НА СМАРТФОНЕ

На Habr вышел очень важный разбор критической уязвимости **мобильных** клиентов на базе xray/sing-box. Суть проблемы в том, что клиент поднимает локальный SOCKS5-прокси без авторизации, а вредоносное приложение  (то есть любое RU приложение: MAX, Yandex, Wildberries, Ozon, Gosuslugi, Rzd, любой банковский софт (Sber, T-Bank), Kaspersky и прочие крупные российские IT-компании) на **том же устройстве** может подключиться к нему в обход `VpnService`, определить ваш выходной IP и тем самым сдать ваш прокси/сервер. Автор отдельно пишет, что `private space`, `Shelter`, `Island` и per-app split tunneling здесь не спасают.

Статья: https://habr.com/ru/articles/1020080/

Зеркало: https://web.archive.org/web/https://habr.com/ru/articles/1020080/

**Состояние на 9 апреля 2026 года:**

**Какие клиенты решили проблему, указанную автором статьи** @runetfreedom **на Хабре (проверено):** 

### ✦ Karing, Throne

Детали:

1. **Karing** вижу добавлена ручная авторизация, только что проверил на ПК, о чем упоминал автор в статье на Хабре. Это отлично. Для Андроида выпущен фикс в Github, но пока что только на AppStore нет обновлений (последнее - 11 марта), возможно еще не успели, т.к. apk только выкатили 7 часов назад.

2. **Throne** - 30 минут назад выкатили обнову - вижу "Add inbound authorization support". Проверил, в настройках есть Inbound Authorization Username/Password. Отлично!

3. Что сделано у **Happ**? Убран HandlerService в Android? Это не убирает проблему как таковую, это лишь ставит его в положение "он теперь на уровне как и все, а не хуже всех". Убран баг, который ставил его в положение "это худший клиент". Проблема авторизации не решена ни на одной из платформ, в changelogах нет нигде информации, проверил на ПК - в настройках нет ничего.

4. **v2raytun**, ни в changelog, ни в настройках самого приложения не увидел как они пофиксили проблему, указанную автором, проблема авторизации не решена.

5. **v2rayN** пока все по нулям, проблема авторизации не решена.

**Что из этого следует на практике:**

✦ больше нельзя считать выходной IP вашего прокси "защищенным по умолчанию", если на устройстве есть недоверенный софт (то есть любое RU приложение: MAX, Yandex, Wildberries, Ozon, Gosuslugi, Rzd, любой банковский софт (Sber, T-Bank), Kaspersky и прочие крупные российские IT-компании);

✦ private space и split tunneling не дают той защиты, на которую многие рассчитывали;

✦ если у вас на смартфоне вперемешку стоит VPN-клиент и куча российского софта - это плохая модель безопасности.

**ЧТО ДЕЛАТЬ ПРЯМО СЕЙЧАС**

**План-минимум:**

✦ следить за обновлениями клиентов и ставить их сразу;

✦ использовать раздельную маршрутизацию `geoip:ru -> direct`, `other -> proxy`;

✦ вариант для Android: полноценный второй профиль и переключение между ними. 

Официальная инструкция Google: https://support.google.com/android/answer/2865483?hl=ru

`Основной профиль` — VPN/Tor, браузер, GitHub, Telegram, почта, пароли;

`Второй RU-профиль` — банки, Госуслуги, Яндекс, Ozon, WB, РЖД и прочий российский софт.

Но это не гарантированная защита от localhost-утечки. Это наилучшая сегрегация данных по сравнению с изоляцией приложения в одном аккаунте, но все равно не изолируется loopback/localhost между пользователями. Неактивный пользователь может продолжать работать в фоне, пока активен другой. В рамках одного устройства - это пока наилучшая защита.

✦ нужно понимать, что это не "полная защита", а только снижение "ущерба".

**План-максимум:**

✦ отдельное устройство под российский софт;

✦ отдельное устройство под VPN, Tor и чувствительные задачи.

**Главный вывод:**
Если вы пользуетесь публичными конфигами или своим сервером, исходите из того, что при плохом раскладе ваш выходной IP смогут узнать. Значит, инфраструктуру и привычки надо строить строже: обновления, чистое/отдельное устройство, раздельная маршрутизация, разделение входного и выходного IP (для владельцев серверов), где это возможно.

---

## ОБЯЗАТЕЛЬНО К ПРОЧТЕНИЮ! 

**Если вы хотите успешно запустить конфиги, скачать правильную подписку и понять что к чему - внимательно читайте следующие разделы!** 

**Ниже вы узнаете:** 

**1.** `В чем разница между черными и белыми списками;`

**2.** `Какие есть подписки и чем они отличаются друг от друга.`

`Обратите внимание, что в Readme присутствуют альтернативные ссылки (зеркала), которые работают в режиме БС, а так же при заблокированном GitHub;`

**3.** `Какие приложения скачивать, где скачивать и как пользоваться;`

**4.** `Другая полезная информация о том, как работает интернет "простым языком", что видит провайдер, когда вы в сети, какие браузеры лучше, что такое DNS-DoH и прочее;`

**Дополнительно читайте раздел "Issues" сверху репозитория, задавайте вопросы, комментируйте, обменивайтесь опытом.**

**Конфиги, которые тут выкладываются - выходят после реальных проверок, то есть большинство будет живыми на момент публикации!**

**Подписки обновляются каждые 1-2 часа, чтобы не потерять своей актуальности!**

---

## <img src="https://raw.githubusercontent.com/igareck/GoldCaviar/refs/heads/main/Files/Download-VPN-configs-banner-RU-RU.svg" width="600">

  *Названия подписок (подсвечены синим) кликабельны и содержат ссылку на RAW формат подписки!*

  

  *Включите автообновление у себя в VPN-клиенте!*

---

<details>

<summary><h3>🧾 ЧЕРНЫЙ СПИСОК ⚫</h3></summary>

---

### **VLESS для телефона (максимум 150 конфигов в подписке):** 

### [BLACK_VLESS_RUS_mobile.txt](https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/main/BLACK_VLESS_RUS_mobile.txt)

<details>
<summary> QR-код </summary>

  ![BLACK_VLESS_RUS_mobile_QR.png](https://github.com/igareck/vpn-configs-for-russia/blob/main/QR-codes/BLACK_VLESS_RUS_mobile_QR.png)

</details>

`Сжатая, легкая телефонная подписка VLESS для Черных Списков. Содержит 150 самых быстрых конфигов из полной VLESS-подписки.`

---

### **VLESS полная (все конфиги):** 

### [BLACK_VLESS_RUS.txt](https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/main/BLACK_VLESS_RUS.txt)

  <details>
<summary> QR-код </summary>

  ![BLACK_VLESS_RUS-QR](https://github.com/igareck/vpn-configs-for-russia/blob/main/QR-codes/BLACK_VLESS_RUS-QR.png)

</details>

  `Полная подписка VLESS для Черных Списков.`

  *Внимание! Осторожнее с загрузкой этой полной подписки на телефон! Может содержать более 1000-2000 конфигураций! Телефоны очень тяжело "переваривают" такое количество! Рекомендовано только для компьютера!*

---

### **SHADOWSOCKS+ALL:** 

### [BLACK_SS+All_RUS.txt](https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/main/BLACK_SS+All_RUS.txt)

  <details>
<summary> QR-код </summary>

  ![BLACK_SS+All_RUS-QR](https://github.com/igareck/vpn-configs-for-russia/blob/main/QR-codes/BLACK_SS+All_RUS-QR.png)

</details>

  `Подписка ShadowSocks, Hysteria2, Vmess, Trojan для Черных Списков.`

</details>

*Подписки, обходящие Черные Списки РКН.*

---
---

<details>

 <summary><h3>🧾 TOR BRIDGES 🧅</h3></summary>

### TOR BRIDGES ТОП-100: 

### [TOR_BRIDGES_TOP100.txt](https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/main/TOR-BRIDGES/TOR_BRIDGES_TOP100.txt)

<details>
<summary> QR-код </summary>



</details>

 `Списки мостов для выхода в сеть Tor. Лучшие 100 мостов.`

---

### TOR BRIDGES ПОЛНАЯ: 

### [TOR_BRIDGES_ALL.txt](https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/main/TOR-BRIDGES/TOR_BRIDGES_ALL.txt)

<details>
<summary> QR-код </summary>



</details>

 `Списки мостов для выхода в сеть Tor. Полный список.`

---

### TOR BRIDGES VANILLA: 

### [TOR_BRIDGES_VANILLA.txt](https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/main/TOR-BRIDGES/TOR_BRIDGES_VANILLA.txt)

<details>
<summary> QR-код </summary>



</details>

 `Списки мостов для выхода в сеть Tor. Тип VANILLA.`

---

### TOR BRIDGES OBFS4: 

### [TOR_BRIDGES_OBFS4.txt](https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/main/TOR-BRIDGES/TOR_BRIDGES_OBFS4.txt)

<details>
<summary> QR-код </summary>



</details>

 `Списки мостов для выхода в сеть Tor. Тип OBFS4.`

---

### TOR BRIDGES WEBTUNNEL: 

### [TOR_BRIDGES_WEBTUNNEL.txt](https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/main/TOR-BRIDGES/TOR_BRIDGES_WEBTUNNEL.txt)

<details>
<summary> QR-код </summary>



</details>

 `Списки мостов для выхода в сеть Tor. Тип WEBTUNNEL.`

</details>

*Списки мостов для выхода в сеть Tor. Аналог Черных Списков.*

---
---

<details>

<summary><h3>🧾 БЕЛЫЙ СПИСОК ⚪</h3></summary>

---

### CIDR-ПОДПИСКА для телефона №1 (лучшие первые 150 конфигов в подписке) ⚪: 

### [Vless-Reality-White-Lists-Rus-Mobile.txt](https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/main/Vless-Reality-White-Lists-Rus-Mobile.txt)

<details>
<summary> QR-код </summary>

  ![WHITE_VLESS_MOBILE_RUS-QR](https://github.com/igareck/vpn-configs-for-russia/blob/main/QR-codes/Vless-Reality-White-Lists-Rus-Mobile-QR.png)

</details>

`Сжатая, легкая телефонная CIDR-подписка для Белых Списков №1. Содержит первые лучшие 150 конфигов из полной CIDR-подписки. Обходит CIDR-блокировки по IP. Протокол VLESS.`

---

### CIDR-ПОДПИСКА для телефона №2 (лучшие вторые 150 конфигов в подписке) ⚪: 

### [Vless-Reality-White-Lists-Rus-Mobile-2.txt](https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/main/Vless-Reality-White-Lists-Rus-Mobile-2.txt)

<details>
<summary> QR-код </summary>

  ![WHITE_VLESS_MOBILE_RUS-QR-2](https://github.com/igareck/vpn-configs-for-russia/blob/main/QR-codes/Vless-Reality-White-Lists-Rus-Mobile-2-QR.png)

</details>

`Сжатая, легкая телефонная CIDR-подписка для Белых Списков №2. Содержит вторые лучшие 150 конфигов из полной CIDR-подписки. 
Пользуйтесь этой дополнительной телефонной подпиской №2, если вдруг не хватает телефонной подписки №1 или если она перегружена.
Обходит CIDR-блокировки по IP. Протокол VLESS.`

---

### CIDR-ПОДПИСКА полная (все конфиги) ⚪: 

### [WHITE-CIDR-RU-all.txt](https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/main/WHITE-CIDR-RU-all.txt)

<details>
<summary> QR-код </summary>

  ![WHITE-CIDR-RU-all-QR](https://github.com/igareck/vpn-configs-for-russia/blob/main/QR-codes/WHITE-CIDR-RU-all-QR.png)

</details>

`Полная CIDR-подписка для Белых Списков. Содержит все известные белые подсети от разных хостеров. Обходит CIDR-блокировки по IP. Протокол VLESS.`

*Внимание! Осторожнее с загрузкой этой полной подписки на телефон! Может содержать более 1000-2000 конфигураций! Телефоны очень тяжело "переваривают" такое количество! Рекомендовано только для компьютера!*

---

### CIDR-ПОДПИСКА только с хостерами: VK, YANDEX, CDNVIDEO, Beeline ⚪:

### [WHITE-CIDR-RU-checked.txt](https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/main/WHITE-CIDR-RU-checked.txt)

<details>
<summary> QR-код </summary>

  ![WHITE-CIDR-RU-checked-QR](https://github.com/igareck/vpn-configs-for-russia/blob/main/QR-codes/WHITE-CIDR-RU-checked-QR.png)

</details>

`Отфильтрованная версия полной CIDR-подписки по конкретным хостерам. Меньше полной версии. В данной сокращенной подписке белые подсети только от этих Российских хостеров: VK, YANDEX, CDNVIDEO и Beeline, а в полной - все хостеры! Обходит CIDR-блокировки по IP. Протокол VLESS.`

*Внимание! Осторожнее с загрузкой этой подписки на телефон! Может содержать более 1000-2000 конфигураций! Телефоны очень тяжело "переваривают" такое количество! Рекомендовано только для компьютера!*

---

### SNI-ПОДПИСКА ⚪: 

### [WHITE-SNI-RU-all.txt](https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/main/WHITE-SNI-RU-all.txt)

<details>
<summary> QR-код </summary>

  ![WHITE-SNI-RU-all-QR](https://github.com/igareck/vpn-configs-for-russia/blob/main/QR-codes/WHITE-SNI-RU-all-QR.png)

</details>

`Обходит только SNI-блокировки по фейковому доменному имени SNI. CIDR-блокировки не обходит. Протокол VLESS.`

</details>

*Подписки, обходящие Белые Списки РКН.*

---
---

<details>

<summary><h3>🪞 ЗЕРКАЛА 🪞</h3></summary>

**Есть много вариантов с зеркалами для альтернативного доступа к подпискам:**

**1. Яндекс Переводчик:** поможет в режиме Белых Списков, т.к. подсети Яндекса самые стабильные и рабочие при БС. 

Способ работает, только если вручную доставать конфиги из браузера, через клиент работать не будет! 

**2. JSDelivr (через CDN):** это обходной путь через крупную сеть доставки контента: https://cdn.jsdelivr.net. 

**3. Statically (через CDN):** это обходной путь через крупную сеть доставки контента: https://cdn.statically.io.  

**4. Githack (через Cloudflare):** https://rawcdn.githack.com 

**5. Githack (напрямую):** https://raw.githack.com

Пункты 2,3,4,5 помогут только в случае Черных Списков. Актуально, если Роскомнадзор заблокирует GitHub.

---

**СПОСОБ №1: ЯНДЕКС.**

**Яндекс Переводчик как "прокси" во время режима Белых Списков.**

Если вы находитесь в режиме Белых Списков или у вас заблокирован GitHub - есть вариант обновить любую подписку через Яндекс Переводчик. 
До недавнего времени был вариант обновлять автоматически через клиент, но "спасибо" разрабам Яндекса, что пофиксили способ в угоду РКН и теперь он недоступен, так как сейчас при автоматическом обновлении всегда обнуляются параметры "sni/security/type/pbk/sid/fp/mode", раньше все работало.

**Варианты доставать подписку через Переводчик остались, но теперь только в ручном режиме методом Copy-Past из браузера (только в таком случае конфиги не бьются)**:

1. **На сайте** "https://translate.yandex.ru/translate" можно вставить нужную ссылку в поле "Введите адрес сайта";

2. **Вставить ссылку** на подписку  **вместо надписи "ПОДПИСКА"** вот здесь:

https://translate.yandex.ru/translate?url=ПОДПИСКА&lang=de-de и потом вставить эту ссылку в браузер, а не клиент!

3. **Воспользоваться готовыми ссылками ниже**, которые вы можете сохранить у себя в заметках на телефоне или ПК и пользоваться при необходимости.

За способ отдельное спасибо пользователям @AmiFox и @HenonBank.

---

**СПОСОБ №2 и №3: JSDelivr CDN и Staticaly CDN.**

Почему JSDelivr CDN и Staticaly CDN будут работать?

Если их заблокируют целиком: перестанут нормально открываться тысячи российских ресурсов (интернет-магазины, форумы, государственные порталы), у которых элементы сайта подгружаются через эти CDN.

JSDelivr - это один из самых стабильных способов достать файл с GitHub в РФ без VPN. 

Staticaly CDN - как отличная альтернатива.

Поможет только при Черных Списках.

---

### Ниже - готовые ссылки на подписки через зеркала. 

### Сохраните себе их на устройстве, на случай блокировки GitHub или режима Белых Списков.

Ссылки Яндекс переводчика работают корректно, только если вы их запускаете в браузере и вручную копируете конфиги оттуда к себе в клиент! Добавление ссылки Яндекса в клиент для автообновления сделает ваши конфиги битыми и нерабочими!

#### Черные Списки VLESS ТОП-150: 

https://translate.yandex.ru/translate?url=https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/main/BLACK_VLESS_RUS_mobile.txt&lang=de-de

https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@main/BLACK_VLESS_RUS_mobile.txt

https://cdn.statically.io/gh/igareck/vpn-configs-for-russia@main/BLACK_VLESS_RUS_mobile.txt

https://rawcdn.githack.com/igareck/vpn-configs-for-russia/main/BLACK_VLESS_RUS_mobile.txt

https://raw.githack.com/igareck/vpn-configs-for-russia/main/BLACK_VLESS_RUS_mobile.txt

#### Черные Списки VLESS Полная: 

https://translate.yandex.ru/translate?url=https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/main/BLACK_VLESS_RUS.txt&lang=de-de

https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@main/BLACK_VLESS_RUS.txt

https://cdn.statically.io/gh/igareck/vpn-configs-for-russia@main/BLACK_VLESS_RUS.txt

https://rawcdn.githack.com/igareck/vpn-configs-for-russia/main/BLACK_VLESS_RUS.txt

https://raw.githack.com/igareck/vpn-configs-for-russia/main/BLACK_VLESS_RUS.txt

#### Черные Списки SHADOWSOCKS+ALL: 

https://translate.yandex.ru/translate?url=https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/main/BLACK_SS+All_RUS.txt&lang=de-de

https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@main/BLACK_SS+All_RUS.txt

https://cdn.statically.io/gh/igareck/vpn-configs-for-russia@main/BLACK_SS+All_RUS.txt

https://rawcdn.githack.com/igareck/vpn-configs-for-russia/main/BLACK_SS+All_RUS.txt

https://raw.githack.com/igareck/vpn-configs-for-russia/main/BLACK_SS+All_RUS.txt

#### TOR BRIDGES ТОП-100:

https://translate.yandex.ru/translate?url=https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/main/TOR-BRIDGES/TOR_BRIDGES_TOP100.txt&lang=de-de

https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@main/TOR-BRIDGES/TOR_BRIDGES_TOP100.txt

https://cdn.statically.io/gh/igareck/vpn-configs-for-russia@main/TOR-BRIDGES/TOR_BRIDGES_TOP100.txt

https://rawcdn.githack.com/igareck/vpn-configs-for-russia/main/TOR-BRIDGES/TOR_BRIDGES_TOP100.txt

https://raw.githack.com/igareck/vpn-configs-for-russia/main/TOR-BRIDGES/TOR_BRIDGES_TOP100.txt

#### TOR BRIDGES ПОЛНАЯ: 

https://translate.yandex.ru/translate?url=https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/main/TOR-BRIDGES/TOR_BRIDGES_ALL.txt&lang=de-de

https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@main/TOR-BRIDGES/TOR_BRIDGES_ALL.txt

https://cdn.statically.io/gh/igareck/vpn-configs-for-russia@main/TOR-BRIDGES/TOR_BRIDGES_ALL.txt

https://rawcdn.githack.com/igareck/vpn-configs-for-russia/main/TOR-BRIDGES/TOR_BRIDGES_ALL.txt

https://raw.githack.com/igareck/vpn-configs-for-russia/main/TOR-BRIDGES/TOR_BRIDGES_ALL.txt

#### TOR BRIDGES VANILLA: 

https://translate.yandex.ru/translate?url=https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/main/TOR-BRIDGES/TOR_BRIDGES_VANILLA.txt&lang=de-de

https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@main/TOR-BRIDGES/TOR_BRIDGES_VANILLA.txt

https://cdn.statically.io/gh/igareck/vpn-configs-for-russia@main/TOR-BRIDGES/TOR_BRIDGES_VANILLA.txt

https://rawcdn.githack.com/igareck/vpn-configs-for-russia/main/TOR-BRIDGES/TOR_BRIDGES_VANILLA.txt

https://raw.githack.com/igareck/vpn-configs-for-russia/main/TOR-BRIDGES/TOR_BRIDGES_VANILLA.txt

#### TOR BRIDGES OBFS4: 

https://translate.yandex.ru/translate?url=https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/main/TOR-BRIDGES/TOR_BRIDGES_OBFS4.txt&lang=de-de

https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@main/TOR-BRIDGES/TOR_BRIDGES_OBFS4.txt

https://cdn.statically.io/gh/igareck/vpn-configs-for-russia@main/TOR-BRIDGES/TOR_BRIDGES_OBFS4.txt

https://rawcdn.githack.com/igareck/vpn-configs-for-russia/main/TOR-BRIDGES/TOR_BRIDGES_OBFS4.txt

https://raw.githack.com/igareck/vpn-configs-for-russia/main/TOR-BRIDGES/TOR_BRIDGES_OBFS4.txt

#### TOR BRIDGES WEBTUNNEL: 

https://translate.yandex.ru/translate?url=https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/main/TOR-BRIDGES/TOR_BRIDGES_WEBTUNNEL.txt&lang=de-de

https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@main/TOR-BRIDGES/TOR_BRIDGES_WEBTUNNEL.txt

https://cdn.statically.io/gh/igareck/vpn-configs-for-russia@main/TOR-BRIDGES/TOR_BRIDGES_WEBTUNNEL.txt

https://rawcdn.githack.com/igareck/vpn-configs-for-russia/main/TOR-BRIDGES/TOR_BRIDGES_WEBTUNNEL.txt

https://raw.githack.com/igareck/vpn-configs-for-russia/main/TOR-BRIDGES/TOR_BRIDGES_WEBTUNNEL.txt

#### Белые Списки CIDR ТОП 150 №1: 

https://translate.yandex.ru/translate?url=https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/main/Vless-Reality-White-Lists-Rus-Mobile.txt&lang=de-de

https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@main/Vless-Reality-White-Lists-Rus-Mobile.txt

https://cdn.statically.io/gh/igareck/vpn-configs-for-russia@main/Vless-Reality-White-Lists-Rus-Mobile.txt

https://rawcdn.githack.com/igareck/vpn-configs-for-russia/main/Vless-Reality-White-Lists-Rus-Mobile.txt

https://raw.githack.com/igareck/vpn-configs-for-russia/main/Vless-Reality-White-Lists-Rus-Mobile.txt

#### Белые Списки CIDR ТОП 150 №2: 

https://translate.yandex.ru/translate?url=https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/main/Vless-Reality-White-Lists-Rus-Mobile-2.txt&lang=de-de

https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@main/Vless-Reality-White-Lists-Rus-Mobile-2.txt

https://cdn.statically.io/gh/igareck/vpn-configs-for-russia@main/Vless-Reality-White-Lists-Rus-Mobile-2.txt

https://rawcdn.githack.com/igareck/vpn-configs-for-russia/main/Vless-Reality-White-Lists-Rus-Mobile-2.txt

https://raw.githack.com/igareck/vpn-configs-for-russia/main/Vless-Reality-White-Lists-Rus-Mobile-2.txt

#### Белые Списки CIDR полная: 

https://translate.yandex.ru/translate?url=https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/main/WHITE-CIDR-RU-all.txt&lang=de-de

https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@main/WHITE-CIDR-RU-all.txt

https://cdn.statically.io/gh/igareck/vpn-configs-for-russia@main/WHITE-CIDR-RU-all.txt

https://rawcdn.githack.com/igareck/vpn-configs-for-russia/main/WHITE-CIDR-RU-all.txt

https://raw.githack.com/igareck/vpn-configs-for-russia/main/WHITE-CIDR-RU-all.txt

#### Белые Списки CIDR только с хостерами: VK, YANDEX, CDNVIDEO, Beeline: 

https://translate.yandex.ru/translate?url=https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/main/WHITE-CIDR-RU-checked.txt&lang=de-de

https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@main/WHITE-CIDR-RU-checked.txt

https://cdn.statically.io/gh/igareck/vpn-configs-for-russia@main/WHITE-CIDR-RU-checked.txt

https://rawcdn.githack.com/igareck/vpn-configs-for-russia/main/WHITE-CIDR-RU-checked.txt

https://raw.githack.com/igareck/vpn-configs-for-russia/main/WHITE-CIDR-RU-checked.txt

#### Белые Списки SNI: 

https://translate.yandex.ru/translate?url=https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/main/WHITE-SNI-RU-all.txt&lang=de-de

https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@main/WHITE-SNI-RU-all.txt

https://cdn.statically.io/gh/igareck/vpn-configs-for-russia@main/WHITE-SNI-RU-all.txt

https://rawcdn.githack.com/igareck/vpn-configs-for-russia/main/WHITE-SNI-RU-all.txt

https://raw.githack.com/igareck/vpn-configs-for-russia/main/WHITE-SNI-RU-all.txt

</details>

*Альтернативные ссылки для доступа к подпискам в режиме белых списков или в случае блокировки GitHub.*

---

## <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3bjF5NnEyM21vMjJhd2UxdWphYnQxZGh6bjc1bjBzMG44eDB0Ym03eCZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/dyX9ixfxMpOUGawfdK/giphy.gif" width="50"> В чем разница между черными и белыми списками и какую подписку выбрать


`⬇   ПОРЯДОК ДЕЙСТВИЙ   ⬇`

`В начале проверим - работает ли интернет вообще: откроем Yandex.ru, Госуслуги, ВК, Rutube.ru, Сбербанк, Mail.ru, Ozon. Если ничего из этого не открывается - у вас не работает интернет в принципе (нет никакого соединения) и никакие конфиги тут не помогут! В этом случае проверьте подключение у себя на устройстве!"`

`Если вдруг "не грузит ни в какую", то часто помогает сброс подключения к сети (перезагрузка): включаете "Авиарежим" на 10-15 секунд, потом выключаете, пробуете подключение снова - профит!`

`Уточню, что при полном блэкауте мобильного интернета (полноценное отключение/ограничение даже сайтов из "белого списка") не поможет никакая перезагрузка сети - придется либо ждать, когда заработают хотя бы сайты из "белого списка", либо альтернативно искать проводной интернет или публичный Wifi.`

### **1)** **Выбираем черное или белое**:  <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3Y3Q4NW94NXo0ZXQwajl1cDRzdHg3ZXFzbWc4aGtzeDA0cGRtNTl2ZSZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/35LH6GkOzEXuw/giphy.gif" width="80">  

| | ЧЕРНЫЕ СПИСКИ / TOR BRIDGES (стандартный интернет) | БЕЛЫЕ СПИСКИ (максимально ограниченный) |
|--|--|--|
| **Кратко** | Черные списки - это когда "разрешено все, что не запрещено" | Белые списки - это когда "запрещено все, что не разрешено" |
| **Какой тип интернета?** | Любой кабельный + мобильный без жестких ограничений | Мобильный с самыми жесткими ограничениями |
| **Что работает?** | Интернет работает как обычно: открывается Google, App Store, Telegram или любой обычный иностранный сайт/сервис, который в России не заблокирован официально | У вас мобильный интернет и ничего не работает кроме Yandex.ru, Госуслуг, ВК, Rutube, Сбербанка, Mail.ru, Ozon и других утвержденных РКН сайтов. Ни Google.com, ни GMail, ни App Store, ни Telegram, ни один иностранный сайт не открывается. Зайти получается только на те Российские сайты, которые одобрил регулятор, используя свои "белые" списки. То есть, например, РКН одобрил только Яндекс и Озон - вы сможете зайти только на Яндекс и Озон и никуда кроме |
| **Какая цель VPN?** | Посетить сервис, который официально заблокирован в России: смотреть YouTube в 4K, звонить/чатиться в WhatsApp, Viber, Signal, FaceTime, Facebook, Discord, постить в Instagram, X(Twitter), пользоваться LinkedIn, играть в Roblox, звонить через Telegram, пользоваться Grok, ChatGPT, Gemini и прочее | Просто зайти хоть куда-нибудь кроме Яндекса, Сбербанка, Госуслуг и ВК во время ограничений. Использовать сервис, который не сильно требователен к пингу и пропускной способности сети: WhatsApp, Telegram, Google, любой E-Mail, видео в YouTube с телефона. Не рассчитано на тяжелый трафик и онлайн-игры (пробовать можно, но результат не гарантирован) |
| **Примечание** | Конфигурации "Черный список" - по сути это самый обычный/универсальный/международный вариант VPN, только с современным протоколом! Черный список также самый быстрый, так как работает в стандартных условиях | Конфигурации "Белый список" - по сути это специализированный VPN, обходящий специфические тяжелые ограничения в текущих Российских условиях |
| **Что мне выбрать?** | Если у вас кабельный интернет, или мобильный без ограничений и ваша ситуация подходит под описание в этой "левой" колонке - то вам нужна подписка "ЧЕРНЫЙ СПИСОК" | Если у вас мобильный интернет, все ограничено и ваша ситуация подходит под описание в этой "правой" колонке, то вам нужна подписка "БЕЛЫЙ СПИСОК" |
| **Какие протоколы и подписки есть?** | В коллекции черных списков есть **2 подписки VLESS** (1 отдельная полная для ПК + 1 сжатая для телефонов), а также **1 подписка Shadowsocks+Hysteria2+Vmess + Trojan** (1 полная одним файлом) |  Протокол тут в основном **VLESS**, разделенный на **4 CIDR-подписки**: 1 полная + 2 сжатые для телефонов + 1 дополнительная (CIDR-ограничения по IP-диапазонам сейчас работают у 100% мобильных операторов РФ, вводящих БС); а также **1-ну SNI-подписку** (ограничения по белым фейковым доменам SNI, что уже редкость) |


---

### **2)** **При обычных черных списках ⚫:** **VLESS**, либо **SHADOWSOCKS+ALL**, либо TOR BRIDGES

  **а)** **VLESS полная • VLESS для телефона • SHADOWSOCKS+ALL:**

При обычных черных списках выбираем самый устойчивый протокол **VLESS**, либо альтернативно **SHADOWSOCKS+ALL** (Shadowsocks, Hysteria2, Trojan, Vmess), но это не обязательно. На ПК или смартфоне - не важно, везде работает.

*Иногда случается, что на проводном интернете доступны все конфигурации, а на Wifi часть не доступна (пингуется тоже не с первого раза, надо повторять).*

————

 **б)** **TOR BRIDGES полная  •  ТОП-100  •  VANILLA • OBFS4 • WEBTUNNEL:**

Достойная альтернатива Черным Спискам VPN - мосты TOR BRIDGES. 

Выполняют те же функции, что и Черные Списки VPN только с одной разницей - выход в сеть осуществляется не через стандартную глобальную сеть (так называемый clearnet), а через сеть Tor. Мосты - это прокси, так как стандартные IP подключения, вшитые в Tor Browser заблокированы РКН. 

Воспользоваться Tor Bridges вы сможете через Tor Browser, а также Orbot или Invizible Pro, которые выступают в качестве клиента на устройстве iOS/Android.

Уточнение, есть нюансы: если пользуетесь мостами Tor и оборачиваете ваш трафик в Tor-туннель через клиенты, то работать будут только TCP-потоки, UDP-соединения работать не будут ни при каких обстоятельствах, т.к. сама архитектура Tor не пропускает UDP. 

Как это повлияет на работоспособность? 

а) Браузеры в большинстве случаев завязаны на TCP-потоках и все, что в них происходит, будет загружаться нормально и обычно.

б) Приложения, завязанные на UDP-соединения, такие как Discord или Steam, потеряют часть своего функционала. Какого? 

В Discord будет отправляться текст/картинки/видео/файлы в сообщениях, все как в обычном мессенджере, но голос/видео/стриминг в реальном времени и звонки не пройдут, т.к. "онлайн" завязан на UDP-трафик.

Telegram - то же самое: чаты, обмен сообщениями (текст/картинки/видео/файлы) работают спокойно, но звонки и онлайн-стримы не пройдут.

Steam, в частности, будет открываться и игра будет запускаться, но уже внутри самой игры не будут загружаться онлайн-сервера, т.к. все что связано с "онлайном", завязано на UDP. 

Но это не значит, что так со всеми приложениями. Есть приложения только для TCP-трафика, такие как почтовые клиенты, SSH-клиенты (Git-инструменты в SSH-режиме), SQL-клиенты, FTP/FTPS-клиенты, Клиенты к базам данных и прочее.

### СВЯЗКА "Tor Bridges" + "Tor-клиент OnionHop V2"

<details>

<summary> Нажмите на стрелку для подробностей </summary> 

VPN, особенно публичный, в настоящее время подвергается атакам Роскомнадзора и конфигурации приходится постоянно обновлять, часто меняя подключение.

### Что делать?

### У меня для вас есть рабочее решение: "Tor Bridges" + "Tor-клиент OnionHop V2".

### Для вас я подготовил пошаговый мануал (там все ссылки на скачивание клиента): 

**[OnionHop V2 — краткий обзор Tor-клиента для ПК (оригинал, доступен через VPN или Tor)](https://telegra.ph/OnionHop-V2--kratkij-obzor-Tor-klienta-dlya-PK-04-04)**

**[OnionHop V2 — краткий обзор Tor-клиента для ПК (зеркало)](https://web.archive.org/web/https://graph.org/OnionHop-V2--kratkij-obzor-Tor-klienta-dlya-PK-04-04)**

*Используя зеркало - не переходите по автоматическим ссылкам, а копируйте текст вручную и вставляйте в соседнюю вкладку, поскольку ссылки в зеркале ведут на ссылки в том же зеркале, а не напрямую на Github.*

**Работает аналогично схеме: "Конфигурации VPN" + "VPN-клиент".** 

**Как долго живет? Подключение не отваливается много дней или пока сами не отключите.** 

Мой последний максимум нон-стоп был 7 дней и я выключил просто потому, что нужна была перезагрузка ПК. 

Некоторые отдельные мосты работают уже несколько лет! Вот она стабильность!

Все работает, как и с обычным VPN, просто весь трафик вашего ПК оборачивается в сеть Tor. 

**Отличие от стандартного Tor Browser** тем, что не только Tor Browser отдельно, а **весь ПК целиком работает через Tor**: все браузеры и приложения, в том числе месседжеры (WhatsApp, Telegram) отправляют/получают сообщения и файлы.

В Readme я писал, что есть один нюанс в Tor архитектуре: работают TCP-соединения, не работают UDP. 

<details>
<summary> Какие нюансы и на что повлияет? (нажмите на стрелку) </summary>

---

На примере любого мессенджера: сообщения, файлы, текст, видео, аудио все отправляется, все работает как обычно. Не пройдут только звонки, т.к. звонок - это UDP-онлайн поток. Захотели позвонить - включили VPN-конфигурацию на телефоне, позвонили.

На примере Steam: само приложение обновляется, игра запускается, но не будет прогружаться список онлайн-серверов, т.к. любая онлайн-активность - это UPD-поток, ровно как и звонок в мессенджере. Просто купить/скачать игру и поиграть на ПК оффлайн - нормально, т.к. это происходит у вас на ПК локально.

---

</details>

**Большинство функций**: любые браузеры, YouTube, Instagram, Facebook, соцсети, переписки, обмены файлами, чаты, мессенджеры (WhatsApp, Telegram, Signal, Viber, Facetime, Discord), ИИ (Google Gemini, ChatGPT, Grok) **работают аналогично, как и с VPN-конфигурациями и соединение не слетает вообще.**

**Вывод: если вам нужен стабильный VPN на ПК, то "Tor Bridges" + "Tor-клиент OnionHop V2" - ваше решение.**

**Стабильнее и проще бесплатного решения на данный момент вы не найдете.** 

Для мобильных устройств используйте **Orbot** или **Invizible Pro**. Подробная информация в разделе "Приложения".

**По поводу безопасности**: TOR безопаснее любого даже самого навороченного платного VPN благодаря тому, что ваше соединение проходит через 3 сервера: 

**Ваш компьютер в вашей сети** ➞ **Подключение через Tor Bridges (Сервер №1)** ➞ **Сервер №2** ➞ **Сервер №3** ➞ **Выход в сеть Tor (интернет)**

1-й сервер не видит IP 3-его, а 3-й не видит IP 1-ого. На этом строится архитектура сетевой безопасности Tor, чтобы пользователи в странах с сильной цензурой не боялись цифровой слежки.

### Просто включите TOR у себя на компьютере и забудьте, что Роскомнадзор и ограничения существуют!

</details>

---

### **3)** **При белых списках ⚪: CIDR-ПОДПИСКА или SNI-ПОДПИСКА** 

  **а)** **CIDR-ПОДПИСКА полная • для телефона • только с хостерами: VK, YANDEX, CDNVIDEO, Beeline** 
  
  Самые жесткие блокировки по белым IP (CIDR-диапазонам) сейчас только на мобильных операторах Мегафон, Билайн, МТС, Т2, Yota и др., поэтому `конфигурации с белыми IP (из белых CIDR-диапазонов), пробивающие самые жесткие ограничения мобильного интернета я положил в TXT-подписки, начинающиеся на "CIDR-ПОДПИСКА"` и пометил `[*CIDR]` в примечаниях к каждому конфигу. 
  
  Эти конфигурации, понятное дело, сработают и в обычных условиях наравне с черными списками, но так делать не стоит! Почему? Просто потому, чтобы не перегружать их ради тех, кто в них серьезно нуждается и живет в регионах с ограниченным интернетом целыми месяцами! Используйте CIDR-конфиги только тогда, когда они вам реально нужны!

⚡ CIDR-подписка является универсальным (а не 100% индивидуальным) решением для обхода ограничений. У одного может работать одна часть конфигов, у второго - другая часть, у третьего - третья. Почему? От оператора к оператору, от региона к региону блокировки разные, реально работающие "белые подсети" у каждого тоже разные, а не у всех одинаковые и что подойдет конкретно вам - проверить можете только вы. Иногда случается, что в отдельных регионах выключают даже проверенные, рабочие "белые подсети", обнаружив аномальную активность на отдельных IP-адресах. Пробуйте, проверяйте, делитесь опытом.

⚡ По наблюдениям, опыту и отзывам лучше всего работают конфиги с транспортами: XHTTP (любое шифрование: Reality, TLS и none), GRPC (шифрование: Reality и none), WS (шифрование: Reality и none). Конфиги с TLS-шифрованием сейчас считаются "худшими", т.к. DPI РКН научился распознавать TLS-over-TLS соединения (в кратце: ваш HTTPS-трафик из браузера/приложения дополнительно "упаковывается" в TLS-оболочку VPN-туннеля вторым слоем и на это могут сработать фильтры DPI). Но это не значит, что конфиги с TLS не пригодны к использованию! Даже наоборот! Их сейчас большинство - они нормальные, просто есть конфиги "получше" и "постабильнее"!

⚡ Иногда в ПОЛНУЮ CIDR-ПОДПИСКУ кроме VLESS попадают такие протоколы как Trojan, Shadowsocks, Hysteria2. Проверяйте - они в самом низу списка.

⚡ Старайтесь во время режима "белых списков" не заходить на сайты из "Белого Списка Роскомнадзора" через конфиги из CIDR-подписки, это может быть одной из причин их будущего бана! Если нужно зайти, например во Вконтакте - выключили VPN и только потом зашли!
  
  **б)** **SNI-ПОДПИСКА:**
  
  Конфигурации, обходящие самые легкие блокировки по белым SNI-спискам (просто по названию домена), я положил в TXT-подписку **SNI-ПОДПИСКА**. Помечены они как `[SNI-RU]` в примечаниях к каждому конфигу, все SNI также подписаны для удобства.

  В настоящее время SNI-блокировки почти не применяются мобильными операторами ввиду их легкого обхода, потому что почти каждый может арендовать и настроить свой сервер за границей с необходимым фейковым доменом из белого списка. Но кому-нибудь все равно может сильно повезти и SNI-конфиги смогут обойти ограничения даже сейчас. Тестируйте.

---

## <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3Yml0MndhcDZ6dzFuYjY3aG0yNWowN2Rqbnp1aTV2cXNvb3FvMnluMiZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/MxryCOQuSYVVD0SPyp/giphy.gif" width="40"> Как мне воспользоваться этими конфигурациями у себя на устройстве 

### Общие инструкции:

1) VPN-конфигурации на вашем устройстве удобнее всего добавлять через *"добавить профиль"* *"подписку"* или *"группу подписки"* в Karing, v2rayN, Throne, v2rayNG, NekoBox, Streisand и прочие.

2) Копируйте Url-адрес txt-файла Github. Проверяйте, чтобы была именно RAW-ссылка, а не обычная! Скопировав ссылку, в приложении нужно нажать "Добавить из буфера обмена" или использовать обычную кнопку "Добавить" -> "Настроить вручную" -> тип "Подписка" -> вставить RAW-ссылку на txt-файл и задать имя подписке.
3) Сканируйте QR-код подписки из следующего пункта. QR-код еще проще - нажимаете кнопку "Добавить" -> "Отсканировать QR-код" и приложение само создаст подписку, вам лишь нужно будет поменять ее имя у себя в телефоне и нажать кнопку "Обновить", если список конфигов не загрузился сразу.
   
   QR-коды находятся под ссылкой на подписку, нажмите на стрелку с названием "QR-код".
   
4) Как проверить какие конфиги/сервера живые и работают в данный момент?

   Нажмите на всю подписку (на названии группы) или отдельный конфиг, обычно нужно нажать и не отпускать - появится меню, выберите, *внимание!*, *"Тест на рельную задержку"* или *"Задержка"*! Не "TCP Ping" или "ICMP Ping" - они не покажут реальную доступность VPN-сервера. Те, что откликнулись зелеными цифрами - их и выбирайте. Выбирайте цифры с наименьшими значениями, т.к. чем меньше число - тем меньше задержка, тем быстрее сервер будет вам "отвечать".

5) Настоятельно рекомендуется включить автообновление подписки хотя бы 2 раза в сутки (раз в 12 часов), а в новогодние праздники и того чаще. Конфигурации обновляются каждый час, т.к. со временем перестают работать. Поэтому, включив обновление, вы будете иметь самую свежую версию подписки с работающими конфигурациями без лишнего "мусора".

7) Конфиги, особенно из белых списков, могут не сразу быть зелеными при проверке "реальной задержки", очень часто пинг по 2-3-4 раза показывает новые доступные сервера.
8) Скачайте себе несколько разных клиентов на телефон - может такое случиться, что разные клиенты увидят разные доступные сервера. Это из-за различий в настройках клиентов при проверке конфигов.

9) Можно, также, добавлять все вручную по-отдельности, просто копируя содержимое каждого txt-файла в клиент v2rayN и др., но подписки удобнее тем, что они обновляются автоматически у вас на устройстве после обновления на Github, без необходимости удаления и нового копирования, упрощая процесс.

---

### Инструкции по каждому клиенту отдельно:

**Инструкция OnionHop V2:**

**[OnionHop V2 — краткий обзор Tor-клиента для ПК (оригинал, доступен через VPN или Tor)](https://telegra.ph/OnionHop-V2--kratkij-obzor-Tor-klienta-dlya-PK-04-04)**

**[OnionHop V2 — краткий обзор Tor-клиента для ПК (зеркало)](https://web.archive.org/web/https://graph.org/OnionHop-V2--kratkij-obzor-Tor-klienta-dlya-PK-04-04)**
  
**Инструкция Karing:**

https://github.com/KaringX/karing/blob/main/README_ru.md

**[Karing – Quick Start (оригинал, доступен через VPN или Tor)](https://web.archive.org/web/https://telegra.ph/Karing-Part1-02-16)**

**[Karing – Quick Start (зеркало)](https://web.archive.org/web/https://graph.org/Karing-Part1-02-16)**

За предоставленнный подробный русифицированный мануал благодарности пользователю @Пупкин Вася.

**Инструкция v2rayN, v2rayNG:**

**[Настройка V2rayN на Windows (зеркало)](https://web.archive.org/web/https://vpnpanels.com/ru/p/setup-v2ray-windows)**

**[Настройка V2rayNG на Android (зеркало)](https://web.archive.org/web/https://vpnpanels.com/ru/p/setup-v2ray-android/)**
 
**Инструкция Throne:**

https://wiki.aeza.net/ru/guides/throne/

**Инструкция Streisand, v2Box:**

**[Настройка Streisand, v2Box на iOS (зеркало)](https://web.archive.org/web/https://vpnpanels.com/ru/p/setup-v2ray-ios/)**
  
**Инструкция Nekobox:**

https://hiddify.com/manager/client-software-on-android/Tutorial-for-Nekobox-app/
  
**Инструкция Hiddify:**

https://hiddify.com/manager/client-software-on-desktop/Tutorial-for-HiddifyN-software/

https://hiddify.com/app/How-to-use-Hiddify-app/

**Инструкция ShadowRocket:**

https://github.com/hiddify/Hiddify-Manager/wiki/Tutorial-for-ShadowRocket-app

---

## 🧩 Приложения (клиенты) для VPN-конфигов на ПК и телефоне 

В зависимости от клиента могут отличаться рабочие сервера. Поэтому поставьте себе на ПК 2-3 разных клиента: v2rayN, Throne и Karing. Например, в v2RayN конфиги могут все пропинговаться идеально, но часть может не "завестись" по скорости - но это НЕ значит, что они "плохие" (уточню, что конфиги на момент обновления - почти все рабочие), просто v2rayN не смог их правильно "завести", это нормально из-за особенностей работы каждого клиента в отдельности. Часть не работающих полноценно конфигов в v2RayN отлично заработает в Throne, часть - в Karing и других клиентах, поэтому подбирайте что вам ближе и удобнее. Конфигов в целом много, поэтому, даже если часть не заводится - не беда, 70-80% заработает через один клиент уж точно.

Эта особенность касается и клиентов на мобильных устройствах. Например, на iOS, кроме Streisand можно поставить Karing или Shadowrocket и сравнить.

###  <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3amtqMmQxOGh0aG0waGk5OGhhNG5odmdob2k1bWc4ejNyZ3E3N2Y2bCZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/xUS4Fp5i6iIn2Y1EYT/giphy.gif" width="25"> Windows/Linux/MacOS - клиенты для VPN-конфигураций на ноутбуках и стационарных компьютерах

Установите официальный клиент v2rayN или Throne (преемник Nekoray), запустите в "режиме Администратора", добавьте конфиг/подписку через Ctrl+V, загрузите подписку через "Группа подписки" - "Обновить текущую подписку без прокси", появится список, нажмите на проверку "Реальной задержки" (значок молнии сверху справа), после завершения - отсортируйте по пингу, выберите несколько верхних зеленых конфигов с наименьшим числом, нажмите правую клавишу мышки - выберите "Тест на скорость загрузки сервера", после теста выберите самый быстрый, нажав на нем Enter, в конце запустите "Режим VPN/Режим TUN".

---

### 1) Karing:

*Рекомендую как лучший бесплатный клиент. Универсальный, адаптивный, мощный инструмент для того, чтобы ваши конфигурации завелись хоть из-под палки. Не подходит для массовых проверок скорости, только пинг.*

   https://github.com/KaringX/karing/releases

   `karing_1.2.10.1300_windows_x64.exe` для Windows
  
   `karing_1.2.10.1300_linux_amd64.deb` для Linux (Ubuntu)
  
   `karing_1.2.10.1300_macos_universal.dmg` для MacOS

---

### 2) v2rayN:
  
   *Рекомендую v2rayN после Karing, стабильно и проверено работает с тысячами конфигов разных протоколов за раз (мой личный максимум 150.000 конфигов). Это тоже универсальный клиент из всех. Идеален для массовых проверок (пинг+скорость). Работает, используя Xray, Sing-Box, Mihomo в одной связке.*

   https://github.com/2dust/v2rayN/releases
  
   `v2rayN-windows-64.zip` для Windows
  
   `v2rayN-linux-64.deb` для Linux (Ubuntu)
  
   `v2rayN-macos-64.dmg` для MacOS

---

### 3) Throne (преемник заброшенного Nekoray, Nekoray не обновляют с 2024 года):

*Рекомендую как альтернативный рабочий клиент после v2rayN. Конфигурации, которые "не завелись" в v2rayN - частично заводятся здесь. Подходит для массовых проверок.*

   https://github.com/throneproj/Throne/releases

   `Throne-1.0.8-windows64-installer.exe` для Windows
  
   `Throne-1.0.8-debian-x64.deb` для Linux (Ubuntu)
  
   `Throne-1.0.8-macos-arm64.zip` для MacOS
   
---

### <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3aGcxcG8yMGNzOTNmZDE1Z3hob3V3ajU4dmhkdnhsY2doMXFrNXowMyZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/oFSDc1Oq12Ie5NJnmA/giphy.gif" width="20"> iOS - используйте Streisand, Shadowrocket, Karing, V2Box или v2RayTun из App Store.

  Рекомендую Streisand, так как заявлено об отсутствии сбора данных в App Store, а также все функции, включая смену DNS работают исправно в отличие от других подобных клиентов, загрузка и работа конфигов стабильна.

  Happ не рекомендуется пользователями из-за нестабильной работы/пинга.

   **1)** `Streisand` https://apps.apple.com/us/app/streisand/id6450534064 
   
   *Лучший бесплатный клиент для iOS без сбора данных*

   **2)** `Shadowrocket` https://apps.apple.com/us/app/shadowrocket/id932747118 
   
   *Не теряет соединения даже после долгого ожидания, не ведется сбор данных, но платный*

   **3)** `Karing` https://apps.apple.com/us/app/karing/id6472431552
     
   *Хорошая альтернатива Streisand*

   **4)** `V2Box` https://apps.apple.com/us/app/v2box-v2ray-client/id6446814690

   **5)** `v2RayTun` https://apps.apple.com/us/app/v2raytun/id6476628951

---
  
### <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExODUzYWRwNzNpa3doMDd1bXo4NTlzanJsaTcya3dlNXA4d3c5cnVzNCZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/UQJlZ2OcaCA2RLfGiZ/giphy.gif" width="20"> Android - используйте v2rayNG и NekoBox из GitHub или v2Box и v2RayTun из Google Play.

 Рекомендую v2rayNG, так как это аналог моего фаворита v2rayN для ПК от того же разработчика "2dust", но для Андроида.

 Также попробуйте NekoBox, пользователи хвалят.

 Happ не рекомендуется пользователями из-за нестабильной работы/пинга.

  **1)** `NekoBox` https://github.com/MatsuriDayo/NekoBoxForAndroid/releases

  **2)** `v2rayNG`  https://github.com/2dust/v2rayNG/releases

  **3)** `v2Box` https://play.google.com/store/apps/details?id=dev.hexasoftware.v2box

  **4)** `v2RayTun` https://play.google.com/store/apps/details?id=com.v2raytun.android&hl=en&pli=1

---

## 🧅 Приложения (клиенты) для Tor Bridges на ПК и телефоне

**Официальная ссылка на скачивание** `Tor Browser` (через VPN или Tor): https://www.torproject.org/ru/download/

**Получить обновленную версию** `Tor Browser` **через бота Telegram**: @gettor_bot

**Получить обновленную версию** `Tor Browser` **можно через E-Mail**, отправив письмо с темой "windows", "macos", "linux" или "android" — в зависимости от вашей операционной системы: gettor@torproject.org

*Доступно для Windows, macOS, Linux, Android.*

**Мосты**, кроме как в этом репозитории, вы можете также официально **получить от проекта Tor Project, Inc.** 

Но в этом случае их придется перебирать и тестировать, т.к. мосты попадаются не всегда рабочие для России.

**Мосты через E-Mail** (отправьте письмо с адреса вашей электронной почты Gmail или Riseup): bridges@torproject.org

**Мосты через бота Telegram**: @GetBridgesBot 

**Мосты на официальном сайте Tor Project**: https://bridges.torproject.org/options

---

###  <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3amtqMmQxOGh0aG0waGk5OGhhNG5odmdob2k1bWc4ejNyZ3E3N2Y2bCZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/xUS4Fp5i6iIn2Y1EYT/giphy.gif" width="25"> Windows/MacOS - клиенты для Tor Bridges на ноутбуках и стационарных компьютерах

### 1) OnionHop V2:

*Рекомендую как лучший бесплатный клиент для использования Tor Bridges на ПК.*

*Универсальный, рабочий, мощный инструмент для того, чтобы ваше соединение работало всегда стабильно.*

   https://github.com/center2055/OnionHop/releases

   `OnionHop-CLI-Setup-2.5.2.exe` - installer-версия CLI для Windows

   `OnionHop-Setup-2.5.2.exe` - installer-версия GUI для Windows

   `OnionHopCLI-Portable-2.5.2-win-x64.zip` - portable-версия CLI для Windows

   `OnionHopV2-Portable-2.5.2-win-x64.zip` - portable-версия GUI для Windows
  
   `OnionHop-2.5.2-macOS.dmg` - installer-версия GUI для MacOS

  Отличия **installer-версии** и **portable-версии**: "installer-версия" полноценно устанавливается в систему, а "portable-версия" не требует полноценной установки - распаковал и запустил.

---

### <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExODUzYWRwNzNpa3doMDd1bXo4NTlzanJsaTcya3dlNXA4d3c5cnVzNCZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/UQJlZ2OcaCA2RLfGiZ/giphy.gif" width="20"> <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3aGcxcG8yMGNzOTNmZDE1Z3hob3V3ajU4dmhkdnhsY2doMXFrNXowMyZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/oFSDc1Oq12Ie5NJnmA/giphy.gif" width="20"> iOS/Android - клиенты для Tor Bridges на мобильных устройствах:

`Orbot` **Wikipedia:** https://en.wikipedia.org/wiki/Orbot

`Orbot` **App Store:** https://apps.apple.com/us/app/orbot/id1609461599

`Orbot` **Google Play:** https://play.google.com/store/apps/details?id=org.torproject.android

`Invizible Pro` **официальный сайт:** https://invizible.net/ru/

`Invizible Pro` **Google Play:** https://play.google.com/store/apps/details?id=pan.alexander.tordnscrypt.gp

---

## <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3ZDhxeG02NHlucTdqZGhtejBnb2V5dGpwaDBmcHhobWlsOHQxdWpoYSZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/8L0hXHQkY4o7eyQHJB/giphy.gif" width="30"> Полезная информация

⚡ Зачем я вообще тестирую конфигурации? В самом начале из 40.000+ взятых на пробу бесплатных публичных конфигураций - проверку на работоспособность прошли примерно 700 штук, а это менее 2%, а в итоге тут выложил около 200 самых качественных с высоким откликом и приличной скоростью, а это уже пол процента. Не у каждого есть время разбираться со сборками из десятков тысяч конфигураций, где реально работающих только пару сотен.

⚡ Протоколов в сети целый вагон, но **самый эффективный**, защищающий от DPI Роскомнадзора и его блокировок - это **VLESS+Reality** из-за способности маскировать трафик под обращение к безобидному HTTPS сайту, делая использование VPN абсолютно невидимым для вашего интернет-провайдера. Остальные протоколы - идут по убывающей в рейтинге, так как легче демаскируются. 

⚡ Самый стабильный транспорт: XHTTP, GRPC и WS.

⚡ Часть конфигураций со временем могут перестать работать из-за независящих от меня причин, поэтому списки будут периодически обновляться.

⚡ Если провайдер блокирует подключение к VPN - попробуйте поменять обычный DNS на своем роутере, ПК или телефоне на шифрованный DNS-over-HTTPS (DoH) или DNS-over-TLS (DoT). Даже если не поможет - просто поставьте себе DoH для вашей же конфиденциальности в сети!

⚡ Во время работы белых списков некоторые иностранные DNS-DoH (Google, например) иногда могут быть недоступны. Сначала я бы проверил работу Cloudflare, OpenDNS, Google, Quad9, AdGuard, Dnsforge, и если ни один не работает, то выбрал бы Яндекс DoH. Если вообще никакой DoH не заводится - отключите и используйте автоматический провайдерский.

<details>

<summary> 🧾 Что такое и как подключить DNS-over-HTTPS (DoH)? </summary>


> *НА РОУТЕРЕ: удалите и отключите дефолтный провайдерский DNS и поставьте DNS-over-HTTPS (DoH), сначала потребуется скачать DoH-клиент в настройках обновления роутера. Можно поставить и DNS-over-TLS (DoT), но его не советуют в России из-за частых блокировок. DNS-over-HTTPS (DoH) должен работать 100% стабильно.*

> *НА ТЕЛЕФОНЕ несколько вариантов:*
> 
> - скачайте приложение "Cloudflare 1.1.1.1 + WARP: Safer Internet" для Android (Google Play Store) / ‎"1.1.1.1: Faster Internet App" для iOS (App Store);
> 
> - для iOS не существует базовых сетевых настроек и DoH-конфигурации скачиваются отдельным файлом с официальных сайтов Quad9, AdGuard, Dnsforge и пр. (читай ниже "Список публичных DoH-серверов");
> 
> - для Android: перейдите в Настройки ➡️ Сеть и интернет (или Wi-Fi и интернет) ➡️ Выберите «Расширенные настройки» ➡️ «Персональный DNS-сервер (Private DNS)» ➡️ Выберите «Имя хоста личного DNS-провайдера» и введите один из адресов из списка публичных DoH-серверов ниже (читай ниже "Список публичных DoH-серверов");*

> *НА ПК: пропишите DoH-сервер в настройках DNS сетевого адаптера.*

> *В ПРИЛОЖЕНИИ VPN: пропишите DoH-сервер в настройках DNS приложения, либо выберите из предустановленных. Корректно работающий DNS обнаружен в Streisand на iOS.*

DNS-over-HTTPS (DoH) - это тот же DNS, только зашифрованный и приватный, DNS через HTTPS: шифрует DNS‑запросы от локальных наблюдателей (провайдера), повышая приватность, но DNS-резолвер (Cloudflare/Google и др.) всё равно видит запросы (вы же запросы через него пропускаете), провайдер видит только соединение с IP‑адресом резолвера DoH/DoT (и объём/время трафика) + конечный IP целевого сервера, т.е. конечный IP посещаемого сайта без названия целевого домена (а при отсутствии ECH — и домен через SNI). По конечному IP (и при отсутствии ECH — по SNI) часто можно идентифицировать сайт. 

Возможно (но не 100%) DoH позволит обойти некоторые ограничения подключения, если таковые имеются. DoH может помочь обойти простые DNS‑блокировки, но не блокировки по IP/SNI или глубокому фильтрованию.  

Стандарт опубликован IETF как RFC 8484 (2018) при содействии по внедрению протокола от ICANN, а впервые внедрили/тестировали его Google аж в 2016-м! Цель - повышение конфиденциальности и безопасности пользователей.

</details>

> *Нажмите на стрелку, чтобы узнать*

<details>

<summary> 🧾 Список публичных DoH-серверов (+ скачать DoH-конфигурации DNS): </summary>

`https://common.dot.dns.yandex.net/dns-query` - *Яндекс DNS Базовый. Внимание! Рекомендуется, только если не работают другие DNS при БС, в нормальном режиме используйте только DNS-сервера ниже;*

`https://safe.dot.dns.yandex.net/dns-query` - *Яндекс DNS Безопасный режим. Внимание! Рекомендуется, только если не работают другие DNS при БС, в нормальном режиме используйте только DNS-сервера ниже;*

`https://dns.adguard-dns.com/dns-query` - *AdGuard DNS. DNS от всем известного лучшего бесплатного блокировщика рекламы и трекеров со штаб-квартирой на Кипре;*

`https://adguard-dns.io/ru/public-dns.html` - *скачать AdGuard DNS-конфигурацию-файл для iOS (+почитать инструкции про другие платформы, на русском);*

`https://dns.quad9.net/dns-query` - *Quad9 DNS базовый. Malware Blocking, DNSSEC Validation. Политика отсутствия логов, Штаб-квартира в Швейцарии;*

`https://dns11.quad9.net/dns-query` - *Quad9 DNS расширенный. Secured w/ECS: Malware blocking, DNSSEC Validation, ECS enabled. Политика отсутствия логов, Штаб-квартира в Швейцарии;*

`https://docs.quad9.net/Setup_Guides/iOS/iOS_14_and_later_(Encrypted)/` - *скачать Quad9 DNS-конфигурацию для iOS (+почитать инструкции про другие платформы, язык - только английский, русского нет);*
 
`https://dnsforge.de/dns-query` - *отличный DNS от немецкого бесплатного блокировщика рекламы и трекеров DNSFORGE dnsforge.de. Политика отсутствия логов, сервера в Германии, вся информация и инструкции на немецком;*

`https://dnsforge.de/dnsforge-doh.mobileconfig`  - *скачать DNSFORGE.DE DNS-конфигурацию-файл для iOS;*

`https://dns.cloudflare.com/dns-query` - *Cloudflare DNS Базовый;*

`https://security.cloudflare-dns.com/dns-query` - *Cloudflare DNS для блокировки вредоносного ПО;*

`https://dns.google/dns-query` - *Google Public DNS (у некоторых недоступен при белых списках);*

`https://doh.opendns.com/dns-query` - *Cisco Umbrella (OpenDNS).*

</details>

> *Нажмите на стрелку, чтобы посмотреть список*

---

##  Альтернативные обходы ограничений

<details>

<summary> Нажмите на стрелку </summary>

.

**Psiphon** — бесплатное и открытое программное обеспечение для обхода Интернет-цензуры. Psiphon разработан специально для поддержки пользователей в странах с интернет-цензурой. Psiphon, Inc. была создана в 2007 году в качестве независимой корпорации в Онтарио, Канада. При сотрудничестве с Citizen Lab при Munk School of Global Affairs, Университетом Торонто.

Информация: https://ru.wikipedia.org/wiki/Psiphon

Официальная ссылка для скачивания на Windows 10/11 (доступно только через VPN или Tor): https://psiphon.ca/ru/

Выгрузил установщик на GitHub: https://github.com/igareck/GoldCaviar/raw/refs/heads/main/Files/Psiphon3_VPN_install.exe

Внимание! Работает только на кабельном интернете на ПК (мобильные сети нет)! Разнообразный выбор локаций!

Система на базе устаревшего протокола SSH, соединение не быстрое, но самое главное, что работает. 

</details>

## 👁️‍🗨️ Что видит провайдер и что вообще кому видно, когда вы сидите в интернете?

<details>

<summary> Нажмите на стрелку, чтобы узнать </summary>

**В целом.**

**Когда вы в интернете - есть 5 сторон, которые оценивают ваши действия:**

**1.** `Вы сами`

**2.** `Ваш интернет провайдер` 

**3.** `Сайт/поисковик, который вы посещаете`

**4.** `Ваш браузер (если он от Yandex, Google и любой публичной компании)` 

**5.** `DNS-резолвер` 

**Некоторые думают, что "провайдер все видит".**

**Но это заблуждение, провайдер мало что видит, если вы правильно ведете себя в сети.**

Опишем стандартную работу интернета на HTTPS сайтах без VPN. Не путать с голым HTTP, который незашифрован. На дворе 2026 год, сайтов на HTTP почти не осталось.

**Разберем все по-отдельности.**

### 1. Провайдер.

Провайдер стандартно видит 3 вещи: конечный IP сайта, к которому вы подключаетесь + название домена + зашифрованные HTTPS-пакеты, приходящие в браузер пользователя. Что происходит на самом сайте знает только 2 стороны - пользователь и сайт, все! Благодаря шифровке HTTPS. То, что вы ищете в Google - знаете только вы и Google.

**Поясню на примере YouTube:**

Вы зашли на наш любимый YouTube, посмотреть полезный видеоурок, открыли это видео и смотрите. Что видит провайдер? IP от YouTube + название домена "YouTube" + зашифрованные HTTPS-пакеты, приходящие на ПК пользователя! Все, больше ничего! Какие именно видео смотрите, что ищете в поисковике - провайдеру не видно, так как это происходит на самом сайте и зашифровано HTTPS. Гляньте слева от названия сайта "https:" - это то самое шифрование, с которым работает сайт, дающее миллионам людей по всей планете цифровую безопасность, защищая пользователей от цифровой слежки. 

**Поясню на примере поисковика Google:** 

Вы зашли на Google.com посмотреть котов, вводите в поиск *"кот мем неси черешню"*, вам выпал список картинок с котом в фартуке. Что видит провайдер? Страшно? Ничего не видит. Видит IP от Google + название домена "Google" + зашифрованные HTTPS-пакеты, приходящие на ПК. Что вы там смотрите, какие именно фотографии котов и в каких позах - провайдер не видит. HTTPS-пакет, конечно, содержит фотографии кота в фартуке, но пакет зашифрован - поэтому провайдер увидит, что вы "что-то смотрите на Google", но это набор пустой для него информации, расшифровать которую даже суперкомпьютерам не под силу, либо займет 100 лет. Представьте, расшифруют через 100 лет, а там "кот мем неси черешню" или "Наталья Морская Пехота".

**А что будет, если вы поставите вместо обычного DNS, например 1.1.1.1 - шифрованный DNS-over-HTTPS (DoH)?**

Провайдер теперь не сможет напрямую увидеть даже название домена, к которому вы подключались. То есть при DoH провайдер не видит DNS-запросы открытыми, видит только, что вы установили соединение с IP‑адресом резолвера DoH/DoT (и объём/время трафика) + конечный IP сайта, не узнаёт конечный домен, но может часто угадать целевой сайт по IP, SNI и поведению трафика; для популярных сайтов это проще, для малоизвестных — сложнее, но не полностью исключено. Если бы DoH скрывал конечный IP, то он заменил бы нам VPN, но конечный посещаемый IP без VPN не скрыть. А провайдер блокирует сайты (например Youtube) именно по конечному IP. Поэтому в итоге для доступа к сайтам используется VPN.

**Кратко по DNS:**

Обычный DNS по типу 1.1.1.1 (plain text) показывает: IP сайта + название домена/SNI + зашифрованные пакеты HTTPS;

DoH показывает: конечный IP от сайта (+анализ) + зашифрованные пакеты HTTPS.

### 2. Сайт/поисковик.

**Сайт видит то, что вы делаете у него на территории и подчиняется законам страны, в которой у него штаб-квартира.**

Все современные сайты , соединения и информация, которой они с вами обмениваются зашифрованы HTTPS (не путать с голым HTTP), поэтому все ваши запросы на сайтах видны только Вам и самому сайту, но не провайдеру. Провайдер видит только бесполезный для него HTTPS зашифрованный трафик, который он не сможет расшифровать.

**В плане поисковиков посоветую два. Ищите с ними без волнения, что спросите вдруг что-то, что не понравится цензуре:** 

> *1. Google-поисковик (самый популярный + у него самая огромная поисковая выдача в мире). Штаб квартира в Маунтин-Вью, штат Калифорния, США.*

> *2. Duckduckgo-поисковик (популярный + отличная поисковая выдача, где можно выбрать регион выдачи + компания завляет о конфиденциальности ваших поисковых запросов). Штаб-квартира в Паоли, штат Пенсильвания, США.*

Yandex-поисковик не могу посоветовать, к сожалению. Штаб квартира в Москве. Все ваши запросы логгируются и анализируются в силу текущей повестки. Используйте обдуманно только для поиска индексируемой по России информации. Для всего остального хватит Google и Duckduckgo.

### 3. Браузер.

Может кто-то и не знал - браузер тоже видит ваши действия. 

**Какие сейчас массовые и популярные браузеры в России?** 

> а) Yandex Browser. Настоятельно не рекомендуется! Если установлен - удалите и замените на любой другой! Логгирует трафик;

> б) Google Chrome. Конфиденциальности тут тоже нет, логгирует трафик. Но для России безопаснее, чем Yandex + своя экосистема от Google; 

> в) Mozilla Firefox. По политике конфиденциальности он лучший среди популярных и массовых; 

Эти массовые браузеры имеют своих создателей, а создатели - публичные компании, которые собирают данные о своих пользователях и видят историю запросов, т.е. открытый трафик (что бы они не говорили) + подчиняются юрисдикциям/законам тех стран, где у них штаб-квартиры, вот и думайте. Чтобы браузер не был "человеком посередине" ("man-in-the-middle") - поставьте конфиденциальный Open-Source браузер, который делают не публичные компании, а независимые разработчики, у которых открытый (Open-Source) код и любой желающий, кто разбирается - может проверить браузер на безопасность, например выложенный на GitHub код.

**Какие браузеры порекомендую для повседневного использования и серфинга интернета?**

Снизу-вверх: от самого популярного к самому конфиденциальному.

**а)** `Mozilla Firefox` - если хочется популярного варианта без заморочек + скачайте к нему расширение uBlock origin (ublockorigin.com) для блокировки трекеров и рекламы. Браузер на движке Firefox от публичной компании Mozilla. По политике конфиденциальности он лучший среди массовых.

https://www.firefox.com/en-US/?utm_campaign=SET_DEFAULT_BROWSER

https://github.com/mozilla-firefox/firefox

**б)** `Ungoogled Chromium` - open-source браузер на движке Chromium с вырезанной Google-телеметрией от независимых разработчиков. Проверен широкой аудиторией. Подойдет для повседневных задач, но нужно будет вручную скачивать с GitHub каждый раз, когда выходят обновления от разработчиков. Скачайте к нему расширение uBlock origin (ublockorigin.com) для блокировки трекеров и рекламы. Для повседневных задач и конфиденциальности я бы назвал Ungoogled Chromium золотой серединой. Ungoogled Chromium работает прямо как Google Chrome один-в-один, только без экосистемы Google.

https://github.com/ungoogled-software/ungoogled-chromium-windows для Windows.

https://github.com/ungoogled-software/ungoogled-chromium-portablelinux для Linux (Portable версия).

https://github.com/ungoogled-software/ungoogled-chromium-macos для MacOS

**в)** `Librewolf (кастомизированный Firefox)` - open-source браузер на движке Firefox c вырезанной телеметрией Mozilla Firefox, от независимых разработчиков. Я бы назвал это "конфиденциальный Firefox-браузер из коробки": скачал и запустил. Проверен широкой аудиторией. Удобен. С автообновлением (во время установки поставьте галочку). Сразу встроен  uBlock origin. Librewolf крут, но иногда из-за полуагрессивных настроек некоторые сайты со стримами могут ломаться или не открываться, хоть это и очень редко случалось.

https://librewolf.net/

https://codeberg.org/librewolf

**г)** `Cromite` - open-source браузер на движке Chromium с вырезанной телеметрией, от независимых разработчиков. Проверен широкой аудиторией. Для повседневного просмотра подойдет, но с оговоркой - очень агрессивная блокировка трекеров и прочей телеметрии. Встроенный AdBlock. Некоторые сайты могут поломаться. В Cromite у меня это было чаще, чем с браузерами выше. Логин в Google прошел еле-еле. А вот проверка браузера на безопасность была лучшей именно у Cromite - даже "железо" ПК не определилось, не говоря уже о других цифровых отпечатках, все было "чисто". И это все "из коробки".

https://github.com/uazo/cromite

Эти браузеры внимания провайдера не привлекут, т.к. провайдер видит только движки, на которых эти браузеры работают, то есть видно, что это Chromium (Google Chrome, Ungoogled Chromium, Cromite) или Firefox (Mozilla Firefox, Librewolf), что за браузер у вас - видите только вы.

### 4. DNS-резолвер.

При обычном DNS (1.1.1.1) перед подключением к сайту мы обращаемся к DNS-резолверу и он видит, куда мы направляемся. Любой оператор DNS-резолвера видит все DNS‑запросы и ответы (какие домены вы разрешаете). По этим записям можно узнать, куда вы собираетесь подключиться.

Что будет если вы поставите вместо обычного DNS 1.1.1.1 (plain text) шифрованный DNS-over-HTTPS (DoH)? 

Интернет-провайдер теперь не сможет видеть название домена/сайта, к которому вы подключались. Провайдер видит только, что вы установили соединение с IP‑адресом резолвера DoH/DoT (и объём/время трафика).

Но DNS-резолвер все также видит название домена + IP, потому что вы пропускаете DNS-запросы через него, даже шифрованные, он их получает и расшифровывает.

### Вывод.

**Чтобы свободно и уверенно чувствовать себя в интернет-пространстве, помогут:**

`DNS-OVER-HTTPS (DoH)` 

➕

 `Правильный поисковик: Google или Duckduckgo` (кроме Yandex) 
 
➕
  
`Безопасные/независимые браузеры: Mozilla Firefox как минимум, Librewolf, Ungoogled Chromium, Cromite как максимум` (ни в коем случае не Yandex-браузер)

---


**Информация со временем будет пополняться и уточняться.**

</details>


## <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExZXJoeTEzZ3FtcGNrdmo2ZnFocDUwOTVvYmdjNWRnaWMwNHozMWN1YiZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/ZcdZ7ldgeIhfesqA6E/giphy.gif" width="25"> Делитесь подписками! 

## Пользуйтесь интернетом свободно и ответственно!

## 🔖 Лицензия

Лицензия GPL-3.0. С лицензией можно ознакомиться в файле [`LICENSE`](LICENSE)

## <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExM2wwMmJ3bDZvMWV2b2JraXZ4ZWk2Y2I5ODYyZ2M2aG5mMHc5ZW81ZyZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/ME8P6ce7Mn3gnRbird/giphy.gif" width="30"> Поддержать автора

**Проект некоммерческий и основан на личном энтузиазме автора.**

**Если есть желание поддержать - можно сделать это через криптовалютный перевод.**

**Средства пойдут на продолжение деятельности и ее развитие.**

**Всем неравнодушным заранее благодарен!**

<details>
<summary><h3> 💳 Адреса кошельков 💳 <h3></summary>

Выберите любую удобную для вас криптовалюту и скопируйте ее адрес. Отправлять следует только на тот кошелек, который соответствует монете, в противном случае средства будут утеряны.

| № | Монета | Адрес |
|--|--|--|
| 1 | `Bitcoin (BTC)` | `18vVz4UzFdxCGnCnAzJtXv6ECsh32ff9VT` |
| 2 | `Монеты_на_базе_Ethereum(ETH): Ethereum (ETH), USDC (ETH), USDT (Ethereum ERC-20), Shiba Inu (SHIB)` | `0xfc668016a823f3EE53d2F3009547666A2BdaBd32` |
| 3 | `Монеты_на_базе_Tron_(TRX): Tron (TRX), USDC (TRX), USDT (TRX)` | `TLnzF6NYgyqBHJMM2qByMXEHLBWNhBWcJ1` |
| 4 | `Монеты_на_базе_Toncoin_(TON): Toncoin (TON), Notcoin (NOT), Hamster Combat (HMSTR), USDT (USDT-TON)` | `EQAGbSuckE93yiACSENJGo8WuRq474Wba1J4yCF1Q59xsL0k` |
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

> *Нажмите на стрелку, чтобы раскрыть список*

##  <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3ZmJ4anB6YjR3aWJpaTRvYzUzejY1dmwzN2c2M3c2NnV0MXUwM3RrcyZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/acN91ftm1tJX23OOBx/giphy.gif" width="60"> Почта для связи: igareck@proton.me

## 👀 Количество посетителей
<img src="https://komarev.com/ghpvc/?username=igareck&label=Visitors&color=0e75b6&style=flat" alt="Visitor Count" /> <img src="https://visitor-badge.laobi.icu/badge?page_id=igareck.visitor-badge&left_color=black&right_color=green&left_text=Cyber+Hits" alt="Cyber Hits"/>  
</div>

## <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExa2RkeXZzdDl1Y3g4dW1xcjFxc2xsMHVsZ2RiY243OHJodjd0cHQ1NSZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/qXp82ZL3eZbbTUrLyy/giphy.gif" width="30"> <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExa2RkeXZzdDl1Y3g4dW1xcjFxc2xsMHVsZ2RiY243OHJodjd0cHQ1NSZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/qXp82ZL3eZbbTUrLyy/giphy.gif" width="30"> <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExa2RkeXZzdDl1Y3g4dW1xcjFxc2xsMHVsZ2RiY243OHJodjd0cHQ1NSZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/qXp82ZL3eZbbTUrLyy/giphy.gif" width="30">
<a href="https://www.star-history.com/#igareck/vpn-configs-for-russia&type=date&legend=top-left"><picture><source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=igareck/vpn-configs-for-russia&type=date&theme=dark&legend=top-left" /><source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=igareck/vpn-configs-for-russia&type=date&legend=top-left" /><img alt="Star History Chart" src="https://api.star-history.com/svg?repos=igareck/vpn-configs-for-russia&type=date&legend=top-left" /></picture></a>

## <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3Z25rOXRoeW1xODR1dWh2b3UycTd6YnB0Y2hlMTZtaDluZW1uNnl4ZyZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/CeYEKonyFQyzWhxmvd/giphy.gif" width="40"> ДИСКЛЕЙМЕР

> *Автор не является владельцем/разработчиком/поставщиком перечисленных VPN-конфигураций. Это независимый информационный обзор и результаты тестирования.*
>
> *Данный пост не является рекламой VPN. Весь материал предназначен исключительно в информационных целях, и только для граждан тех стран, где эта информация легальна, как минимум - в научных целях. Если вам такое читать нельзя - закройте эту страницу немедленно!* 
>
> *Автор не имеет никаких намерений, не побуждает, не поощряет и не оправдывает использование VPN и любых других программ ни при каких обстоятельствах.*
>
> *Ответственность за любое применение данных VPN-конфигураций — на их пользователе.*
>
> *Отказ от ответственности: автор не несёт ответственность за действия третьих лиц и не поощряет противоправное использование VPN.*
>
> *Автор не несет ответственности за точность, полноту и достоверность опубликованных данных. Все совпадения случайны. Вся информация предоставлена «как есть» и может не соответствовать действительности.*
>
> *Используйте в соответствии с местным законодательством.* 
>
> *Используйте VPN только в законных целях: в частности - для обеспечения вашей безопасности в сети и защищённого удалённого доступа, и ни в коем случае не применяйте данную технологию для обхода блокировок.*
>
> *Проект некоммерческий, бесплатный, вся представленная "платежная" информация найдена случайным образом где-то в интернет-пространстве, скопирована "как есть" для демонстрации возможного примера и автору не принадлежит.*
>
> *Совет - закройте эту страницу, удалите все VPN с вашего компьютера, поставьте MAX и Yandex на все устройства, чтобы "ловило" даже на парковке, и пользуйтесь только интернет-ресурсами, которые разрешены вашим интернет-провайдером, ну вы поняли.*
