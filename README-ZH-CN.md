<div align="center">
  
![maxresdefault](https://raw.githubusercontent.com/igareck/GoldCaviar/refs/heads/main/Files/vpn-configs-for-russia-4.svg)

</div>

# <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNTljeGk4d3lzZnU3Mm1peDBienFpbmEyb3JmaDB5N21tMW9oczIwdyZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/8p1WPEOeDWFCksfe18/giphy.gif" width="45">  在俄罗斯可用的免费 VPN 配置

[![Stars](https://img.shields.io/github/stars/igareck/vpn-configs-for-russia?style=flat)](https://github.com/igareck/vpn-configs-for-russia/stargazers)
<img src="https://komarev.com/ghpvc/?username=igareck&label=Visitors&color=0e75b6&style=flat" alt="Visitor Count" /> 
[![Issues](https://img.shields.io/github/issues/igareck/vpn-configs-for-russia?style=flat&color=0e75b6)](https://github.com/igareck/vpn-configs-for-russia/issues)
[![last commit][1]][1]
![Open Source Love](https://badges.frapsoft.com/os/v2/open-source.png?v=103)

[1]: https://custom-icon-badges.demolab.com/github/last-commit/igareck/vpn-configs-for-russia?logo=history&logoColor=white&color=0e75b6&style=flat

**🌐 Язык: [Русский](README.md) | 🌐 Language: [English](README-EN-US.md) | 🌐 语言: [中文](README-ZH-CN.md) | 🌐 زبان: [فارسی](README-FA-IR.md)**

<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExa2RkeXZzdDl1Y3g4dW1xcjFxc2xsMHVsZ2RiY243OHJodjd0cHQ1NSZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/qXp82ZL3eZbbTUrLyy/giphy.gif" width="20"> 公共且免费的、可自动更新并自动检测的 VPN 配置合集，已在俄罗斯联邦境内测试可用（`VLESS` / `VMess` / `Shadowsocks` / `Hysteria2` / `Tuic` / `Trojan` 等）。

用于绕过 Roskomnadzor（RKN）的封锁。

本合集按类别过滤为：黑/白 CIDR 与 SNI 列表。

每个配置都是一个 TXT 订阅，可导入到你需要的任意客户端（`v2rayN`、`Streisand`、`NekoBox`、`Throne` 等）。

每 1–2 小时在发布前，配置都会在位于俄罗斯的服务器上进行自动可用性测试；速度慢或不可用的会被剔除。

这里做的是实际的可达性、延迟、速度测试，而不是简单的自动抓取和去重。11 月 13 日到 12 月 28 日我一直手动完成；12 月 28 日完成了脚本，将检查流程自动化并加速，同时保持同样高质量的“手工”结果。

传统 VPN（OpenVPN、WireGuard 等）很久以前就不太能用了——与你用的是付费订阅还是免费订阅无关。

因此，使用专门验证过在俄罗斯可用的配置很重要，才能随时保持在线。

同样，频繁更新公共配置也很重要，因为它们往往“出现得快、失效也快”。所以我加上了自动更新 + 自动检测/自动测试，让每位在俄罗斯的用户都能随时拿到最新、干净且高质量的 VPN 配置列表。

## 🔴 非俄罗斯用户请注意！

❗❗❗ 如果你不在俄罗斯（中国、伊朗或任何其他国家），请只使用“黑名单”（"BLACK_SS+All_RUS.txt"、"BLACK_VLESS_RUS.txt" 和 "BLACK_VLESS_RUS_mobile.txt"）中的配置。

“白名单”（WHITE）对你不会有帮助，因为“白名单”仅用于绕过俄罗斯境内特定且最强的限制！对其他国家而言，“白名单”几乎不可用、很慢且没有意义。

“黑名单”（BLACK LIST）是“国际通用的 VPN 方案”，包含互联网上可获得的最高速公共配置。

感谢理解！

## <img src="https://raw.githubusercontent.com/igareck/GoldCaviar/refs/heads/main/Files/Download-VPN-configs-banner-ZH-CN.svg" width="350">

  *请在你的 VPN 客户端中开启自动更新！*

<details>

<summary><h3>🧾 黑名单 ⚫</h3></summary>

---

### **手机用 VLESS（订阅内最多 100 个配置）：**

### [BLACK_VLESS_RUS_mobile.txt](https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/main/BLACK_VLESS_RUS_mobile.txt)

  *压缩、轻量的手机 VLESS 黑名单订阅。包含完整 VLESS 订阅中速度最快的 100 个配置。*

<details>
<summary> QR 码 </summary>

  ![BLACK_VLESS_RUS_mobile_QR.png](https://github.com/igareck/vpn-configs-for-russia/blob/main/QR-codes/BLACK_VLESS_RUS_mobile_QR.png)

</details>

### **VLESS 完整版（全部配置）：**

### [BLACK_VLESS_RUS.txt](https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/main/BLACK_VLESS_RUS.txt)

  *黑名单的完整 VLESS 订阅。*

<details>
<summary> QR 码 </summary>

  ![BLACK_VLESS_RUS-QR](https://github.com/igareck/vpn-configs-for-russia/blob/main/QR-codes/BLACK_VLESS_RUS-QR.png)

</details>

### **SHADOWSOCKS+ALL：**

### [BLACK_SS+All_RUS.txt](https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/main/BLACK_SS+All_RUS.txt)

  *黑名单的 ShadowSocks、Hysteria2、Vmess、Trojan 订阅。*

<details>
<summary> QR 码 </summary>

  ![BLACK_SS+All_RUS-QR](https://github.com/igareck/vpn-configs-for-russia/blob/main/QR-codes/BLACK_SS+All_RUS-QR.png)

</details>


</details>

*[点击箭头]*

---

<details>

<summary><h3>🧾 白名单 ⚪</h3></summary>

---

### 手机用 CIDR 订阅（订阅内最多 100 个配置）⚪：

### [Vless-Reality-White-Lists-Rus-Mobile.txt](https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/main/Vless-Reality-White-Lists-Rus-Mobile.txt)

<details>
<summary> QR 码 </summary>

  ![WHITE_VLESS_MOBILE_RUS-QR](https://github.com/igareck/vpn-configs-for-russia/blob/main/QR-codes/Vless-Reality-White-Lists-Rus-Mobile-QR.png)

</details>

*压缩、轻量的手机 CIDR 白名单订阅。包含完整 CIDR 订阅中速度最快的 100 个配置。通过 IP 绕过 CIDR 封锁。VLESS 协议。*


### CIDR 订阅完整版（全部配置）⚪：

### [WHITE-CIDR-RU-all.txt](https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/main/WHITE-CIDR-RU-all.txt)

<details>
<summary> QR 码 </summary>

  ![WHITE-CIDR-RU-all-QR](https://github.com/igareck/vpn-configs-for-russia/blob/main/QR-codes/WHITE-CIDR-RU-all-QR.png)

</details>

*白名单的完整 CIDR 订阅。包含来自不同托管商的所有已知“白”网段。通过 IP 绕过 CIDR 封锁。VLESS 协议。*


### 仅包含托管商：VK、YANDEX、CDNVIDEO、Beeline 的 CIDR 订阅 ⚪：

### [WHITE-CIDR-RU-checked.txt](https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/main/WHITE-CIDR-RU-checked.txt)

<details>
<summary> QR 码 </summary>

  ![WHITE-CIDR-RU-checked-QR](https://github.com/igareck/vpn-configs-for-russia/blob/main/QR-codes/WHITE-CIDR-RU-checked-QR.png)

</details>

*完整 CIDR 订阅按指定托管商过滤后的版本，比完整版更小。该订阅仅包含已验证有效的俄罗斯托管商白网段：VK、YANDEX、CDNVIDEO、Beeline。通过 IP 绕过 CIDR 封锁。VLESS 协议。*


### SNI 订阅 ⚪：

### [WHITE-SNI-RU-all.txt](https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/main/WHITE-SNI-RU-all.txt)

<details>
<summary> QR 码 </summary>

  ![WHITE-SNI-RU-all-QR](https://github.com/igareck/vpn-configs-for-russia/blob/main/QR-codes/WHITE-SNI-RU-all-QR.png)

</details>

*仅通过伪装的域名 SNI 绕过 SNI 封锁。不绕过 CIDR 封锁。VLESS 协议。*

</details>

*[点击箭头]*

---

## <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3bjF5NnEyM21vMjJhd2UxdWphYnQxZGh6bjc1bjBzMG44eDB0Ym03eCZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/dyX9ixfxMpOUGawfdK/giphy.gif" width="50"> 黑名单与白名单有什么区别？该选哪个订阅

**黑名单**：**“未被禁止的都允许”**。*这在 90% 的情况下就是互联网的正常状态。*

**白名单**：**“除非明确允许，否则一律禁止”**。也就是说，你除了 Yandex、VK 等被 RKN 允许的网站之外几乎什么都打不开——甚至 Google.com 和 Gmail 也打不开。

*白名单模式下的互联网限制最严。你只能访问监管方通过其“白名单”允许的资源。比如只允许 Yandex 和 Ozon，那么你只能打开 Yandex 和 Ozon，其他都不行。这类限制目前正在被移动运营商大规模测试和实际使用。*

`⬇   操作顺序   ⬇`

`先确认互联网本身是否能用：打开 Yandex.ru、Gosuslugi、VK、Rutube.ru、Sberbank、Mail.ru、Ozon。如果这些都打不开，说明你的网络本身就不通（完全没有连接），任何配置都帮不了你！这种情况下请先检查设备的网络连接！` 

`如果突然“怎么都加载不了”，通常重置网络连接会有帮助：开启“飞行模式”10–15 秒，然后关闭，再试一次连接——往往就好了！`

### **1)** **先选黑还是白：**  <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3Y3Q4NW94NXo0ZXQwajl1cDRzdHg3ZXFzbWc4aGtzeDA0cGRtNTl2ZSZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/35LH6GkOzEXuw/giphy.gif" width="80">

a) 常规情况下，网络正常（Google 能打开），但你想看被封锁的 YouTube 或玩被封锁的 Roblox —— 使用“黑名单”配置。

**“黑名单”本质上就是普通 VPN，只是用了更现代的协议！** 黑名单通常也是最快的，因为它适用于正常网络环境。

b) **如果除了 Yandex.ru、Gosuslugi、VK、Rutube、Sberbank、Mail.ru 或 Ozon 之外什么都打不开**，说明网络被强限制，此时 **使用“白名单”配置**。

### **2)** **普通黑名单 ⚫：** **VLESS** 或 **SHADOWSOCKS+ALL**

在普通黑名单环境下 ⚫，优先选择最稳的协议 **VLESS**；也可以选择 **SHADOWSOCKS+ALL** 作为替代（不是必须）。电脑或手机都可以，基本通用。

*补充：对我来说，Hysteria2 在电脑有线环境下很好用，但在手机 Wi‑Fi 上经常拒绝工作（而且延迟测试往往要试好几次），原因我没弄明白。VLESS 和 Shadowsocks 在各种设备上通常都没问题。*

*有时 VLESS 在电脑有线完全正常，但在 Wi‑Fi 下延迟测试会不稳定。*

### **3)** **白名单 ⚪：CIDR 订阅 或 SNI 订阅**

  **a)** **“CIDR 订阅（完整版）”或“CIDR 订阅（仅包含托管商：VK、YANDEX、CDNVIDEO）”：**
  
  目前最严的 CIDR“白 IP”封锁主要出现在移动运营商（Megafon、Beeline、MTS、T2、Yota 等），因此我把 `用于穿透移动网络白 IP 列表的 CIDR 配置放进了 TXT 订阅 “CIDR 订阅”`，并在每个配置的备注里标了 `[*CIDR]`。
  
  这些配置当然也能在正常环境下使用（和黑名单一样能用），但不建议这么做！原因很简单：避免把资源压垮，让真正需要的人（在受限地区可能连续数月网络受限）能用到。只有在确实需要时再用 CIDR 配置。

如果某个配置突然不可用，它可能过一段时间又“复活”（原因：服务器过载（免费公开服务器常见）、或临时下线）。不要立刻删除！
  
  **b)** **SNI 订阅：**
  
  用于绕过最轻量的“白 SNI 列表”（仅按域名）封锁的配置，放在 TXT 订阅 **SNI 订阅** 中。它们在每个配置的备注里标为 `[SNI-RU]`，并且所有 SNI 值也都做了标注，方便选择。

## <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3Yml0MndhcDZ6dzFuYjY3aG0yNWowN2Rqbnp1aTV2cXNvb3FvMnluMiZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/MxryCOQuSYVVD0SPyp/giphy.gif" width="40"> 如何在我的设备上使用这些配置？

1) 在设备上添加 VPN 配置，最方便的方法是通过 v2rayN、Throne、v2rayNG、NekoBox、Streisand、Karing 里的 *“订阅”* 或 *“订阅组”*。

2) 复制 Github 的 txt 文件 URL。复制后，在应用中点击“从剪贴板添加”，或使用常见流程：“添加” -> “手动配置” -> 类型选择“订阅” -> 粘贴 txt 文件链接并为订阅命名。

3) 扫描下一部分的订阅 QR 码。更简单：点“添加” -> “扫描 QR 码”，应用会自动创建订阅；你只需要在手机里重命名它，并在列表没有立刻加载时点一下“更新”。
   
   QR 码在订阅链接下面，点击写着“QR 码”的箭头即可展开。
   
4) 如何检查当前哪些配置/服务器是可用的？

   点击整个订阅（顶部的订阅名）或单个配置，通常需要长按弹出菜单。选择——*注意！*——*“真实延迟测试”* 或 *“延迟”*！不要用 “TCP Ping” 或 “ICMP Ping”，它们不能反映 VPN 服务器的真实可用性。能返回绿色数字的就是可用的。数字越小延迟越低，服务器响应越快。

5) 强烈建议至少每天自动更新 2 次（每 12 小时一次），节假日可以更频繁。配置每小时都会更新，因为它们会随时间失效。开启自动更新后，你会一直拿到最新、可用且更“干净”的订阅版本。

7) 配置（尤其是白名单）在“真实延迟”测试中可能不会立刻变绿；很多时候需要连续测试 2–3–4 次才能看到新可用的服务器。

8) 建议手机上安装多个不同客户端：有时不同客户端会“看到”不同的可用服务器，这是因为客户端在检测配置时的设置差异。

你也可以把每个 txt 文件的内容逐条手动导入 v2rayN 等客户端，但订阅的好处是：Github 更新后，订阅会在你的设备上自动更新，无需反复删除/重新复制，流程更简单。

## 🧩 PC 与手机的配置客户端：

###  <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3amtqMmQxOGh0aG0waGk5OGhhNG5odmdob2k1bWc4ejNyZ3E3N2Y2bCZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/xUS4Fp5i6iIn2Y1EYT/giphy.gif" width="25"> Windows/Linux/MacOS

安装官方客户端 v2rayN 或 Throne（Nekoray 的继任者），以“管理员”模式运行，添加配置/订阅并更新，出现列表后执行“真实延迟”测试，测试结束后按延迟排序，选一个绿色且数字最小的条目（回车），最后开启“VPN 模式 / TUN 模式”。

**1)** **v2rayN：**
  
   *推荐 v2rayN：稳定且经验证能一次处理成千上万条不同协议配置（我个人最多 150,000）。它是最通用的客户端之一，可在同一套环境中使用 Xray、Sing-Box、Mihomo。*

   https://github.com/2dust/v2rayN/releases
  
   `v2rayN-windows-64.zip`（Windows）
  
   `v2rayN-linux-64.deb`（Linux / Ubuntu）
  
   `v2rayN-macos-64.dmg`（MacOS）

**2)** **Throne（Nekoray 的继任者，Nekoray 自 2024 年起不再更新）：**

