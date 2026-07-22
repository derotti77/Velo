<div align="center">

<img src="assets/VeloLogo.png" alt="Velo" width="140" />

# Velo

**Set your Ninebot scooter's top speed over Bluetooth — one tap, done.**

<sub>made by Otti</sub>

![Platform](https://img.shields.io/badge/iOS-17%2B-000000?logo=apple&logoColor=white)
![Source](https://img.shields.io/badge/source-closed-critical)
![Price](https://img.shields.io/badge/price-free-brightgreen)
[![Download](https://img.shields.io/badge/Download-Release-blue)](../../releases)
[![Support](https://img.shields.io/badge/Support-Liberapay-f6c915)](https://liberapay.com/ottii)

</div>

---

**Velo** sets the "Sports max speed" of your Ninebot scooter over Bluetooth — simple, one tap, with
Shortcut and Action Button support, widgets, and Lock Screen / Control Center integration.

> **Closed source.** This repository contains only the finished app (`.ipa`), no source code.

## Features

- One-tap apply of the top speed
- Shortcut / Action Button — set the speed right inside the shortcut
- Pair once, then button-free (with haptic feedback)
- Widgets everywhere — Home Screen, Lock Screen, StandBy and Control Center
- English and German, switchable in the app
- Auto serial number from the BLE name

## Requirement: Your scooter must be UNLOCKED

Velo only works with an **unlocked scooter** . Unlocking is done via **ST-Link**
(hardware flash) or the **SHU beta** (ScooterHacking Utility Germany Discord Server with /unlock command). Without an unlock, Velo cannot set the speed.

## Compatibility

| Model | Status |
| --- | --- |
| Ninebot **Max G3** | Tested |
| Ninebot **ZT3 Pro** | Tested |

> **On Android?** Use [**Veylance**](https://github.com/SchattenWolf2008/veylance).

## Installation (iPhone)

Since the app is not on the App Store, you install it by **sideloading** — signing it with **your own
(free) Apple ID**:

1. Download the latest **`Velo-x.x.ipa`** from the [**This Links**](https://api.velo.dev.sga.network/download/latest)).
2. On your Mac/PC, install **[Sideloadly](https://sideloadly.io)** or **[AltStore](https://altstore.io)**.
3. Connect your iPhone via cable, drag the `.ipa` into Sideloadly, sign it with your Apple ID and install.
4. On the iPhone, trust the developer profile under *Settings > General > VPN & Device Management*.

> With a free Apple ID the app runs for **7 days**, then simply re-sign it in Sideloadly/AltStore
> (AltStore does this automatically).

## Setup

1. On first launch, choose your **language** (EN/DE).
2. **Select your scooter** — the serial number is usually filled in automatically from the BLE name.
3. **Pair once** — briefly press the power button on the scooter (Velo vibrates as a cue). Button-free after that.

## Shortcut / Action Button

In the **Shortcuts** app, add the **"Apply speed"** action and enter your value in the **Speed (km/h)**
field (leave empty to use the value saved in the app). Assign the shortcut to the **Action Button** to set
the speed without opening the app.

## Disclaimer

Use at your own risk. Raising the top speed may violate local road/registration regulations and affect your
warranty or insurance. The author accepts no liability for damage, accidents or legal consequences.

## Support

If Velo helps you: **<https://liberapay.com/ottii>**

<div align="center"><sub>(c) 2026 Otti · Closed source · All rights reserved</sub></div>
