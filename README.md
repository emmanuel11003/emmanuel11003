<div align="center">
  <img src="https://raw.githubusercontent.com/emmanuel11003/emmanuel11003/main/screenshots/header_banner.svg" width="100%" alt="Emmanuel J Joseph - Android TV Tweaking & Customization" />
</div>

<p align="center">
  <a href="https://github.com/emmanuel11003/cleanyourtv"><img src="https://img.shields.io/badge/Focus-Android_TV_Tweaks-0A84FF?style=for-the-badge&logo=android&logoColor=white" alt="Focus" /></a>
  <a href="https://github.com/emmanuel11003/cleanyourtv"><img src="https://img.shields.io/badge/Platform-Google_TV_14-30D158?style=for-the-badge&logo=google&logoColor=white" alt="Platform" /></a>
  <a href="https://github.com/emmanuel11003/cleanyourtv"><img src="https://img.shields.io/badge/Hardware-MediaTek_SoC-FF9F0A?style=for-the-badge&logo=arm&logoColor=white" alt="Hardware" /></a>
  <a href="https://github.com/emmanuel11003/cleanyourtv/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-BF5AF2?style=for-the-badge" alt="License" /></a>
</p>

---

### 🛠️ Overview

Android TV enthusiast passionate about **tweaking, customizing, and optimizing smart TV experiences**. Focused on stripping bloatware, eliminating interface latency, and tailoring custom launcher themes for maximum speed and clean minimalism on smart TV hardware (MediaTek SoCs).

- 📺 **Custom Setup**: Performance-tuned fork for [CleanYourTV (Haier 55" Platform)](https://github.com/emmanuel11003/cleanyourtv).
- ⚡ **Goal**: Zero bloat, instant remote responsiveness, and clean aesthetic customization.
- 🎯 **Target Device**: Haier 55P7GT-P / HR9676EU (Board: `omonia` / MediaTek, Google TV 14).

---

## 📺 Featured Project: CleanYourTV (Haier 55" Edition)

> Built on top of the open-source [Gathin23/cleanyourtv](https://github.com/Gathin23/cleanyourtv) baseline, customized and tuned for real-world personal use on 55" 4K Google TV 14 displays.

<div align="center">
  <table border="0" cellspacing="10" cellpadding="0">
    <tr>
      <td colspan="2" align="center">
        <a href="https://github.com/emmanuel11003/cleanyourtv">
          <img src="https://raw.githubusercontent.com/emmanuel11003/emmanuel11003/main/screenshots/home_aurora.png" width="95%" alt="CleanYourTV Aurora Edition" />
        </a>
        <br>
        <sub><b>Primary Interface:</b> Hardcoded Aurora Glass Theme, Dynamic Status Bar, and 5-Column Responsive App Dock</sub>
      </td>
    </tr>
    <tr>
      <td width="50%" align="center">
        <a href="https://raw.githubusercontent.com/emmanuel11003/emmanuel11003/main/screenshots/dock_view.png" target="_blank">
          <img src="https://raw.githubusercontent.com/emmanuel11003/emmanuel11003/main/screenshots/dock_view.png" width="95%" alt="Calibrated 5-Column Dock" />
        </a>
        <br>
        <sub><b>Dock Architecture:</b> 5-Column layout calibrated for 55" D-Pad remote navigation <i>(Click to enlarge)</i></sub>
      </td>
      <td width="50%" align="center">
        <a href="https://raw.githubusercontent.com/emmanuel11003/emmanuel11003/main/screenshots/task_switch.png" target="_blank">
          <img src="https://raw.githubusercontent.com/emmanuel11003/emmanuel11003/main/screenshots/task_switch.png" width="95%" alt="Flicker-Free Task Switcher" />
        </a>
        <br>
        <sub><b>Engineered Transitions:</b> 0.5x duration scales with zero icon flash or pop-up latency <i>(Click to enlarge)</i></sub>
      </td>
    </tr>
  </table>
</div>

---

### ⚙️ Tweaks & Customization Highlights

```
┌────────────────────────────────────────────────────────────────────────┐
│                        HAIER 55P7GT-P PLATFORM                         │
├──────────────────────┬───────────────────────┬─────────────────────────┤
│    THEME & DOCK      │ PERFORMANCE TUNING    │    SUBSYSTEM FIXES      │
├──────────────────────┼───────────────────────┼─────────────────────────┤
│ • Permanent Aurora   │ • 0.5x System Scale   │ • Fixed Clock Baseline  │
│ • Transparent Glass  │ • Instant App Launch  │ • Digit Ghosting Solved │
│ • 5-Column Geometry  │ • No Window Pop-up    │ • Idle Thread Pauses    │
│ • Zero Background UI │ • Eliminated Icon Lag │ • Hardened Dock Bounds  │
└──────────────────────┴───────────────────────┴─────────────────────────┘
```

| Area | Tweaks & Applied Customizations |
| :--- | :--- |
| **Theme Engine** | Built-in permanent **Aurora Theme** defaults featuring translucent card backings, custom wallpaper gradients, and zero background render overhead. |
| **Motion & Latency** | Hardcoded **0.5x animation scales** across window, transition, and animator durations to cut interface traversal latency in half on MediaTek processors. |
| **Task Lifecycle** | Neutralized standard Android 14 task launch artifacts; eliminated the previous application's ghost icon flash when switching tasks via remote. |
| **LiveClock Core** | Patched typeface baseline clipping and simultaneous dual-digit rendering; integrated lifecycle listeners to pause clock tick threads during background states. |
| **System Hygiene** | Implemented non-destructive package disabling for background retail demo services (`com.mediatek.tv.retaildemo`) without root or partition modification. |

---

### 🧰 Tools & Environment

<div align="center">

| Domain | Tools & Setup |
| :--- | :--- |
| **Operating Systems** | `Android TV (Pie → 14)` `Google TV` `Linux / Shell` `Windows CLI` |
| **Languages & Configs**| `Java (Android SDK)` `Python` `XML Configs` `Bash / PowerShell` |
| **Diagnostics & Tools**| `Android Debug Bridge (ADB)` `Logcat` `Git` `GitHub` |
| **Hardware Targets** | `MediaTek Smart TV SoCs` `Haier 55" 4K TV` |

</div>

---

### 📈 GitHub Analytics

<div align="center">
  <p align="center">
    <a href="https://github.com/emmanuel11003">
      <img src="https://streak-stats.demolab.com/?user=emmanuel11003&theme=dark&hide_border=true&background=0d1117&ring=58a6ff&fire=58a6ff&currStreakNum=58a6ff" alt="Emmanuel's Contribution Streak" />
    </a>
  </p>
  <table border="0" cellspacing="0" cellpadding="0">
    <tr>
      <td align="center">
        <a href="https://github.com/emmanuel11003">
          <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=emmanuel11003&theme=github_dark" alt="Profile Details" />
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/emmanuel11003">
          <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=emmanuel11003&theme=github_dark" alt="Most Commit Language" />
        </a>
      </td>
    </tr>
  </table>
</div>

---

<div align="center">
  <sub>Maintained by <b>Emmanuel J Joseph</b> • Code licensed under <a href="https://github.com/emmanuel11003/cleanyourtv/blob/main/LICENSE">MIT</a> • Upstream base: <a href="https://github.com/Gathin23/cleanyourtv">Gathin23/cleanyourtv</a></sub>
</div>