*作为 v2rayN 之后的可用替代客户端推荐。*

   https://github.com/throneproj/Throne/releases

   `Throne-1.0.8-windows64-installer.exe`（Windows）
  
   `Throne-1.0.8-debian-x64.deb`（Linux / Ubuntu）
  
   `Throne-1.0.8-macos-arm64.zip`（MacOS）

**3)** **Karing：**

   https://github.com/KaringX/karing/releases

   `karing_1.2.10.1300_windows_x64.exe`（Windows）
  
   `karing_1.2.10.1300_linux_amd64.deb`（Linux / Ubuntu）
  
   `karing_1.2.10.1300_macos_universal.dmg`（MacOS）
   
**4)** **Singbox-launcher：**

  *值得尝试的新客户端，用于测试 VPN 配置，可与 Sing-Box 配合工作。可以试试，开发者很友好也很活跃。*

   https://github.com/Leadaxe/singbox-launcher/releases

   `singbox-launcher-v0.7.1-win64.zip`（Windows）
  
   `singbox-launcher-v0.7.1-macos.zip`（MacOS）

### <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3aGcxcG8yMGNzOTNmZDE1Z3hob3V3ajU4dmhkdnhsY2doMXFrNXowMyZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/oFSDc1Oq12Ie5NJnmA/giphy.gif" width="20"> iOS —— 在 App Store 使用 Streisand、Shadowrocket、Karing、V2Box 或 v2RayTun。

  推荐 Streisand：其在 App Store 中声明不收集数据，而且包括 DNS 切换在内的功能都能正常工作；加载与使用配置也更稳定。

  由于运行/延迟不稳定，用户不推荐 Happ。

   **1)** `Streisand` https://apps.apple.com/us/app/streisand/id6450534064
   
   *最好的免费 iOS 客户端之一，并声明不收集数据*

   **2)** `Shadowrocket` https://apps.apple.com/us/app/shadowrocket/id932747118
   
   *长时间待机后也不易断连，不收集数据，但为付费应用*

   **3)** `Karing` https://apps.apple.com/us/app/karing/id6472431552
     
   *对 Karing 的评价分化：有人喜欢，也有人遇到连接问题*

   **4)** `V2Box` https://apps.apple.com/us/app/v2box-v2ray-client/id6446814690

   **5)** `v2RayTun` https://apps.apple.com/us/app/v2raytun/id6476628951
  
