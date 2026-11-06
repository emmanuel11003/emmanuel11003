# Hi there, I'm Emmanuel 👋

Android Enthusiast & Developer specializing in lightweight, bloat-free TV experiences and performance tuning for the **Haier 55P7GT-P / HR9676EU** (MediaTek `omonia`, Google TV 14).

---

## 📺 Featured Project: [CleanYourTV (Haier 55P7GT-P Edition)](https://github.com/emmanuel11003/cleanyourtv)
*A custom, performance-tuned fork of [Gathin23/cleanyourtv](https://github.com/Gathin23/cleanyourtv) engineered specifically for the Haier 55" Google TV platform.*

### 📸 Live Screen Captures (Captured from Haier 55P7GT-P)

<p align="center">
  <img src="screenshots/home_aurora.png" width="800" alt="Aurora Theme with Transparent Glass Dock on Haier 55P7GT-P" />
  <br>
  <em>Home Screen with Permanent Aurora Glass UI, 5-Column Responsive Dock & LiveClock Subsystem</em>
</p>

<p align="center">
  <img src="screenshots/dock_view.png" width="49%" alt="5-Column Dock Navigation" />
  <img src="screenshots/task_switch.png" width="49%" alt="Fluid Task Transitions & Zero Pop-Up" />
  <br>
  <em>Left: 5-column calibrated dock navigation | Right: Instant task switching without pop-up or icon flash</em>
</p>

---

### 🚀 Key Features & Customizations

#### 🎨 Visual & Theme Engine
- **Permanent Aurora Glass Defaults**: Hardcoded high-performance Aurora theme with transparent backgrounds, subtle card outlines, and zero background render overhead.
- **5-Column Responsive Dock**: Dock geometry calibrated for 55-inch viewing distance and ergonomic D-pad step navigation.
- **Custom Wallpaper & Card Integration**: Handled theme configuration with clean glass aesthetic and border focus highlights.

#### ⚡ Performance & Animation Tuning
- **0.5x Global Animation Scales**: Hardcoded `window_animation_scale`, `transition_animation_scale`, and `animator_duration_scale` to `0.5x`, cutting UI lag and latency on MediaTek SoCs in half.
- **Android 14 Pop-Up & Flicker Elimination**: Removed activity launch window pop-up animations and resolved the Android 14 task-switch glitch where the previous app's icon flashed before launching the new task.
- **Hardware-Accelerated Fluidity**: Stripped redundant view invalidations during rapid remote input.

#### ⏱️ LiveClock Subsystem Fixes
- **Baseline Alignment & Font Clipping**: Resolved vertical font cut-off on custom typefaces for the top status bar.
- **Digit Doubling Fix**: Prevented simultaneous dual-text rendering during rapid time changes.
- **Idle CPU Thread Conservation**: Automatically pauses the background clock ticker handler when the launcher is not in the foreground, saving CPU cycles and reducing standby RAM footprint.

#### 🛡️ Dock Stability & System Debloat
- **Dock Boundary Hardening**: Hardened layout boundaries and bounds checking in `DockDecoration` to eliminate scrolling glitches and focus traps.
- **Retail Demo & Bloat Removal**: Deactivated the background retail store demo loop (`com.mediatek.tv.retaildemo`) and Google launcher bloat for an instant, clean boot.

---

### 🛠️ Tech Stack & Platform
<p align="left">
  <img src="https://img.shields.io/badge/Android%20TV-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android TV" />
  <img src="https://img.shields.io/badge/Google%20TV%2014-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Google TV 14" />
  <img src="https://img.shields.io/badge/MediaTek%20SoC-00A4E4?style=for-the-badge&logo=arm&logoColor=white" alt="MediaTek" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/ADB%20Tooling-02569B?style=for-the-badge&logo=android&logoColor=white" alt="ADB" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
</p>

---

### 📊 GitHub Activity
<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=emmanuel11003&show_icons=true&theme=tokyonight&hide_border=true" alt="Emmanuel's GitHub stats" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=emmanuel11003&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" height="150" />
</p>

---

<p align="center">
  <i>Engineered for speed. Crafted for minimalism. Powered by open source.</i>
</p>
