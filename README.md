<h1 align="center">TroyMetrics Benchmark Overlays 2</h1>
<p align="center">RTSS / RivaTuner Overlays by TroyMetrics 👻</p>

<div align="center">
  <a href="https://www.youtube.com/watch?v=B1buBwhr-H0">
    <img src="https://github.com/TroyMetrics/Ultimate-Benchmark-Overlays/blob/main/assets/images/YT_Thumbnail.png?raw=true" width="850">
  </a>
</div>

# 📖 Overview

A high-precision, **adaptive** performance overlay for RTSS that automatically aligns with your system’s hardware configuration—covering CPU & GPU telemetry, latency, animation error, frametime, power delivery, and more. Designed for benchmarkers, gamers, system builders, enthusiasts, and content creators, it unifies dozens of advanced metrics into a single clean, cohesive display. Powered by **RTSS** and **HWiNFO64**, the overlay is optimized for accurate, real-time analysis for 4K displays, whether for gameplay monitoring or benchmarking.

# 📺 Video Walkthrough

<div align="center">
  <a href="https://youtu.be/UXC3-rGV7BA">
    <img src="https://github.com/TroyMetrics/TM-Benchmark-2/blob/main/assets/images/Thumbnail%20v3%20PB.png?raw=true" width="850">
  </a>
</div>

# 🛠️ Setup & Installation

## ✅ Prerequisites

Before setting up the TM Benchmark 2 Overlays, make sure the following software is installed and properly configured:

**✅ MSI Afterburner + RivaTuner Statistics Server (RTSS)**

🔽 Download the latest BETA versions of **MSI Afterburner & RTSS** from [www.guru3d.com](https://www.guru3d.com/files-details/msi-afterburner-beta-download.html)
> 📝 Note: The latest beta builds are often shared exclusively on the official Guru3D forums by the developer, Unwinder.
- The MSI Afterburner installer includes **RivaTuner Statistics Server (RTSS)** as a bundle — this is required for the overlay to function.
- During installation, ensure that **✅ RivaTuner Statistics Server** is left **check-marked.**

---

**✅ HWiNFO64**

🔽 Download the latest version of **HWiNFO64** from [www.hwinfo.com](https://www.hwinfo.com/download/)
> **🛡️ Recommended for Power Users:** Consider purchasing the paid version to remove the **12-hour Shared Memory Support time limit** and **enable automatic updates.**

**⚙️ Important Configuration Steps:**
1. Launch HWiNFO64 (Sensors Only) and click the **`[Sensors]`** button
2. Click the Cogwheel button in the bottom-right ⚙️ **`"Configure Sensors"`**
3. In the new window, click **`[Main Settings]`** (bottom-right)
4. Make sure **`✔ Shared Memory Support`** is enabled

> ✅ Shared Memory Support is required for RTSS to read sensor data from HWiNFO — especially critical for modules like the **12VHPWR Power Detector** (per-pin amperage monitoring).

---

## 🛠️ Setup Instructions

> ⚠️ **Important:** RTSS must be installed on the **C:\\ drive**. Installing it elsewhere (e.g. D:\\) can cause missing or broken overlay icons due to location-dependent resources. See [Issue #7](https://github.com/TroyMetrics/Benchmark-Overlays/issues/7) for details and a potential work around.

**1. 📦 Extract and Prepare Files**
- Open the downloaded package
- In a **new File Explorer window**, navigate to your **`C:\` drive**

**2. 📁 Copy Overlay Files to RTSS**
- **Drag and drop** (or **copy/paste**) the folder named **`Program Files (x86)`** from the downloaded package directly into your **`C:\` drive**
- If prompted for admin permission:
  - ✅ Check **"Do this for all current items"**
  - ✅ Click **"Continue"**

> This step places the overlay files in the correct RTSS directory.

---

**3. 🔤 Install the Required Font**
- Navigate to:  
  `C:\Program Files (x86)\RivaTuner Statistics Server\Fonts`
- Double-click to install: **Adderley Bold.ttf**

> **Font credit:** *Adderley* by gorohovskiy  
> Licensed under the SIL Open Font License. All rights reserved by the original creator.

---

**4. ⚙️ Enable OverlayEditor in RTSS**
1. Launch **RivaTuner Statistics Server (RTSS)**  
2. Click the **`[Setup]`** button  
3. In the new window, go to the **Plugins** tab:
   - ✅ Enable **`OverlayEditor.dll`**
   - ✅ (Optional but recommended) Enable **`HotkeyHandler.dll`**
     - Highlight **`HotkeyHandler.dll`** & Click **`[Setup]`** at the bottom to assign hotkeys:
       - **Toggle On-Screen Display**: e.g., `Home`
       - **Begin/End Recording**: e.g., `Page Up / Page Down`

> ⚠️ If you’ve already assigned hotkeys in **MSI Afterburner**, you can skip this step or unassign them there. Only **one program** should manage OSD hotkeys to avoid conflicts.

---

**5. 🎛 Load the Overlay in OverlayEditor**
1. With **OverlayEditor.dll** enabled, double-click it or click **`[Setup]`** after high-lighting it 
2. In the Overlay Editor window:
   - Go to the **`Layouts`** tab → Click **`Load`**
   - Select one of the **`TM Benchmark 2`** presets → Click **`Open`**

---

**6. 🧠 Apply Master Settings (Important)**
- Since **RTSS Beta 7.3.2**, you can now use **`Ctrl + Shift + M`** to apply the overlay’s master layout settings. Otherwise, follow the steps below for manual application.
- Back in the **Layouts** tab → Click **`Edit`**
- In the **Overlay Properties** window:
  - Click **`[Master Settings]`**
  - Click **`Yes`** when prompted
  - Click **`OK`** to finalize

---

**7. 🔍 Adjust Zoom Slider (if necessary)**

[Size Reference Chart](https://github.com/TroyMetrics/Benchmark-Overlays-2/blob/main/assets/images/TMBO2%20Size%20Reference%20Chart.png) — Download and view at 100% scale for accurate size representation.

The overlay was originally designed for 4K displays at a 300% Zoom level for maximum sharpness and pixel clarity.

To adjust scaling, simply use the Zoom slider in RTSS to fit your display.
<div align="center">
  <img src="https://github.com/TroyMetrics/Benchmark-Overlays/blob/main/assets/images/RTSS_Zoom_Example.gif?raw=true">
</div>
🖥️ For 1080p users, select the 1080p presets — these were fully redesigned to deliver crisp visuals and proper scaling at 1080p resolution. <br><br>

✅ Your overlay is now fully active and ready to use!

# ❤️ A Note to the Community

If you encounter any issues, or anything that feels off — please open an Issue on GitHub. Screenshots are incredibly helpful and greatly speed up fixes.

Your reports and suggestions directly help these project grow.
Thank you for testing, supporting, and helping improve these overlays for everyone. 🙏

# 🧙‍♂️ More from TroyMetrics

If you enjoy this overlay, check out some other designs:

- [📌 **TroyMetrics Benchmark Overlays**](https://github.com/TroyMetrics/Benchmark-Overlays)
- [📌 **TM GamerStats 1080p**](https://github.com/TroyMetrics/TM-GamerStats-1080p)

*(This list will continue to expand as more designs are released.)*

🚀 Happy Benchmarking!  