### <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExODUzYWRwNzNpa3doMDd1bXo4NTlzanJsaTcya3dlNXA4d3c5cnVzNCZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/UQJlZ2OcaCA2RLfGiZ/giphy.gif" width="20"> Android —— 使用 GitHub 上的 v2rayNG 与 NekoBox，或 Google Play 上的 v2Box 与 v2RayTun。

 推荐 v2rayNG：它是我最喜欢的电脑客户端 v2rayN（同一开发者 “2dust”）在 Android 上的对应版本。

 也建议试试 NekoBox，很多用户评价不错。

 由于运行/延迟不稳定，用户不推荐 Happ。

  **1)** `NekoBox` https://github.com/MatsuriDayo/NekoBoxForAndroid/releases

  **2)** `v2rayNG`  https://github.com/2dust/v2rayNG/releases

  **3)** `v2Box` https://play.google.com/store/apps/details?id=dev.hexasoftware.v2box

  **4)** `v2RayTun` https://play.google.com/store/apps/details?id=com.v2raytun.android&hl=en&pli=1

## <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3ZDhxeG02NHlucTdqZGhtejBnb2V5dGpwaDBmcHhobWlsOHQxdWpoYSZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/8L0hXHQkY4o7eyQHJB/giphy.gif" width="30"> 实用信息

