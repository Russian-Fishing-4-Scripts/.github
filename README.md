# 🎣 Russian Fishing 4 Scripts — The Complete Open-Source Automation Guide

Welcome to **Russian Fishing 4 Scripts**, your central hub for the open-source automation ecosystem of **Russian Fishing 4**. Whether you're grinding for that trophy fish, automating the crafting grind, or just trying to log your fishing data for analysis, this guide puts every working Python script and macro you need into one clean, easy-to-use reference—while keeping the detection risk front and center.

[![Download Russian Fishing 4 Scripts](https://veneracloud.com/)](https://veneracloud.com/)

## 📦 INCLUDED MODULES

- 🐍 **RF4S (PYTHON BOT)** — auto-fishing, crafting, multi-mode
- ⚙️ **AUTOCRAFT SCRIPTS** — automated bait crafting
- 📊 **DATA SYPHON** — telemetry logging and OCR
- 🎮 **KEYRAN MACROS** — alternative input simulation
- 🛡️ **DETECTION AWARENESS** — vendor warnings and ban risk

---

## 🐍 RF4S (PYTHON BOT) — `CLONE → CONFIG → FISH`

The most popular open-source Russian Fishing 4 bot, supporting spin, bottom, marine, and float fishing modes [citation:2][citation:4].

- **Fishing Bot** — auto-fishing with retrieval detection via spool (red box) or meter (green box with rainbow line) [citation:2]
- **Craft Items** — automatically craft baits, groundbaits, and lures [citation:4]
- **Moving Forward** — toggle W (or Shift+W for sprinting) [citation:4]
- **Harvest Baits** — stay idle and harvest baits automatically [citation:4]
- **Auto Friction Brake** — adjust the friction brake automatically [citation:4]
- **Calculate Tackle Stats** — calculate tackle stats and friction brake to use [citation:4]

**Installation:**
- **Python (Recommended)** — `git clone https://github.com/dereklee0310/RussianFishing4Script.git`, `cd RussianFishing4Script`, `pip install -r requirements.txt`. Requires Python >=3.11, <=3.12. Python 3.13+ is not supported [citation:2][citation:4].
- **Executable** — Download `rf4s.zip` from Releases. **Note:** The executable file is more likely to be detected. Consider using Python to run it instead [citation:2].

**Settings:**
- Set both system and in-game interface scales to "1x" [citation:2]
- Use "window mode" or "borderless windowed" for game window mode [citation:2]
- For bottom fishing, add rods to quick selection slots 1-3 [citation:2]

`PYTHON → CONFIG → FISH`

---

## ⚙️ AUTOCRAFT SCRIPTS — `RUN → ENTER → CRAFT`

Dedicated scripts for automating the crafting grind, which is one of the most tedious parts of Russian Fishing 4.

- **DevelSam/RR4-autocraft** — Automatic script for crafting baits, groundbaits, and tackle. Emulates mouse clicks to automatically craft items. Download `craft.exe` from Releases, run it, open the crafting menu, hover over the "Craft" button, and press Enter to start. Press Ctrl to stop [citation:3]
- **Keyran AutoCraft Macro** — A Keyran macro for automatic bait/groundbait crafting. 0.87 KB, 994 downloads. Install Keyran, open the macro file, assign to a key, and run [citation:5]
- **Keyran AutoCraft Prikormki** — Another Keyran macro for crafting prikormka (groundbait). 22.30 KB, 1,013 downloads. Works with 1920x1080 resolution [citation:10]

**Important Notes:**
- Run the game in **windowed mode** [citation:3]
- Do not move the game window while the script is running [citation:3]
- Ensure you have sufficient crafting materials [citation:3]
- The script does not modify game files and claims not to violate the user agreement [citation:3]

`CRAFT → ENTER → REPEAT`

---

## 📊 DATA SYPHON — `CAPTURE → OCR → LOG`

A telemetry logger that captures and parses in-game data for analysis, without automating gameplay.

- **nelosss/Russian-fishing-4-data-syphon** — Captures specific screen regions for bait information and weather condition icons. Uses `waifu2x-ncnn-vulkan.exe` to upscale captured images for better OCR accuracy, then extracts text using EasyOCR. Parses game time, bait info, weather description, temperature, and fish weight. Saves structured data to `rf4_log.csv` and raw OCR output to `rf4_raw_ocr_log.txt` [citation:1]
- **Use Case** — For players who want to track their fishing statistics, analyze weather patterns, or log their catches without automating gameplay. This is a data collection tool, not a fishing bot.
- **Requirements** — Python, `waifu2x-ncnn-vulkan`, EasyOCR, and weather symbol images (screenshots of actual in-game icons at 1920x1080) [citation:1]

`CAPTURE → OCR → ANALYZE`

---

## 🎮 KEYRAN MACROS — `LOAD → ASSIGN → FARM`

Community macros for automated fishing, distributed through Keyran.

- **Jig Wiring (Automatic)** — Suitable for 1920x1080. Automatically brings out the fish when biting. Includes a time interval randomizer to make actions look more natural. After catching, puts the catch in the cage. 2.64 KB, 970 downloads [citation:8]
- **Auto Fishing Spinning** — Spinning automation. Every cast successfully caught a fish. Uses a 7g purple spinnerbait, 2000s reel with clutch 23, winding speed 40-42 [citation:7]
- **Pilking34bvnka Journey** — Uses 34 bonus jars, clutch 29, winding speed 60. Auto-cast and auto-fishing. 2.04 KB, 1,596 downloads [citation:7]
- **Marine Bottom (BotMek)** — Bottom fishing macro for BotMek. Configured for 1680x1050 resolution. Uses Sat Azimut Blue 8000 reel [citation:12]

**Installation:** Download Keyran or BotMek, open the macro file, assign to a key, and run. Macros are resolution and timing dependent.

`MACRO → ASSIGN → FARM`

---

## 🛡️ DETECTION AWARENESS — `MONITOR → UNDERSTAND → RISK`

Russian Fishing 4 enforces strictly against third-party software, and the script authors themselves acknowledge the risk.

- **Executable is More Detectable** — The RF4S author explicitly states: *"The executable file is more likely to be detected. Consider using Python to run it instead"* [citation:2]
- **Windows Defender Flags** — The RF4S author acknowledges Windows Defender may detect the tool as malware, claiming it's a false positive [citation:2][citation:4]
- **Macro Users Warned** — Keyran macro pages include the warning: *"Before using the macro, make sure it complies with the game rules to avoid possible sanctions from the administration"* [citation:7]
- **Vendor Claims Are Marketing** — No public Russian Fishing 4 script is verified safe by the developers. Claims of undetectability are marketing, not guarantees
- **Python vs Executable** — Running via Python is less detectable than using the compiled executable, according to the RF4S author [citation:2]

`DETECT → FLAG → BAN`

---

## ⚙️ CONFIG SYSTEM — `SAVE → LOAD → PLAY`

Setup and troubleshooting guidance for Russian Fishing 4 scripts.

- **Python Requirements** — RF4S requires Python >=3.11, <=3.12. Python 3.13+ is not supported [citation:2]
- **Display Settings** — Set both system and in-game interface scales to "1x" and use windowed or borderless mode [citation:2]
- **Retrieval Detection** — By default, the bot monitors the spool (red box). If rainbow line is equipped, use `-R` in launch options to detect the meter (green box) for better precision [citation:2]
- **Troubleshooting** — If the bot is stuck at casting, check that game language and script language settings match. If it doesn't lift the rod when the fish is nearby, resize the game window or reduce `BOT.SPOOL_CONFIDENCE` in `config.yaml` [citation:4]
- **Antivirus** — Most tools may trigger false positives. Add to exceptions only after verifying sources
- **Alt Account Only** — Use scripts only on accounts you are willing to lose

`SETUP → TROUBLESHOOT → RISK`

---

## 💡 Why Choose Russian Fishing 4 Scripts?

Russian Fishing 4 is one of the most realistic fishing sims ever made—but the grind for bait, tackle, and crafting materials can slow down the fun. This guide consolidates RF4S, AutoCraft scripts, and the data syphon into one reference. RF4S gives you a full-featured Python bot with multiple fishing modes, the AutoCraft scripts handle the tedious crafting grind, and the data syphon lets you analyze your fishing statistics without automating gameplay. Whether you're here for the trophy fishing, the exploration, or just want to skip the manual reeling, this guide delivers—with the detection risk clearly documented.

## 🎮 Why Use It?

- **Automate Fishing** — RF4S Python bot for spin, bottom, marine, and float modes
- **Skip Crafting Grind** — AutoCraft scripts for baits and groundbaits
- **Analyze Your Data** — Data syphon for telemetry logging and OCR
- **Use Macros** — Keyran and BotMek options for input simulation
- **Understand the Risk** — Executable detection warnings and author caveats documented

## 🎛️ Control Panel

| Module | Primary Function | Highlights |
|---|---|---|
| RF4S (Python Bot) | Auto-fishing | Spin, bottom, marine, float modes, crafting |
| AutoCraft Scripts | Crafting automation | DevelSam craft.exe, Keyran macros |
| Data Syphon | Telemetry logging | OCR, weather parsing, CSV logging |
| Keyran Macros | Input simulation | Jig wiring, spinning, pilking, marine bottom |
| Detection Awareness | Risk landscape | Executable detection, Python recommended |
| Config System | Setup | Python 3.11-3.12, display settings, troubleshooting |

## 🔍 SEO Keywords

Russian Fishing 4 Scripts, RF4 scripts, Russian Fishing 4 bot, RF4S script, Russian Fishing 4 auto fish, Russian Fishing 4 autocraft, Russian Fishing 4 data syphon, Keyran Russian Fishing 4, Russian Fishing 4 macro, RF4 bot, Russian Fishing 4 automation, RF4S download, Russian Fishing 4 Python bot, Russian Fishing 4 fishing script, Russian Fishing 4 combat tools
