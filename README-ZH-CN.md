<div align="center">
  
![maxresdefault](https://cdn.jsdelivr.net/gh/igareck/GoldCaviar@refs/heads/main/Files/vpn-configs-for-russia-4.svg)

</div>

# <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNTljeGk4d3lzZnU3Mm1peDBienFpbmEyb3JmaDB5N21tMW9oczIwdyZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/8p1WPEOeDWFCksfe18/giphy.gif" width="45"> 可在俄罗斯联邦使用的免费 VPN 配置

[![访问者计数](https://komarev.com/ghpvc/?username=igareck&label=Visitors&color=0e75b6&style=flat)](https://github.com/igareck)
[![星标](https://img.shields.io/github/stars/igareck/vpn-configs-for-russia?style=flat)](https://github.com/igareck/vpn-configs-for-russia/stargazers)
[![问题](https://img.shields.io/github/issues/igareck/vpn-configs-for-russia?style=flat&color=0e75b6)](https://github.com/igareck/vpn-configs-for-russia/issues)
[![最近提交](https://img.shields.io/github/last-commit/igareck/vpn-configs-for-russia?style=flat&color=0e75b6)](https://github.com/igareck/vpn-configs-for-russia/commits/main/)
![开源之爱](https://img.shields.io/badge/Open%20Source-%E2%9D%A4-0e75b6)
[![电子邮件](https://img.shields.io/badge/Email-igareck%40proton.me-0e75b6?logo=gmail&logoColor=white)](mailto:igareck@proton.me)

[![在 Patreon 支持我](https://img.shields.io/badge/Support_me_on-Patreon-f96854?style=for-the-badge&logo=patreon&logoColor=white)](https://www.patreon.com/igareck/shop)
[![Telegram](https://img.shields.io/badge/Join_me_on-Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/igareq)

**🌐 Язык: [Русский](README.md) | 🌐 Language: [English](README-EN-US.md) | 🌐 语言: [中文](README-ZH-CN.md) | 🌐 زبان: [فارسی](README-FA-IR.md)**

<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExa2RkeXZzdDl1Y3g4dW1xcjFxc2xsMHVsZ2RiY243OHJodjd0cHQ1NSZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/qXp82ZL3eZbbTUrLyy/giphy.gif" width="20"> 公共且免费的 VPN 配置合集，可自动更新、自动检测，并已在俄罗斯联邦境内测试可用（`VLESS` / `Trojan` / `Shadowsocks` / `Hysteria2` / `VMess` / `TUIC` 等）。

**用于绕过 Roskomnadzor（RKN）的封锁。**

本合集按类别分为基于 CIDR 和 SNI 的黑名单与白名单。

每个配置列表均以 TXT/YAML/JSON 订阅形式提供，可导入你选择的客户端（`Karing`、`Clash Verge Rev`、`Clash Mi`、`v2rayN`、`Happ`、`Streisand`、`Throne` 等）。

发布前，所有配置都会在俄罗斯境内的服务器上每 2–4 小时自动测试一次。速度过慢或无法使用的配置会被过滤；具体间隔取决于订阅类型。

检测内容包括实际可达性、延迟和速度，而不只是自动汇总与去重。2025 年 11 月 13 日至 12 月 28 日期间，整个流程均由我手动完成。12 月 28 日，我完成了一套自动化脚本，在保留此前人工筛选质量的同时，大幅加快了检测速度。

为持续提高订阅质量，该脚本也会定期接受检查与改进。

OpenVPN 和 WireGuard 等传统 VPN 协议早已表现得不够稳定，无论服务是免费还是付费。

因此，如果你希望保持联网，使用专门在俄罗斯境内验证过的配置十分重要。

公共配置也需要频繁更新，因为它们通常出现得快、失效得也快。自动更新和检测可确保俄罗斯用户始终获得最新、优质且没有无效条目的 VPN 配置列表。

## 🔴 非俄罗斯用户请注意！

<details>
<summary><em><code> 点击箭头 </code></em></summary>

❗❗❗ 如果你不在俄罗斯（中国、伊朗或任何其他国家），请只使用“黑名单”（"BLACK_SS+All_RUS.txt"、"BLACK_VLESS_RUS.txt" 和 "BLACK_VLESS_RUS_mobile.txt"）中的配置。

“白名单”（WHITE）对你不会有帮助，因为“白名单”仅用于绕过俄罗斯境内特定且最强的限制！对其他国家而言，“白名单”几乎不可用、很慢且没有意义。

“黑名单”（BLACK LIST）是“国际通用的 VPN 方案”，包含互联网上可获得的最高速公共配置。

感谢理解！

</details>

---

<h2><code> 主题 №1 </code></h2>

### 请关注 Telegram 频道: https://t.me/igareq <img src="https://thumb.wikimedia.org/wikipedia/commons/thumb/8/83/Telegram_2019_Logo.svg/960px-Telegram_2019_Logo.svg.png" width="25" align="absmiddle">

---

<h2><code> 主题 №2 </code></h2>

### 亲爱的朋友们！
### 由于俄罗斯可能封锁 GitHub，请保存镜像链接！ 

<details>
<summary><em><code> 点击箭头查看详情 </code></em></summary>

㋡

镜像将与主频道同步更新。 

**封锁不会影响 GitHub 本身；原始仓库在任何情况下都将继续工作！**

我强烈建议现在就在您的客户端中将原始 RAW 链接替换为任一镜像的订阅 `https://raw.githubusercontent.com/` 的 RAW 链接：见 `table` 或章节 `MIRRORS 🪞`！ 

**如何从镜像获取 RAW 文件？** 在那里找到您感兴趣的同名 txt 订阅，点击链接进入，在上方找到标有 `RAW`、`Open Raw`、`View Raw` 或 `Source` 的按钮，点击该按钮，然后从地址栏复制链接。**或者直接使用章节 `MIRRORS 🪞` 的现成链接。**

**原始 GitHub README 描述中的订阅和二维码已被替换为代理 `GitHack-RAW` 上的 `GitHub-RAW` 和 `CDN.jsDelivr`**。

镜像列表：

| | | |
|---:|---|---|
| **GitLab** | https://gitlab.com/igareck/vpn-configs-for-russia/ | Git 镜像 / 开放核心 SaaS |
| **Codeberg** | https://codeberg.org/igareck/vpn-configs-for-russia | Git 镜像 / FOSS |
| **Gitea** | https://gitea.com/igareck/vpn-configs-for-russia | Git 镜像 / 基于 FOSS |
| **SourceHut** | https://git.sr.ht/~igareck/vpn-configs-for-russia | Git 镜像 / FOSS |
| **Bitbucket** | https://bitbucket.org/igareck/vpn-configs-for-russia/ | Git 镜像 / 商业 |
| **GitHack** | https://raw.githack.com/| 实时 RAW 代理 |
| **Yandex+BB** | https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/WHITE-CIDR-RU-all.txt&lang=de-de | 白名单 RAW 代理 Yandex+Bitbucket |
| | | |

✦ **GitLab/Codeberg/Gitea/SourceHut/Bitbucket** - 这些是 GitHub 的完整副本，所有信息都在其中（README 和订阅），与原版完全相同，并且大多数 **无需 VPN 即可使用**。 

✦ **GitLab** - 所有镜像中最好的。

✦ **GitHack** 用于 RAW 链接的镜像 - 即使那些在访问其他镜像时看到“您当前正在从被屏蔽的 IP 地址或国家/地区访问”的消息的人也能使用。

✦ **Yandex+Bitbucket** 用于 RAW 链接的镜像 **在白名单模式下**。 

**请注意，只有 Yandex+Bitbucket 组合才能正常工作**，所有其他与 Yandex 的连接都会破坏配置！

**通过 Yandex+Bitbucket 下载的配置的性能已由订阅用户在 Karing、Clash Mi 和 v2rayN/v2rayNG 的无人机威胁期间的网络限制下测试。** 

> 关于在俄罗斯的 GitHub 类站点上发布仓库副本的问题很多。
> 
> 让我澄清：直接或间接推动在俄罗斯联邦的审查和/或从属于 Roskomnadzor 的网站，由于客观原因，非常不适合列入此仓库官方镜像列表。如果你想以白名单模式获取配置，请使用可用的代理链接 Yandex+Bitbucket（章节 `MIRRORS 🪞`）。Yandex+Bitbucket 正好是规则的例外，它允许你不直接将仓库资源放到不希望出现的网站上，但即使在无人机威胁期间的网络限制下也能下载它们！

</details>

---

<h2><code> 主题 №3 </code></h2>

### 对于第一次来到这里且不清楚一开始选择哪个客户端和 VPN 订阅的人

<details>
<summary><em><code> 点击箭头查看详情 </code></em></summary>

㋡

```diff
请注意！

负载和封锁最严重的时段是在白天。
白天抗封锁能力最强的是两个订阅：
BLACK_SS+All_RUS（标准格式或 Clash 格式），尤其是 TOR BRIDGES！
由于负载增加以及大规模封锁不断加强，
自 9 月 1 日起，其他订阅的运行变得非常不稳定。
对于其他所有订阅（以及总体上的 VPN），目前最佳使用时段
是莫斯科时间 23:00 至次日 11:00。根据个人观察，
公共配置在此期间的表现更加稳定且更容易预测。
```

**仅推荐带有自动健康检查的客户端/订阅组合！**

在本仓库中，所有订阅格式都分为“通用”（仅代理列表）和“关联特定客户端”（已内置自动健康检查和路由）。

✦ **`通用/标准格式（仅代理列表）：`** 

**在 Karing、Shadowrocket、Exclave 和 V2Box(iOS) 上稳定工作，这些客户端自身配置了自动健康检查功能。**

✦ **`内置自动健康检查的Clash格式（我推荐它作为最稳定的选项）：`** 

**可通过任意Clash/Mihomo客户端使用（Clash Verge Rev / Clash Mi / ClashMetaforAndroid等）。**

✦ **`针对带内置自动健康检查的独立客户端的特殊格式：`**

**可通过v2rayN / v2rayNG / Streisand / Happ / v2RayTun使用。** 

*v2rayNG/Streisand/Happ/v2RayTun/V2Box客户端的订阅是一键单连，自动选择服务器；不会像其他订阅那样有配置列表。v2rayN - PolicyGroup自动配置，但仍附带完整的服务器列表。* 

*如果具备自动健康检查的订阅在使用过程中突然断开，有时发生在配置失败时，为了不等待自动化，只需重新启动连接，等待5-20秒，应用会重新选择最佳代理，连接将再次出现。如果在Mihomo客户端工作，可以从列表中手动选择（更方便），无需等待自动化和完整重连。*

| | |
|:---|:---|
| **用于黑名单** | **用于白名单** |
| **标准格式** **[BLACK_VLESS_RUS_mobile.txt](https://raw.githack.com/igareck/vpn-configs-for-russia/main/BLACK_VLESS_RUS_mobile.txt)**（移动端黑名单，150个配置）+ **Karing（PC/iOS/Android）、Exclave（Android）、Shadowrocket（iOS）或V2Box（iOS）** | **通用/标准格式** **[Vless-Reality-White-Lists-Rus-Mobile.txt](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Vless-Reality-White-Lists-Rus-Mobile.txt&lang=de-de)**（移动端白名单，150个配置）或 **[WHITE-CIDR-RU-all.txt](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/WHITE-CIDR-RU-all.txt&lang=de-de)**（完整白名单）+ **Karing（PC/iOS/Android）、Shadowrocket（iOS）或V2Box（iOS）** |
| 或 | 或 |
| **Clash格式** **[BLACK_VLESS_RUS_mobile_clash_global.yaml](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/Clash/GLOBAL/BLACK_VLESS_RUS_mobile_clash_global.yaml)**（移动端黑名单，150个配置）+ **Clash/Mihomo客户端** | **Clash格式** **[Vless-Reality-White-Lists-Rus-Mobile-clash-global.yaml](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/Clash/GLOBAL/Vless-Reality-White-Lists-Rus-Mobile-clash-global.yaml&lang=de-de)**（移动端白名单，150个配置）或 **[WHITE-CIDR-RU-all-clash-global.yaml](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/Clash/GLOBAL/WHITE-CIDR-RU-all-clash-global.yaml&lang=de-de)**（完整白名单）+ **Clash/Mihomo客户端** |
| | |

TOP 150黑名单和白名单订阅轻便、优化且兼容大多数客户，是移动设备或首次使用的最佳选择。

**如果移动黑名单订阅不稳定，请尝试全套 （大约从 11:00 到 23:00，BLACK_SS+All_RUS 订阅的运行效果最佳）：**

 **[BLACK_SS+All_RUS.txt](https://raw.githack.com/igareck/vpn-configs-for-russia/main/BLACK_SS%2BAll_RUS.txt) 或 [BLACK_SS+All_RUS_clash_global.yaml](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/Clash/GLOBAL/BLACK_SS%2BAll_RUS_clash_global.yaml)** 

**[BLACK_VLESS_RUS.txt](https://raw.githack.com/igareck/vpn-configs-for-russia/main/BLACK_VLESS_RUS.txt) 或 [BLACK_VLESS_RUS_clash_global.yaml](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/Clash/GLOBAL/BLACK_VLESS_RUS_clash_global.yaml)**

**适用于 Karing 或 Mihomo 客户。**

您将找到所有订阅的链接和二维码，以及适用于 PC/路由器/iOS/Android 的所有客户端列表，并附有详细说明。

</details>

---

<h2><code> 第4话题 </code></h2>

**注意那些没有白名单（无限制有线和移动网络）的用户，如果您在家或工作需要免费的 VPN 黑名单替代方案 - 使用捆绑** <img src="https://upload.wikimedia.org/wikipedia/commons/d/df/Tor_Browser_icon_%28New%29.png" width="20" align="absmiddle"> `Tor Bridges` **+** `Tor 客户端 OnionHop V3` 或 `OnionFruit Tor 客户端` 或 `Tor 浏览器` **（详情见章节** `黑名单与白名单的区别` ➞ `常规黑名单` ➞ `TOR BRIDGES`）。

**如果 VPN 黑名单突然不稳定，则使用此方法。在下行时总能起作用。根据观察，TOR 比 VPN 稳定多倍；连接可以持续多天。**

**本仓库中的所有 [TOR BRIDGES](https://github.com/igareck/vpn-configs-for-russia/tree/main/TOR-BRIDGES) ，均每 4 小时测试一次，专门用于在俄罗斯工作，会检查其延迟、速度和完全可用性。** 不要与普通的 ping 混淆；它不显示实际性能。

自 9 月 1 日起，VPN 连接在白天一直非常不稳定，尤其是在莫斯科时间上午 11 点到晚上 11 点之间。情况最糟糕的通常是下午 1 点左右：此时大量公共 VPN 节点会同时变得无法连接，其中 VLESS 节点受到的影响最为严重。通常要到晚上 7—8 点以后，情况才会开始逐渐恢复。目前，VPN 只有在夜间相对稳定，大约从晚上 11 点到次日上午 11 点。

因此，白天请改用 TOR，它在任何时段都能保持稳定！

---

<h2><code> 主题 №5 </code></h2>

### 关于 DNS 的重要说明

<details>
<summary><em><code> 点击箭头查看详情 </code></em></summary>

㋡

**客户端中的 DNS**

最近我遇到了一些配置，虽然通过了测试、连接成功，但随后拒绝工作。

也就是说，它们的 ping 成功，但流量随着时间停止传输。

这一切都通过客户端中的 DNS 设置解决。

我给你举个例子：

<details>
<summary><strong><code> Karing </code></strong> ⬅ 点击打开 </summary>

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
<summary><strong><code> v2rayN </code></strong> ⬅ 点击打开 </summary>

㋡

```diff
Path: "Settings" -> "DNS Settings" -> "Basic DNS Settings"

Replace the contents of "Remote DNS" (Remote DNS) per line:

https://dns.google/dns-query,https://dns.quad9.net/dns-query,https://dns.adguard-dns.com/dns-query,https://freedns.controld.com/p0,https://dns.mullvad.net/dns-query,https://cloudflare-dns.com/dns-query,https://doh.opendns.com/dns-query
```

</details>

<details>
<summary><strong><code> Exclave </code></strong> ⬅ 点击打开 </summary>

㋡

```diff
In the section "☰" → "Settings" find the line/item called "Remote DNS".
Instead of the default value, put: https://dns.google/dns-query
```

</details>

▷ 对于 **`Shadowrocket`**，在 **单独为每个客户端的说明** 部分下载配置文件。

▷ 对于特殊客户端订阅 **`Clash-Mihomo / v2rayNG / Happ / Streisand / V2rayTun / V2Box`**，无需配置任何内容，**所有内容都带有自动订阅**。

━━━

**设备上的 DNS（路由器、电脑或手机）**

将设备上的提供商/自动 DNS 替换为加密的 DNS-over-HTTPS (DoH)。 

**确实存在实际案例（而且越来越多），当在设备/路由器上安装 DoH 时，可以解决配置的性能问题，连接中断发生的频率大大降低，流量变得更加稳定和可预测。**

推荐的 DNS-over-HTTPS (DoH) 列表请查看 README 部分 **DNS-over-HTTPS** 的最底部。

**在 2026 年 8 月 17 日至 8 月 23 日经历一波大规模 Roskomnadzor 封锁后，俄罗斯开始对 DNS-over-HTTPS (DoH) 实施限制**。但这并不意味着现在所有的国外 DoH 完全不可用。它们仍然可用，只是现在每个运营商选择性地与自己的 DoH 配合使用，而不像以前那样全部可用。 

例如，一个提供商可能只有 Google DoH，而另一个可能有 Cloudflare 和 OpenDNS DoH，而 Quad9 DoH 在我这里完全无法使用。只能通过与运营商核实来确定。我们连接 DoH——开启网络：浏览器能加载网站——说明 DoH 正在工作，无法加载——意味着我们需要换下一个 DoH 并继续检查。

花一些时间找到可用的 DoH，它会增加连接的稳定性。

━━━

**在白名单模式（无人机威胁期间的网络限制）期间，所有国外 DNS 提供商均无法使用（没有 Google、没有 Cloudflare、没有 Quad9、没有阿里巴巴、没有 OpenDNS）。在这种情况下，使用提供商的自动 DNS 或 Yandex 的 DNS/DNS-over-HTTPS。否则，白名单的 VPN 配置将根本无法工作。**

━━━

**DoH 并不是万能药或解决所有问题的魔法，但在设置网络和客户端时，它是一个非常重要的细节。**

</details>

---

<h2><code> 第六话题 </code></h2>

### 这是对所有在智能手机上使用 VPN 的人都很重要的消息

**Habr 上发布了一篇关于基于 xray/sing-box 的移动客户端关键漏洞的非常重要的分析，并整理了最安全客户端的小型排名。** 

**对俄罗斯应用中已识别的监控方法进行了分析。**

**我们还为您的设备制定了最低-最高安全计划，以确保 VPN 能够正常工作。**

<details>
<summary><em><code> 点击箭头查看详情 </code></em></summary>

㋡

Habr 上发布了一篇关于基于 xray/sing-box 的 **移动** 客户端关键漏洞的非常重要的分析。问题的本质是，客户端在没有授权的情况下启动本地 SOCKS5 代理，而恶意应用（即任何俄罗斯应用：MAX、Yandex、Wildberries、Ozon、Gosuslugi、Rzd、任何银行软件（Sber、T-Bank）、Kaspersky 以及其他大型俄罗斯 IT 公司）在 **同一设备** 上可以绕过 `VpnService` 连接到该代理，确定您的出口 IP，从而传递您的代理/服务器。作者还单独指出，`private space`、`Shelter`、`Island` 和按应用分割隧道在这里无效。

条目： https://habr.com/ru/articles/1020080/

镜像：https://web.archive.org/web/https://habr.com/ru/articles/1020080/

在线发布了一份PDF，描述了在俄罗斯应用中发现的监控方法：

PDF 文件：**[Russian_apps_spy_for_vpn.pdf](https://github.com/igareck/GoldCaviar/blob/main/Files/Russian_apps_spy_for_vpn.pdf)**

**哪些客户解决了文章作者指出的问题** @runetfreedom **在 Habré 上（已验证）：** 

1. **Karing** ✅ - 增加了 **手动授权**（针对混合类型入站连接添加授权设置（设置-混合）），正如作者在 Habr 上的文章é中提到的。Android 已在 Github 发布修复，iOS 在 AppStore 发布。所有客户端均已测试！**开发者解决了该问题！**

2. **Throne** ✅ - 在更新中 **增加了入站授权支持**。仅 PC 版本。我已检查设置中有“入站授权用户名/密码”。**开发者解决了该问题！**

3. **Happ** ✅ - **在安卓上移除了 HandlerService；在安卓、iOS 和 PC 版本上，已实现“授权入站”。**

4. **v2rayNG** ✅ - **安卓版本设置中增加了“本地代理用户/密码”**。在 **PC 版本**（**v2rayN**❌）中该问题尚未解决。

5. **v2raytun** - 在 **安卓** ✅ 为本地 socks5 代理增加了登录/密码功能，对于 **iOS** ❌ 未做任何处理。

6. **Exclave** ✅ - **安卓版本设置中增加了“本地代理用户/密码”**（Exclave 没有其他平台）。

7. **Hiddify** ❌ - 最近一次更新是在 3 月 5 日。**本地主机端口授权问题尚未解决。**

8. **Streisand, NekoBox, V2Box** ❌ - 我在更新日志或应用程序设置中都没有看到作者针对该问题的解决方案。**本地主机端口授权问题尚未解决。**


**实践中的结果如下：**

✦ 如果设备上有不可信/恶意软件（也就是任何俄罗斯应用：MAX、Yandex、Wildberries、Ozon、Gosuslugi、Rzd、VK、任何银行软件（Sber、T-Bank）、Kaspersky 及其他大型俄罗斯 IT 公司），你不能再认为你的代理输出 IP 是“默认受保护”的；

✦ 私人空间和分流隧道并不能提供许多人期望的保护；

✦ 如果你的智能手机上同时安装了 VPN 客户端和一堆俄罗斯软件，这是一种糟糕的安全模式；

✦ 如果你的智能手机或 PC 上根本没有俄罗斯软件，那么你无需担心，这些漏洞不会影响你。

**现在应该做什么**

**最低计划：**

✦ 如果你的智能手机或电脑上有任何俄罗斯软件 - **仅使用 Karing (Android+iOS+PC)、Throne (PC)、v2rayNG (Android)、v2rayTun (Android)、Happ (Android+iOS)，并确保在设置中为“Karing 的设置-混合”(Settings-Mixed)、Throne 和 Happ 的“入站授权”(Inbound Authorization)、v2rayNG 和 v2rayTun 的“本地代理用户名/密码”(Local proxy user/password) 设置登录/密码**；

✦ 监控其他客户端的更新并立即安装；

✦ 使用分流路由 `geoip:ru -> 直连`, `other -> 代理`；

✦ Android 的选项：完整的第二配置文件，并在它们之间切换。 

谷歌官方说明： https://support.google.com/android/answer/2865483?hl=ru

`主配置文件` — VPN/Tor、浏览器、GitHub、Telegram、邮件、密码；

`第二个俄罗斯配置文件` - 银行、国家服务、Yandex、Ozon、WB、俄罗斯铁路和其他俄罗斯软件。

但这不能保证防止本地主机泄漏。这比在同一账户中隔离应用程序的数据隔离更好，但仍然无法隔离用户之间的回环/本地主机。一个不活跃的用户可以在后台继续工作，而另一个用户处于活跃状态。在单一设备内，这是迄今为止最好的保护。

✦ 你需要理解，这不是“完全保护”，只是减少“损害”。

**最大计划（在这里隔离保证接近 100%）：**

✦ **主移动设备**：任何非俄罗斯应用程序、VPN、Tor 和敏感任务；

✦ **附加移动设备**：用于俄罗斯软件，购买最便宜的二手手机用于运行 RU 应用程序。

✦ **电脑**：不要安装俄罗斯应用程序（完全不安装），或者仅在虚拟机( VirtualBox )中安装。 

现在任何RU应用都应被视为潜在恶意应用，并且应隔离！

✦ **电脑上的浏览器**：访问俄罗斯网站时，选择带有 uBlock Origin 扩展并启用“阻止外部入侵局域网”过滤器的独立浏览器，或者在虚拟机中运行。

**主要结论：**
如果你使用公共配置文件或自己的服务器，假设在最坏情况下，你的输出 IP 会被发现。现在需要更严格地建立基础设施和使用习惯：更新、纯净/分离的设备、分离路由、分离输入和输出 IP（对于服务器所有者）、隔离恶意软件。

</details>

---

## `必须阅读！`

**如果你想成功启动配置，下载正确的订阅并了解各项内容，请仔细阅读以下部分！** 

**你将在下面了解到：** 

`1. 黑名单和白名单的区别；`

`2. 订阅的类型以及它们之间的差异。`

`请注意，Readme 中有备用链接（镜像），即使在白名单模式下也可使用；`

`3. 需要下载的应用程序、下载位置以及使用方法；`

`4. 哪些应用程序和订阅的组合可实现配置的最流畅和自动化操作；`

`5. 关于网络如何工作、你在线时提供商能看到什么、哪些浏览器更好等其他有用的信息（通俗易懂）；`

**此外，请阅读仓库顶部的“问题”部分，提问、评论并分享经验。**

**这里发布的配置都是经过实际检查发布的，也就是说，大多数在发布时都是可用的！**

**每个订阅大约每 2-4 小时更新一次，以保持其有效性！**

---

## <img src="https://raw.githubusercontent.com/igareck/GoldCaviar/refs/heads/main/Files/Download-VPN-configs-banner-ZH-CN.svg" width="350">

 ✦ *订阅名称（蓝色高亮）可点击，并包含指向RAW订阅格式的链接！*

 ✦ *该仓库包含适用于单个客户端的 **标准**、**Base64**、**Clash/Mihomo 及特殊格式**（Export 文件夹）。*

 ✦ *在您的VPN客户端中启用每1小时自动更新！*

 ✦ *对于黑名单：如果您身处俄罗斯并且需要 RU-DIRECT 路由（俄罗斯网站不经过 VPN，直接连接）：*

 * *请前往俄语版 README 中对应的 "Download VPN-configs" 部分，那里提供了带 RU-DIRECT 路由的链接。*
 
 * *或者在 Export 文件夹中查找 RU-DIRECT 配置。*

---

<details>

<summary><h2> 🧾 <code> 黑名单 ⚫ </code></h2></summary>

---

### 移动端 TOP 150（订阅中速度最快的 150 个配置，混合协议）：

<details>
<summary><strong><code> 打开 </code></strong></summary>

㋡

| | | | | | | | | | | |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **订阅格式** | **通用（标准格式）** | **通用（Base64 格式）** | **Clash/Mihomo（PC/iOS/Android）** | **v2rayN（PC）** | **v2rayNG（Android）** | **Streisand（iOS）** | **Happ（PC/iOS/Android）** | **V2Box（Android）** | **v2RayTun（Android）** | **v2RayTun（iOS）** |
| **链接** | [BLACK_VLESS_RUS_mobile](https://raw.githack.com/igareck/vpn-configs-for-russia/main/BLACK_VLESS_RUS_mobile.txt) | [BLACK_VLESS_RUS_mobile](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/Base64/PROXIES_ONLY/BLACK_VLESS_RUS_mobile_base64.txt) | [BLACK_VLESS_RUS_mobile](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/Clash/GLOBAL/BLACK_VLESS_RUS_mobile_clash_global.yaml) | [BLACK_VLESS_RUS_mobile](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/v2rayN_PC/BLACK_VLESS_RUS_mobile_v2rayN.txt) | [BLACK_VLESS_RUS_mobile](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/v2rayNG_Android/GLOBAL/BLACK_VLESS_RUS_mobile_v2rayNG_global.json) | [BLACK_VLESS_RUS_mobile](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/Streisand_iOS/GLOBAL/BLACK_VLESS_RUS_mobile_Streisand_global.json) | [BLACK_VLESS_RUS_mobile](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/Happ/GLOBAL/BLACK_VLESS_RUS_mobile_Happ_global.json) | [BLACK_VLESS_RUS_mobile](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/V2Box_Android/GLOBAL/BLACK_VLESS_RUS_mobile_V2Box_Android_global.json) | [BLACK_VLESS_RUS_mobile](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/v2RayTun_Android/GLOBAL/BLACK_VLESS_RUS_mobile_v2RayTun_Android_global.json) | [BLACK_VLESS_RUS_mobile](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/v2RayTun_iOS/GLOBAL/BLACK_VLESS_RUS_mobile_v2RayTun_iOS_global.json) |
| **二维码** | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Standard/PROXIES_ONLY/BLACK_VLESS_RUS_mobile_standard_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Base64/PROXIES_ONLY/BLACK_VLESS_RUS_mobile_base64_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Clash/GLOBAL/BLACK_VLESS_RUS_mobile_clash_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2rayN_PC/BLACK_VLESS_RUS_mobile_v2rayN_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2rayNG_Android/GLOBAL/BLACK_VLESS_RUS_mobile_v2rayNG_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Streisand_iOS/GLOBAL/BLACK_VLESS_RUS_mobile_Streisand_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Happ/GLOBAL/BLACK_VLESS_RUS_mobile_Happ_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/V2Box_Android/GLOBAL/BLACK_VLESS_RUS_mobile_V2Box_Android_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2RayTun_Android/GLOBAL/BLACK_VLESS_RUS_mobile_v2RayTun_Android_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2RayTun_iOS/GLOBAL/BLACK_VLESS_RUS_mobile_v2RayTun_iOS_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> |
| **自动健康检查？** | **无自动健康检查。** 在客户端中配置 | **无自动健康检查。** 在客户端中配置 | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** |
| **路由：GLOBAL** | **无 GLOBAL 路由。** 在客户端中配置 | **无 GLOBAL 路由。** 在客户端中配置 | **有，GLOBAL 已内置于订阅** | **无 GLOBAL 路由。** 在 v2rayN 中配置 | **有，GLOBAL 已内置于订阅** | **有，GLOBAL 已内置于订阅** | **有，GLOBAL 已内置于订阅** | **有，GLOBAL 已内置于订阅** | **有，GLOBAL 已内置于订阅** | **有，GLOBAL 已内置于订阅** |
| **用途** | 标准格式的通用订阅，不包含客户端专用设置或路由；仅包含代理列表。适用于 Karing、Exclave、Shadowrocket 和 V2Box（iOS） | 同一种仅包含代理的通用订阅，以 Base64 格式提供，作为其他客户端的兼容备用方案 | Clash/Mihomo 订阅，为 Mihomo 客户端内置健康检查：Clash Verge Rev、Clash Mi、Clash Lite、Stash、Clash Meta for Android 和 FlClash | v2rayN 订阅，内置健康检查。若要使用自动选择，请选择列表底部的 `PolicyGroup` 配置 | v2rayNG 订阅，为 Android 内置健康检查和路由 | Streisand 订阅，为 iOS 内置健康检查和路由 | Happ 订阅，为 PC、iOS 和 Android 内置健康检查和路由 | V2Box 订阅，为 Android 内置健康检查和路由；iOS 版本使用标准订阅 | v2RayTun 订阅，为 Android 内置健康检查和路由 | v2RayTun 订阅，为 iOS 内置健康检查和路由 |
| | | | | | | | | | | |

</details>

`简洁轻量的手机订阅，用于黑名单。包含来自完整 VLESS 和 SHADOWSOCKS+ALL 订阅的 150 个最快配置（协议混合）。`

---

### VLESS: 

<details>
<summary><strong><code> 打开 </code></strong></summary>

㋡

| | | | | | | | | | | |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **订阅格式** | **通用（标准格式）** | **通用（Base64 格式）** | **Clash/Mihomo（PC/iOS/Android）** | **v2rayN（PC）** | **v2rayNG（Android）** | **Streisand（iOS）** | **Happ（PC/iOS/Android）** | **V2Box（Android）** | **v2RayTun（Android）** | **v2RayTun（iOS）** |
| **链接** | [BLACK_VLESS_RUS](https://raw.githack.com/igareck/vpn-configs-for-russia/main/BLACK_VLESS_RUS.txt) | [BLACK_VLESS_RUS](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/Base64/PROXIES_ONLY/BLACK_VLESS_RUS_base64.txt) | [BLACK_VLESS_RUS](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/Clash/GLOBAL/BLACK_VLESS_RUS_clash_global.yaml) | [BLACK_VLESS_RUS](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/v2rayN_PC/BLACK_VLESS_RUS_v2rayN.txt) | [BLACK_VLESS_RUS](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/v2rayNG_Android/GLOBAL/BLACK_VLESS_RUS_v2rayNG_global.json) | [BLACK_VLESS_RUS](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/Streisand_iOS/GLOBAL/BLACK_VLESS_RUS_Streisand_global.json) | [BLACK_VLESS_RUS](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/Happ/GLOBAL/BLACK_VLESS_RUS_Happ_global.json) | [BLACK_VLESS_RUS](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/V2Box_Android/GLOBAL/BLACK_VLESS_RUS_V2Box_Android_global.json) | [BLACK_VLESS_RUS](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/v2RayTun_Android/GLOBAL/BLACK_VLESS_RUS_v2RayTun_Android_global.json) | [BLACK_VLESS_RUS](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/v2RayTun_iOS/GLOBAL/BLACK_VLESS_RUS_v2RayTun_iOS_global.json) |
| **二维码** | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Standard/PROXIES_ONLY/BLACK_VLESS_RUS_standard_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Base64/PROXIES_ONLY/BLACK_VLESS_RUS_base64_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Clash/GLOBAL/BLACK_VLESS_RUS_clash_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2rayN_PC/BLACK_VLESS_RUS_v2rayN_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2rayNG_Android/GLOBAL/BLACK_VLESS_RUS_v2rayNG_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Streisand_iOS/GLOBAL/BLACK_VLESS_RUS_Streisand_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Happ/GLOBAL/BLACK_VLESS_RUS_Happ_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/V2Box_Android/GLOBAL/BLACK_VLESS_RUS_V2Box_Android_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2RayTun_Android/GLOBAL/BLACK_VLESS_RUS_v2RayTun_Android_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2RayTun_iOS/GLOBAL/BLACK_VLESS_RUS_v2RayTun_iOS_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> |
| **自动健康检查？** | **无自动健康检查。** 在客户端中配置 | **无自动健康检查。** 在客户端中配置 | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** |
| **路由：GLOBAL** | **无 GLOBAL 路由。** 在客户端中配置 | **无 GLOBAL 路由。** 在客户端中配置 | **有，GLOBAL 已内置于订阅** | **无 GLOBAL 路由。** 在 v2rayN 中配置 | **有，GLOBAL 已内置于订阅** | **有，GLOBAL 已内置于订阅** | **有，GLOBAL 已内置于订阅** | **有，GLOBAL 已内置于订阅** | **有，GLOBAL 已内置于订阅** | **有，GLOBAL 已内置于订阅** |
| **用途** | 标准格式的通用订阅，不包含客户端专用设置或路由；仅包含代理列表。适用于 Karing、Exclave、Shadowrocket 和 V2Box（iOS） | 同一种仅包含代理的通用订阅，以 Base64 格式提供，作为其他客户端的兼容备用方案 | Clash/Mihomo 订阅，为 Mihomo 客户端内置健康检查：Clash Verge Rev、Clash Mi、Clash Lite、Stash、Clash Meta for Android 和 FlClash | v2rayN 订阅，内置健康检查。若要使用自动选择，请选择列表底部的 `PolicyGroup` 配置 | v2rayNG 订阅，为 Android 内置健康检查和路由 | Streisand 订阅，为 iOS 内置健康检查和路由 | Happ 订阅，为 PC、iOS 和 Android 内置健康检查和路由 | V2Box 订阅，为 Android 内置健康检查和路由；iOS 版本使用标准订阅 | v2RayTun 订阅，为 Android 内置健康检查和路由 | v2RayTun 订阅，为 iOS 内置健康检查和路由 |
| | | | | | | | | | | |


</details>

  `黑名单的 VLESS 订阅。`

---

### SHADOWSOCKS+ALL:

<details>
<summary><strong><code> 打开 </code></strong></summary>

㋡

| | | | | | | | | | | |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **订阅格式** | **通用（标准格式）** | **通用（Base64 格式）** | **Clash/Mihomo（PC/iOS/Android）** | **v2rayN（PC）** | **v2rayNG（Android）** | **Streisand（iOS）** | **Happ（PC/iOS/Android）** | **V2Box（Android）** | **v2RayTun（Android）** | **v2RayTun（iOS）** |
| **链接** | [BLACK_SS+All_RUS](https://raw.githack.com/igareck/vpn-configs-for-russia/main/BLACK_SS%2BAll_RUS.txt) | [BLACK_SS+All_RUS](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/Base64/PROXIES_ONLY/BLACK_SS%2BAll_RUS_base64.txt) | [BLACK_SS+All_RUS](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/Clash/GLOBAL/BLACK_SS%2BAll_RUS_clash_global.yaml) | [BLACK_SS+All_RUS](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/v2rayN_PC/BLACK_SS%2BAll_RUS_v2rayN.txt) | [BLACK_SS+All_RUS](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/v2rayNG_Android/GLOBAL/BLACK_SS%2BAll_RUS_v2rayNG_global.json) | [BLACK_SS+All_RUS](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/Streisand_iOS/GLOBAL/BLACK_SS%2BAll_RUS_Streisand_global.json) | [BLACK_SS+All_RUS](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/Happ/GLOBAL/BLACK_SS%2BAll_RUS_Happ_global.json) | [BLACK_SS+All_RUS](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/V2Box_Android/GLOBAL/BLACK_SS%2BAll_RUS_V2Box_Android_global.json) | [BLACK_SS+All_RUS](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/v2RayTun_Android/GLOBAL/BLACK_SS%2BAll_RUS_v2RayTun_Android_global.json) | [BLACK_SS+All_RUS](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Export/v2RayTun_iOS/GLOBAL/BLACK_SS%2BAll_RUS_v2RayTun_iOS_global.json) |
| **二维码** | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Standard/PROXIES_ONLY/BLACK_SS%2BAll_RUS_standard_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Base64/PROXIES_ONLY/BLACK_SS%2BAll_RUS_base64_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Clash/GLOBAL/BLACK_SS%2BAll_RUS_clash_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2rayN_PC/BLACK_SS%2BAll_RUS_v2rayN_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2rayNG_Android/GLOBAL/BLACK_SS%2BAll_RUS_v2rayNG_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Streisand_iOS/GLOBAL/BLACK_SS%2BAll_RUS_Streisand_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Happ/GLOBAL/BLACK_SS%2BAll_RUS_Happ_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/V2Box_Android/GLOBAL/BLACK_SS%2BAll_RUS_V2Box_Android_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2RayTun_Android/GLOBAL/BLACK_SS%2BAll_RUS_v2RayTun_Android_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2RayTun_iOS/GLOBAL/BLACK_SS%2BAll_RUS_v2RayTun_iOS_global_GitHack_QR.png" style="max-width:100%; height:auto;" /></div> |
| **自动健康检查？** | **无自动健康检查。** 在客户端中配置 | **无自动健康检查。** 在客户端中配置 | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** |
| **路由：GLOBAL** | **无 GLOBAL 路由。** 在客户端中配置 | **无 GLOBAL 路由。** 在客户端中配置 | **有，GLOBAL 已内置于订阅** | **无 GLOBAL 路由。** 在 v2rayN 中配置 | **有，GLOBAL 已内置于订阅** | **有，GLOBAL 已内置于订阅** | **有，GLOBAL 已内置于订阅** | **有，GLOBAL 已内置于订阅** | **有，GLOBAL 已内置于订阅** | **有，GLOBAL 已内置于订阅** |
| **用途** | 标准格式的通用订阅，不包含客户端专用设置或路由；仅包含代理列表。适用于 Karing、Exclave、Shadowrocket 和 V2Box（iOS） | 同一种仅包含代理的通用订阅，以 Base64 格式提供，作为其他客户端的兼容备用方案 | Clash/Mihomo 订阅，为 Mihomo 客户端内置健康检查：Clash Verge Rev、Clash Mi、Clash Lite、Stash、Clash Meta for Android 和 FlClash | v2rayN 订阅，内置健康检查。若要使用自动选择，请选择列表底部的 `PolicyGroup` 配置 | v2rayNG 订阅，为 Android 内置健康检查和路由 | Streisand 订阅，为 iOS 内置健康检查和路由 | Happ 订阅，为 PC、iOS 和 Android 内置健康检查和路由 | V2Box 订阅，为 Android 内置健康检查和路由；iOS 版本使用标准订阅 | v2RayTun 订阅，为 Android 内置健康检查和路由 | v2RayTun 订阅，为 iOS 内置健康检查和路由 |
| | | | | | | | | | | |

</details>

  `黑名单的 ShadowSocks、Hysteria2、Vmess、Trojan 订阅。`

</details>


*绕过 RKN 黑名单的订阅。*

---
---

<details>

 <summary><h2> 🧾 <code> TOR 网桥 <img src="https://upload.wikimedia.org/wikipedia/commons/d/df/Tor_Browser_icon_%28New%29.png" width="35" align="absmiddle"> </code></h2></summary>

### TOR 网桥 前100名： 

### [TOR_BRIDGES_TOP100.txt](https://raw.githack.com/igareck/vpn-configs-for-russia/main/TOR-BRIDGES/TOR_BRIDGES_TOP100.txt)

<details>
<summary> 二维码 </summary>

![TOR_BRIDGES_TOP100_GitHack_QR.png](https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/GitHack-proxy/TOR_BRIDGES_TOP100_GitHack_QR.png)

</details>

 `用于访问 Tor 网络的桥接列表。前100名桥接。`

---

### TOR 网桥 完整列表： 

### [TOR_BRIDGES_ALL.txt](https://raw.githack.com/igareck/vpn-configs-for-russia/main/TOR-BRIDGES/TOR_BRIDGES_ALL.txt)

<details>
<summary> 二维码 </summary>

![TOR_BRIDGES_ALL_GitHack_QR.png](https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/GitHack-proxy/TOR_BRIDGES_ALL_GitHack_QR.png)

</details>

 `用于访问 Tor 网络的桥接列表。完整列表。`

---

### TOR 网桥 VANILLA： 

### [TOR_BRIDGES_VANILLA.txt](https://raw.githack.com/igareck/vpn-configs-for-russia/main/TOR-BRIDGES/TOR_BRIDGES_VANILLA.txt)

<details>
<summary> 二维码 </summary>

![TOR_BRIDGES_VANILLA_GitHack_QR.png](https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/GitHack-proxy/TOR_BRIDGES_VANILLA_GitHack_QR.png)

</details>

 `用于访问 Tor 网络的桥接列表。类型为 VANILLA。`

---

### TOR 网桥 OBFS4： 

### [TOR_BRIDGES_OBFS4.txt](https://raw.githack.com/igareck/vpn-configs-for-russia/main/TOR-BRIDGES/TOR_BRIDGES_OBFS4.txt)

<details>
<summary> 二维码 </summary>

![TOR_BRIDGES_OBFS4_GitHack_QR.png](https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/GitHack-proxy/TOR_BRIDGES_OBFS4_GitHack_QR.png)

</details>

 `用于访问 Tor 网络的桥接列表。类型为 OBFS4。`

---

### TOR 网桥 WEBTUNNEL： 

### [TOR_BRIDGES_WEBTUNNEL.txt](https://raw.githack.com/igareck/vpn-configs-for-russia/main/TOR-BRIDGES/TOR_BRIDGES_WEBTUNNEL.txt)

<details>
<summary> 二维码 </summary>

![TOR_BRIDGES_WEBTUNNEL_GitHack_QR.png](https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/GitHack-proxy/TOR_BRIDGES_WEBTUNNEL_GitHack_QR.png)

</details>

 `用于访问 Tor 网络的桥接列表。类型为 WEBTUNNEL。`

</details>

*用于访问 Tor 网络的桥接列表。类似于黑名单。*

---
---

<details>

<summary><h2> 🧾 <code> 白名单 ⚪ </code></h2></summary>

---

### 移动端 CIDR 订阅（订阅中速度最快的 150 个配置）⚪： 

<details>
<summary><strong><code> 打开 </code></strong></summary>

㋡

| | | | | | | | | | | |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **订阅格式** | **通用（标准格式）** | **通用（Base64 格式）** | **Clash/Mihomo（PC/iOS/Android）** | **v2rayN（PC）** | **v2rayNG（Android）** | **Streisand（iOS）** | **Happ（PC/iOS/Android）** | **V2Box（Android）** | **v2RayTun（Android）** | **v2RayTun（iOS）** |
| **链接** | [Vless-Reality-White-Lists-Rus-Mobile](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Vless-Reality-White-Lists-Rus-Mobile.txt&lang=de-de) | [Vless-Reality-White-Lists-Rus-Mobile](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/Base64/PROXIES_ONLY/Vless-Reality-White-Lists-Rus-Mobile-base64.txt&lang=de-de) | [Vless-Reality-White-Lists-Rus-Mobile](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/Clash/GLOBAL/Vless-Reality-White-Lists-Rus-Mobile-clash-global.yaml&lang=de-de) | [Vless-Reality-White-Lists-Rus-Mobile](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/v2rayN_PC/Vless-Reality-White-Lists-Rus-Mobile-v2rayN.txt&lang=de-de) | [Vless-Reality-White-Lists-Rus-Mobile](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/v2rayNG_Android/GLOBAL/Vless-Reality-White-Lists-Rus-Mobile-v2rayNG-global.json&lang=de-de) | [Vless-Reality-White-Lists-Rus-Mobile](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/Streisand_iOS/GLOBAL/Vless-Reality-White-Lists-Rus-Mobile-Streisand-global.json&lang=de-de) | [Vless-Reality-White-Lists-Rus-Mobile](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/Happ/GLOBAL/Vless-Reality-White-Lists-Rus-Mobile-Happ-global.json&lang=de-de) | [Vless-Reality-White-Lists-Rus-Mobile](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/V2Box_Android/GLOBAL/Vless-Reality-White-Lists-Rus-Mobile-V2Box-Android-global.json&lang=de-de) | [Vless-Reality-White-Lists-Rus-Mobile](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/v2RayTun_Android/GLOBAL/Vless-Reality-White-Lists-Rus-Mobile-v2RayTun-Android-global.json&lang=de-de) | [Vless-Reality-White-Lists-Rus-Mobile](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/v2RayTun_iOS/GLOBAL/Vless-Reality-White-Lists-Rus-Mobile-v2RayTun-iOS-global.json&lang=de-de) |
| **二维码** | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Standard/PROXIES_ONLY/Vless-Reality-White-Lists-Rus-Mobile-standard-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Base64/PROXIES_ONLY/Vless-Reality-White-Lists-Rus-Mobile-base64-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Clash/GLOBAL/Vless-Reality-White-Lists-Rus-Mobile-clash-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2rayN_PC/Vless-Reality-White-Lists-Rus-Mobile-v2rayN-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2rayNG_Android/GLOBAL/Vless-Reality-White-Lists-Rus-Mobile-v2rayNG-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Streisand_iOS/GLOBAL/Vless-Reality-White-Lists-Rus-Mobile-Streisand-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Happ/GLOBAL/Vless-Reality-White-Lists-Rus-Mobile-Happ-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/V2Box_Android/GLOBAL/Vless-Reality-White-Lists-Rus-Mobile-V2Box-Android-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2RayTun_Android/GLOBAL/Vless-Reality-White-Lists-Rus-Mobile-v2RayTun-Android-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2RayTun_iOS/GLOBAL/Vless-Reality-White-Lists-Rus-Mobile-v2RayTun-iOS-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> |
| **自动健康检查？** | **无自动健康检查。** 在客户端中配置 | **无自动健康检查。** 在客户端中配置 | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** |
| **路由：GLOBAL** | **无 GLOBAL 路由。** 在客户端中配置 | **无 GLOBAL 路由。** 在客户端中配置 | **有，GLOBAL 已内置于订阅** | **无 GLOBAL 路由。** 在 v2rayN 中配置 | **有，GLOBAL 已内置于订阅** | **有，GLOBAL 已内置于订阅** | **有，GLOBAL 已内置于订阅** | **有，GLOBAL 已内置于订阅** | **有，GLOBAL 已内置于订阅** | **有，GLOBAL 已内置于订阅** |
| **用途** | 标准格式的通用订阅，不包含客户端专用设置或路由；仅包含代理列表。适用于 Karing、Exclave、Shadowrocket 和 V2Box（iOS） | 同一种仅包含代理的通用订阅，以 Base64 格式提供，作为其他客户端的兼容备用方案 | Clash/Mihomo 订阅，为 Mihomo 客户端内置健康检查：Clash Verge Rev、Clash Mi、Clash Lite、Stash、Clash Meta for Android 和 FlClash | v2rayN 订阅，内置健康检查。若要使用自动选择，请选择列表底部的 `PolicyGroup` 配置 | v2rayNG 订阅，为 Android 内置健康检查和路由 | Streisand 订阅，为 iOS 内置健康检查和路由 | Happ 订阅，为 PC、iOS 和 Android 内置健康检查和路由 | V2Box 订阅，为 Android 内置健康检查和路由；iOS 版本使用标准订阅 | v2RayTun 订阅，为 Android 内置健康检查和路由 | v2RayTun 订阅，为 iOS 内置健康检查和路由 |
| | | | | | | | | | | |

</details>

`简洁、轻量的 CIDR 手机白名单订阅。包含完整 CIDR 订阅中的前 150 个配置（不超过 150 条，并且不超过完整 CIDR 订阅，如果少于 150 个配置）。绕过 CIDR IP 封锁。VLESS 协议。`

---

### 完整 CIDR 订阅（所有配置） ⚪： 

<details>
<summary><strong><code> 打开 </code></strong></summary>

㋡

| | | | | | | | | | | |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **订阅格式** | **通用（标准格式）** | **通用（Base64 格式）** | **Clash/Mihomo（PC/iOS/Android）** | **v2rayN（PC）** | **v2rayNG（Android）** | **Streisand（iOS）** | **Happ（PC/iOS/Android）** | **V2Box（Android）** | **v2RayTun（Android）** | **v2RayTun（iOS）** |
| **链接** | [WHITE-CIDR-RU-all](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/WHITE-CIDR-RU-all.txt&lang=de-de) | [WHITE-CIDR-RU-all](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/Base64/PROXIES_ONLY/WHITE-CIDR-RU-all-base64.txt&lang=de-de) | [WHITE-CIDR-RU-all](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/Clash/GLOBAL/WHITE-CIDR-RU-all-clash-global.yaml&lang=de-de) | [WHITE-CIDR-RU-all](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/v2rayN_PC/WHITE-CIDR-RU-all-v2rayN.txt&lang=de-de) | [WHITE-CIDR-RU-all](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/v2rayNG_Android/GLOBAL/WHITE-CIDR-RU-all-v2rayNG-global.json&lang=de-de) | [WHITE-CIDR-RU-all](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/Streisand_iOS/GLOBAL/WHITE-CIDR-RU-all-Streisand-global.json&lang=de-de) | [WHITE-CIDR-RU-all](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/Happ/GLOBAL/WHITE-CIDR-RU-all-Happ-global.json&lang=de-de) | [WHITE-CIDR-RU-all](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/V2Box_Android/GLOBAL/WHITE-CIDR-RU-all-V2Box-Android-global.json&lang=de-de) | [WHITE-CIDR-RU-all](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/v2RayTun_Android/GLOBAL/WHITE-CIDR-RU-all-v2RayTun-Android-global.json&lang=de-de) | [WHITE-CIDR-RU-all](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/v2RayTun_iOS/GLOBAL/WHITE-CIDR-RU-all-v2RayTun-iOS-global.json&lang=de-de) |
| **二维码** | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Standard/PROXIES_ONLY/WHITE-CIDR-RU-all-standard-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Base64/PROXIES_ONLY/WHITE-CIDR-RU-all-base64-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Clash/GLOBAL/WHITE-CIDR-RU-all-clash-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2rayN_PC/WHITE-CIDR-RU-all-v2rayN-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2rayNG_Android/GLOBAL/WHITE-CIDR-RU-all-v2rayNG-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Streisand_iOS/GLOBAL/WHITE-CIDR-RU-all-Streisand-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Happ/GLOBAL/WHITE-CIDR-RU-all-Happ-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/V2Box_Android/GLOBAL/WHITE-CIDR-RU-all-V2Box-Android-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2RayTun_Android/GLOBAL/WHITE-CIDR-RU-all-v2RayTun-Android-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2RayTun_iOS/GLOBAL/WHITE-CIDR-RU-all-v2RayTun-iOS-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> |
| **自动健康检查？** | **无自动健康检查。** 在客户端中配置 | **无自动健康检查。** 在客户端中配置 | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** |
| **路由：GLOBAL** | **无 GLOBAL 路由。** 在客户端中配置 | **无 GLOBAL 路由。** 在客户端中配置 | **有，GLOBAL 已内置于订阅** | **无 GLOBAL 路由。** 在 v2rayN 中配置 | **有，GLOBAL 已内置于订阅** | **有，GLOBAL 已内置于订阅** | **有，GLOBAL 已内置于订阅** | **有，GLOBAL 已内置于订阅** | **有，GLOBAL 已内置于订阅** | **有，GLOBAL 已内置于订阅** |
| **用途** | 标准格式的通用订阅，不包含客户端专用设置或路由；仅包含代理列表。适用于 Karing、Exclave、Shadowrocket 和 V2Box（iOS） | 同一种仅包含代理的通用订阅，以 Base64 格式提供，作为其他客户端的兼容备用方案 | Clash/Mihomo 订阅，为 Mihomo 客户端内置健康检查：Clash Verge Rev、Clash Mi、Clash Lite、Stash、Clash Meta for Android 和 FlClash | v2rayN 订阅，内置健康检查。若要使用自动选择，请选择列表底部的 `PolicyGroup` 配置 | v2rayNG 订阅，为 Android 内置健康检查和路由 | Streisand 订阅，为 iOS 内置健康检查和路由 | Happ 订阅，为 PC、iOS 和 Android 内置健康检查和路由 | V2Box 订阅，为 Android 内置健康检查和路由；iOS 版本使用标准订阅 | v2RayTun 订阅，为 Android 内置健康检查和路由 | v2RayTun 订阅，为 iOS 内置健康检查和路由 |
| | | | | | | | | | | |

</details>

`完整的白名单 CIDR 订阅。包含来自不同托管提供商的所有已知白色子网。绕过 CIDR IP 封锁。VLESS 协议。`

*注意！由于配置数量可能较多，对性能较弱的设备可能较重！*

---

### 仅包含托管提供商的 CIDR 订阅：VK、YANDEX、CDNVIDEO、Beeline ⚪：

<details>
<summary><strong><code> 打开 </code></strong></summary>

㋡

| | | | | | | | | | | |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **订阅格式** | **通用（标准格式）** | **通用（Base64 格式）** | **Clash/Mihomo（PC/iOS/Android）** | **v2rayN（PC）** | **v2rayNG（Android）** | **Streisand（iOS）** | **Happ（PC/iOS/Android）** | **V2Box（Android）** | **v2RayTun（Android）** | **v2RayTun（iOS）** |
| **链接** | [WHITE-CIDR-RU-checked](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/WHITE-CIDR-RU-checked.txt&lang=de-de) | [WHITE-CIDR-RU-checked](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/Base64/PROXIES_ONLY/WHITE-CIDR-RU-checked-base64.txt&lang=de-de) | [WHITE-CIDR-RU-checked](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/Clash/GLOBAL/WHITE-CIDR-RU-checked-clash-global.yaml&lang=de-de) | [WHITE-CIDR-RU-checked](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/v2rayN_PC/WHITE-CIDR-RU-checked-v2rayN.txt&lang=de-de) | [WHITE-CIDR-RU-checked](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/v2rayNG_Android/GLOBAL/WHITE-CIDR-RU-checked-v2rayNG-global.json&lang=de-de) | [WHITE-CIDR-RU-checked](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/Streisand_iOS/GLOBAL/WHITE-CIDR-RU-checked-Streisand-global.json&lang=de-de) | [WHITE-CIDR-RU-checked](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/Happ/GLOBAL/WHITE-CIDR-RU-checked-Happ-global.json&lang=de-de) | [WHITE-CIDR-RU-checked](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/V2Box_Android/GLOBAL/WHITE-CIDR-RU-checked-V2Box-Android-global.json&lang=de-de) | [WHITE-CIDR-RU-checked](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/v2RayTun_Android/GLOBAL/WHITE-CIDR-RU-checked-v2RayTun-Android-global.json&lang=de-de) | [WHITE-CIDR-RU-checked](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/v2RayTun_iOS/GLOBAL/WHITE-CIDR-RU-checked-v2RayTun-iOS-global.json&lang=de-de) |
| **二维码** | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Standard/PROXIES_ONLY/WHITE-CIDR-RU-checked-standard-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Base64/PROXIES_ONLY/WHITE-CIDR-RU-checked-base64-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Clash/GLOBAL/WHITE-CIDR-RU-checked-clash-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2rayN_PC/WHITE-CIDR-RU-checked-v2rayN-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2rayNG_Android/GLOBAL/WHITE-CIDR-RU-checked-v2rayNG-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Streisand_iOS/GLOBAL/WHITE-CIDR-RU-checked-Streisand-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Happ/GLOBAL/WHITE-CIDR-RU-checked-Happ-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/V2Box_Android/GLOBAL/WHITE-CIDR-RU-checked-V2Box-Android-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2RayTun_Android/GLOBAL/WHITE-CIDR-RU-checked-v2RayTun-Android-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2RayTun_iOS/GLOBAL/WHITE-CIDR-RU-checked-v2RayTun-iOS-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> |
| **自动健康检查？** | **无自动健康检查。** 在客户端中配置 | **无自动健康检查。** 在客户端中配置 | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** |
| **路由：GLOBAL** | **无 GLOBAL 路由。** 在客户端中配置 | **无 GLOBAL 路由。** 在客户端中配置 | **有，GLOBAL 已内置于订阅** | **无 GLOBAL 路由。** 在 v2rayN 中配置 | **有，GLOBAL 已内置于订阅** | **有，GLOBAL 已内置于订阅** | **有，GLOBAL 已内置于订阅** | **有，GLOBAL 已内置于订阅** | **有，GLOBAL 已内置于订阅** | **有，GLOBAL 已内置于订阅** |
| **用途** | 标准格式的通用订阅，不包含客户端专用设置或路由；仅包含代理列表。适用于 Karing、Exclave、Shadowrocket 和 V2Box（iOS） | 同一种仅包含代理的通用订阅，以 Base64 格式提供，作为其他客户端的兼容备用方案 | Clash/Mihomo 订阅，为 Mihomo 客户端内置健康检查：Clash Verge Rev、Clash Mi、Clash Lite、Stash、Clash Meta for Android 和 FlClash | v2rayN 订阅，内置健康检查。若要使用自动选择，请选择列表底部的 `PolicyGroup` 配置 | v2rayNG 订阅，为 Android 内置健康检查和路由 | Streisand 订阅，为 iOS 内置健康检查和路由 | Happ 订阅，为 PC、iOS 和 Android 内置健康检查和路由 | V2Box 订阅，为 Android 内置健康检查和路由；iOS 版本使用标准订阅 | v2RayTun 订阅，为 Android 内置健康检查和路由 | v2RayTun 订阅，为 iOS 内置健康检查和路由 |
| | | | | | | | | | | |

</details>

`针对特定托管提供商的完整CIDR订阅的过滤版本。较不完整的版本。在此缩短的订阅中，白名单子网仅来自这些俄罗斯托管提供商：VK、YANDEX、CDNVIDEO和Beeline，而在完整订阅中——所有托管提供商！可绕过CIDR IP阻止。VLESS协议。`

---

### SNI 订阅 ⚪: 

<details>
<summary><strong><code> 打开 </code></strong></summary>

㋡

| | | | | | | | | | | |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **订阅格式** | **通用（标准格式）** | **通用（Base64 格式）** | **Clash/Mihomo（PC/iOS/Android）** | **v2rayN（PC）** | **v2rayNG（Android）** | **Streisand（iOS）** | **Happ（PC/iOS/Android）** | **V2Box（Android）** | **v2RayTun（Android）** | **v2RayTun（iOS）** |
| **链接** | [WHITE-SNI-RU-all](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/WHITE-SNI-RU-all.txt&lang=de-de) | [WHITE-SNI-RU-all](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/Base64/PROXIES_ONLY/WHITE-SNI-RU-all-base64.txt&lang=de-de) | [WHITE-SNI-RU-all](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/Clash/GLOBAL/WHITE-SNI-RU-all-clash-global.yaml&lang=de-de) | [WHITE-SNI-RU-all](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/v2rayN_PC/WHITE-SNI-RU-all-v2rayN.txt&lang=de-de) | [WHITE-SNI-RU-all](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/v2rayNG_Android/GLOBAL/WHITE-SNI-RU-all-v2rayNG-global.json&lang=de-de) | [WHITE-SNI-RU-all](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/Streisand_iOS/GLOBAL/WHITE-SNI-RU-all-Streisand-global.json&lang=de-de) | [WHITE-SNI-RU-all](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/Happ/GLOBAL/WHITE-SNI-RU-all-Happ-global.json&lang=de-de) | [WHITE-SNI-RU-all](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/V2Box_Android/GLOBAL/WHITE-SNI-RU-all-V2Box-Android-global.json&lang=de-de) | [WHITE-SNI-RU-all](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/v2RayTun_Android/GLOBAL/WHITE-SNI-RU-all-v2RayTun-Android-global.json&lang=de-de) | [WHITE-SNI-RU-all](https://translate.yandex.ru/translate?url=https://bitbucket.org/igareck/vpn-configs-for-russia/raw/main/Export/v2RayTun_iOS/GLOBAL/WHITE-SNI-RU-all-v2RayTun-iOS-global.json&lang=de-de) |
| **二维码** | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Standard/PROXIES_ONLY/WHITE-SNI-RU-all-standard-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Base64/PROXIES_ONLY/WHITE-SNI-RU-all-base64-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Clash/GLOBAL/WHITE-SNI-RU-all-clash-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2rayN_PC/WHITE-SNI-RU-all-v2rayN-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2rayNG_Android/GLOBAL/WHITE-SNI-RU-all-v2rayNG-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Streisand_iOS/GLOBAL/WHITE-SNI-RU-all-Streisand-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/Happ/GLOBAL/WHITE-SNI-RU-all-Happ-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/V2Box_Android/GLOBAL/WHITE-SNI-RU-all-V2Box-Android-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2RayTun_Android/GLOBAL/WHITE-SNI-RU-all-v2RayTun-Android-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> | <div style="width:200px;"><img src="https://cdn.jsdelivr.net/gh/igareck/vpn-configs-for-russia@refs/heads/main/QR-codes/v2RayTun_iOS/GLOBAL/WHITE-SNI-RU-all-v2RayTun-iOS-global-Yandex-QR.png" style="max-width:100%; height:auto;" /></div> |
| **自动健康检查？** | **无自动健康检查。** 在客户端中配置 | **无自动健康检查。** 在客户端中配置 | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** | **有，已内置于订阅** |
| **路由：GLOBAL** | **无 GLOBAL 路由。** 在客户端中配置 | **无 GLOBAL 路由。** 在客户端中配置 | **有，GLOBAL 已内置于订阅** | **无 GLOBAL 路由。** 在 v2rayN 中配置 | **有，GLOBAL 已内置于订阅** | **有，GLOBAL 已内置于订阅** | **有，GLOBAL 已内置于订阅** | **有，GLOBAL 已内置于订阅** | **有，GLOBAL 已内置于订阅** | **有，GLOBAL 已内置于订阅** |
| **用途** | 标准格式的通用订阅，不包含客户端专用设置或路由；仅包含代理列表。适用于 Karing、Exclave、Shadowrocket 和 V2Box（iOS） | 同一种仅包含代理的通用订阅，以 Base64 格式提供，作为其他客户端的兼容备用方案 | Clash/Mihomo 订阅，为 Mihomo 客户端内置健康检查：Clash Verge Rev、Clash Mi、Clash Lite、Stash、Clash Meta for Android 和 FlClash | v2rayN 订阅，内置健康检查。若要使用自动选择，请选择列表底部的 `PolicyGroup` 配置 | v2rayNG 订阅，为 Android 内置健康检查和路由 | Streisand 订阅，为 iOS 内置健康检查和路由 | Happ 订阅，为 PC、iOS 和 Android 内置健康检查和路由 | V2Box 订阅，为 Android 内置健康检查和路由；iOS 版本使用标准订阅 | v2RayTun 订阅，为 Android 内置健康检查和路由 | v2RayTun 订阅，为 iOS 内置健康检查和路由 |
| | | | | | | | | | | |

</details>

`仅可基于伪造的SNI域名绕过SNI阻止。CIDR锁定无法绕过。VLESS协议。`

---

</details>


*可绕过RKN白名单的订阅。*

`用于电话2的CIDR订阅 Vless-Reality-White-Lists-Rus-Mobile-2.txt 因其不相关而已从仓库中移除！`

---
---

<details>

<summary><h2> 🧾 <code> 镜像 🪞 </code></h2></summary>

**有几种带镜像的选项可供替代访问订阅。**

### `方法 1： Yandex 翻译器` 

它将在白名单模式下提供帮助，因为……Yandex子网在白名单下最稳定且可用。 

*该方法可通过直接将链接添加到客户端（Yandex+Bitbucket），或通过从浏览器窗口手动复制配置（其他连接方式）来实现！* 

**Yandex 翻译器在白名单模式下作为“代理”工作。**

若您处于白名单模式且GitHub被阻止，可通过两种方式通过Yandex 翻译器更新任何订阅：

**1. 通过客户端自动进行。** **但注意！只有一个 Bitbucket 镜像在通过 Translator 时工作正常：** **Yandex+Bitbucket**！ 

**在 Karing、Clash Mi 以及 v2rayN/v2rayNG 的无人机威胁期间的网络限制下，订阅者已经测试了通过 Yandex+Bitbucket 导入的配置性能。**

其余的镜像 GitLab/Codeberg/Gitea/SourceHut/Githack，与 Yandex 翻译器一起，在通过客户端自动更新时会破坏配置；在这些情况下，参数“sni/security/type/pbk/sid/fp/mode”总是被重置。这是 Yandex 自身开发者故意破坏的，因为之前一切正常。

**2. 使用浏览器手动复制粘贴的方法**。在手动模式下，来自任何源 GitHub/GitLab/Codeberg/Gitea/SourceHut/Bitbucket/Githack 的链接都适用于 Yandex。

**如何自己创建 Yandex 链接？**

✦ **在网站** "https://translate.yandex.ru/translate" **上**，可在“输入网站地址”字段中粘贴所需的 RAW 订阅链接；

✦ 使用 Bitbucket 镜像（或替代方案），**在此处** 插入订阅链接 **替换“SUBSCRIPTION”的文字**：

https://translate.yandex.ru/translate?url=SUBSCRIPTION&lang=de-de 然后将此链接粘贴到客户端（用于自动模式）或浏览器（用于手动模式）中！

✦ **使用下面的 Yandex（Yandex+Bitbucket）现成链接**，你可以将其保存在手机或电脑的笔记中，并在需要时使用。Yandex 翻译器中的 Bitbucket 链接已经被替换。

感谢用户 @AmiFox 和 @HenonBank 关于 Yandex 翻译器方法的最初提示。

---

### `方法 2. GitLab/Codeberg/Gitea/SourceHut/Bitbucket`

| | | |
|---:|---|---|
| **GitLab** | https://gitlab.com/igareck/vpn-configs-for-russia/ | Git 镜像 / 开放核心 SaaS |
| **Codeberg** | https://codeberg.org/igareck/vpn-configs-for-russia | Git 镜像 / FOSS |
| **Gitea** | https://gitea.com/igareck/vpn-configs-for-russia | Git 镜像 / 基于 FOSS |
| **SourceHut** | https://git.sr.ht/~igareck/vpn-configs-for-russia | Git 镜像 / FOSS |
| **Bitbucket** | https://bitbucket.org/igareck/vpn-configs-for-russia/ | Git 镜像 / 商业 |
| | | |

*完整的 Git 镜像。不是代理。原始仓库的副本位于 5 台独立服务器上。*

---

### `方法 3. Githack RAW`

| | | |
|---:|---|---|
| **GitHack** | https://raw.githack.com/| 实时 RAW 代理 |
| | | |

*为来自 GitHub/GitLab/Bitbucket/Gitea/Codeberg 的 RAW 文件缓存实时代理。*

与方法 2 的镜像不同，后者会在其独立服务器上保留完整的仓库副本，Githack RAW 的不同之处在于它在请求时始终访问原始仓库（此处为 GitHub），充当 RAW 文件的代理。

即使对于尝试访问其他镜像时收到“您当前正在从被阻止的 IP 地址或国家访问”的用户，它也能正常工作。

---

**方法 1 将有助于白名单/无人机威胁期间的网络限制。**

**方法 2 和 3 仅在黑名单情况下才有帮助。当 Roskomnadzor 阻止 GitHub 时相关。**

JSDelivr CDN（https://cdn.jsdelivr.net 通过 CDN）和 Githack CDN（https://rawcdn.githack.com 通过 Cloudflare）由于数据缓存延迟大而被删除。 

JSDelivr CDN - 在 5-24 小时内。Githack CDN - 延迟可能达到 2 周。

GitLab/Codeberg/Gitea/SourceHut/Bitbucket/Githack RAW - 信息始终是最新的，没有延迟。

---

**该怎么办？** 在客户端中将原始 RAW 链接替换为订阅 `https://raw.githubusercontent.com/`，指向以下列表中某个镜像的 RAW 链接（列表就在本文下方）或复制镜像网站上的 RAW 链接。 

**如何从镜像下载订阅？** 要从镜像获取 RAW 文件，只需在镜像中找到与原始同名的 txt 订阅，点击链接，在上方找到标有 RAW（Open Raw、View Raw、Source）的按钮，点击按钮并从地址栏复制链接。 

---

### `以下是通过镜像的现成订阅链接。` 

### 将其保存在设备上，以防 GitHub 被阻止或启用了白名单限制。

Yandex 翻译器链接 **Yandex+Bitbucket 白名单模式** 可以通过客户端正常工作。下载的配置功能已由订阅者在 Karing 和 v2rayN/v2rayNG 的无人机威胁期间的网络限制下测试。请注意，能够工作的组合是 Yandex+Bitbucket；与 Yandex 的其他所有连接都会破坏配置！

在添加之前，先在浏览器中检查可用性。

**如果收到消息“您当前正在从被封锁的 IP 地址或国家/地区访问”** - 这意味着镜像本身的 GeoBlock 已生效，请尝试下一个镜像。 

**最大可用选项** - 这是 **GitHack** (raw.githack.com)，它几乎对所有人都适用，因为它是一个代理，而不是大型公司；同时还有 **SourceHut** (git.sr.ht)，因为这是一个私人小型项目。

**[MIRRORS_LINKS_FULL.txt](https://raw.githack.com/igareck/GoldCaviar/main/Files/MIRRORS_LINKS_FULL.txt)** - **下载完整镜像列表为一个 TXT 文件** 

所有订阅格式的完整镜像列表也已移至单独页面：

#### [➡️ 打开完整镜像列表](./MIRRORS.md)

</details>

*访问订阅的替代链接，在白名单模式下或 GitHub 被屏蔽时使用。*

---

## <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3bjF5NnEyM21vMjJhd2UxdWphYnQxZGh6bjc1bjBzMG44eDB0Ym03eCZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/dyX9ixfxMpOUGawfdK/giphy.gif" width="50"> `黑名单和白名单有什么区别，该选择哪种订阅？`


`⬇ 操作流程 ⬇`

`首先，让我们检查互联网是否正常：打开 Yandex.ru、State Services、VK、 Rutube.ru、Sberbank、 Mail.ru、Ozon。如果这些都打不开，说明你的互联网完全无法使用。（没有连接）此时任何配置都没有用！在这种情况下，请检查设备的网络连接！`

`如果突然“根本无法加载”，通常重置网络连接（重启）会有帮助：开启“飞行模式”10-15 秒，然后关闭，再尝试连接——搞定！`

`我要说明，如果移动网络完全中断（即使“白名单”中的网站也被完全禁用/限制），任何网络重启都无济于事——你要么等待至少“白名单”中的网站恢复工作，要么寻找有线网络或公共 Wifi。`

### ① `选择黑名单还是白名单：` <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3Y3Q4NW94NXo0ZXQwajl1cDRzdHg3ZXFzbWc4aGtzeDA0cGRtNTl2ZSZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/35LH6GkOzEXuw/giphy.gif" width="80">  

| | 黑名单 / TOR 网桥（标准互联网） | 白名单（最大限度限制） |
|--|--|--|
| **简要** | 黑名单是指“允许一切未被禁止的内容” | 白名单是指“禁止一切未被允许的内容” |
| **什么类型的互联网？** | 任意电缆+移动网络，无严格限制 | 移动网络，限制最严 |
| **什么可用？** | 互联网照常工作：Google、App Store、Telegram 或任何在俄罗斯未被官方屏蔽的普通国外网站/服务可以访问 | 你有移动互联网，但除了 Yandex.ru、国家服务、VK、Rutube、Sberbank、 Mail.ru、Ozon 和 RKN 批准的其他网站外，其他都无法使用。 Google.com、GMail、App Store、Telegram 或任何国外网站都无法访问。你只能访问监管机构批准的这些俄罗斯网站，使用它们的“白名单”。例如，RKN 只批准了 Yandex 和 Ozone——你只能访问 Yandex 和 Ozone，不能访问其他网站。 |
| **VPN 的目的是什么？** | 访问在俄罗斯官方屏蔽的服务：观看 4K YouTube、在 WhatsApp、Viber、Signal、FaceTime、Facebook、Discord 上通话/聊天，在 Instagram、X（推特）上发帖，使用 LinkedIn、玩 Roblox（是的，Roblox 已解封，但谁知道明天会发生什么），使用 Telegram、Grok、ChatGPT、Gemini 等。 | 在限制期间，只要去 Yandex、Sberbank、国家服务和 VK 以外的地方即可。使用对延迟和网络带宽要求不高的服务：WhatsApp、Telegram、Google、任何电子邮件、在手机上观看 YouTube 视频。不适用于高流量和网络游戏（你可以尝试，但结果不保证）。 |
| **注意** | “黑名单”配置——实际上，这是最常见/通用/国际化 VPN 选项，只是采用了现代协议！黑名单也是最快的，因为它在标准条件下运行 | “白名单”配置本质上是一种专门的VPN，可以绕过当前俄罗斯环境中的特定严重限制 |
| **我应该选择什么？** | 如果你有有线互联网，或者没有限制的移动网络，并且你的情况符合此“左侧”列中的描述，那么你需要“黑名单”或“TOR 网桥”订阅 | 如果你有移动互联网，一切有限制，并且你的情况符合此“右侧”列中的描述，那么你需要“白名单”订阅 |
| **有哪些协议和订阅？** | 黑名单集合按协议划分：**订阅 Shadowsocks+Hysteria2+Vmess+Trojan** **[BLACK_SS+All_RUS.txt](https://raw.githack.com/igareck/vpn-configs-for-russia/main/BLACK_SS+All_RUS.txt)**，**VLESS 订阅** **[BLACK_VLESS_RUS.txt](https://raw.githack.com/igareck/vpn-configs-for-russia/main/BLACK_VLESS_RUS.txt)**，以及面向移动端的精简 TOP 150 订阅 **[BLACK_VLESS_RUS_mobile.txt](https://raw.githack.com/igareck/vpn-configs-for-russia/main/BLACK_VLESS_RUS_mobile.txt)**（名称中的 VLESS 仅为原始命名，实际上是所有可用配置的 TOP 150 混合） |  这里的协议基本为 **VLESS**，按 **4 个 CIDR 订阅** 划分：1 个完整订阅 **[WHITE-CIDR-RU-all.txt](https://raw.githack.com/igareck/vpn-configs-for-russia/main/WHITE-CIDR-RU-all.txt)** + 1 个手机压缩订阅 **[Vless-Reality-White-Lists-Rus-Mobile.txt](https://raw.githack.com/igareck/vpn-configs-for-russia/main/Vless-Reality-White-Lists-Rus-Mobile.txt)** + 1 个额外订阅 **[WHITE-CIDR-RU-checked.txt](https://raw.githack.com/igareck/vpn-configs-for-russia/main/WHITE-CIDR-RU-checked.txt)**（不同IP段的CIDR限制现在适用于引入白名单的100%俄罗斯移动运营商）；以及 **1 个 SNI 订阅** **[WHITE-SNI-RU-all.txt](https://raw.githack.com/igareck/vpn-configs-for-russia/main/WHITE-SNI-RU-all.txt)**（对白名单伪造 SNI 域的限制，现在已无法在绕过白名单方面使用，仅用于紧急情况） |

---

### ② `在正常黑名单条件下 ⚫：` 

**[VLESS 手机] • [VLESS 完整] • [SHADOWSOCKS+ALL 完整] • [Shadowsocks 弱 DPI]**

**[TOR 网桥 完整] • TOP 100 • VANILLA • OBFS4 • WEBTUNNEL**

<details>
<summary><em><code> 点击箭头查看详情 </code></em></summary>

㋡

#### `a) VLESS 手机 • VLESS • SHADOWSOCKS+ALL`

对于常规黑名单，选择精简的手机订阅 **[BLACK VLESS 手机](#---black-list--)**——这是两个订阅 **VLESS** 和 **SHADOWSOCKS+ALL** 的 TOP 150 混合；或按协议划分的完整订阅 **[BLACK VLESS](#---black-list--)** 或 **[BLACK SHADOWSOCKS+ALL](#---black-list--)**——这些包括 Shadowsocks、Hysteria2、Trojan、Vmess。 

**根据客户端，我们选择订阅格式：标准、Clash 或为单个客户端的特殊格式**。

**BLACK VLESS** 和 **BLACK SHADOWSOCKS+ALL** 可能包含来自移动订阅的超过 150 个配置（如 **BLACK VLESS Mobile**）。大量配置在检查时可能会给设备带来很大压力。而移动 TOP 150 选项始终轻量，不会因大量 ping 负载设备，是手机的最理想选择。

在 移动端 TOP 150 订阅 **BLACK VLESS Mobile** 中——标题中的“VLESS”一词是象征性的（自仓库创建以来存在），实际上，这是黑名单所有可用配置/协议的 TOP 150 混合。

————

#### `b) Shadowsocks 弱 DPI`

为黑名单提供的新 Shadowsocks 订阅，无混淆和插件 **[BLACK_SS_WEAK_DPI_RUS.txt](https://raw.githack.com/igareck/vpn-configs-for-russia/main/BLACK_SS_WEAK_DPI_RUS.txt)**

设计用于 DPI 弱或过滤水平较低的网络环境。

建议使用小型区域运营商的网络，主要是有线网络。大型全俄罗斯移动运营商，如 Megafon、MTS、Beeline，很可能不起作用：也就是说，它们能够 ping 没有混淆的 Shadowsocks，但流量无法通过，网站无法加载。有线区域运营商在这方面更简单；任何订阅对它们来说效果更好。

您需要在路由器或 PC 网络适配器设置中配置 DNS-over-HTTPS（DoH）。没有 DoH，即使配置 ping 验证成功，流量也可能被阻止。

性能无法保证，并且可能因运营商而异。

————

#### `c) TOR 网桥 完整 • TOP 100 • VANILLA • OBFS4 • WEBTUNNEL`

VPN 黑名单的工作替代方案——桥接 **[TOR BRIDGES](#---tor-bridges--)**。 

执行与 VPN 黑名单相同的功能，唯一的区别是——访问网络不是通过标准全球网络（所谓的 Clearnet）进行，而是通过 Tor 网络。桥接是代理，因为 Tor 浏览器内置的标准 IP 连接被 Roskomnadzor (RKN) 阻止。

您可以通过 Tor 浏览器、Tor 客户端 OnionHop V3（PC/笔记本）、OnionFruit Tor 客户端（PC/笔记本）、以及 Orbot（电话）或 Invizible Pro（电话）使用 Tor 网桥，它们充当 Windows/macOS/iOS/Android 设备上的客户端。

澄清，有些细节需要注意：如果你使用 Tor 网桥并通过客户端将你的流量变成 Tor 隧道，那么只有 TCP 流可以工作，UDP 连接在任何情况下都无法工作，因为 Tor 架构本身不允许 UDP 通过。 

一些应用程序即使在没有 UDP 的情况下仍能 100% 正常工作，如果它提供了 TCP 回退。这就是 Telegram 的工作方式，例如。（直到最近 TCP 回退都能工作，现在我们需要检查）。

**这会如何影响性能？** 

a) **浏览器**——几乎不会有影响，因为在大多数情况下它们依赖于 TCP 流，并且其中发生的一切将正常加载和运行。

b) **应用程序**，依赖于 UDP 连接的，如 Discord 或 Steam，将失去部分功能。哪些功能呢？ 

c) **Discord** 的文本/图片/视频/文件会在消息中发送，一切和普通的即时通讯应用一样，但语音/视频/实时流和通话可能无法进行，因为“在线”状态依赖于 UDP 流量。但再一次——一切由 TCP 回退决定，如果它能工作的话。

**Telegram**——一切将像在普通 VPN 下那样工作，如果你在设置中为通话配置 P2P。通话中的 TCP 回退在这里可以正常工作。聊天、消息（文本/图片/视频/文件）无需额外设置即可顺利运行。 

> 通话有个细节！
> 
> 如果通话通过 Telegram 服务器（通常是默认设置情况下），
> 那么此时的通话是一个 UDP 在线流，将无法进行。
> 
> 但如果你在 Telegram 设置中启用 P2P：`隐私 - 通话 - 使用点对点`
> 对所有或选定的联系人
> 那么 TCP 回退将会起作用，并且通过 Tor 的通话也将可用！已检查！
> 
> 更新：在设置中使用 P2P 的方法可能不再有效，所以请在本地检查。

**Steam** 尤其如此，它会打开并启动游戏，但在游戏内部，在线服务器将无法加载，因为所有与“在线”相关的内容都依赖于 UDP。 

> 仅仅是在 PC 上购买/下载游戏并离线玩是没有问题的，因为……这是在你的 PC 本地发生的。

但这并不意味着所有应用程序都是如此。有些应用程序只支持 TCP 流量，例如电子邮件客户端、SSH 客户端（SSH 模式下的 Git 工具）、SQL 客户端、FTP/FTPS 客户端、数据库客户端等。

### `组合 "Tor Bridges" + Tor 客户端 "OnionHop V3" 或 "OnionFruit"`

<details>

<summary><em><code> 打开 </code></em></summary> 

㋡

VPN，尤其是公共 VPN，总是存在流量限制，并且还容易受到俄罗斯通信监管局的攻击。其后果是配置需要不断更新，连接也常常需要更改。为了在无需手动切换的情况下自动更改配置，可以使用 Karing 或 Clash 订阅客户端。

#### 是否有替代方案，比 VPN 更稳定的？ - 有！

#### 我为你提供了一个可行的解决方案：“Tor Bridges” + “OnionHop V3” 或 “OnionFruit”。
#### 我为你准备了一份循序渐进的手册，其中包含所有客户端下载链接（手册是根据 V2 版本制作的，我稍后会更新到 V3，但总体上都类似）。

| | |
|---:|---|
|**Tor Bridges，支持俄罗斯联邦使用**|https://github.com/igareck/vpn-configs-for-russia/tree/main/TOR-BRIDGES|
|**Tor 客户端 OnionHop V3**|https://github.com/center2055/OnionHop/releases|
|**OnionFruit Tor 客户端**|https://github.com/dragonfruitnetwork/onionfruit/releases|
|**Telegraph 手册（原版）**|**[OnionHop V2 - PC 版 Tor 客户端简要概述](https://telegra.ph/OnionHop-V2--kratkij-obzor-Tor-klienta-dlya-PK-04-04)**|
|**WayBack Machine 手册（镜像）**|**[OnionHop V2 - PC 版 Tor 客户端简要概述](https://web.archive.org/web/https://graph.org/OnionHop-V2--kratkij-obzor-Tor-klienta-dlya-PK-04-04)**|
| | |

*在阅读手册时使用镜像，勿点击自动链接，而是手动复制文本并粘贴到下一个标签页，因为镜像中的链接会指向同一镜像中的链接，而不是直接跳转到 Github。*

**它的工作方式类似于：“VPN 配置”+“VPN 客户端”。**

**它能持续多久？连接可以持续好几天不断掉线，或者直到你自己断开。** 

我最长的连续使用是 7 天，我关闭它只是因为需要重启电脑。 

一些单独的桥接已经运作了好几年！这就是稳定性！

一切运作方式与普通 VPN 相同，只不过你电脑上的所有流量都通过 Tor 网络。 

**与标准 Tor 浏览器的区别** 在于不仅是 Tor 浏览器单独运行，而是 **整个 PC 都通过 Tor**：所有浏览器和应用程序，包括通讯工具（WhatsApp、Telegram）都可发送/接收消息和文件。

在说明文件中，我写到 Tor 架构中有一个细节：TCP 连接可用，UDP 连接不可用。 

**`有哪些细节，又会受到什么影响？`**

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

**大多数功能**：任何浏览器、YouTube、Instagram、Facebook、社交网络、通信、文件交换、聊天、即时通讯工具（WhatsApp、Telegram、Signal、Viber、Facetime、Discord）、AI（Google Gemini、ChatGPT、Grok）**它们的工作方式与VPN配置相同，连接完全不会中断。**

**结论：如果你需要在PC上使用稳定的VPN，那么“Tor Bridges” + “OnionHop V3”或“OnionFruit”是你的解决方案。**

**目前你找不到比这更稳定、更简单的免费解决方案。** 

移动设备请使用 **Orbot** 或 **Invizible Pro**。详细信息请见“应用程序”部分。

---

</details>

### TOR本身安全吗？

<details>
<summary><em><code> 打开 </code></em></summary> 

㋡

TOR比最复杂的付费VPN更安全，因为你的连接会经过3台服务器： 

**`你的电脑在你的网络上`** ➞ **`通过Tor 网桥接连接（服务器#1）`** ➞ **`服务器#2`** ➞ **`服务器#3`** ➞ **`访问Tor网络（互联网）`**

第1台服务器看不到第3台的IP，第3台也看不到第1台的IP。这就是Tor网络安全架构的基础，使得身处高度审查国家的用户无需担心数字监控。

**只需在你的电脑上启用TOR，就可以忘记俄罗斯联邦通信监管局和各种限制的存在！**

</details>

</details>

---

### ③ `在白名单限制下 ⚪：CIDR订阅或SNI订阅`

**[完整CIDR订阅] • [手机前150]**

**[仅限托管服务提供商：VK、YANDEX、CDNVIDEO、Beeline] • SNI订阅**

<details>
<summary><em><code> 点击箭头查看详情 </code></em></summary>

㋡

#### `a) 完整 CIDR 订阅 • 手机 TOP 150 • 仅适用于以下托管提供商：VK、YANDEX、CDNVIDEO、Beeline`
  
  对白名单 IP（CIDR 网段）的最严格封锁现在仅适用于移动运营商 Megafon、Beeline、MTS、T2、Yota 等，因此 `带有白名单/俄罗斯 IP（来自白名单/俄罗斯 CIDR 网段）、突破移动互联网最严格限制的配置，我放在以` **[CIDR 订阅](#---white-list--)** 开头的 TXT 订阅中，并在每个配置的备注中标记为`[*CIDR]`。

**根据客户端选择订阅格式：标准或 Clash**。
  
  这些配置当然在正常条件下也可以与黑名单一起使用，但你不应该这样做！为什么？仅仅是为了不让订阅过载，以便那些真正需要它们并且在受限互联网的地区生活数月的人可以正常使用！仅在你确实需要时使用 CIDR 配置！

⚡ CIDR 订阅是绕过限制的通用（非 100% 个性化）解决方案。部分配置可能工作，另一部分可能有另一种配置，第三部分可能有第三种配置。为什么？不同运营商、不同地区封锁情况不同，实际可用的“白名单子网”对每个人也不同，并非每个人都相同，只有你自己可以检查哪种适合你。某些地区即便经过验证的、可用的“白名单子网”，在检测到个别 IP 异常活动后也可能被关闭。尝试、检查并分享你的经验。

⚡ 有时，除了 VLESS 外，完整 CIDR 订阅还包括 Trojan、Shadowsocks、Hysteria2 等协议。请查看 - 它们在列表的最底部。

⚡ 在“白名单”模式下，尽量不要通过 CIDR 订阅中的配置访问“Roskomnadzor 白名单”中的网站，这可能是将来被封禁的原因之一！例如，如果你需要登录 VKontakte，请先关闭 VPN，然后再登录！
  
#### `b) SNI 订阅`
  
  绕过最轻量 SNI 白名单阻止（仅按域名）的配置，我把它放在 TXT 订阅中 **[SNI SUBSCRIPTION](#---white-list--)**。它们在每个配置的备注中标记为 `[SNI-RU]`，所有 SNI 也为了方便而进行了签署。

  目前，由于易于绕过，移动运营商并不使用 SNI 阻止，因为几乎任何人都可以在国外租用并设置包含必要白名单的伪域名的服务器。

  **SNI SUBSCRIPTION** 目前 **可以安全作为黑名单使用**，因为在当前条件下，它并不绕过白名单机制。

  *更新：现在 SNI 订阅会自动添加到黑名单，以提高多功能性。*

  </details>

---

## <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3Yml0MndhcDZ6dzFuYjY3aG0yNWowN2Rqbnp1aTV2cXNvb3FvMnluMiZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/MxryCOQuSYVVD0SPyp/giphy.gif" width="40"> `如何在我的设备上使用这些配置？` 

### `一般说明/建议：`

1) **首先，选择订阅选项 黑名单或白名单 `➞`，然后选择其类型（移动版、完整版等） `➞`，然后根据客户端选择订阅格式：通用（标准）、Clash 或特定客户端的特殊格式（v2rayN、v2rayNG、Happ、Streisand、v2rayTun、V2Box）。**

2) **强烈建议使用在后台具有自动健康检查功能的订阅/客户端组合。** 为什么？所有公开配置往往在最出乎意料的时刻停止工作，有时不太频繁，有时较频繁。为了不反复对整个列表进行 ping，也不必时时搜索最佳配置，你需要手头有合适的订阅/客户端，它们会自动为你完成这些工作。在大多数情况下，这通过所谓的负载均衡器实现，但名称可能有所不同。

### `推荐带自动健康检查的“订阅 + 客户端”组合：`

| | | |
|:---:|:---:|:---:|
| **①** | **②** | **③** |
| **`通用（标准）格式`（来自常规字符串 vless://、ss://、trojan:// 等，带 .TXT 扩展名）** | **`Clash 订阅格式`（带 .YAML 扩展名的订阅）** | **`用于独立客户端应用程序的格式`（带 .JSON 扩展名的订阅）** |
| **➕** | **➕** | **➕** |
| **`Karing 客户端(PC/iOS/Android)、Shadowrocket(iOS)、V2Box(iOS)、Exclave(Android)`** | **`Mihomo/Clash 兼容客户端`**：Clash Verge Rev、Clash Mi、Clash Lite、Stash - 基于规则的代理、ClashMetaForAndroid、FlClash | **`客户端本身`**：v2rayN(txt)、v2rayNG、Happ、Streisand、v2rayTun、V2Box(Android) |
| *自动化在客户端本身配置，即 V **Karing**、Shadowrocket、Exclave 或 V2Box(iOS)* | *自动化可以在客户端本身配置（对普通用户更困难），或者通过订阅提供（推荐，无需操作）。在 Igareck 仓库中，所有自动健康检查和路由设置都已内置到 Clash 订阅中，方便使用* | *在 Igareck 仓库中，所有自动验证和路由设置都已经内置在这些订阅中。这些订阅是自动“一键式”选项：导入、设置每小时自动更新、启动，服务器本身在后台切换和检查。它消失了——它们只需重新连接，就完事了。一键操作，无需庞大列表* |
| | | |

### `最稳定的是 Clash/Yaml 订阅 + Mihomo 客户端 和 Standard + Karing。`

3）在您的设备上添加 VPN 配置的最方便方式是通过 Karing、Clash Verge Rev、Clash Mi、ClashMetaForAndroid、v2rayN、Throne、v2rayNG、Streisand、Happ 等中的 `new profile`、`add profile`、`subscription` 或 `subscription group`。

4) 从 Github 复制 TXT/YAML 文件的 URL。确保它是 RAW 链接，而不是普通链接！复制链接后，在应用中需要点击 `从剪贴板添加` 或使用常规按钮 `添加` ➞ `手动配置` ➞ 输入 `订阅` ➞ 插入 TXT/YAML 文件的 RAW 链接并为订阅命名。

5) **如果更方便，可以扫描订阅二维码**。二维码更加简单：在手机上按一下按钮 `添加` ➞ `扫描二维码` ➞ 应用程序/客户端将使用相机扫描二维码并自动创建订阅，你只需在手机上更改其名称，并在配置列表未立即加载时点击“更新”按钮。
   
   VPN 配置的二维码位于订阅链接下方（“下载 VPN 配置”版块）。

   Tor 网桥的二维码也位于订阅链接下方，但你必须点击标有“二维码”的箭头。
   
6) **如何检查哪些配置/服务器目前在线并可用？**

   点击所有订阅（在组名上）或单独配置，通常需要长按——会出现菜单，选择 **注意！** **`实时延迟测试`**、**`延迟`** 或 **`网址测试`**！不要选择“TCP Ping”或“ICMP Ping”——它们不会显示 VPN 服务器的实际可用性。那些显示绿色数字的——选择它们。选择数值最低的数字，因为……数字越低，延迟越低，服务器响应你的请求越快。

7) **强烈建议每 1-2 小时启用自动订阅更新**。配置经常更新，因为……随着时间推移，它们可能会停止工作。因此，启用更新后，你将获得包含可用配置的最新订阅版本，而不会有不必要的“垃圾”。

8) 检查“实际延迟”时，特别是白名单中的配置，可能不会立即显示为绿色；很多时候 ping 两三次或四次会显示新的可用服务器。

9) 下载几个不同的客户端到你的手机——不同客户端可能会看到不同的可用服务器。这是由于客户端在检查配置时设置的差异造成的。

10) 您也可以手动分别添加所有内容，只需将 TXT/YAML 文件的内容复制到 Karing/Throne/v2rayN 客户端中，但使用订阅更方便，因为在 Github 更新后，它们会自动在您的设备上更新，无需重新删除和复制，从而简化了流程。

---

## 🧾 `每个客户端的单独说明`


<details>
<summary><strong><code> OnionHop V3 手动说明 </code></strong> ⬅ 点击打开 </summary>

---

### `OnionHop V3`

手册是根据 V2 版本制作的，我稍后会更新到 V3，但总体来说一切都类似。

**[OnionHop V2 - PC 版 Tor 客户端简要概述（原版，可通过 VPN 或 Tor 访问）](https://telegra.ph/OnionHop-V2--kratkij-obzor-Tor-klienta-dlya-PK-04-04)**

**[OnionHop V2 - PC 版 Tor 客户端简要概述（镜像）](https://web.archive.org/web/https://graph.org/OnionHop-V2--kratkij-obzor-Tor-klienta-dlya-PK-04-04)**

---

</details>


<details>
<summary><strong><code> Karing 使用说明 </code></strong> ⬅ 点击打开 </summary>

---

### `Karing` 

https://github.com/KaringX/karing/blob/main/README_ru.md

**[Karing – 快速入门 第 1 部分（原版，可通过 VPN 或 Tor 访问）](https://telegra.ph/Karing-Part1-02-16)**

**[Karing – 快速入门 第 1 部分（镜像）](https://web.archive.org/web/https://graph.org/Karing-Part1-02-16)**

**[Karing – 快速入门 第 2 部分（原版，可通过 VPN 或 Tor 访问）](https://telegra.ph/Karing-Part2-02-15)**

**[Karing – 快速入门第二部分（镜像）](https://web.archive.org/web/https://graph.org/Karing-Part2-02-15)**

*感谢用户 @Pupkin Vasya 提供的详细俄化手册。*

<details>
<summary><strong><code> 解决 Karing 中 “有 ping，但没有速度” 或 “无限加载” 的问题 </code></strong> ⬅ 点击打开 </summary>

㋡

```diff
   Go to "Settings" ⚙️ → "DNS" → "Server" → Click on "Traffic Proxy" → Uncheck all boxes except:

   https://doh.pub/dns-query
   https://dns.alidns.com/dns-query
   https://cloudflare-dns.com/dns-query
   https://dns.google/dns-query

   Or, alternatively, try one, for example: https://dns.google/dns-query.

   Other items in the "DNS" menu → There is no need to touch the "Server".
```

</details>

<details>
<summary><strong><code> 绕过 Karing 阻塞的指南 </code></strong> ⬅ 点击打开 </summary>

---

来自用户 @999ivan33

**移动网络和 Wi-Fi 下稳定运行的配置**

**1. 导入配置和管理配置文件**

· 订阅：通过“添加配置链接”添加 → 粘贴原始订阅 URL（推荐 BLACK_VLESS_RUS_mobile.txt 手机使用或 BLACK_VLESS_RUS.txt 电脑使用）。启用自动更新。

· 单独密钥：从剪贴板导入。每个密钥或订阅会创建一个独立的配置文件。导入时通过多选可以将多个密钥添加到同一个配置文件。

· 选择服务器：在主界面点击服务器名称 → “延迟测试”。使用“自动选择”可自动切换到最快的服务器。

**2. 路由规则（分流/Split-Tunneling）**

规则从上到下处理，直到匹配到第一个条件。最后一条是用于未匹配流量的陷阱。

· 一般方法：为不同类型的流量创建独立组。在每个组中激活内置规则集（build-in），如有必要，添加 domain_suffix 和应用程序包 ID（仅限 Android）。

· 俄罗斯服务（政府服务、银行、市场）：

  · 逻辑操作：或（OR）。
  
  · 规则集（build-in）：geosite:ru（基本）+ geoip:ru（如果不影响通话）。
  
  · 操作：“直连”（Direct）。
  
  · 原因：来自 .ru/.su/.рф 区域和俄罗斯 IP 的所有流量绕过 VPN，以获得最大速度并避免 IP 制裁阻塞。
  
· 即时通讯（Telegram/AyuGram、WhatsApp）：

  · 问题：封锁攻击会攻击通话协议。GeoIP 路由使流量容易受到 DPI 攻击。
  
  · 解决方案：为每个应用创建独立规则。
  
  · 对于 AyuGram：
  
    · 规则集（build-in）：geosite:telegram, acl:Telegram。务必禁用 geoip:telegram。
    · domain_suffix（可选，为保险起见）： t.me, telegram.org。
    · 包 ID: com.radolyn.ayugram.
    · 操作: “自动选择” 或 “当前服务器”。
    
  · 针对 WhatsApp:
  
    · 规则集（内置）: geosite:whatsapp.
    · 域名后缀: whatsapp.net, whatsapp.com （由于 NDIS 阻止，两个都是必需的）。
    · 包 ID: com.whatsapp.
    · 操作: “当前服务器”。
    
· 人工智能服务（ChatGPT, Claude, Gemini, Grok 等）:

  · geosite:ai 没有单一分类。我们从组件中组装:
  
  · 规则集（内置）: geosite:openai, geosite:anthropic, geosite:google-gemini, geosite:microsoft（用于 Copilot）, geosite:meta, geosite:xai.
  
  · 域名后缀（适用于不在列表中的）: deepseek.com, midjourney.com, x.ai, grok.com.
  
  · 包 ID（Android）: com.openai.chatgpt, com.anthropic.claude, com.microsoft.copilot 等.
  
  · 操作: “当前服务器”。
  
· 其他被封锁的（YouTube、Discord、Instagram、GitHub）：

  · 激活相应的内置规则（geosite:youtube, geosite:discord 等）或创建一个通用“Blocked”组，列出所需类别。操作: "当前服务器"。
  
· 最终：

  · 操作: "当前服务器"。所有未包含在规则中的流量默认通过代理。
  

**3. DNS：流分离**

目标：通过本地 DNS 快速解析到俄罗斯服务器的请求，而被封锁的则通过加密隧道解析。

· 协议：仅使用 DNS-over-HTTPS（DoH）（https://）。UDP（udp://）不提供隐私，TLS（tls://）在 853 端口容易被封锁，本地/dhcp://auto - 无控制。

· "DNS 服务器"（用于提升 VPN）：保持 https://223.5.5.5/dns-query （AliDNS）。

· "代理服务器"（备用，最终流量）： https://1.1.1.1/dns-query （Cloudflare）， https://8.8.8.8/dns-query （Google）。为容错选择两个。

· "直连流"（用于俄罗斯服务）：

  · 基本： https://common.dot.dns.yandex.net/dns-query. 位于俄罗斯境内，ping 最低。
  
  · 备用：添加 https://1.1.1.1/dns-query 和 https://8.8.8.8/dns-query.
  
  · 手动添加: 通过“+” → ISP字段（名称），URL字段（地址）。
  
· “代理流量”（用于被屏蔽）：与“代理服务器”相同 - Cloudflare + Google。

· 其他设置：

  · TUN HijackDNS：启用。
  
  · 启用DNS规则：启用（流量分流所需）。
  
  · [直连流量] 启用ECS：启用。
  
  · [代理流量] 解析方法：不使用FakeIP。将解析方法字段留空。相反，启用选项“[代理流量] 通过代理解析DNS”。这将强制请求通过标准VPN隧道路径，而无需不稳定的IP模拟。
  
  · TTL: 2小时（缓存的最佳值）。
  
  · 优先使用静态IP解析：禁用。
  
  · 静态IP：DNS部分的子项。类似系统hosts文件 - 留空。

**4. TUN精细调整**

· TUN模式：启用。

· MTU：1400（对于防止分片至关重要）。

· 严格路由：启用。

· 堆栈（Stack）：gvisor（最大隔离）。

· UDP 超时：1 分钟。

· 注意：TLS 设置（分片、混合 SNI）不在 TUN 部分，而是在单独的菜单部分（见第 6 点）。

**5. 配置文件管理和自动服务器选择**

· 服务器组：在“配置文件和服务器”部分，你可以创建自己的组（例如，“流媒体”、“种子下载”、“新闻”）并将节点分配到它们中。

· 自动选择模式：当你为一个组选择自动选择模式时，Karing 不会不断切换服务器。它仅在当前服务器显著恶化或停止响应时，或根据计划（通常每几分钟一次）切换到另一个节点。

这可以消除配置正确时“切换过于频繁”的问题。

· 延迟检查（延迟检查 URL）：标准地址 http://www.gstatic.com/generate_204 在一些代理上可能不稳定。如果你注意到服务器频繁更换，请使用以下替代地址之一：
  
  · http://www.google.com/generate_204
  
  · http://connect.rom.miui.com/generate_204
  
· 找到设置：设置 → 延迟检测 URL（或延迟）。

**6. TLS 分片和 DPI 绕过**

· 这是主设置菜单中的一个独立部分，与 TUN 无关。

· 所有选项（分片、混合 SNI、填充）默认关闭。它们是为应对激进 DPI 而设计，会降低速度和稳定性。

**7. 配置传输和跨平台**

· 备份：设置 → 备份 → 导出为 .zip 文件。包含 json 配置文件、规则、密钥。

· 传输到 iPhone（iOS）：

  · 在 Android 上，在“通过局域网同步”中生成二维码。
  
  · 在 iPhone（iOS 15+）上安装 Karing，扫描二维码。
  
  · 注意：基于应用包 ID（Android）的规则可以迁移，但在 iOS 上无效。需要手动替换为 domain_suffix 规则（例如，对于 AyuGram - domain_suffix: telegram.org）。

**8. 解决与路由器（OpenWrt）的冲突**

· 症状：通过 Wi-Fi 访问公共服务（及其他俄罗斯服务）无效，显示错误“出于安全原因访问受限。”

· 原因：路由器上强制 DNS 重定向或与提供商的 DNS 冲突。

· 解决方案：
  · 在 OpenWrt 界面中，禁用 DNS 重定向：网络 → DHCP 和 DNS → 取消选中 DNS 重定向。
  
  · 在 WAN 上配置静态 DNS：网络 → 接口 → WAN → 高级设置 → 使用自定义 DNS 服务器，添加 77.88.8.8, 77.88.8.1。
  
  · 重启路由器。

  ---

</details>

---

</details>


<details>
<summary><strong><code> Clash Verge Rev 使用说明 </code></strong> ⬅ 点击打开 </summary>

---

### `Clash Verge Rev`

**https://github.com/clash-verge-rev/clash-verge-rev/releases**

Clash Verge Rev 仅适用于 Clash YAML 格式的配置文件。

*尝试导入非 YAML 订阅时，Clash Verge Rev 会报错，例如 `远程配置文件数据不是合法的 yaml`，或 `配置文件不包含代理或代理提供者`.*

支持所有现代 VLESS、Trojan、VMess、Hysteria2 协议，但这些协议必须用 Clash 配置格式描述。客户端本身运行在 Mihomo 内核上，前称 Clash.Meta。

我自己开始积极使用 Clash Verge Rev，感觉有 VPN 的互联网几乎不间断，配置会在后台自动检查并相互更改，顺畅到我都没注意到它。也许这个客户端甚至比 Karing 更好，因为 Karing 有时长时间运行后仍需要强制重启。

**要使用此客户端，请仅使用来自名为 Clash 的仓库文件夹中的 YAML 订阅：** https://github.com/igareck/vpn-configs-for-russia/tree/main/Export/Clash

**Igareck 已经在所有 Clash 订阅中内置了后台配置自动健康检查，以方便用户。**
  
**Clash 订阅按地区划分：**
  
- **针对俄罗斯用户的Clash订阅**（RU-DIRECT，可让所有俄罗斯网站无需VPN访问）： 

https://github.com/igareck/vpn-configs-for-russia/tree/main/Export/Clash/RU_DIRECT

- **国际选项的Clash订阅**（适用于其他不需要RU-DIRECT的国家）： 

https://github.com/igareck/vpn-configs-for-russia/tree/main/Export/Clash/GLOBAL

**所有设置将在客户端导入时自动获取。**

**用户只需在客户端每隔一到两个小时配置订阅的自动更新并运行配置：** 

1. 进入“配置文件”部分，对导入的配置右键点击(RMB)；
2. 在下拉菜单中点击“修改信息”；
3. 在弹出的菜单中，激活“允许自动更新”开关，输入更新间隔（以分钟为单位，例如60或120）。如果需要，可以编辑标题/描述；
4. 最后，点击“保存”；
5. 然后对导入的配置右键点击(RMB)，选择“更新”或“通过代理更新”以从订阅加载配置；
6. 然后进入“代理”部分；
7. 在配置列表右上角，点击过滤器图标（形状像漏斗图标 🌪️），左侧会出现一个输入框；
8. 在输入框中输入“delay<5000”以隐藏不可用服务器（请注意，它们不会立即消失，而是在后台扫描重复进行5-10分钟后消失）；
9. 然后再次点击过滤器图标（看起来像一个漏斗图标 🌪️）以隐藏输入字段；
10. 然后转到“设置”部分；
11. 在左上角的“设置”部分，找到“TUN模式”，在其右侧有一个带有“安装服务”字样的小蓝色扳手图标，点击它并等待安装。确认“TUN模式”和“系统代理”的开关已激活；
12. 然后转到“主页”部分；
13. 在“主页”部分，找到“网络设置”面板，选择所需的操作模式：“系统代理”或“TUN模式”，使用开关按钮激活它。通常只需激活其中一个模式即可，但有时为了完全运行需要同时激活两者，根据情况而定；
14. 完成！
15. “主页”部分显示Clash Verge Rev客户端配置的运行统计：速度、上传/下载、出口-IP/ASN等。
16. **针对俄罗斯（RU-DIRECT，使所有RU网站无需VPN）提供带自动健康检查的现成YAML配置文件，用于全局配置Clash Verge Rev客户端本身。** 

    **不必要，因为同样的设置会随Igareck订阅自动生效。普通用户可以跳过此步骤，在步骤15停止。**这是为了用户方便，按以下原则：添加订阅后即可立即使用。

    **在哪里添加？** **转到“配置文件”部分，找到“全局合并配置”，右键（RMB）-“编辑文件”，删除全部内容并插入下面块中的现成YAML设置，点击“保存”。**

    **为什么要这样做？** 对于高级用户：如果需要在Clash Verge Rev客户端中手动更改任何Clash订阅选项，并使其对所有输入订阅全局生效。在Clash Verge Rev客户端记录的设置将覆盖所有输入的Clash订阅中匹配的设置。

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
<summary><strong><code> Exclave指南 </code></strong> ⬅ 点击打开 </summary>

## `Exclave`

在 Android 上设置Exclave的说明

### 1. 安装

从 [官方仓库](https://github.com/ExclaveNetwork/Exclave/releases) 下载 Exclave。

### 2. 添加订阅

1. 复制订阅链接。
2. 打开Exclave。
3. 打开左侧侧边菜单 `☰`。
4. 前往 **配置** 部分。
5. 点击右上角按钮 **添加配置文件** — 带加号的叶子图标。
6. 选择 **从剪贴板导入**。
7. 通过按钮 **导入订阅** 确认操作。
8. 打开左侧的侧边菜单 `☰` → **群组**。
9. 如果新群组旁边显示 **尚未更新**，点击刷新箭头按钮。
10. 在新群组旁边，点击铅笔图标以进行编辑。
11. 在群组设置中，设置 **群组名称**，按延迟 **排序**，在下面的更新设置中，启用 **自动更新** 并设置 **自动更新延迟（分钟）** 为 60 或 120。
12. 在右上角，点击对勾以应用更改。

下载订阅后，返回 `☰` → **配置**

点击 `⋮` → **连接测试** → **URL测试** 进行初始手动测试。但务必继续进行以下第3、4、5点的设置。


### 3. 推荐设置

在 `☰` → **设置** 中安装：

| 设置                                             | 含义                                                        |
| ------------------------------------------------ | -----------------------------------------------------------|
| 服务模式                                         | `VPN`                                                       |
| TCP/IP 协议栈                                    | `gVisor`                                                    |
| IPv6 路由                                        | 关闭                                                        |
| 局域网绕过                                        | 包含                                                       |
| 域名解析策略                                      | `原样`                                                     |
| 启用流量分析                                      | 包含                                                       |
| 覆盖目标                                          | 关闭                                                       |
| 路由模式                                          | RU-DIRECT 模式下使用 `rule` 或全代理模式下使用 `global`      |
| 远程 DNS                                         | `https://dns.google/dns-query`                             |
| 远程 DNS 策略                                     | `仅 IPv4`                                                  |
| 使用本地 DNS 作为直连 DNS                         | 包含                                                        |
| 直连 DNS 策略                                     | `仅 IPv4`                                                  |
| 使用系统 DNS 作为启动 DNS                         | 包含                                                        |
| 启用 DNS 路由                                    | 包含                                                        |
| 启用假 DNS                                       | 关闭                                                        |

对于 `☰` 部分的 RU-DIRECT 模式，必须存在 → **路由** 规则：

```diff
geosite:category-ru → bypass
geoip:ru            → bypass
geoip:private       → bypass
```

如果这些规则存在，则一切正常。

如果这些规则不存在，必须通过左上角的菜单手动添加 `☰` → **路线** → `⋮` → **从剪贴板导入**。

RU-DIRECT 规则本身可以从这里复制：

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

确保出现三个规则并已启用：
* RU-DIRECT: 本地和私人 IP；
* RU-DIRECT: 俄罗斯域名；
* RU-DIRECT: 俄罗斯 IP。
在每条规则中，出站方向应显示为 **绕过**。
如果 VPN 已经连接，请先禁用然后重新启用它。


### 4. 自动选择最佳节点

要进行自动健康检查并选择最佳节点：

1. 打开 `☰` → **配置**。
2. 点击右上角的按钮 **添加配置文件** — 带加号的叶子图标。
3. 选择 **手动设置** → **负载均衡器**。
4. 指定：

```diff
Profile name: Igareck Auto Select
Type: Groups
Strategy: leastPing
Group: Select imported subscription
Custom Connection Test URL: https://www.gstatic.com/generate_204
Interval between checks: 300
```

5. 点击右上角的勾选按钮保存。
6. 在 `☰` → **配置** 部分选择新创建的负载均衡器。

### 5. 连接

1. 在 `☰` → **配置** 部分，为手动模式选择单独的节点，或选择创建的负载均衡器 `Igareck 自动选择` 作为活动配置（推荐）。
2. 点击屏幕底部的连接按钮（纸飞机图标）。
3. 第一次启动时，确认 Android 系统的 VPN 连接创建请求。


---

</details>


<details>
<summary><strong><code> Shadowrocket 使用说明 </code></strong> ⬅ 点击打开 </summary>

---

### `Shadowrocket`

https://github.com/hiddify/Hiddify-Manager/wiki/Tutorial-for-ShadowRocket-app

**1. RU-DIRECT 配置文件**

**[下载 Shadowrocket_RU_DIRECT_ROUTING.conf](https://raw.githack.com/igareck/GoldCaviar/main/Files/Shadowrocket_RU_DIRECT_ROUTING.conf)**

<details>
<summary><code> 打开 </code></summary>

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
# ZH-CN
# 此文件不包含代理节点。
# 请先向 Shadowrocket 添加普通的 RAW/Base64 订阅，并配置
# Shadowrocket 内置的代理自动测试/选择功能。然后导入此 .conf 文件，
# 并在“配置”（“设置”）路由模式中将其启用。
#
# RU-DIRECT 表示俄罗斯域名和 IP 地址使用 DIRECT。所有其他外部
# 互联网流量均使用 PROXY。本地主机、私有网络和局域网设备也
# 保持使用 DIRECT，以确保路由器和本地设备仍可正常访问。
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


**2. GLOBAL 配置文件**

**[下载 Shadowrocket_GLOBAL_ROUTING.conf](https://raw.githack.com/igareck/GoldCaviar/main/Files/Shadowrocket_GLOBAL_ROUTING.conf)**

<details>
<summary><code> 打开 </code></summary>

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
# ZH-CN
# 此文件不包含代理节点。
# 请先向 Shadowrocket 添加普通的 RAW/Base64 订阅，并配置
# Shadowrocket 内置的代理自动测试/选择功能。然后导入此 .conf 文件，
# 并在“配置”（“设置”）路由模式中将其启用。
#
# GLOBAL 表示所有外部互联网流量均使用 PROXY。本地主机、私有网络和
# 局域网设备保持使用 DIRECT，以确保路由器和本地设备仍可正常访问。
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
<summary><strong><code> v2rayN, v2rayNG 使用说明 </code></strong> ⬅ 点击打开 </summary>

---

### `v2rayN, v2rayNG`

**[在 Windows 上设置 V2rayN（镜像）](https://web.archive.org/web/https://vpnpanels.com/ru/p/setup-v2ray-windows)**

**[在 Android 上设置 V2rayNG（镜像）](https://web.archive.org/web/https://vpnpanels.com/ru/p/setup-v2ray-android/)**

<details>
<summary><strong><code> v2rayN - 客户端设置 1 </code></strong> ⬅ 点击打开 </summary>

---

安装官方 v2rayN 客户端，以“管理员模式”运行。

进入“设置” - “区域预设”，选择“俄罗斯”。点击“重启”菜单或重新启动应用程序。

通过 **订阅组 - 订阅组设置** 添加订阅，通过 **订阅组 - 更新当前订阅（无代理）** 下载订阅，将会显示一个列表。

点击“真实延迟”检查（右上角闪电图标），完成后 - 按 Ping 值排序，选择顶部几个绿色的、数值最低的配置。

选择几个 Ping 值最低的服务器，右键点击，选择“服务器加载速度测试”，测试完成后按 Enter 选择最快的。但最近即使是在线服务器，v2rayN 的速度测试也显示假结果，因此我会冷静地只关注 Ping。在我的订阅中，如果服务器有 Ping 值，原则上应能工作。

最后，启动“VPN 模式/TUN 模式”，或者激活“设置系统代理”。右侧选择路由规则“RUv1-除 RF 外的所有”，以确保 VPN 不用于访问 RU 网站。

---

</details>

<details>
<summary><strong><code> v2rayN - 客户端设置 2 </code></strong> ⬅ 点击打开 </summary>

---

**v2rayN — 客户端设置**

编译说明所用的界面版本：v2rayN 7.24.4。 

界面语言为英语。

下面完成的行复制到指定的 v2rayN 字段中，开关手动设置一次即可。


**`1. DNS 设置`**

**路径：设置 -> DNS 设置 -> 基本 DNS 设置**

**国内 DNS**

一行插入：

```diff
8.8.8.8,8.8.4.4,9.9.9.9,94.140.14.14,76.76.2.0,76.76.10.0,1.0.0.1,1.1.1.1,208.67.220.220,208.67.222.222
```

**远程 DNS**

一行插入：

```diff
https://dns.google/dns-query,https://dns.quad9.net/dns-query,https://dns.adguard-dns.com/dns-query,https://freedns.controld.com/p0,https://dns.mullvad.net/dns-query,https://cloudflare-dns.com/dns-query,https://doh.opendns.com/dns-query,https://doh.libredns.gr/dns-query,https://doh.dns4all.eu/dns-query,https://wikimedia-dns.org/dns-query,https://dns.hostux.net/dns-query,https://blank.dnsforge.de/dns-query
```

**引导 DNS**

一行插入：

```diff
8.8.8.8,8.8.4.4,9.9.9.9,94.140.14.14,76.76.2.0,76.76.10.0,1.0.0.1,1.1.1.1,208.67.220.220,208.67.222.222
```

其他基本 DNS 设置参数：

```diff
• Direct Target Resolution Strategy: UseIPv4
• Proxy Target Resolution Strategy: UseIPv4
• Proxy Dial Resolution Strategy: AsIs or empty value
• Parallel Query: Off
• Serve Stale: Off
• Enable Happy Eyeballs: Off
```

不要将代理拨号解析策略设置为使用IPv4：v2rayN界面
警告，该策略可能会导致路由循环。


**`2. 高级 DNS 设置`**

**路径：设置 -> DNS 设置 -> 高级 DNS 设置**

```diff
• Use System Hosts: On
• Add Common DNS Hosts: On
• FakeIP: Off
• Block SVCB and HTTPS Queries: On
• Validate Regional Domain IPs: leave blank
• DNS Hosts: leave blank
```

FakeIP 保持禁用：v2rayN界面有完整的例外列表
FakeIP 可用于 sing-box，而此公共配置文件使用 Xray。


**`3. 自定义 DNS`**

**路径：设置 -> DNS 设置 -> V2ray 自定义 DNS**

保持禁用：

```diff
• V2ray Custom DNS -> HTTP/SOCKS: Enable = Off
• sing-box Custom DNS -> HTTP/SOCKS: Enable = Off
```

“点击导入默认 DNS 配置”按钮会加载内置的 v2rayN 模板。
从磁盘单独导入的自定义 JSON 不会通过此方法导入。


**`4. 核心：基本设置`**

**路径: 设置 -> 选项设置 -> 核心: 基本设置**

```diff
• Enable UDP: On
• Turn on Sniffing: On
• Sniffing type: http, tls, quic
• Route Only: Off
• Allow connections from the LAN: Off
• Enable fragment: Off
```

如果你有意将代理分发到局域网的其他设备，
"允许局域网连接" 参数需要单独配置，以兼顾安全性。


**`5. V2RAYN 设置`**


**路径: 设置 -> 选项设置 -> v2rayN 设置**

```diff
• Speed Ping Test URL: https://www.gstatic.com/generate_204
• Automatic update interval for Geo files: 24 hours
• Number of concurrent tests during multi-test: 5
```

**`6. 订阅分组设置`**

**路径: 订阅分组 -> 订阅分组设置 -> *分组* -> 编辑** 

```diff
• Automatic update interval: 60 minutes
```

可以将订阅更新间隔增加到120分钟。


**`7. TUN 模式设置`**

**路径: 设置 -> 选项设置 -> TUN 模式设置**

```diff
• Auto Route: On
• Strict Route: On
• Stack: gvisor
• MTU: 4000
• Enable IPv6 Address: Off
• Legacy TUN Protect: On
```


**`8. RU-直连路由`**

**路径: 设置 -> 区域预设设置 -> 俄罗斯**


**`9. 更新`**

**路径：帮助 -> 检查更新**

更新客户端组件。

然后点击顶部菜单中的重新加载按钮。


**`10. 应用`**

• 在所有更改的窗口中点击确认。

• 点击重新加载或重新连接 v2rayN。

• 在 v2rayN 中直接选择 RU-DIRECT 路由。

• 在启用 TUN 按钮右侧激活 RU-DIRECT：选择“RUv1-除 RF 外全部”。

• 对于 GLOBAL，选择“RUv1-全部”。

---

</details>

---

</details>
 
**`Throne 说明:`**

https://wiki.aeza.net/en/guides/throne/

**`Streisand，v2Box 说明:`**

**[在 iOS 上设置 Streisand, v2Box（镜像）](https://web.archive.org/web/https://vpnpanels.com/ru/p/setup-v2ray-ios/)**
  
**`Nekobox 使用说明:`**

https://hiddify.com/manager/client-software-on-android/Tutorial-for-Nekobox-app/
  
**`Hiddify 使用说明:`**

https://hiddify.com/manager/client-software-on-desktop/Tutorial-for-HiddifyN-software/

https://hiddify.com/app/How-to-use-Hiddify-app/

---

### `针对 OpenWrt 路由器、NAS 和 Linux 系统的客户端说明:`

<details>
<summary><code><strong> ShellCrash 使用说明 </strong></code></summary>

### `ShellCrash`

**https://github.com/juewuy/ShellCrash**

**`1.`** **适用于各种平台的通用选项：OpenWrt 路由器及其衍生固件、NAS、Docker 和 Linux 系统。兼容 OpenWrt、Padavan、Pandora、ASUS Merlin、Debian、Ubuntu、CentOS、Armbian、Linux/BusyBox、Docker、Synology 和 PVE。**

**`2.`** **核心:** Mihomo/Sing-box。

**`3.`** **支持什么功能？** TUN、REDIRECT、PROXY、nftables/iptables、路由规则、本地网络设备规则。

**`4.`** **可在后台进行自动健康检查和节点选择，参考 Karing 示例。**

支持按计划自动更新订阅、配置和规则。在客户端作为本地策略配置：通过客户端模板。当使用适当的 Mihomo 组或 sing-box 时，可在后台自动检查和选择节点：Mihomo - `url-test` 或 `fallback`；sing-box - `urltest`。

  A. 客户端模板，Mihomo 的 `url-test` 组是 Karing 自动选择的类似功能。

  b. 客户端模板，组 `urltest` Sing-box 与 `url-test` Mihomo 不同，需要不同的设置——但它也是 Karing Auto Select（`urltest`）的一个类似物。我们在本手册中不讨论 Sing-box。

  工作原理 `url-test` Mihomo 和 `urltest` Sing-box（“a”和“b”点）：

  - 定期通过每个节点发送验证请求；
  - 测量延迟；
  - 选择结果最好的节点；
  - 按规定间隔重复测试；
  - 将新的连接切换到最佳节点。
  - 容差参数设置切换所需的最小延迟差异。这可以防止在结果几乎相同的节点之间频繁跳转。

  **4-a 和 4-b 点的结果：用户下载 Clash YAML 订阅（当在 ShellCrash 中选择 Mihomo 内核时）并使用自动订阅。** 如果需要（但不一定）可以在 ShellCrash 客户端中添加一个本地客户端模板 `url-test`，即第10点中的 YAML 配置文件。

  V. 客户端模板，组 `fallback`（自动备份）也执行后台检查，但选择的不是最快的节点，而是给定顺序中的第一个可用节点。`fallback` V **ShellCrash** —— 这是客户端 **PassWall2** 中 `Auto Switch` 的一个类似功能。

**`5.`** **接受哪些订阅？** 原生接受 Clash YAML 订阅。常规订阅（来自常规字符串 vless://、ss://、trojan:// 等）和 Base64 会在导入时自动转换为 Clash 格式。

**`6.`** **GEO 规则。** ShellCrash 包含现成的 Geo 规则集合和模板、自动 GeoSite/GeoIP 更新，以及 ACL4SSR 等流行配置，但主要针对中国。标准安装中没有现成的俄罗斯或伊朗策略；你需要通过客户端或在订阅中配置来设置。有关 ShellCrash 客户端在俄罗斯的最终配置文件，请参见第10点。对于普通用户，9 点已足够，因为所有 GEO 规则都已内置在该 Igareck 仓库的 Clash 订阅中。

**`7.`** **Clash 订阅。在该 Igareck 仓库的 Clash 订阅中，已经内置了现成的 YAML 配置文件和自动健康检查，方便用户使用：**

- 适用于俄罗斯用户的 Clash 订阅（RU-DIRECT，使所有俄罗斯网站无需 VPN 访问）： 

https://github.com/igareck/vpn-configs-for-russia/tree/main/Export/Clash/RU_DIRECT

- 国际版 Clash 订阅（适用于不需要 RU-DIRECT 的其他国家）： 

https://github.com/igareck/vpn-configs-for-russia/tree/main/Export/Clash/GLOBAL

**`8.`** **如何将 Clash 订阅添加到 ShellCrash？**

<details>
<summary><code> 展开详情 </code></summary>

首先连接到路由器：

```diff
ssh root@192.168.1.1
```

然后运行 ShellCrash：

```diff
crash
```

之后，会出现带有以下提示的文本菜单：

```diff
Please enter a number >
or
请输入对应数字 >
```

也就是说，输入 `crash` 后，我们进入 **ShellCrash 主交互菜单**，菜单中有 0 到 9 的 10 个数字选项：

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

位于 `6` 的配置管理（Configuration Management）。

接下来，输入一个数字并按 **Enter**：你需要输入数字 `6`：

```diff
6
```

接下来在菜单 **配置管理 / Configuration Management 菜单** 中：

```diff
a - add configuration/subscription provider (Add provider);
b — generate local configuration;
c — generate online configuration;
d — clear the list of suppliers;
e — select a custom configuration file.
```

输入字母/命令 `a`：

```diff
a
```

选择 `a` 后将打开一个菜单 **添加提供者 / 个人提供者编辑器**：

```diff
1 — set the name of the supplier;
2 — set a link or path;
3 — configure local override;
a — save supplier;
b - generate local configuration only from this provider;
c - generate online configuration only from this provider;
e - load this configuration directly without conversion.
```

输入数字/命令 `1`：

```diff
1
```

然后输入订阅名称：

```diff
Igareck BLACK VLESS Mobile
```

然后输入数字/命令 `2`：

```diff
2
```

粘贴链接：

```diff
https://raw.githack.com/igareck/vpn-configs-for-russia/main/Clash/BLACK_VLESS_RUS_mobile.yaml
```

之后，保存配置提供者，输入字母/命令 `a`：

```diff
a
```

接下来选择 `e` — 直接加载此配置而无需转换。供应商编辑器中的 `e` 将下载 YAML 并作为现成配置应用而无需转换：

```diff
e
```

**最终步骤：**

```diff
6 → a → 1 → Igareck BLACK VLESS Mobile → 2 → Link → a → e
```

如果不小心进入了错误的菜单，输入 `0` 并按 **Enter** 可返回上一级：

```diff
0
```

---

</details>

**`9.`** **设置 ShellCrash 订阅为每小时自动更新：**

<details>
<summary><code> 展开详情 </code></summary>

首先连接到路由器：

```diff
ssh root@192.168.1.1
```

然后运行 ShellCrash：

```diff
crash
```

接下来，每次输入一个值，每次按 **Enter**：

```diff
5 → 1 → 5 → 3 → 1 → 1
```

说明：

```diff
5 - open Scheduled Tasks / Task Scheduler.
1 - Add Task / Add a task.
5 — Hot update online subscriptions (without restart) — update your online subscription without restarting ShellCrash.
3 - Every N hours / Every N hours.
1 - perform every 1 hour.
1 — confirm adding the task.
```

**如何检查？**

返回菜单 **计划任务**，按 `2`：

```diff
2
```

这是 **管理任务 / 任务管理**。订阅更新任务应每小时出现在列表中。要返回请使用 `0`：

```diff
0
```

---

</details>

**`10.`** **ShellCrash 的现成 YAML 配置文件，带俄罗斯自动健康检查（RU-DIRECT，使所有 RU 网站无需 VPN 即可访问）通过客户端模板（url-test Mihomo，第 4-a 点）：**

***说明：本第10段是可选的**，只有高级用户在想要手动更改任何Clash订阅选项，或通过将其添加到客户端本身来使设置对任何即将到来的订阅生效时才需要。写入ShellCrash客户端本身的设置，如果与任何即将到来的Clash订阅匹配，将会覆盖它们的设置。对于普通用户，第7、8、9点以及**来自Igareck仓库的现成Clash订阅就已经足够，并且已经包含第10点中的所有设置。**这样做是为了用户的方便，遵循的原则是：添加订阅后即可立即使用。*

**ShellCrash 的设置块分布在三个文件中：** **`通用设置`** + **`分组`** + **`规则`**

<details>
<summary><code> 常规 user.yaml 参数 </code></summary>

**通用设置** `user.yaml`

选择：

```diff
ssh root@192.168.1.1
→ crash → 6 → e → 5
```

ShellCrash 将创建一个 user.yaml 文件并显示其位置。然后需要通过 WinSCP、vi 或 nano 打开该文件：

```diff
$CRASHDIR/yamls/user.yaml
```

粘贴通用参数：

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
<summary><code> 分组 proxy-groups.yaml </code></summary>

**分组** `proxy-groups.yaml`

选择：

```diff
ssh root@192.168.1.1
→ crash → 6 → e → 4
```

ShellCrash 将创建一个 proxy-groups.yaml 文件并显示其位置。

接下来：

```diff
1 — add a group manually;
2 — view created groups;
3 — clear groups;
0 - back.
```

但最好直接打开它：

```diff
$CRASHDIR/yamls/proxy-groups.yaml
```

并插入分组而不添加 `proxy-groups:` 行。内置菜单不允许你设置所有参数，如 `include-all`、`exclude-type`、`tolerance`、`lazy` 等。

粘贴分组内容，不加 `proxy-groups:` 行：

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
<summary><code> 规则 rules.yaml </code></summary>

**规则** `rules.yaml`

选择：

```diff
ssh root@192.168.1.1
→ crash → 6 → e → 2
```

ShellCrash 将创建一个 rules.yaml 文件并显示其位置。

接下来：

```diff
1 — add one rule manually;
2 — delete the rule;
3 — clear the rules;
0 - back.
```

但最好直接打开它：

```diff
$CRASHDIR/yamls/rules.yaml
```

只插入规则行，不加 `rules:` 行：

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

**保存文件后：**

```diff
ssh root@192.168.1.1
→ crash → 6 → b
```

---

</details>



<details>
<summary><code><strong> OpenClash 使用说明 </strong></code></summary>

### `OpenClash`

**https://github.com/vernesong/openclash**

**`1.`** **最著名的 OpenWrt+LuCI 客户端之一（及兼容的衍生版本）。**

**`2.`** **核心：** Mihomo。

**`3.`** **它支持什么？** TUN、REDIRECT、PROXY、nftables/iptables、路由规则、url 测试、回退和负载均衡。

**`4.`** **可在后台进行自动健康检查和节点选择，参考 Karing 示例。**

  由 Mihomo 核心提供支持，因此这里可以使用标准的 Mihomo 群组 `url-test` 和 `fallback`。通过这些群组，配置了后台节点的自动检查和选择。在客户端作为本地策略配置：通过本地群组或覆盖模块。

  A. 组 `url-test` Mihomo 是 Karing 自动选择的一个类似物：

  - 定期通过每个节点发送验证请求；
  - 测量延迟；
  - 选择结果最好的节点；
  - 按规定间隔重复测试；
  - 将新的连接切换到最佳节点。
  - 容差参数设置切换所需的最小延迟差异。这可以防止在结果几乎相同的节点之间频繁跳转。

  **第4-a点的结果：用户下载Clash YAML订阅并使用自动订阅。** 如有必要（但不一定）添加本地组（覆盖模块），然后在OpenClash客户端中配置组 `url-test`，即第10点的配置文件。

  b. 组 `fallback`（自动备用）也执行后台检查，但选择的不是最快的节点，而是给定顺序中第一个可用节点。`fallback` 在 **OpenClash** 中是客户端 **PassWall2** 中 `Auto Switch` 的类比。

**`5.`** **接受哪些订阅？** 原生接受 Clash YAML 订阅。常规订阅（来自常规字符串 vless://、ss://、trojan:// 等）和 Base64 会在导入时自动转换为 Clash 格式。

**`6.`** **GEO 规则。** 支持 GeoIP、GeoSite、MMDB 和规则提供者；现成的内置套件主要面向中国。标准安装中没有现成的俄罗斯或伊朗策略；你需要通过客户端或在订阅中自行配置。关于 OpenClash 客户端用于俄罗斯的最终配置文件，请参见第 10 点。对于普通用户，9 点就足够了，因为该 Igareck 仓库的 Clash 订阅中已经内置了所有 GEO 规则。

**`7.`** **为了方便用户，这个 Igareck 仓库的 Clash 订阅中已经内置了带有自动健康检查的现成 YAML 配置文件：**

- 适用于俄罗斯用户的 Clash 订阅（RU-DIRECT，使所有俄罗斯网站无需 VPN 访问）： 

https://github.com/igareck/vpn-configs-for-russia/tree/main/Export/Clash/RU_DIRECT

- 国际版 Clash 订阅（适用于不需要 RU-DIRECT 的其他国家）： 

https://github.com/igareck/vpn-configs-for-russia/tree/main/Export/Clash/GLOBAL

**`8.`** **如何将 Clash 订阅添加到 OpenClash？**

在 LuCI 中：

```diff
Services → OpenClash → Config Subscription → Add
```

填写：

```diff
Enabled: enabled
Config Alias: Igareck BLACK VLESS Mobile
Subscribe Address: YAML link
User-Agent: Mihomo or Clash.Meta
Subscription Conversion: disabled
```

然后：

```diff
Save & Apply → Update Subscription
```

**`9.`** **设置 OpenClash 订阅自动续订：**

在 LuCI 中：

```diff
Services → OpenClash → Config Subscription → Auto Update: Enabled
Update Mode: Loop Mode
Update Interval: 1 hour
```
   
**`10.`** **为 OpenClash 准备 YAML 配置文件，并针对俄罗斯（RU-DIRECT，使所有 RU 网站无需 VPN）进行自动健康检查，通过本地组或覆盖模块（url-test Mihomo，第4-a点）：**

***说明：第10点为可选内容**，仅在高级用户希望手动更改任何 Clash 订阅选项，或者通过将订阅添加到客户端本身来让设置对所有传入订阅生效时才需要。在 OpenClash 客户端中设置的内容，如果与传入的 Clash 订阅匹配，将会覆盖这些订阅的设置。对于普通用户来说，第7、8、9点以及**IgaReck 仓库提供的现成 Clash 订阅就足够使用，且已包含第10点中的所有设置。**此举是为了方便用户，原则是：添加订阅即可立即使用。*

**OpenClash 的设置块分为三组：** **`通用设置和嗅探器`** + **`分组`** + **`规则`** + **`DNS 设置`**

<details>
<summary><code> 通用设置和嗅探器 </code></summary>

LuCI 路径：

```diff
Services
→ OpenClash
→ Overwrite Settings
→ Meta Settings
```

打开：

```diff
Enable Tcp Concurrent
Enable Unified Delay
Enable Sniffer
Forced Sniff Pure IP
Custom Sniffer Settings
```

在自定义嗅探器设置字段中，仅插入：

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
<summary><code> 分组 </code></summary>

LuCI 路径：

```diff
Services
→ OpenClash
→ Config Manage
→ Config File List
→ For active YAML, select Other: Servers Manage
→ Apply
```

在打开的服务器和分组管理页面上，首先点击 **读取配置**

只有这样才能通过创建组：

```diff
Proxy Groups → Add
```

OpenClash 明确警告您在更改之前必须阅读当前配置。

然后依次创建以下内容：
Igareck 自动选择（自动连接） → Igareck 手动（手动连接） → GLOBAL

**1. Igareck 自动选择**

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

在“其他参数”字段中插入：

```diff
    include-all: true
    exclude-type: "Direct|Reject|RejectDrop|Compatible|Pass|Dns"
    lazy: true
    timeout: 5000
    max-failed-times: 2
    expected-status: 204
```

然后 **提交设置**

**2. Igareck 手动**

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

在“其他参数”字段中插入：

```diff
    include-all: true
    exclude-type: "Direct|Reject|RejectDrop|Compatible|Pass|Dns"
    default-selected: "Igareck Auto Select (Auto connect)"
```

然后 **提交设置**

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

在“其他参数”字段中插入：

```diff
    default-selected: "Igareck Auto Select (Auto connect)"
```

然后 **提交设置**

创建完所有三个组后，返回“服务器与组管理”页面并点击 **应用设置**。

---

</details>


<details>
<summary><code> 规则 </code></summary>

LuCI 路径：

```diff
Services
→ OpenClash
→ Overwrite Settings
→ Rules Setting
→ Custom Clash Rules: Enable
→ Priority
```

在“优先级”字段中插入整段规则内容：

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

**之后：**

```diff
Commit Settings → Apply Settings
```

---

</details>

<details>
<summary><code> DNS 设置 </code></summary>

这里有两种选择：`当 DNS 已经来自 Igareck 订阅` 和 `如果 DNS 需要仅在本地配置`

**1. 当 DNS 设置已经来自 Igareck 订阅**

LuCI 路径：

```diff
Services
→ OpenClash
→ Overwrite Settings
→ DNS Settings
```

安装：

```diff
Custom DNS Setting: Disable
Respect Rules: Disable
Append Upstream DNS: Disable
Append Default DNS: Disable
Fake-IP Range: 198.18.0.1/16
Persistence Fake-IP: Enable
```

**2. 如果 DNS 需要在本地配置**

LuCI 路径：

```diff
Services
→ OpenClash
→ Overwrite Settings
→ DNS Settings
→ Custom DNS Setting: Enable
```

将会出现以下部分：

```diff
Add Custom DNS Servers → Add
```

OpenClash 界面只允许你添加组：

```diff
nameserver
fallback
default-nameserver
```

这非常不方便且耗时，因此最好直接通过 Igareck 订阅获取完整的 DNS 配置，而不是通过 LuCI OpenClash 收集。

</details>

---

</details>


<details>
<summary><code><strong> 指南 Nikki </strong></code></summary>

### `Nikki`

**https://github.com/nikkinikki-org/OpenWrt-nikki**

**`1.`** **比 OpenClash 更现代和紧凑的替代方案。**

   **定位为适用于 OpenWrt 24.10+、Linux 5.13+，支持 firewall4/nftables 的现代透明代理。** 

**`2.`** **核心：** Mihomo。

**`3.`** **支持哪些功能？** TUN、REDIRECT、PROXY、防火墙4/nftables 和路由规则。Nikki 不支持旧的 firewall3/iptables。

**`4.`** **可在后台进行自动健康检查和节点选择，参考 Karing 示例。**

  通过“Profile Mixin”在客户端配置为本地策略。 

  Nikki 明确提供：
   - Profile Mixin;
   - Profile Editor。

  **用户下载 Clash YAML 订阅并利用自动订阅功能。**如有必要（但不一定需要），可以在 Nikki 的“Profile Mixin”中添加第 8 步准备好的配置文件。

  Nikki 每次更新时：
   
  `下载配置文件` → `应用本地“Profile Mixin”` → `运行最终配置`

**`5.`** **它接受哪些订阅？** 仅接受 Clash YAML 订阅。导入其他格式将出现错误。

**`6.`** **GEO 规则。** 标准安装中没有现成的俄罗斯或伊朗策略；需要通过客户端或在订阅中自行配置。有关 Nikki 客户端的俄罗斯最终配置文件，请参见第 10 点。对于普通用户，9 点即可，因为所有 GEO 规则已内置于本 Igareck 仓库的 Clash 订阅中。

**`7.`** **为了方便用户，这个 Igareck 仓库的 Clash 订阅中已经内置了带有自动健康检查的现成 YAML 配置文件：**

- 适用于俄罗斯用户的 Clash 订阅（RU-DIRECT，使所有俄罗斯网站无需 VPN 访问）： 

https://github.com/igareck/vpn-configs-for-russia/tree/main/Export/Clash/RU_DIRECT

- 国际版 Clash 订阅（适用于不需要 RU-DIRECT 的其他国家）： 

https://github.com/igareck/vpn-configs-for-russia/tree/main/Export/Clash/GLOBAL

**`8.`** **如何将 Clash 订阅添加到 Nikki？**

在 LuCI 中：

```diff
Services → Nikki → Profile → Subscription → Add

In some versions the path is shown as:

Services → Nikki → Configuration Files → Subscriptions
```

填写：

```diff
Subscription Name: Igareck BLACK VLESS Mobile
Subscription URL: YAML link
User Agent: clash.meta or mihomo
Prefer: Remote
```

然后：

```diff
Save & Apply → Update
```

更新成功后，在 Nikki 主设置中选择查看配置文件：

```diff
subscription: Igareck BLACK VLESS Mobile
```

**`9.`** **设置 Nikki 订阅的自动续订：**

在 LuCI 中：

```diff
Services → Nikki → Profile → Subscription → Edit
Auto Update: Enabled
Update Interval: 1 hour
```

**`10.`** **为Nikki准备的YAML配置文件，带有针对俄罗斯的自动健康检查（RU-DIRECT，这样所有RU站点无需VPN）通过“Profile Mixin”：**

***说明：这一段第10点是可选的**，仅在高级用户需要手动更改任何Clash订阅选项，或者通过将其添加到客户端本身使设置对任何传入订阅生效时才需要。如果在Nikki客户端本身记录了设置，将覆盖所有匹配的传入Clash订阅的设置。对于普通用户，第7、8、9点以及**来自Igareck仓库的现成Clash订阅已足够，并且已包含第10点的所有设置。**这是为了方便用户，根据原则：添加订阅即可立即使用。*

<details>
<summary><code> 展开详情 </code></summary>

在Nikki中，通过Mixin文件插入块是最方便的。

路径：

```diff
Services
→ Nikki
→ Editor
→ Choose File
→ File for Mixin
```

这是文件：

```diff
/etc/nikki/mixin.yaml
```

将以下整个块粘贴到其中：

*注意：Nikki-YAML与标准YAML不同，其`rules:`块称为`nikki-rules:`。*

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

然后：

```diff
Save & Apply
```

或者，如果正常重启未应用更改：

```diff
Force Apply
```

另外检查：

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
<summary><code><strong> PassWall2 使用说明 </strong></code></summary>

### `PassWall2`

**https://github.com/Openwrt-Passwall/openwrt-passwall2**

**`1.` OpenWrt 21.02+ 的通用选项，以及LuCI和派生固件（例如ImmortalWrt）。** 

**`2.`** **核心:** Xray/Sing-box。

**`3.`** **支持什么？** 支持 REDIRECT、PROXY、nftables/iptables 和路由规则。未声明 TUN。

**`4.`** **后台自动健康检查、节点选择与切换，参考 Karing，均可使用。**

  这可以通过 Sing-Box 的 `URLTest` 实现，或者通过 `Auto Switch` 实现，例如自动切换到备用预配置节点或列表中的下一个节点。

  Sing-Box 方案 `URLTest` 在 **PassWall2** 中与 `urltest` Sing-box **ShellCrash** 类似，接近 **Karing Auto Select**：`定期检查多个节点` → `比较它们的延迟` → `选择最佳节点`。

  方案 `Auto Switch` 接近行为 `fallback` V **ShellCrash**，工作原理如下：`主节点` → `不可用` → `备用节点 1` → `不可用` → `备用节点 2` → `以此类推`。

  PassWall2 提供两种添加备用节点的方式：手动（手动列表）和批量（选择整组节点）。对于移动 TOP 150 订阅，技术上可行的选项是批量。

**`5.`** **接受哪些订阅？** 普通订阅（常规字符串 vless://、ss://、trojan:// 等），以及 Base64 格式。Clash YAML 可导入订阅，但会转换为常规格式。

**`6.`** **GEO 规则。** 支持 GeoIP/GeoSite；现成方案/模板主要针对中国：中国域名/IP 直接发送，其余通过代理发送。没有现成的俄罗斯或伊朗模式；需要在客户端自行配置——参见第 9 点关于俄罗斯的现成 GEO 规则设置。

**`7.`** **如何在 PassWall2 中添加 VPN 订阅？**

在 LuCI 中：

```diff
Services → PassWall2 → Node Subscribe → Add
```

填写：

```diff
Remark/Name: Igareck BLACK TOP 150
Subscription URL: link to TXT
```

如果有 `User-Agent` 字段，请使用/保留 `v2rayN`。

完成后，手动更新：

```diff
Save & Apply → return to Node Subscribe → Manual subscription All (Update All Subscriptions)
```

节点将出现在 LuCI 的节点列表中：

```diff
Services → PassWall2 → Node List
```

**`8.`** **设置 PassWall2 订阅的自动续订：**
   
   **每个订阅的自动续订在其 PassWall2 参数中单独配置。**

在 LuCI 中：

```diff
Services → PassWall2 → Node Subscribe → edit subscription
```

   有：

```diff
Update Once on Boot - update once after booting the router; disabled by default.
 
Auto Update Mode:
   - Disable;
   - Loop Mode - update cyclically;
   - Every day;
   - selected day of the week.
```

选择自动更新模式和循环模式。

对于循环模式，间隔可以设置为 1 到 24 小时；默认值为 2 小时。
   
对于每日或每周模式，设置特定的更新时间。

   **对于 Igareck BLACK TOP 150 订阅：**
   
```diff
Auto Update Mode: Loop Mode
Update Interval: 1 hour
```

**`9.`** **PassWall2 客户端内的现成设置：**
  
**自动选择（自动健康检查）+ 直接访问俄国资源（RU-DIRECT），在 PassWall2 客户端内配置**

*说明：这里自动 YAML 设置不起作用，因为它不是 Mihomo/Clash 客户端，而是 Xray/Sing-box。*

A. 在第 8 步中，我们已经导入订阅并为其分配了一个单独的组（备注/名称）`Igareck BLACK TOP 150`。

b. 然后在 `Node List → Add Node` 中创建一个节点：

在 LuCI 中：

```diff
Services → PassWall2 → Node List → Add Node
```

* 节点备注：`Igareck 自动选择`
* 类型/核心：`Sing-Box`
* 协议：`URLTest`
* 节点添加方法：`批量`
* 选择分组：`Igareck BLACK TOP 150`
* 节点匹配规则：留空
* 探测 URL：`https://www.gstatic.com/generate_204`
* 测试间隔：`5m`
* 测试容差：`150`
* 空闲超时：`30m`
* 中断现有连接：禁用

五. 在 `Rule Manage` 中创建规则：

在 LuCI 中：

```diff
Services → PassWall2 → Rule Manage
```

规则 `LOCAL`：

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

规则 `RU-DIRECT`：

```diff
Domain:
geosite:category-ru
domain:ru
domain:xn--p1ai

IP:
geoip:ru
```

d. 创建一个节点 `Sing-Box Shunt`：

在 LuCI 中：

```diff
Services → PassWall2 → Node List → Add Node
→ Type/Core: Sing-Box
→ Protocol: Shunt
```

然后分配规则 `Sing-Box Shunt` 并保存：

```diff
LOCAL → Direct Connection
RU-DIRECT → Direct Connection
Default → Igareck Auto Select (node created in step 9-b `Sing-Box URLTest`)
→ Save & Apply
```

e. 选择 Shunt 作为主节点：

```diff
Services → PassWall2 → Basic Settings → Main
→ Node → select the created Sing-Box Shunt
→ Save & Apply
```

结果是，俄罗斯和本地资源将被直接打开，其余流量将通过所选订阅组中延迟最佳的节点打开。

---

</details>



<details>
<summary><code><strong> Instructions dae/daed </strong></code></summary>

### `dae/daed`

**https://github.com/daeuniverse/dae**

**https://github.com/daeuniverse/daed**

**`1.`** **适用于现代 Linux 服务器系统、迷你电脑和基于 Linux 的无 GUI 网络网关的高性能解决方案。** 

**`2.`** **核心：** 独立的代理核心 `dae`。该项目不使用 Xray、Sing-box 或 Mihomo。开发者直接说明，该项目作为 v2rayA 的继任者，已放弃 v2ray-core。`dae` 是独立的代理内核，而 `daed` 提供基于浏览器的控制面板。

**`3.`** **它支持什么？** 相较于基于 Xray/Sing-box/Mihomo 的经典客户端，dae 拥有不同的架构；流量通过 Linux 中的 eBPF/PF 机制直接被拦截和分类。因此，将其描述为常规的 TUN/iptables 客户端并不完全正确。 

**`4.`** **可在后台进行自动健康检查和节点选择，参考 Karing 示例。**

  在配置之间有自动背景选择/切换功能。对于 dae 来说，这已经是内核自身的内置功能。

  配置指定了一组节点和策略，例如：

  `policy: min_moving_avg`

  dae 会定期执行节点检查。官方示例设置了时间间隔：

  `check_interval: 30s`

  允许的差异也被设置：

  `check_tolerance: 150ms`

  这意味着只有当新节点的结果比当前节点至少好到达指定值时，才会被选中。这个阈值可以防止在两个几乎相同的节点之间频繁切换。

  Auto Select dae 在概念上类似于 Karing 中的 Auto Select。

**`5.`** **它接受哪些订阅？** 仅常规订阅（来自常用字符串 vless://、ss://、trojan:// 等），以及 Base64。

**`6.`** **GEO 规则。** 有地理规则机制，但没有现成的配置文件。在配置中你可以使用：geoip:ru, geosite:ru, geoip:cn, geosite:cn（如果有相应数据库可用）。对于 category-ru 和 geoip:ru 规则，必须安装当前的 geosite.dat 和 geoip.dat。第一次安装时不包含开箱即用的国家策略。

**`7.`** **如何在 dae 中添加 VPN 订阅以及现成的配置？**

**准备好的配置文件 / 配置文件 dae: RU-DIRECT + 自动选择 (dae/daed 不使用 YAML，而是使用自己的 .dae 配置格式)**

   *说明 1: 此配置文件是为黑名单 TOP 150 (BLACK_VLESS_RUS_mobile.txt)的移动订阅制作的，对于其他订阅/镜像 - 请替换 “subscription” 参数中的链接。*

   *`https-file://` 是一种特殊的 dae 方案。这不是浏览器链接。*

   *说明 2: 自动 YAML 设置在此处无法使用，因为这不是 Mihomo/Clash 客户端，而是 dae。*

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

更改文件后:

```diff
sudo dae reload
```

如果特定软件包不支持 reload 命令:

```diff
sudo systemctl restart dae
```

对于 category-ru 和 geoip:ru 规则，必须安装当前的 geosite.dat 和 geoip.dat。

**`8.`** **外部 systemd 定时器每小时自动续订一次订阅: 时间表无法直接配置到 config.dae 中。**

**要自动续订您的订阅，请创建一个文件:**

```diff
/etc/systemd/system/dae-subscription-refresh.service
```

文件内容:

```diff
[Unit]
Description=Refresh dae subscriptions
After=network-online.target dae.service
Wants=network-online.target

[Service]
Type=oneshot
ExecStart=/usr/bin/dae reload
```

然后创建:

```diff
/etc/systemd/system/dae-subscription-refresh.timer
```

文件内容:

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

激活:

```diff
sudo systemctl daemon-reload
sudo systemctl enable --now dae
sudo systemctl enable --now dae-subscription-refresh.timer
```

手动更新：

```diff
sudo dae reload
```

</details>

---
---

## <img src="https://upload.wikimedia.org/wikipedia/commons/8/8d/Shadowsocks_logo.png" width="40" align="absmiddle"> `PC、移动设备和路由器的 VPN 配置客户端`

根据不同的客户端，可用的服务器可能会有所不同；这是正常现象，因为每个客户端的运行特性不同；更新时的配置大多可以正常使用。因此，在您的 PC 上安装 2-3 个不同的客户端：Karing、Clash Verge Rev、v2rayN、Throne、Exclave、Happ 等。有些在 Karing 中无法使用的配置，在 Clash-Verge-Rev/v2RayN 中可以正常使用，有些在 Throne 或其他客户端中可用，所以请选择最接近且最方便您的。一般来说，配置很多，即使有些无法启动也没关系，其中大约 50% 的配置通过一个客户端肯定能用。

此功能同样适用于移动设备客户端。例如，在 iOS 上，除了 Karing 和 Clash Mi，您还可以安装 Shadowrocket 或 Streisand 并进行比较。

请关注更新，并且不要忘记至少每两周更新一次客户端。配置的性能直接依赖于此。最新版本包含修复并看到更多可用服务器。

### <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3amtqMmQxOGh0aG0waGk5OGhhNG5odmdob2k1bWc4ejNyZ3E3N2Y2bCZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/xUS4Fp5i6iIn2Y1EYT/giphy.gif" width="25"> `Windows/Linux/MacOS`

<details>
<summary><em><code> 展开 </code></em></summary>

㋡

<details>
<summary><strong><em><code> 我推荐的客户端 #1 是 Karing </code></em></strong></summary>

⇩

**https://github.com/KaringX/karing/releases**

安装官方 Karing 客户端，以“管理员模式”运行，通过 **添加配置文件 - 添加订阅** 添加订阅，将订阅链接粘贴到顶部窗口，在“备注”中写入名称，将更新间隔设置为 1 小时，激活“配置更新后重启”和“配置更新后开始延迟测试”，然后在右上角点击 ✅️。

在主窗口中，找到 Karing 设置图标 ⚙️ （左上角），然后找到“自动选择”菜单，将延迟检查间隔设置为 10 分钟，允许误差设置为 150ms，当前服务器健康检查间隔设置为 3 秒。

服务器会出现在主菜单底部中央（在盾牌 🛡️下方），它右侧是右箭头 - 点击它，服务器选择菜单将会打开。在右上角，点击 ⚙️ 并激活那里所有的按钮。返回，点击“自动选择”。然后通过左上角的箭头返回主菜单。 

底部中央点击盾牌图标 🛡️，等待订阅重启，ping 值和最快服务器会自动选择。如果服务器不满意，打开并关闭护盾 🛡️。或者进入服务器选择菜单，选择当前服务器并点击“拒绝”，它将不再参与搜索。你可以通过点击服务器选择菜单中的“云”手动重启你的订阅。

---

</details>

<details>
<summary><strong><em><code> 我推荐的客户端 #2 是 Clash Verge Rev </code></em></strong></summary>

⇩

**https://github.com/clash-verge-rev/clash-verge-rev/releases**

Clash Verge Rev 仅适用于 Clash YAML 格式的配置文件。

*尝试导入非 YAML 订阅时，Clash Verge Rev 会报错，例如 `远程配置文件数据不是合法的 yaml`，或 `配置文件不包含代理或代理提供者`.*

支持所有现代 VLESS、Trojan、VMess、Hysteria2 协议，但这些协议必须用 Clash 配置格式描述。客户端本身运行在 Mihomo 内核上，前称 Clash.Meta。

我自己开始积极使用 Clash Verge Rev，感觉有 VPN 的互联网几乎不间断，配置会在后台自动检查并相互更改，顺畅到我都没注意到它。也许这个客户端甚至比 Karing 更好，因为 Karing 有时长时间运行后仍需要强制重启。

**要使用此客户端，请仅使用来自名为 Clash 的仓库文件夹中的 YAML 订阅：** https://github.com/igareck/vpn-configs-for-russia/tree/main/Export/Clash

**Igareck 已经在所有 Clash 订阅中内置了后台配置自动健康检查，以方便用户。**
  
**Clash 订阅按地区划分：**
  
- **针对俄罗斯用户的Clash订阅**（RU-DIRECT，可让所有俄罗斯网站无需VPN访问）： 

https://github.com/igareck/vpn-configs-for-russia/tree/main/Export/Clash/RU_DIRECT

- **国际选项的Clash订阅**（适用于其他不需要RU-DIRECT的国家）： 

https://github.com/igareck/vpn-configs-for-russia/tree/main/Export/Clash/GLOBAL

**所有设置将在客户端导入时自动获取。**

**用户只需在客户端每隔一到两个小时配置订阅的自动更新并运行配置：** 

1. 进入“配置文件”部分，对导入的配置右键点击(RMB)；
2. 接下来，点击“更改信息”；
3. 在弹出的菜单中，激活“允许自动更新”开关，输入更新间隔（以分钟为单位，例如60或120）。如果需要，可以编辑标题/描述；
4. 最后，点击“保存”；
5. 然后对导入的配置右键点击(RMB)，选择“更新”或“通过代理更新”以从订阅加载配置；
6. 然后进入“代理”部分；
7. 在配置列表右上角，点击过滤器图标（形状像漏斗图标 🌪️），左侧会出现一个输入框；
8. 在输入框中输入“delay<5000”以隐藏不可用服务器（请注意，它们不会立即消失，而是在后台扫描重复进行5-10分钟后消失）；
9. 然后再次点击过滤器图标（看起来像一个漏斗图标 🌪️）以隐藏输入字段；
10. 然后转到“设置”部分；
11. 在左上角的“设置”部分，找到“TUN模式”，在其右侧有一个带有“安装服务”字样的小蓝色扳手图标，点击它并等待安装。确认“TUN模式”和“系统代理”的开关已激活；
12. 然后转到“主页”部分；
13. 在“主页”部分，找到“网络设置”面板，选择所需的操作模式：“系统代理”或“TUN模式”，使用开关按钮激活它。通常只需激活其中一个模式即可，但有时为了完全运行需要同时激活两者，根据情况而定；
14. 完成！
15. “主页”部分显示Clash Verge Rev客户端配置的运行统计：速度、上传/下载、出口-IP/ASN等。
16. **针对俄罗斯（RU-DIRECT，使所有RU网站无需VPN）提供带自动健康检查的现成YAML配置文件，用于全局配置Clash Verge Rev客户端本身。** 

    **不必要，因为同样的设置会随Igareck订阅自动生效。普通用户可以跳过此步骤，在步骤15停止。**这是为了用户方便，按以下原则：添加订阅后即可立即使用。

    **在哪里添加？** **转到“配置文件”部分，找到“全局合并配置”，右键（RMB）-“编辑文件”，删除全部内容并插入下面块中的现成YAML设置，点击“保存”。**

    **为什么要这样做？** 对于高级用户：如果需要在Clash Verge Rev客户端中手动更改任何Clash订阅选项，并使其对所有输入订阅全局生效。在Clash Verge Rev客户端记录的设置将覆盖所有输入的Clash订阅中匹配的设置。 

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
<summary><strong><em><code> 我推荐的客户端 #3 是 v2rayN </code></em></strong></summary>

⇩

**https://github.com/2dust/v2rayN/releases**

安装官方 v2rayN 客户端，以“管理员模式”运行。

进入“设置” - “区域预设”，选择“俄罗斯”。点击“重启”菜单或重新启动应用程序。

通过 **订阅组 - 订阅组设置** 添加订阅，通过 **订阅组 - 更新当前订阅（无代理）** 下载订阅，将会显示一个列表。

点击“真实延迟”检查（右上角闪电图标），完成后 - 按 Ping 值排序，选择顶部几个绿色的、数值最低的配置。

选择几个 Ping 值最低的服务器，右键点击，选择“服务器加载速度测试”，测试完成后按 Enter 选择最快的。但最近即使是在线服务器，v2rayN 的速度测试也显示假结果，因此我会冷静地只关注 Ping。在我的订阅中，如果服务器有 Ping 值，原则上应能工作。

最后，启动“VPN 模式/TUN 模式”，或者激活“设置系统代理”。右侧选择路由规则“RUv1-除 RF 外的所有”，以确保 VPN 不用于访问 RU 网站。

---

</details>

<details>
<summary><strong><em><code> 我推荐的客户端 #4 是 Throne </code></em></strong></summary>

⇩

**https://github.com/throneproj/Throne/releases**

安装官方 Throne 客户端，以“管理员模式”运行，通过 **设置 - 组 - 新建组** 添加订阅。

输入订阅名称，选择“订阅”类型，并在下方粘贴订阅的 RAW 链接。

你应该在主窗口看到一个带有相应名称的组。用鼠标右键点击它并点击“更新”。应该会出现服务器列表。

然后再次右键点击组名，选择“整个组的延迟测试”；测试完成后，选择延迟数值最低的服务器。

然后前往 **路由 - 下载配置文件** 部分，选择 **Bypass_Russia**，然后将路由从 **默认** 改为 **Bypass_Russia**。

---

</details>

更详细的说明可以在上面的段落中找到。（点击箭头）以及在[每个客户端单独说明](#-%D0%B8%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%86%D0%B8%D0%B8-%D0%BF%D0%BE-%D0%BA%D0%B0%D0%B6%D0%B4%D0%BE%D0%BC%D1%83-%D0%BA%D0%BB%D0%B8%D0%B5%D0%BD%D1%82%D1%83-%D0%BE%D1%82%D0%B4%D0%B5%D0%BB%D1%8C%D0%BD%D0%BE)部分中。

**最稳定的是Clash/Yaml订阅 + Mihomo客户端，以及Standard + Karing。**

---

## `Clash订阅的PC客户端：`

 Clash订阅按区域划分：
  
- 适用于俄罗斯用户的 Clash 订阅（RU-DIRECT，使所有俄罗斯网站无需 VPN 访问）： 

https://github.com/igareck/vpn-configs-for-russia/tree/main/Export/Clash/RU_DIRECT

- 国际版 Clash 订阅（适用于不需要 RU-DIRECT 的其他国家）： 

https://github.com/igareck/vpn-configs-for-russia/tree/main/Export/Clash/GLOBAL

| | |
|---|---|
| **① Clash Verge Rev（Clash Verge的继任者）** | **② Clash Mi（开发者Karing）** |
| **[GitHub上的Clash Verge Rev](https://github.com/clash-verge-rev/clash-verge-rev/releases)** | **[GitHub上的Clash Mi](https://github.com/KaringX/clashmi/releases)** |
| *我推荐它作为Karing的直接竞争对手。Mihomo核心。Clash Verge Rev仅适用于Clash YAML格式配置文件！* | *Clash Verge Rev之后的可用替代客户端，带有自动健康检查。Mihomo核心。* |
| *我自己开始积极使用Clash Verge Rev，感觉VPN下的网络几乎没有中断，配置在后台自动检查并相互切换得非常顺畅，以至于我几乎没有注意到。也许这个客户端比Karing工作得更好，因为Karing在运行很长时间后有时仍需要强制重启。* | *功能类似，但不如Clash Verge Rev强大。带有连接统计和详细设置的面板（Panel）在浏览器中打开，并不内置在客户端本身。Clash Verge Rev的所有功能都内置在应用中。是一个不错的替代选择。对于内置Igareck Clash订阅的设置，你几乎不需要做什么，除了更改界面语言并在内核设置中激活TUN。* |
| | |

Igareck 已经将自动健康检查后台配置功能内置到所有 Clash 订阅中，以方便用户。你所要做的就是下载 RAW-Clash 订阅，并在客户端中配置每 1-2 小时自动更新。
   
---

## `标准和特殊订阅的 PC 客户端`

### ① `Karing` **https://github.com/KaringX/karing/releases**

*适用于标准订阅。我推荐它作为最佳通用免费客户端，在运行时自动检查服务器。一个通用、适应性强、功能强大的工具，确保你的配置即使在高负荷下也能启动。不适合大量速度测试，仅适用于 ping。*

### ② `v2rayN` **https://github.com/2dust/v2rayN/releases**

*适用于 v2rayN 的特殊订阅。稳定运行，经过成千上万种不同协议配置验证（我个人最大为 150,000 个配置）。这是一个适用于所有现代协议的通用客户端。适合大规模检测（ping+速度）。通过 Xray、Sing-Box 或 Mihomo 运行。*

*后台自动健康检查配置可用（已内置在订阅中），通过本地策略组与最小延迟策略实现。*

### ③ `Throne`（Nekoray 的继任者） **https://github.com/throneproj/Throne/releases**

*适用于标准订阅。在 Karing/v2rayN 中未启动的配置部分在这里启动。这是一个适用于所有现代协议的通用客户端。适合大规模检测。通过 Xray、Sing-Box、Mihomo 一体运行。后台没有配置自动健康检查功能。*

</details>
   
---

### <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExODUzYWRwNzNpa3doMDd1bXo4NTlzanJsaTcya3dlNXA4d3c5cnVzNCZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/UQJlZ2OcaCA2RLfGiZ/giphy.gif" width="20" align="absmiddle"> `iOS`

<details>
<summary><em><code> 展开 </code></em></summary>

㋡

* 使用 Karing、Shadowrocket、V2Box 配合标准/通用订阅。路由和自动健康检查必须首先在客户端中检查和/或配置； 

* Clash Mi 和 Clash Lite、Stash - 配合 Clash 订阅使用。自动健康检查 + 路由内置在订阅本身； 

* Happ、Streisand、v2RayTun，为这些客户端提供特殊订阅。订阅本身内置自动健康检查和路由。一键VPN选项； 

**最稳定的是Clash/Yaml订阅 + Mihomo客户端，以及Standard + Karing。**

---

### `iOS客户端用于Clash订阅` (Mihomo)：

 Clash订阅按区域划分：
  
- 适用于俄罗斯用户的 Clash 订阅（RU-DIRECT，使所有俄罗斯网站无需 VPN 访问）： 

https://github.com/igareck/vpn-configs-for-russia/tree/main/Export/Clash/RU_DIRECT

- 国际版 Clash 订阅（适用于不需要 RU-DIRECT 的其他国家）： 

https://github.com/igareck/vpn-configs-for-russia/tree/main/Export/Clash/GLOBAL

| | | |
|---|---|---|
| **① `Clash Mi`** | **② `Clash Lite`** | **③ `Stash - 基于规则的代理`** |
| **[AppStore中的Clash Mi](https://apps.apple.com/us/app/clash-mi/id6744321968)** | **[AppStore中的Clash Lite](https://apps.apple.com/us/app/clash-lite/id6761357475)** | **[AppStore上的Stash](https://apps.apple.com/us/app/stash-rule-based-proxy/id1596063349)** |
| *来自同一开发者Karing的Clash订阅免费客户端* | *无需数据收集的Clash订阅替代免费客户端* | *iOS上的Clash订阅替代客户端，付费* |
| | | |

Igareck已经在所有Clash订阅中为用户方便内置了配置的自动健康检查。你所要做的只是下载RAW-Clash订阅，并在客户端中设置每1-2小时自动更新。

---

### `用于标准订阅和带有自动健康检查的特殊订阅的 iOS 客户端：`

   **① `Karing`** **https://apps.apple.com/us/app/karing/id6472431552**
     
   *用于标准订阅。目前最佳的免费通用客户端。后台自动检查配置的健康状况。地理列表和节点路由在初次安装时即可方便配置。对内存要求较高。*

   **② `Shadowrocket`** **https://apps.apple.com/us/app/shadowrocket/id932747118** 
   
   *用于标准订阅。付费。具有内置自动健康检查机制，通过菜单“连接测试 - URL 测试设置”实现。RU-DIRECT 的路由设置请参考 Shadowrocket 说明。对内存要求较高。*

   **③ `V2Box`** **https://apps.apple.com/us/app/v2box-v2ray-client/id6446814690**

   *用于标准订阅。在后台自动检查配置（在主菜单中需要激活“智能连接”）。地理列表和节点路由可在主菜单中方便配置。*

   **④ `Happ`** **https://apps.apple.com/us/app/happ-proxy-utility/id6504287215**

   *用于 Happ 的特殊订阅。目前最佳的一键选项！客户端对低配置/老设备优化良好。如果 Karing/Shadowrocket/Streisand 因内存不足断开连接，可使用 Happ。*

   **⑤ `Streisand`** **https://apps.apple.com/us/app/streisand/id6450534064**
   
   *用于 Streisand 的特殊订阅。对内存要求较高。*

   **⑥ `v2RayTun`** **https://apps.apple.com/us/app/v2raytun/id6476628951**

   *用于 v2RayTun 的特殊订阅。* 


</details>

---
  
### <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExODUzYWRwNzNpa3doMDd1bXo4NTlzanJsaTcya3dlNXA4d3c5cnVzNCZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/UQJlZ2OcaCA2RLfGiZ/giphy.gif" width="20" align="absmiddle"> `Android`

<details>
<summary><em><code> 展开 </code></em></summary>

㋡

* 使用 Karing、Exclave 的标准/通用订阅。路由和自动健康检查必须首先在客户端中检查和/或配置； 

* Clash Mi、ClashMetaForAndroid 和 FlClash - 使用 Clash 订阅。自动健康检查 + 路由已内置于订阅中； 

* Happ、v2rayNG、v2RayTun、V2Box 使用这些客户端的特殊订阅。自动健康检查 + 路由已内置于订阅中。一键 VPN 选项；  

**最稳定的是Clash/Yaml订阅 + Mihomo客户端，以及Standard + Karing。**

---

### `适用于 Clash 订阅的 Android 客户端` (Mihomo)：

 Clash订阅按区域划分：
  
- 适用于俄罗斯用户的 Clash 订阅（RU-DIRECT，使所有俄罗斯网站无需 VPN 访问）： 

https://github.com/igareck/vpn-configs-for-russia/tree/main/Export/Clash/RU_DIRECT

- 国际版 Clash 订阅（适用于不需要 RU-DIRECT 的其他国家）： 

https://github.com/igareck/vpn-configs-for-russia/tree/main/Export/Clash/GLOBAL

| | | |
|---|---|---|
| **① `Clash Mi`** | **② `ClashMetaForAndroid`** | **③ `FlClash`** |
| **[GitHub上的Clash Mi](https://github.com/KaringX/clashmi/releases)** | **[GitHub 上的 ClashMetaForAndroid](https://github.com/MetaCubeX/ClashMetaForAndroid/releases)** | **[GitHub 上的 FlClash](https://github.com/chen08209/FlClash/releases)** |
| *来自同一开发者Karing的Clash订阅免费客户端* | *客户端来自 Mihomo 内核的创建者，本人推荐桌面版最佳免费 Clash 客户端 "Clash Verge Rev" 的开发者* | *比 ClashMetaForAndroid 更现代的 Flutter 界面。对于希望简单 YAML 导入和连接按钮的人，FlClash 可能更好* |
| | | |

Igareck已经在所有Clash订阅中为用户方便内置了配置的自动健康检查。你所要做的只是下载RAW-Clash订阅，并在客户端中设置每1-2小时自动更新。

---

### `用于标准订阅和带自动健康检查的特殊订阅的 Android 客户端：`

**① `Karing`** https://github.com/KaringX/karing/releases

*用于标准订阅。目前最佳的免费通用客户端。后台自动检查配置的健康状况。地理列表和节点路由在初次安装时即可方便配置。对内存要求较高。*

**② `Exclave`** https://github.com/dyhkwong/Exclave/releases

*用于标准订阅。该平台专为 Android 设计。内置了自动健康检查机制，通过“Balancer”（负载均衡器）使用“LeastPing”策略实现。配置在客户端自身。RU-DIRECT 地理路由内置于客户端，但如果没有，请参阅 Exclave 的说明并手动添加。仔细查看其他设置！*

**③ `Happ`** https://play.google.com/store/apps/details?id=com.happproxy

*用于 Happ 的特殊订阅。一键选项。订阅包内置自动健康检查和路由机制。客户端针对低端/老旧设备进行了优化。如果 Karing 因 RAM不足而断开连接，请使用 Happ。*

**④ `v2rayNG`** https://github.com/2dust/v2rayNG/releases

*用于 v2rayNG 的特殊订阅。一键选项。订阅包内置自动健康检查机制，通过“策略组”(Policy Group) 使用“Least Ping”策略实现，同时包含路由功能。*

**⑤ `v2Box`** https://play.google.com/store/apps/details?id=dev.hexasoftware.v2box

*用于 v2Box 的特殊订阅。一键选项。订阅包内置自动健康检查和路由机制。*

**⑥ `v2RayTun`** https://play.google.com/store/apps/details?id=com.v2raytun.android&hl=en&pli=1

*用于 v2RayTun 的特殊订阅。一键选项。订阅包内置自动健康检查和路由机制。客户端针对低端/老旧设备进行了优化。如果 Karing 因 RAM 不足而断开连接，请使用 v2RayTun。*

**⑦ `NekoBox`** https://github.com/MatsuriDayo/NekoBoxForAndroid/releases

*适用于标准订阅。该平台仅限Android使用。原版NekoBox没有内置自动健康检查机制，只有手动URL测试。*

</details>

---

### <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExODUzYWRwNzNpa3doMDd1bXo4NTlzanJsaTcya3dlNXA4d3c5cnVzNCZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/UQJlZ2OcaCA2RLfGiZ/giphy.gif" width="20" align="absmiddle"> `OpenWrt路由器、NAS和Linux系统`

<details>
<summary><em><code> 展开 </code></em></summary>

### ① `ShellCrash`

**https://github.com/juewuy/ShellCrash**

1. **适用于多种平台的通用选项：OpenWrt路由器及其衍生固件、NAS、Docker和Linux系统。兼容OpenWrt、Padavan、Pandora、ASUS Merlin、Debian、Ubuntu、CentOS、Armbian、Linux/BusyBox、Docker、Synology和PVE。**

2. **核心:** Mihomo/Sing-box。

3. **自动健康检查。**

4. **接受哪些订阅？** 原生支持Clash YAML订阅。常规订阅（常见的vless://、ss://、trojan://等）和Base64在导入时会自动转换为Clash格式。

**详细说明请参见“各客户端单独使用说明”部分。**

---

### ② `OpenClash`

**https://github.com/vernesong/openclash**

1. **最著名的OpenWrt+LuCI客户端之一（及其兼容衍生版本）。**

2. **核心:** Mihomo。

3. **自动健康检查。**

4. **接受哪些订阅？** 原生支持Clash YAML订阅。常规订阅（常见的vless://、ss://、trojan://等）和Base64在导入时会自动转换为Clash格式。

**详细说明请参见“各客户端单独使用说明”部分。**

---

### ③ `Nikki`

**https://github.com/nikkinikki-org/OpenWrt-nikki**

1. **OpenClash 的更现代化且紧凑的替代方案。**

   **定位为适用于 OpenWrt 24.10+、Linux 5.13+，支持 firewall4/nftables 的现代透明代理。** 

2. **核心:** Mihomo。

3. **自动健康检查。**

4. **它接受哪些订阅？** 仅接受 Clash YAML 订阅。导入其他格式会报错。

**详细说明请参见“各客户端单独使用说明”部分。**

---

### ④ `PassWall2`

**https://github.com/Openwrt-Passwall/openwrt-passwall2**

1. **适用于 OpenWrt 21.02+ 的通用选项，以及 LuCI 和衍生固件（例如 ImmortalWrt）。** 

2. **核心：** Sing-box/Xray。

3. **自动健康检查。**

4. **它接受哪些订阅？** 常规订阅（来自常见字符串 vless://、ss://、trojan:// 等），以及 Base64。Clash YAML 可导入订阅，但会转换为常规格式。

**详细说明请参见“各客户端单独使用说明”部分。**

---

### ⑤ `dae/daed`

**https://github.com/daeuniverse/dae**

**https://github.com/daeuniverse/daed**

1. **适用于现代 Linux 服务器系统、迷你 PC 和没有 GUI 的基于 Linux 的网络网关的高性能解决方案。** 

2. **核心：** 独立代理核心 `dae`。该项目不使用 Xray、Sing-box 或 Mihomo。开发者直接说明，该项目是 v2rayA 的后继者，已放弃 v2ray-core。`dae` 是独立代理内核，`daed` 提供基于浏览器的控制面板。

3. **自动健康检查。**

4. **它接受哪些订阅？** 常规订阅（来自常见字符串 vless://、ss://、trojan:// 等），以及 Base64。

**详细说明请参见“各客户端单独使用说明”部分。**

</details>

---
---

## <img src="https://upload.wikimedia.org/wikipedia/commons/d/df/Tor_Browser_icon_%28New%29.png" width="38" align="absmiddle"> `PC、手机、路由器上的 Tor 网桥应用（客户端）`

**官方下载链接** `Tor 浏览器`（通过 VPN 或 Tor）： https://www.torproject.org/zh-CN/download/

**通过 Telegram 机器人获取更新版本** `Tor 浏览器`：@gettor_bot

**通过电子邮件获取更新版本** `Tor 浏览器`，发送电子邮件主题为 “windows”、“macos”、“linux” 或 “android” - 取决于你的操作系统： gettor@torproject.org

*适用于 Windows、macOS、Linux、Android.*

**桥接节点** 除了在本仓库中，你也可以从 Tor Project, Inc. 官方获取。 

但在这种情况下，它们需要进行筛选和测试，因为……你遇到的桥接节点并不总是在俄罗斯可用。

**通过电子邮件获取桥接节点**（从你的 Gmail 或 Riseup 邮箱地址发送邮件）： bridges@torproject.org

**通过 Telegram 机器人获取桥接节点**：@GetBridgesBot 

**在 Tor Project 官方网站获取桥接节点**： https://bridges.torproject.org/options

---

### <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3amtqMmQxOGh0aG0waGk5OGhhNG5odmdob2k1bWc4ejNyZ3E3N2Y2bCZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/xUS4Fp5i6iIn2Y1EYT/giphy.gif" width="25"> `Windows/MacOS/Linux`

<details>
<summary><em><code> 展开 </code></em></summary>

### 笔记本和台式电脑的 Tor 网桥客户端。

### ① `OnionHop V3`

*我推荐它作为在PC上使用Tor 网桥的最佳免费客户端。*

*一个通用、可用且功能强大的工具，确保你的连接始终稳定。*

   **https://github.com/center2055/OnionHop/releases**

---

  ### ② `OnionFruit`

*在PC上使用Tor 网桥的另一种免费客户端。*

*适用于所有类型的Tor 网桥：原生 · obfs4 · webtunnel · meek · snowflake · conjure*

*可自定义出口IP - 不再是随机出口国家，而是可以从列表中选择特定国家，例如：美国、德国、澳大利亚或日本。*

*作为系统代理工作，未声明TUN模式。*

   **https://github.com/dragonfruitnetwork/onionfruit/releases**

   **https://dragonfruit.network/onionfruit**

   `install-x64.exe` - GUI安装程序版本2026.301.0，适用于Windows 10/11（仅Windows平台，其他平台不可用）

  通过双击 install-x64.exe即可立即安装。可在桌面和开始菜单中找到已安装的OnionFruit。

</details>

---

### <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExODUzYWRwNzNpa3doMDd1bXo4NTlzanJsaTcya3dlNXA4d3c5cnVzNCZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/UQJlZ2OcaCA2RLfGiZ/giphy.gif" width="20" align="absmiddle"> `iOS/Android`

<details>
<summary><em><code> 展开 </code></em></summary>

### 移动设备上的Tor 网桥客户端。

**① `Onion Browser` App Store:** https://apps.apple.com/us/app/onion-browser/id519296448

**② `Onion Browser` Google Play:** https://play.google.com/store/apps/details?id=org.torproject.torbrowser

**③ `Orbot` Wikipedia:** https://zh.wikipedia.org/wiki/Orbot

**④ `Orbot` App Store:** https://apps.apple.com/us/app/orbot/id1609461599

**⑤ `Orbot` Google Play:** https://play.google.com/store/apps/details?id=org.torproject.android

**⑥ `Invizible Pro` 官方网站:** https://invizible.net/en

**⑦ `Invizible Pro` Google Play:** https://play.google.com/store/apps/details?id=pan.alexander.tordnscrypt.gp

</details>

---

### <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExODUzYWRwNzNpa3doMDd1bXo4NTlzanJsaTcya3dlNXA4d3c5cnVzNCZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/UQJlZ2OcaCA2RLfGiZ/giphy.gif" width="20" align="absmiddle"> `路由器`

<details>
<summary><em><code> 展开 </code></em></summary>

### ① `TorBox`

**https://github.com/radio24/TorBox**

1. **将 Raspberry Pi 或其他 Debian/Ubuntu/DietPi Linux 设备转变为独立的 Tor 路由器的选项。TorBox 创建一个独立的 Wi-Fi 网络，或接受通过以太网连接的设备，并将它们的 TCP 流量通过 Tor 路由。**

2. **它接受哪些桥接？** 界面声称支持 Vanilla、Obfs4、Snowflake 和 meek-azure。

---

### ② `Tor Bridges Proxy - OpenWrt LuCI`

**https://github.com/zerolabnet/luci-app-torbp**

1. **一个在 OpenWrt 中运行的有用的 Tor LuCI 配置模块。**

2. **它支持哪些桥接？** 接口显示 Obfs4。

</details>

---
---

## <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3ZDhxeG02NHlucTdqZGhtejBnb2V5dGpwaDBmcHhobWlsOHQxdWpoYSZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/8L0hXHQkY4o7eyQHJB/giphy.gif" width="45" align="absmiddle"> `有用信息`

⚡ **我为什么要测试 VPN 配置？** 在我最初开始建设该仓库的时候（2025 年 11 月），从 40,000 多个用于测试的免费公共配置中，大约有 700 个通过了性能测试，不到 2%，最终我在这里发布了大约 200 个高质量、响应速度快且速度尚可的配置，已经是总数的一半百分点。并不是每个人都有时间处理数以万计的配置集合，而实际上只有几百个配置可以使用。

⚡ 到 2026 年 9 月，根据我们自己的分析，**活跃 VPN 配置所占百分比**在总检查量中变为：每 1000-2000 个配置中只有 1 个活跃配置。但得益于定期的脚本审计、更新和改进，检查的质量和 `igareck/vpn-configs-for-russia` 订阅的相关性维持在相当高的水平，尽管难度在增加。

⚡ 网络上有一整车的协议，但**最有效的**、可以防护 Roskomnadzor 的 DPI 及其封锁的是 **VLESS+Reality**，因为它能够将流量伪装成访问无害 HTTPS 网站，使 VPN 的使用对互联网服务提供商完全不可见。其余协议按排名降序排列，因为它们更容易被识别。 

⚡ 由于一些原因超出我的控制范围，某些配置可能随着时间停止工作，因此 **清单将定期更新**。

⚡ **如果工作开始后连接经常快速断开** 3-5 分钟内 - 尝试 **在客户端降低 MTU 参数**，从 9000 改为 3000/1500/1300/1200。

⚡ **如果你的 ISP 阻止你的 VPN 连接或流量** - 将路由器、电脑或手机上的常规 DNS 改为加密的 DNS：**使用 DNS-over-HTTPS (DoH)**。在某些情况下，这确实有帮助。

一个明显的例子说明这个方法可行：在有线互联网和没有严格过滤的运营商环境下，配置 DoH 有助于创建无需混淆的 Shadowsocks 配置（不带插件的 SS）。参见订阅 **[BLACK_SS_WEAK_DPI_RUS.txt](https://raw.githack.com/igareck/vpn-configs-for-russia/main/BLACK_SS_WEAK_DPI_RUS.txt)**。使用 ISP/自动 DNS 时，没有插件的 Shadowsocks 很可能无法传输流量。

DNS-over-TLS (DoT) 对大多数人来说不太可能奏效。 

即使更改 DNS 无效（那意味着你需要寻找其他原因）——只需为自己的在线隐私设置一个 DoH 就可以了！

⚡ **如果有 ping 但没有流量**——尝试在客户端设置中 **将远程 DNS (Remote DNS) 替换为标准的 DNS-over-HTTPS (DoH)**。

⚡ **在白名单模式（无人机威胁期间的网络限制）下，没有任何外国 DNS 提供商可用**（没有 Google、没有 Cloudflare、没有 Quad9、没有 Alibaba、没有 OpenDNS）。在这种情况下，使用运营商提供的自动 DNS 或来自 Yandex 的 DNS/DNS-over-HTTPS。否则，白名单的 VPN 配置根本无法工作。

⚡ 也许，**在不久的将来**，由于公共 DNS-over-HTTPS (DoH) 阻止越来越多，我们将得出结论 **与其使用 Google/Cloudflare/Quad9 等公共 DNS 提供商，不如在租用的 VPS 上创建自己的 DoH**，即所谓的 **DNS-on-a-VPS**，它将与 VPN 服务器协同工作。

⚡ **为什么我要测试 Tor 网桥，而它们也可以从 Tor 项目获取？** 是的，你可以从 Tor 项目获取，这也是我提供各种联系方式的原因。但问题是 Tor 项目提供的桥接并不针对特定的地区/国家，而是全球提供。也就是说，在美国，同样的 Tor 网桥可以完美工作，但在俄罗斯，由于封锁、网络问题及其他原因，它将无法提供连接。我的仓库中的桥接每 4 小时会专门测试在俄罗斯的可用性，使终端用户更容易、更快速地找到真正可用的选项。不仅仅是测试 ping，还测试每个桥接的完整连接，因为普通的 ping 并不能作为性能的指标。

⚡ **请关注更新，并且别忘了至少每两周更新一次客户端应用。配置的性能直接依赖于此。最新版本包含修复，并能看到更多活跃服务器。**

⚡ **为了在俄罗斯实现最稳定的互联网操作，建议与 VPN 一起使用小型地区运营商的网络**，这些运营商的基础设施没有与大型提供商连接，如 Rostelecom、ER-Telecom (Dom.ru)、Beeline、Megafon、MTS 等。 

地区有线运营商的过滤器较弱。更换运营商比忍受无休止的延迟要容易。

我计划创建一个推荐供应商的列表。

## `DNS-over-HTTPS`

### 🧾 什么是 DNS-over-HTTPS(DoH) 以及如何连接？ 

<details>

<summary><em> 点击箭头查看详情 </em></summary>

㋡

***DNS-over-HTTPS (DoH)*** - 这就是 DNS，只是加密和私密化。DNS over HTTPS 会加密本地观察者（提供商）的 DNS‑请求，从而提高隐私性。 

但 DNS 解析器本身（Cloudflare/Google 等）仍然可以看到请求（你是通过它传递请求的）。提供商只看到与 IP‑DoH/DoT 解析器地址的连接（以及流量量/时间）+ 目标服务器的最终 IP，即访问网站的最终 IP，而不包括目标域名的名称（如果没有 ECH 的话，则通过 SNI 得到域名）。通过最终 IP（以及在没有 ECH 的情况下通过 SNI）通常（但并非总是）可以识别网站。 

也许（但不 100%）DoH 能让你绕过一些连接限制（如果有的话）。DoH 可以帮助绕过简单的 DNS‑屏蔽，但不能绕过 IP/SNI 屏蔽或深度过滤。  

该标准由 IETF 发布为 RFC 8484（2018），并在 ICANN 的协助下实现该协议，而 Google 早在 2016 年就首次实现/测试了它！其目标是提高用户隐私和安全。

㋡

### `如何启用通过 HTTPS 的 DNS？`

### `在路由器上：` 

如果你可以访问路由器，这是最正确的选项。

移除并禁用默认提供商 DNS 并设置 DNS-over-HTTPS (DoH)，你首先需要在路由器更新设置中下载 DoH 客户端。DNS-over-HTTPS (DoH) 应该可以 100% 稳定工作。可以尝试 DNS-over-TLS (DoT)，但结果不保证，在俄罗斯不推荐使用，因为经常被屏蔽，实际上现在对于俄罗斯联邦的大多数居民来说 DoT 无法使用。

### `在手机上` 有 3 个选项：

***1. 专用的 DNS-over-HTTPS 应用*** 

| | |
|---|---|
| **iOS（AppStore）** | **Android（Google Play 商店）** | 
| **1.1.1.1: 更快的互联网**（Cloudflare）： https://apps.apple.com/us/app/1-1-1-1-faster-internet/id1423538627 | **Cloudflare 1.1.1.1 + WARP：更安全的互联网**： https://play.google.com/store/apps/details?id=com.cloudflare.onedotonedotonedotone&hl=en-US |
| **AdGuard DNS**： https://apps.apple.com/us/app/adguard-dns/id6754605049 | **AdGuard DNS**： https://play.google.com/store/apps/details?id=com.adguard.dnsclient |
| **DNSecure**： https://apps.apple.com/us/app/dnsecure/id1533413232 | **Intra**： https://play.google.com/store/apps/details?hl=en&id=app.intra |
| **Control D 快速设置：** https://apps.apple.com/us/app/control-d-quick-setup/id1518799460 | **Nebulo**： https://play.google.com/store/apps/details?hl=en&id=com.frostnerd.smokescreen （他们写道它能完美过滤广告） |
| | |

除了 DoH，Cloudflare 应用的主要功能是 WARP 模式，即通过 Cloudflare 网络的全系统加密通道。WARP 可以用作 VPN，如果你的 ISP 没有阻止它，可以绕过屏蔽。但在俄罗斯 WARP 被阻止，因此只能使用 DoH。由于 Cloudflare 系统性地受到 Roskomnadzor 的限制，通过 Cloudflare 应用连接 DoH 可能会有问题。必要时使用替代方案。

从这一点起的应用通常使用本地 VPN 接口。因此，它们很可能无法与 Karing、v2rayNG 或其他 VPN 模式客户端同时工作：Android/iOS 通常只允许一个活动用户 VPN。

 对于 Karing/Exclave/Throne 等应用，更好的做法是：直接在 Karing/Exclave/Throne 内配置 DoH，或使用 iOS 系统配置文件（第 2 点），或者 Android 网络设置（第 3 点）。

***2. iOS（系统配置文件 .mobileconfig）。*** 

**对于 iOS，没有基本网络设置，DoH 配置以单独文件的形式下载**： 

* 或者在 Quad9、AdGuard、Dnsforge 等官方网站上。 

* 或从我专门收集的这个 Igareck 仓库中获得 DoH .mobileconfig，用于 Google/OpenDNS/Cloudflare/Yandex（因为这些提供商并未官方提供 iPhone 的 DoH 配置）。 

在下面的“公共 DoH 服务器列表”部分查找链接；

DoH 配置链接，供 iPhone 正确下载和安装，只能在 Safari 浏览器中打开。

***3. Android（网络设置）*** 

对于 Android，进入 **设置** ➡️ **网络和互联网**（或 **Wi-Fi 和互联网**） ➡️ 选择 **高级设置** ➡️ **个人 DNS 服务器（私人 DNS）** ➡️ 选择 **个人 DNS 提供商主机名** 并输入其中一个公共 DoH 地址的 **主机名**（见下方“公共 DoH 服务器列表”），例如 `dns.google` / `doh.opendns.com` / `dns.cloudflare.com` / `dns.alidns.com` 或 `common.dot.dns.yandex.net`；

### `在电脑/笔记本电脑上:` 

在网络适配器的 DNS 设置中注册 DoH 服务器，例如 `https://dns.google/dns-query` / `https://doh.opendns.com/dns-query` / `https://dns.cloudflare.com/dns-query` / `https://dns.alidns.com/dns-query` 或 `https://common.dot.dns.yandex.net/dns-query`。

### `在 VPN 应用/客户端内:`

在应用/客户端的 DNS 设置中注册 DoH 服务器，或从预设中选择。

---

</details>


### 🧾 公共 DoH 服务器列表（+ 下载 DoH 配置 .mobileconfig）

<details>

<summary><em> 点击箭头查看详情 </em></summary>

㋡

**Yandex**

**`https://common.dot.dns.yandex.net/dns-query`** - *Yandex DNS 基础。注意！仅建议用于白名单模式，在普通模式（黑名单）下使用下面的 DNS 服务器；*

**`https://safe.dot.dns.yandex.net/dns-query`** - *Yandex DNS 安全模式。注意！仅建议在白名单模式下使用，普通模式（黑名单）请使用以下 DNS 服务器；*

**[Yandex_DoH_iPhone.mobileconfig](https://raw.githack.com/igareck/GoldCaviar/main/Files/Yandex_DoH_iPhone.mobileconfig)** - *下载 Yandex DoH 配置文件（Yandex DNS 基础版）用于 iOS；*

**Google**

**`https://dns.google/dns-query`** 或 **`https://8.8.8.8/dns-query`** - *Google 公共 DNS，总部位于美国加州山景城；*

**[Google_DoH_iPhone.mobileconfig](https://raw.githack.com/igareck/GoldCaviar/main/Files/Google_DoH_iPhone.mobileconfig)** - *下载适用于 iOS 的 Google DoH 配置文件；*

**Cloudflare**

**`https://dns.cloudflare.com/dns-query`** 或 **`https://cloudflare-dns.com/dns-query`** 或 **`https://one.one.one.one/dns-query`** - *Cloudflare DNS 基础版，总部位于美国加州旧金山；*

**`https://security.cloudflare-dns.com/dns-query`** - *Cloudflare 反恶意软件 DNS，总部位于美国加州旧金山；*

**[Cloudflare_DoH_iPhone.mobileconfig](https://raw.githack.com/igareck/GoldCaviar/main/Files/Cloudflare_DoH_iPhone.mobileconfig)** - *下载 Cloudflare DoH 配置文件（Cloudflare DNS 基础版）用于 iOS；*

**OpenDNS**

**`https://doh.opendns.com/dns-query`** - *思科 Umbrella（OpenDNS），总部位于美国加州旧金山；*

**[OpenDNS_DoH_iPhone.mobileconfig](https://raw.githack.com/igareck/GoldCaviar/main/Files/OpenDNS_DoH_iPhone.mobileconfig)** - *下载适用于 iOS 的 OpenDNS DoH 配置文件；*

**AdGuard**

**`https://family.adguard-dns.com/dns-query`** 或 **`https://dns.adguard-dns.com/dns-query`** - *AdGuard DNS。来自总部位于塞浦路斯利马索尔的知名免费广告和追踪器拦截服务的DNS；*

**https://adguard-dns.io/ru/public-dns.html** - *下载适用于iOS的AdGuard DNS配置文件，并阅读关于其他平台的使用说明，提供俄语/英语版本；*

**Quad9**

**`https://dns.quad9.net/dns-query`** - *Quad9 DNS基础版。恶意软件拦截，DNSSEC验证。无日志策略。总部位于瑞士苏黎世；*

**`https://dns11.quad9.net/dns-query`** - *Quad9 DNS高级版。通过ECS保护：恶意软件拦截，DNSSEC验证，启用ECS。无日志策略。总部位于瑞士苏黎世；*

**https://docs.quad9.net/Setup_Guides/iOS/iOS_14_and_later_(Encrypted)** - *下载适用于iOS的Quad9 DNS配置文件，并阅读关于其他平台的使用说明，语言仅提供英语/法语，不提供俄语；*

**DNSFORGE**
 
**`https://blank.dnsforge.de/dns-query`** 或 **`https://dnsforge.de/dns-query`** - *来自德国免费广告和追踪器拦截器DNSFORGE (dnsforge.de) 的DNS (Blank/Normal)。无日志策略，服务器位于德国法尔肯施泰因。所有信息和使用说明为德语；*

**[dnsforge-doh.mobileconfig](https://dnsforge.de/dnsforge-doh.mobileconfig)** - *下载适用于iOS的DNSFORGE.DE DNS配置文件 (普通模式)；*

**[blank-dnsforge-doh.mobileconfig](https://dnsforge.de/blank-dnsforge-doh.mobileconfig)** - *下载适用于iOS的DNSFORGE.DE DNS配置文件 (空白模式)；*

**https://dnsforge.de** - *下载其他DNSFORGE配置文件，并阅读关于其他平台的使用说明，提供德语版本；*

**休息**

**`https://dns.alidns.com/dns-query`** 或 **`https://223.5.5.5/dns-query`** - *阿里巴巴公共DNS/AliDNS，总部位于中国大陆杭州。*

**`https://doh.pub/dns-query`** - *服务公司腾讯云，总部位于中国大陆深圳。*

**`https://freedns.controld.com/p0`** 或 **`https://freedns.controld.com/p2`** - *Control D 免费DNS，总部位于加拿大多伦多；*

**`https://base.dns.mullvad.net/dns-query`** 或 **`https://dns.mullvad.net/dns-query`** - *Mullvad 加密DNS，总部位于瑞典哥德堡；*

**`https://dns.hostux.net/dns-query`** - *Hostux 网络，总部位于卢森堡；*

**`https://doh.dns.sb/dns-query`** - *xTom GmbH，DNS.SB 服务，总部位于德国 Dü斯杜尔多夫；*

**`https://adl.adfilter.net/dns-query`** - *ADFilter，总部位于澳大利亚阿德莱德；*

**`https://v.recipes/dns-query`** - *PT VRECIPES AMANAH SEMESTA，总部位于印度尼西亚南雅加达；*

**`https://wurzn.hagezi.org/dns-query`** - *HaGeZi DNS，私人非盈利项目；服务器托管在德国纽伦堡的 Hetzner Online GmbH；*

**`https://ada.openbld.net/dns-query`** - *OpenBLD，私人项目，哈萨克斯坦阿拉木图；*

**`https://xbox-dns.ru/dns-query`** - *Xbox DNS，私人非盈利项目；服务器托管在俄罗斯莫斯科的 Selectel；*

```diff
注意：
在 White List 模式（无人机威胁限制）下，所有境外 DNS 提供商都无法使用。
Google、Cloudflare、Quad9、Alibaba、OpenDNS 等均无法使用。
在这种情况下，请使用运营商自动提供的 DNS，或使用 Yandex 的 DNS / DNS-over-HTTPS。
否则，White List 的 VPN 配置将无法正常工作。
```

</details>

---

## <img src="https://upload.wikimedia.org/wikipedia/commons/7/77/Psiphon-logo-512.png" width="30" align="absmiddle"> `替代解决方法` (Psiphon)

<details>

<summary><code><em> 点击箭头查看详情 </em></code></summary>

<h3><code> Psiphon </code></h3>

**Psiphon** - 免费开源软件，用于绕过网络审查。Psiphon 专门设计用于支持处于网络审查国家的用户。Psiphon 公司成立于2007年，是位于加拿大安大略省的独立公司。与多伦多大学孟克全球事务学院下属的公民实验室合作。

**信息：** https://zh.wikipedia.org/wiki/%E8%B3%BD%E9%A2%A8

**官方下载链接**（Windows 10/11，需通过 VPN 或 Tor 访问）： https://psiphon.ca/zh

**已将安装程序上传至 GitHub：** https://github.com/igareck/GoldCaviar/raw/refs/heads/main/Files/Psiphon3_VPN_install.exe

注意！仅在 PC 上的有线网络有效（不支持移动网络）！可选择多种位置！

系统基于过时的 SSH 协议，连接速度不快，但最重要的是它能用。 

**截至2026年8月的状态：** 在许多提供商上可能无法使用，需要自行检查。

**结合仓库中的订阅（VPN-over-VPN 方案），Psiphon 可作为替代地理位置的来源，如果标准订阅中没有所需地理位置。**

---

</details>

## 👁️‍🗨️ `提供商能看到什么？` 当你在上网时，任何人能看到什么？

<details>

<summary><code><em> 点击箭头查看详情 </em></code></summary>

⇩

**一般情况：**

**当你在互联网上时，有五方会评估你的行为：**

**1.** `你自己`

**2.** `你的互联网服务提供商` 

**3.** `你正在访问的网站/搜索引擎`

**4.** `你的浏览器（如果是来自 Yandex、Google 或任何公共公司）` 

**5.** `DNS 解析器` 

**有些人认为“提供商能看到一切。”**

**但这是一个误解；如果你在网络上行为正确，提供商看到的内容很少。**

让我们描述没有 VPN 的情况下，HTTPS 网站的互联网标准操作。不要与未加密的 HTTP 混淆。现在是 2026 年，几乎没有 HTTP 网站存在。

### `让我们分别看看每一项`

### `1. 提供商`

提供商通常能看到三件事：你正在连接的网站的最终 IP + 域名 + 到达用户浏览器的加密 HTTPS 数据包。网站本身正在发生什么，只有两方知道——用户和网站，仅此而已！感谢 HTTPS 加密。只有你和 Google 知道你在 Google 上搜索的内容。

**让我以 YouTube 为例来解释：**

你去我们最喜欢的 YouTube，观看了一个有用的视频教程，打开这个视频并观看。服务提供商能看到什么？来自 YouTube 的 IP + 域名“Youtube”+ 发到用户 PC 的加密 HTTPS 数据包！就是这样，仅此而已！你观看什么视频，在搜索引擎中搜索什么内容，服务提供商是看不到的，因为这些都发生在网站内部，并通过 HTTPS 加密。在网站名称“https:”左边看看——这就是网站使用的加密，它为全球数百万人提供数字安全，保护用户免受数字监控。 

**让我以 Google 搜索引擎为例来解释：** 

你去 Google.com 查看猫，搜索 *"cat meme bring cherries"*，你收到了穿围裙的猫的图片列表。服务提供商能看到什么？很可怕吗？什么都看不到。看到的是来自 Google 的 IP + 域名“Google”+ 发送到 PC 的加密 HTTPS 数据包。你在那里具体看了哪张猫的照片、什么姿势——服务提供商看不到。HTTPS 数据包当然包含穿围裙的猫照片，但数据包是加密的——所以服务提供商只会看到你“在 Google 上看某些内容”，但这对他来说是一堆空信息，即使是超级计算机也无法解密，或者需要 100 年。想象一下，他们 100 年后解密，也可能得到“cat meme carry the cherry” 或 “Natalia Marine Corps”。

**如果你使用加密的 DNS-over-HTTPS 而不是普通的 DNS，例如 1.1.1.1，会发生什么？（DoH）**

现在提供商将无法直接看到您连接的域名。也就是说，通过DoH，提供商看不到打开的DNS请求，他只看到您已建立到IP‑DoH/DoT解析器地址的连接（以及流量量/时间）+ 网站的最终IP。提供商无法识别目标域名，但通常可以根据IP、SNI和流量行为猜测目标网站；对于热门网站，这比较容易，对于不太知名的网站则更难，但不能完全排除。如果DoH隐藏了最终IP，它就可以替代VPN，但最终访问的IP无法在没有VPN的情况下隐藏。而提供商正是根据最终IP阻止网站（例如Youtube）。因此，最终仍需要使用VPN来访问网站。

**简要说明DNS:**

常规DNS类型1.1.1.1（明文）显示：网站IP + 域名/SNI + 加密的HTTPS数据包；

DoH显示：仅显示网站的最终IP（+分析）+ 加密的HTTPS数据包。

### `2. 网站/搜索引擎`

**网站会看到您在其域内的活动，并受其总部所在国家法律约束。**

所有现代网站、连接及其与您交换的信息均通过HTTPS加密（不要与未加密的HTTP混淆），因此您在网站上的所有请求仅对您自己和网站可见，而对提供商不可见。提供商仅看到HTTPS加密流量，这对他来说无用，无法解密。

**在搜索引擎方面，我推荐两个。使用它们搜索时，不必担心突然询问到审查机构不喜欢的内容:** 

> *1. 谷歌搜索引擎（最受欢迎 + 拥有全球最大的搜索结果）。总部位于美国加州山景城。*
>
> *2. DuckDuckGo搜索引擎（受欢迎 + 搜索结果出色，可选择搜索区域 + 公司声明保护您的搜索隐私）。总部位于美国宾夕法尼亚州Paoli。*

不幸的是，我无法推荐 Yandex 搜索引擎。总部位于莫斯科。您的所有请求都会被记录并根据当前议程进行分析。明智地使用，仅搜索在俄罗斯索引的信息。至于其他所有内容，谷歌和DuckDuckGo就足够了。

### `3. 浏览器`

也许有人不知道——浏览器也会看到你的操作。 

**目前俄罗斯常用和流行的浏览器有哪些？** 

> A) Yandex 浏览器。强烈不推荐！如果安装了，请删除并换成其他任何浏览器！会记录流量；
>
> B) 谷歌 Chrome。这款浏览器同样没有隐私保护，流量也会被记录。但对于俄罗斯来说，它比 Yandex 更安全 + 属于谷歌自有生态系统； 
>
> C) Mozilla Firefox。根据隐私政策，它是在流行和大众中最好的浏览器； 

这些主流浏览器都有自己的开发者，开发者是公开公司，会收集用户数据并可能查看查询/浏览历史（无论他们怎么说）+ 受其总部所在国家的法律/管辖区约束，所以要谨慎考虑。为了防止浏览器成为“中间人”（"man-in-the-middle"）——安装一个保密的开源浏览器，它不是由上市公司制作，而是由具有公开（开源）代码的独立开发者制作，任何懂的人都可以检查其安全性，例如 GitHub 上发布的代码。

**我推荐哪些浏览器用于日常使用和上网？**

从下至上：从最流行到最保密。

**A)** `Mozilla Firefox` - 如果你想要一个流行且无问题的选项 + 为它下载安装 uBlock Origin 扩展（ublockorigin.com）以屏蔽追踪器和广告。基于 Mozilla 公共公司的 Firefox 引擎的浏览器。根据隐私政策，它是在大众中最好的选择。

https://www.firefox.com/en-US/?utm_campaign=SET_DEFAULT_BROWSER

https://github.com/mozilla-firefox/firefox

**b)** `Ungoogled Chromium` - 基于 Chromium 引擎的开源浏览器，由独立开发者移除了 Google 遥测功能。经过广泛用户测试。适合日常使用，但每次开发者发布更新时，你需要手动从 GitHub 下载。为其下载 uBlock Origin 插件 (ublockorigin.com) 以阻止跟踪器和广告。对于日常使用和隐私，我会称 Ungoogled Chromium 为中庸之选。Ungoogled Chromium 的使用体验与 Google Chrome 一模一样，只是没有 Google 生态系统。

https://github.com/ungoogled-software/ungoogled-chromium-windows Windows 版本

https://github.com/ungoogled-software/ungoogled-chromium-portablelinux Linux (便携版本)

https://github.com/ungoogled-software/ungoogled-chromium-macos MacOS

**V)** `Librewolf (定制版 Firefox)` - 基于 Firefox 引擎的开源浏览器，移除了 Mozilla Firefox 的遥测功能，由独立开发者提供。我会称其为“开箱即用的隐私 Firefox 浏览器”：下载即可启动。经过广泛用户测试。方便使用。支持自动更新（安装时勾选）。内置 uBlock Origin。Librewolf 很棒，但有时由于半激进的设置，一些流媒体网站可能会无法使用或打不开，虽然这种情况非常少见。

https://librewolf.net/

https://codeberg.org/librewolf

**G)** `Cromite` - 基于 Chromium 引擎的开源浏览器，移除了遥测功能，由独立开发者提供。经过广泛用户测试。适合日常浏览，但有一个注意事项——对跟踪器和其他遥测功能阻拦非常激进。内置 AdBlock。一些网站可能无法使用。这在 Cromite 中比上述浏览器更常发生。登录 Google 几乎不可能。但是 Cromite 在浏览器安全检查方面表现最佳——甚至连 PC 硬件都无法被检测到，更不用说其他数字指纹，一切都是“干净的”。而这一切都是开箱即用的。

https://github.com/uazo/cromite

这些浏览器不会引起提供商注意，因为…提供商只看到这些浏览器所使用的引擎，也就是说，很明显是 Chromium（Google Chrome、Ungoogled Chromium、Cromite）或 Firefox（Mozilla Firefox、Librewolf）。只有你自己能看到你使用的是哪种浏览器。

### `4. DNS 解析器`

使用普通 DNS (1.1.1.1) 在连接网站之前，我们会联系 DNS 解析器，它会看到我们要去哪里。任何 DNS 解析器运营商都能看到所有 DNS‑查询和响应（你允许访问哪些域名）。通过这些记录，你可以发现你将要连接到哪里。

如果你将 1.1.1.1 设置为加密的 DNS-over-HTTPS (DoH) 而不是普通 DNS (明文)，会发生什么？ 

你的 ISP 将无法再看到你连接的域名/网站名称。提供商只会看到你已建立到 IP‑DoH/DoT 解析器地址的连接（以及流量/时间）。

但 DNS 解析器仍然可以看到域名 + IP，因为你通过它传递 DNS 请求，即使是加密的，它也会接收并解密它们。

### `结论`

**为了在网络空间自由且有信心，以下方法有帮助：**

`DNS-OVER-HTTPS (DoH)` 

➕

 `正确的搜索引擎：Google 或 Duckduckgo`（不包括 Yandex） 
 
➕
  
`安全/独立浏览器：至少使用 Mozilla Firefox，最多 LibreWolf、Ungoogled Chromium、Cromite`（绝不使用 Yandex 浏览器）

---


**信息将会随着时间更新和完善。**

</details>


## <img src="https://cdn.jsdelivr.net/gh/igareck/GoldCaviar@refs/heads/main/Files/NYC_Statue_of_Liberty_2.gif" width="100" align="absmiddle"> 分享你的订阅！自由且负责任地使用互联网！

## 🔖 许可证

许可 GPL-3.0。许可证文件可以在 [`LICENSE`](LICENSE) 中找到。

## <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExM2wwMmJ3bDZvMWV2b2JraXZ4ZWk2Y2I5ODYyZ2M2aG5mMHc5ZW81ZyZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/ME8P6ce7Mn3gnRbird/giphy.gif" width="30"> `支持作者`

**该项目是非商业性的，基于作者的个人兴趣。**

**如果您想支持，可以通过两种方式：通过 `在 Patreon.com上捐赠` 或 `加密货币转账`。**

资金将用于持续活动和开发。

预先感谢每一位关心的人！

### 1. 向 `Patreon.com/igareck` 捐赠

[![在 Patreon 支持我](https://img.shields.io/badge/Support_me_on-Patreon-f96854?style=for-the-badge&logo=patreon&logoColor=white)](https://www.patreon.com/igareck/shop)

Patreon 在俄罗斯仅能通过 VPN 使用。

在俄罗斯，您可以通过以下方式支付：

**`国际银行卡`**

**`外国发行的虚拟卡`**

**`App Store 和 Google Play：通过手机内购支付 Patreon`**

**`中介支付服务（如下所列）`**

用于支付任何 Patreon 订阅、充值 App Store / Google Play 余额或提供国际 Visa/Mastercard 银行卡发行服务的中介列表：

<details>
<summary><code><em> 点击箭头展开支付/转账中介列表 </em></code></summary>

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

### 2. 加密货币转账

<details>
<summary><code><em> 点击箭头展开加密钱包列表 </em></code></summary>

⇩

选择任何便于您的加密货币并复制其地址。您只能向与所选币种匹配的钱包发送，否则资金将丢失。

| № | 币种 | 地址 |
|--|--|--|
| 1 | `比特币（BTC）` | `18vVz4UzFdxCGnCnAzJtXv6ECsh32ff9VT` |
| 2 | `数据库上的币种_Ethereum(ETH)：以太坊 (ETH), USDC (ETH), USDT (以太坊 ERC-20), 柴犬币 (SHIB)` | `0xfc668016a823f3EE53d2F3009547666A2BdaBd32` |
| 3 | `Tron 数据库中的币种_(TRX)：Tron (TRX)，USDC (TRX)，USDT (TRX)` | `TLnzF6NYgyqBHJMM2qByMXEHLBWNhBWcJ1` |
| 4 | `Toncoin 数据库中的币种_(TON)：Toncoin (TON)，Notcoin (NOT)，Hamster Combat (HMSTR)，USDT (USDT-TON)` | `EQAGbSuckE93yiACSENJGo8WuRq474Wba1J4yCF1Q59xsL0k` |
| 5 | `莱特币 (LTC)` | `LcHbh84V5PgWk1gTzjGWeef6NQT4MwE9RK` |
| 6 | `瑞波币 (XRP)` | `rNaKXrfLGsAVvA8JMr9dApMgCNzFmPbvTR` |
| 7 | `门罗币 (XMR)` | `47uvnonFqbyHMRrZadCAAvL2q9ed476PKdGtbLxXeUj1fs7gtPZ6mx3BeRBd2JM6Wmc16tN7K3ZcDMfds3cE8NaMCgAbD5Q` |
| 8 | `ZCash (ZEC)` | `t1cjEDjtLxatccB6o1pUPxb3pMByCz1L5Ct` |
| 9 | `狗狗币 (DOGE)` | `DRNBruzYDv5vWEz1ndGDjywqugVhd2Zmbm` |
| 10 | `索拉纳 (SOL)` | `Hxm9MjxfD1LNKaWuiFFLzBDTR5CnJSty7gRnkTfubiWj` |
| 11 | `恒星币 (XLM)` | `GDRN4K4VDDGNFIWJ3BAN7KL7576764RN44TBHTXYJIXMLK7RNP4UTSJ6` |
| 12 | `卡尔达诺 (ADA)` | `addr1qxpw4m02auvmrfee3suz98tvj82cm4mpfllvyda8fz004j40dpemdcuzntj5ykxwv2x6azyp982stfxegm9zvl9kf74s309qhu` |
| 13 | `NEAR 币 (NEAR)` | `d9cba0ec6233589267f43b91d8c156efb7fcd0a0177d7e8a34f7b791a61e7e35` |

</details>

<details>
<summary><code><em> 你在哪里买加密货币？ </em></code></summary>

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


## <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3ZmJ4anB6YjR3aWJpaTRvYzUzejY1dmwzN2c2M3c2NnV0MXUwM3RrcyZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/acN91ftm1tJX23OOBx/giphy.gif" width="60"> 联系邮箱: igareck@proton.me

## 👀 访客数量
<img src="https://komarev.com/ghpvc/?username=igareck&label=Visitors&color=0e75b6&style=flat" alt="Visitor Count" /> <img src="https://visitor-badge.laobi.icu/badge?page_id=igareck.visitor-badge&left_color=black&right_color=green&left_text=Cyber+Hits" alt="Cyber Hits"/>  
</div>

## <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExa2RkeXZzdDl1Y3g4dW1xcjFxc2xsMHVsZ2RiY243OHJodjd0cHQ1NSZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/qXp82ZL3eZbbTUrLyy/giphy.gif" width="30"> <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExa2RkeXZzdDl1Y3g4dW1xcjFxc2xsMHVsZ2RiY243OHJodjd0cHQ1NSZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/qXp82ZL3eZbbTUrLyy/giphy.gif" width="30"> <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExa2RkeXZzdDl1Y3g4dW1xcjFxc2xsMHVsZ2RiY243OHJodjd0cHQ1NSZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/qXp82ZL3eZbbTUrLyy/giphy.gif" width="30">

[![Star History](https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/refs/heads/star-tracker-data/charts/star-history.svg)](https://github.com/igareck/vpn-configs-for-russia)

## <img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3Z25rOXRoeW1xODR1dWh2b3UycTd6YnB0Y2hlMTZtaDluZW1uNnl4ZyZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/CeYEKonyFQyzWhxmvd/giphy.gif" width="40"> 免责声明

> *作者不是所列 VPN 配置的所有者/开发者/提供者。这是一篇独立的信息评测和测试结果。*
>
> *此文章不是 VPN 广告。所有材料仅供信息参考，且仅供所在国家法律允许的公民使用，至少用于科学目的。如果您无法阅读，请立即关闭此页面！* 
>
> *作者无意、也不鼓励、支持或容忍在任何情况下使用 VPN 或任何其他程序。*
>
> *使用这些 VPN 配置的任何行为由用户自行负责。*
>
> *免责声明：作者不对第三方行为负责，也不鼓励非法使用 VPN。*
>
> *作者不对所发布数据的准确性、完整性和可靠性负责。所有巧合均属随机。所有信息均按“原样”提供，可能不准确。*
>
> *请按照当地法规使用。* 
>
> *仅将 VPN 用于合法用途：特别是确保您的在线安全和安全远程访问，绝不可用此技术绕过封锁。*
>
> *该项目为非商业、免费项目，所有展示的“付款”信息均为在互联网上随机找到的，按原样复制，仅示例展示，不属于作者。*
>
> *建议 - 关闭此页面，从你的电脑上移除所有VPN，在所有设备上安装MAX和Yandex，这样即使在停车场也能“捕捉”，并且只使用互联网服务提供商允许的互联网资源，你明白我的意思。*