⚡ 为什么我要测试这些配置？最开始从 40,000+ 条免费公开配置里做抽样测试时，通过可用性检测的大约只有 700 条（不到 2%）；最终我在这里发布了大约 200 条质量最高、延迟响应好、速度也不错的配置——也就约 0.5%。并不是每个人都有时间去处理动辄上万条配置的“合集”，而真正能用的往往只有几百条。

⚡ 互联网上协议种类很多，但 **最有效**、同时能对抗 Roskomnadzor 的 DPI 与封锁的是 **Vless+Reality**：它能把流量伪装成对无害 HTTPS 网站的访问，让你使用 VPN 对运营商几乎“不可见”。其他协议在排名上会依次递减，因为更容易被识别/去伪装。

⚡ 最稳定的传输：XHTTP、GRPC 和 WS。

⚡ 部分配置可能会因为非我原因随着时间失效，因此列表会周期性更新。

⚡ 如果某条配置突然不能用了，不必急着删除——直接切到列表里的下一条；它过一段时间可能会“复活”。但这不保证！这只是常见现象，很正常。

⚡ 如果运营商阻断你连接 VPN，试试把路由器/电脑/手机上的普通 DNS 换成加密的 DNS-over-HTTPS (DoH) 或 DNS-over-TLS (DoT)。即便不一定能解决问题，也建议你开启 DoH 来提升自己在网络中的隐私。

⚡ 在使用白名单（WHITE）时，一些国外的 DNS-DoH（例如 Google）有时可能不可用。我建议先依次测试 Cloudflare、OpenDNS、Google、Quad9、AdGuard、Dnsforge；如果都不行，再选择 Yandex DoH。若任何 DoH 都无法使用——就关闭 DoH，改回运营商自动 DNS。

<details>

<summary> 🧾 什么是 DNS-over-HTTPS (DoH)，以及如何启用/连接？ </summary>


> *在路由器上：删除/禁用默认的运营商 DNS，改用 DNS-over-HTTPS (DoH)。可能需要先在路由器固件/设置里下载或启用 DoH 客户端。也可以用 DNS-over-TLS (DoT)，但在俄罗斯不推荐，因为经常被封。DNS-over-HTTPS (DoH) 理论上应当 100% 稳定工作。*

> *在手机上有几种方式：*
> 
> - Android（Google Play Store）：下载 “Cloudflare 1.1.1.1 + WARP: Safer Internet”；iOS（App Store）：下载 “1.1.1.1: Faster Internet App”；
> 
> - iOS 没有系统级的基础网络设置入口，DoH 配置通常需要从 Quad9、AdGuard、Dnsforge 等官方站点以独立文件下载（见下方 “公共 DoH 服务器列表”）；
> 
> - Android：进入 设置 ➡️ 网络和互联网（或 Wi‑Fi 和互联网）➡️ “高级” ➡️ “私人 DNS (Private DNS)” ➡️ 选择 “私人 DNS 提供商主机名”，并填写下方公共 DoH 服务器列表中的任意一个地址（见下方 “公共 DoH 服务器列表”）。*

> *在 PC 上：在网卡/网络适配器的 DNS 设置里填入 DoH 服务器。*

> *在 VPN 应用里：在应用的 DNS 设置里填入 DoH 服务器，或从预设列表中选择。已在 iOS 的 Streisand 中发现可稳定工作的 DNS。*

DNS-over-HTTPS (DoH) 本质上还是 DNS，只是通过 HTTPS 加密后变得更私密：它会把 DNS 查询对本地观察者（运营商）加密，从而提升隐私；但 DNS 解析器（Cloudflare/Google 等）仍然能看到你的查询（毕竟查询要通过它转发）。运营商只能看到：你与 DoH/DoT 解析器 IP 的连接（以及流量大小/时间）+ 目标服务器的最终 IP，也就是“访问网站的最终 IP（不含目标域名）”（在缺少 ECH 时，还可能通过 SNI 暴露域名）。通过最终 IP（以及缺少 ECH 时的 SNI）往往可以识别出你访问的是哪个网站。

DoH 也许（但不保证）能绕过一些“连接层面”的限制。如果存在限制，DoH 可能帮你绕过一些简单的 DNS 封锁，但它无法绕过基于 IP/SNI 的封锁或更深层的过滤。

该标准由 IETF 以 RFC 8484（2018）发布，并在 ICANN 的推广协助下落地；而 Google 早在 2016 年就已经开始实现/测试！目标是提升用户的隐私与安全。

</details>

> *点击箭头了解更多*

<details>

<summary> 🧾 公共 DoH 服务器列表（+ 下载 DoH DNS 配置文件）： </summary>

`https://common.dot.dns.yandex.net/dns-query` - *Yandex DNS 基础版。注意：仅在白名单模式下其他 DNS 不可用时建议使用；正常情况下请优先使用下方的 DNS 服务器；*

`https://safe.dot.dns.yandex.net/dns-query` - *Yandex DNS 安全模式。注意：仅在白名单模式下其他 DNS 不可用时建议使用；正常情况下请优先使用下方的 DNS 服务器；*

`https://dns.adguard-dns.com/dns-query` - *AdGuard DNS。来自知名的免费广告与追踪器拦截方案 AdGuard（总部位于塞浦路斯）的 DNS；*

`https://adguard-dns.io/ru/public-dns.html` - *下载 AdGuard 的 DNS 配置文件（iOS）+ 查看其他平台的说明（俄语）；*

`https://dns.quad9.net/dns-query` - *Quad9 DNS 基础版：恶意软件拦截、DNSSEC 校验；无日志政策；总部在瑞士；*

`https://dns11.quad9.net/dns-query` - *Quad9 DNS 扩展版：Secured w/ECS（恶意软件拦截、DNSSEC 校验、启用 ECS）；无日志政策；总部在瑞士；*

`https://docs.quad9.net/Setup_Guides/iOS/iOS_14_and_later_(Encrypted)/` - *下载 Quad9 的 iOS DNS 配置（也可阅读其他平台说明；仅英文，无俄语）；*

`https://dnsforge.de/dns-query` - *来自德国 DNSFORGE（dnsforge.de）的优秀 DNS（免费广告与追踪器拦截）；无日志政策；服务器在德国；站点与说明为德语；*

`https://dnsforge.de/dnsforge-doh.mobileconfig`  - *下载 DNSFORGE.DE 的 iOS DNS 配置文件；*

`https://dns.cloudflare.com/dns-query` - *Cloudflare DNS 基础版；*

`https://security.cloudflare-dns.com/dns-query` - *Cloudflare DNS：拦截恶意软件；*

`https://dns.google/dns-query` - *Google Public DNS（在白名单模式下部分用户可能不可用）；*

`https://doh.opendns.com/dns-query` - *Cisco Umbrella (OpenDNS)。*

</details>

> *点击箭头查看列表*

## 👁️‍🗨️ 运营商能看到什么？以及你上网时到底谁能看到什么？

<details>

<summary> 点击箭头了解更多 </summary>

**总体来说。**

**当你在互联网上时，大致有 5 方会“评估/观察”你的行为：**

**1.** `你自己`

**2.** `你的互联网运营商 (ISP)`

**3.** `你正在访问的网站/搜索引擎`

**4.** `你的浏览器（如果它来自 Yandex、Google 或任何公开公司）`

**5.** `DNS 解析器 (DNS resolver)`

**有些人觉得“运营商什么都能看到”。**

**但这是误解：如果你在网上正确行事，运营商能看到的东西其实很少。**

下面描述的是不使用 VPN 时，访问 HTTPS 网站的“标准工作方式”。不要和明文 HTTP 混淆（HTTP 不加密）。现在都快 2026 年了，纯 HTTP 网站几乎已经不存在了。

**我们逐项拆开说明。**

### 1. 运营商 (ISP).

运营商通常能看到三样东西：你连接的目标网站的最终 IP + 域名 + 发送到用户浏览器的加密 HTTPS 数据包。网站内部发生了什么，只有两方知道——用户和网站本身，仅此而已！这就是 HTTPS 加密的意义。你在 Google 里搜索什么，也只有你和 Google 知道。

**以 YouTube 为例说明：**

你打开我们最爱的 YouTube 去看一个有用的视频教程，点开视频并开始观看。运营商能看到什么？来自 YouTube 的 IP + 域名 “YouTube” + 发往用户电脑的加密 HTTPS 数据包。就这些，不会更多！你具体看了哪些视频、在站内搜索了什么——运营商都看不到，因为这些发生在网站内部，而且都被 HTTPS 加密了。看看地址栏里网站名称左侧的 “https:”——这就是网站使用的加密方式，它为全球数以百万计的人提供数字安全，保护用户免受数字监视。

**以 Google 搜索为例说明：**

你打开 Google.com 去看猫图，输入 *"кот мем неси черешню"*，结果页出现一堆穿围裙的猫的图片。运营商能看到什么？可怕吗？其实什么都看不到。它只看到来自 Google 的 IP + 域名 “Google” + 发往你电脑的加密 HTTPS 数据包。你看的是哪张猫图、猫是什么姿势——运营商都看不到。HTTPS 数据包当然包含图片，但数据包是加密的——因此运营商只能知道你“在 Google 上看东西”，对它而言这是一堆无意义的信息，哪怕超级计算机也无法解密，或者需要 100 年。想象一下 100 年后解出来，里面是 *"кот мем неси черешню"* 或者 “Наталья Морская Пехота”。

**如果你把普通 DNS（例如 1.1.1.1）换成加密的 DNS-over-HTTPS (DoH)，会怎样？**

此时运营商甚至无法直接看到你要连接的域名。使用 DoH 时，运营商看不到明文 DNS 请求，只能看到：你与 DoH/DoT 解析器 IP 的连接（以及流量大小/时间）+ 目标网站的最终 IP。它无法得知最终域名，但往往仍能根据 IP、SNI 和流量行为猜出目标网站：对热门网站更容易，对冷门网站更难，但并非完全不可能。若 DoH 能隐藏最终 IP，那它就能替代 VPN；但不使用 VPN 无法隐藏最终访问 IP。而运营商封站（例如 Youtube）恰恰是按最终 IP 来封的。所以最终访问网站仍需要 VPN。

**DNS 简要总结：**

普通 DNS（例如 1.1.1.1，明文 plain text）会暴露：网站 IP + 域名/SNI + 加密 HTTPS 数据包；

DoH 会暴露：来自网站的最终 IP（+ 行为分析）+ 加密 HTTPS 数据包。

### 2. 网站/搜索引擎.

**网站能看到你在它“地盘”里做什么，并受其总部所在国家的法律约束。**

现代网站、连接以及与用户交换的信息基本都使用 HTTPS 加密（不要与明文 HTTP 混淆）。因此你在网站上的请求只有你和网站可见，而运营商只能看到对它无用的 HTTPS 加密流量，它无法解密。

**关于搜索引擎，我建议两个。用它们搜索时不必担心你问了什么会“触碰审查”：**

> *1. Google 搜索（最流行 + 全球最大的搜索结果覆盖）。总部：美国加州 Mountain View。*

> *2. Duckduckgo 搜索（很流行 + 结果质量优秀，可选择结果地区 + 公司宣称不记录你的搜索隐私）。总部：美国宾夕法尼亚州 Paoli。*

很遗憾我不建议使用 Yandex 搜索。总部在莫斯科。在当前环境下，你的请求会被记录并分析。仅在需要检索“面向俄罗斯索引”的信息时谨慎使用。其他情况下 Google 和 Duckduckgo 足够了。

### 3. 浏览器.

也许有人不知道：浏览器也能看到你的行为。

**目前在俄罗斯有哪些大众且流行的浏览器？**

> a) Yandex Browser。强烈不推荐！如果已安装——删除并换成任何其他浏览器！会记录（log）你的流量；

> b) Google Chrome。也谈不上隐私，同样会记录流量。但对俄罗斯来说比 Yandex 更“安全”，并且属于 Google 生态；

> c) Mozilla Firefox。在大众浏览器里，它的隐私政策相对最好；

这些大众浏览器都有自己的“创建者”，而创建者是公开公司，它们会收集用户数据并能看到请求历史，也就是明文流量（无论它们怎么说）；同时还受其总部所在地的司法管辖/法律约束——自己想想就明白。为了避免浏览器成为“中间人”（"man-in-the-middle"），建议使用隐私向的开源浏览器：它们由独立开发者维护，代码开源（Open-Source），懂行的人可以审计其安全性，例如在 GitHub 上公开的源代码。

**我推荐哪些浏览器用于日常使用与上网冲浪？**

从“最大众”到“最注重隐私”：

**a)** `Mozilla Firefox` —— 如果你想要一个无需折腾的主流选择；同时安装扩展 uBlock origin (ublockorigin.com) 来拦截追踪器与广告。Firefox 引擎浏览器，背后是公开公司 Mozilla。在大众浏览器中隐私政策相对最好。

https://www.firefox.com/en-US/?utm_campaign=SET_DEFAULT_BROWSER

https://github.com/mozilla-firefox/firefox

**b)** `Ungoogled Chromium` —— 基于 Chromium 引擎的开源浏览器，由独立开发者移除了 Google 遥测（telemetry）。经广泛用户验证。适合日常使用，但需要在 GitHub 上手动下载更新版本。建议安装 uBlock origin (ublockorigin.com) 以拦截追踪器与广告。就“日常使用 + 隐私”而言，Ungoogled Chromium 是我认为的黄金平衡点。它的体验几乎与 Google Chrome 一模一样，只是没有 Google 生态。

https://github.com/ungoogled-software/ungoogled-chromium-windows （Windows）

https://github.com/ungoogled-software/ungoogled-chromium-debian （Linux / Ubuntu）

**c)** `Librewolf（定制版 Firefox）` —— 基于 Firefox 引擎的开源浏览器，由独立开发者移除了 Mozilla Firefox 的遥测。我称它为“开箱即用的隐私 Firefox”：下载即用。经广泛验证。使用方便，并支持自动更新（安装时勾选即可）。内置 uBlock origin。Librewolf 很棒，但有时因为半激进的隐私设置，少数流媒体网站可能会打不开或表现异常（虽然很少发生）。

https://librewolf.net/

https://codeberg.org/librewolf

**d)** `Cromite` —— 基于 Chromium 引擎的开源浏览器，移除了遥测，由独立开发者维护。经广泛验证。适合日常浏览，但有一个前提：它对追踪器与遥测的屏蔽非常激进。内置 AdBlock，部分网站可能会出问题。在我这里，Cromite 出现站点兼容问题比上述浏览器更频繁；登录 Google 也非常费劲。但在“浏览器指纹/安全检测”方面，Cromite 的表现是最好的：甚至连电脑硬件都没被识别，更不用说其他数字指纹了，一切都非常“干净”，而且这些都是开箱即用的。

https://github.com/uazo/cromite

这些浏览器不会引起运营商注意，因为运营商只能看到它们使用的内核：也就是 Chromium（Google Chrome、Ungoogled Chromium、Cromite）或 Firefox（Mozilla Firefox、Librewolf）。至于你具体用的是哪一个——只有你自己知道。

### 4. DNS 解析器 (DNS resolver).

使用普通 DNS（例如 1.1.1.1）时，在连接网站之前我们会先向 DNS 解析器发起请求，它能看到我们要去哪里。任何 DNS 解析器的运营方都能看到所有 DNS 查询与响应（你解析了哪些域名）。通过这些记录可以推断你准备连接到哪里。

如果你把普通 DNS 1.1.1.1（明文 plain text）换成加密的 DNS-over-HTTPS (DoH)，会怎样？

此时互联网运营商将无法看到你连接的域名/网站名称。运营商只能看到：你与 DoH/DoT 解析器 IP 的连接（以及流量大小/时间）。

但 DNS 解析器仍然能看到域名 + IP，因为你的 DNS 请求仍然要经过它；即使是加密请求，它也会接收并解密。

### 结论.

**想在互联网空间里更自由、更有底气地上网，这些会有帮助：**

`DNS-OVER-HTTPS (DoH)`

➕

`正确的搜索引擎：Google 或 Duckduckgo`（不要用 Yandex）

➕

`安全/独立浏览器：至少用 Mozilla Firefox；更注重隐私可用 Librewolf、Ungoogled Chromium、Cromite`（千万不要用 Yandex 浏览器）

---


**信息会随着时间持续补充与完善。**

</details>

##  

## <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExZXJoeTEzZ3FtcGNrdmo2ZnFocDUwOTVvYmdjNWRnaWMwNHozMWN1YiZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/ZcdZ7ldgeIhfesqA6E/giphy.gif" width="25"> 分享订阅！ 

## 自由且负责任地使用互联网！

## 🔖 许可证

许可证为 GPL-3.0。可在文件 [`LICENSE`](LICENSE) 中查看许可证全文。

## <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExM2wwMmJ3bDZvMWV2b2JraXZ4ZWk2Y2I5ODYyZ2M2aG5mMHc5ZW81ZyZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/ME8P6ce7Mn3gnRbird/giphy.gif" width="30"> 支持作者

**本项目为非商业项目，基于作者的个人热情与兴趣。**

**如果你愿意支持作者，可以通过加密货币转账的方式。**

**资金将用于继续维护并发展项目。**

**提前感谢所有关心与支持的人！**

<details>
<summary><h3> 💳 钱包地址 💳 <h3></summary>

请选择任意你方便的加密货币并复制对应地址。请务必只转到与币种匹配的钱包地址，否则资金将会丢失。

| № | 币种 | 地址 |
|--|--|--|
| 1 | `Bitcoin (BTC)` | `18vVz4UzFdxCGnCnAzJtXv6ECsh32ff9VT` |
| 2 | `基于_Ethereum(ETH)_的代币: Ethereum (ETH), USDC (ETH), USDT (Ethereum ERC-20), Shiba Inu (SHIB)` | `0xfc668016a823f3EE53d2F3009547666A2BdaBd32` |
| 3 | `基于_Tron_(TRX)_的代币: Tron (TRX), USDC (TRX), USDT (TRX)` | `TLnzF6NYgyqBHJMM2qByMXEHLBWNhBWcJ1` |
| 4 | `基于_Toncoin_(TON)_的代币: Toncoin (TON), Notcoin (NOT), Hamster Combat (HMSTR), USDT (USDT-TON)` | `EQAGbSuckE93yiACSENJGo8WuRq474Wba1J4yCF1Q59xsL0k` |
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

> *点击箭头展开列表*

##  <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3ZmJ4anB6YjR3aWJpaTRvYzUzejY1dmwzN2c2M3c2NnV0MXUwM3RrcyZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/acN91ftm1tJX23OOBx/giphy.gif" width="60"> 联系邮箱：igareck@proton.me

## 👀 访客数量
<img src="https://komarev.com/ghpvc/?username=igareck&label=Visitors&color=0e75b6&style=flat" alt="Visitor Count" /> <img src="https://visitor-badge.laobi.icu/badge?page_id=igareck.visitor-badge&left_color=black&right_color=green&left_text=Cyber+Hits" alt="Cyber Hits"/>  
</div>

## <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExa2RkeXZzdDl1Y3g4dW1xcjFxc2xsMHVsZ2RiY243OHJodjd0cHQ1NSZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/qXp82ZL3eZbbTUrLyy/giphy.gif" width="30"> <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExa2RkeXZzdDl1Y3g4dW1xcjFxc2xsMHVsZ2RiY243OHJodjd0cHQ1NSZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/qXp82ZL3eZbbTUrLyy/giphy.gif" width="30"> <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExa2RkeXZzdDl1Y3g4dW1xcjFxc2xsMHVsZ2RiY243OHJodjd0cHQ1NSZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/qXp82ZL3eZbbTUrLyy/giphy.gif" width="30">
<a href="https://www.star-history.com/#igareck/vpn-configs-for-russia&type=date&legend=top-left"><picture><source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=igareck/vpn-configs-for-russia&type=date&theme=dark&legend=top-left" /><source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=igareck/vpn-configs-for-russia&type=date&legend=top-left" /><img alt="Star History Chart" src="https://api.star-history.com/svg?repos=igareck/vpn-configs-for-russia&type=date&legend=top-left" /></picture></a>

## <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3Z25rOXRoeW1xODR1dWh2b3UycTd6YnB0Y2hlMTZtaDluZW1uNnl4ZyZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/CeYEKonyFQyzWhxmvd/giphy.gif" width="40"> 免责声明

> *作者并非上述 VPN 配置的拥有者/开发者/提供方。这是一份独立的信息性综述与测试结果。*
>
> *本文并非 VPN 广告。所有材料仅用于信息目的，并且仅面向那些在其所在国家/地区该信息合法的读者（至少用于科研/学习目的）。如果你不应该阅读这些内容——请立刻关闭此页面！*
>
> *作者没有任何意图，也不鼓励、不支持、不为在任何情况下使用 VPN 或任何其他程序进行辩护。*
>
> *任何对这些 VPN 配置的使用所产生的后果，均由使用者自行承担。*
>
> *免责声明：作者不对第三方的行为负责，也不鼓励任何违法使用 VPN 的行为。*
>
> *作者不对已发布数据的准确性、完整性与真实性负责。所有巧合纯属偶然。所有信息按“原样”提供，可能与现实不符。*
>
> *请遵守当地法律法规使用。*
>
> *仅将 VPN 用于合法目的：例如保障你在网络中的安全与受保护的远程访问；在任何情况下都不要将此技术用于绕过封锁。*
>
> *本项目为非商业、免费项目；所有展示的“支付”信息都是在互联网空间中随机找到并按“原样”复制，仅用于示例展示，并不属于作者。*
>
> *建议：关掉这个页面，删掉你电脑上的所有 VPN，在所有设备上安装 MAX 和 Yandex，这样“停车场里都能满格”，并且只使用你的互联网运营商允许的网络资源……你懂的。*
