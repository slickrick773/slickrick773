### slickrick773 🏴‍☠️

**Offensive security researcher — embedded, wireless, RF.**

I break and rebuild the hardware people trust — finding what the datasheets
hide, bending locked-down silicon to new purposes, and proving every claim on
real metal.

`Wi-Fi` · `BLE` · `sub-GHz` · `RF` · `GPS` · `hardware RE`

[Discord](https://discord.com/users/257432464815947776) · [Instagram](https://www.instagram.com/slickrick773_/) · [YouTube](https://www.youtube.com/@SlickyRicky773)

### ESP32-C5-BSP

**[ESP32-C5-BSP](https://github.com/slickrick773/ESP32-C5-BSP)** is board support for the Waveshare ESP32-C5 3.5-inch and 2.8-inch touch boards: display, touch, GPS, speaker and microphone, clock, IMU, battery and microSD. Every capability is tagged by how it was proven, and the [hardware findings](https://github.com/slickrick773/ESP32-C5-BSP/blob/main/docs/HARDWARE-FINDINGS.md) record what the bench showed, including the things that did not work.

Install from the PlatformIO registry as `slickrick773/ESP32-C5-BSP`.

### One board, ten firmwares

I brought the Waveshare ESP32-C5-Touch-LCD-3.5 up on each of these and carry the fixes upstream.

| Firmware | Landed | In review |
|---|---|---|
| [Bruce](https://github.com/BruceDevices/firmware) | board port [#2995](https://github.com/BruceDevices/firmware/pull/2995), audio fix [#2994](https://github.com/BruceDevices/firmware/pull/2994) | clean boot [#3067](https://github.com/BruceDevices/firmware/pull/3067), header docs [#2998](https://github.com/BruceDevices/firmware/pull/2998) |
| [Marauder](https://github.com/justcallmekoko/ESP32Marauder) | board support, in `develop` | clean boot [#1691](https://github.com/justcallmekoko/ESP32Marauder/pull/1691), wardrive BLE bridge [#1671](https://github.com/justcallmekoko/ESP32Marauder/pull/1671), USB serial [#1669](https://github.com/justcallmekoko/ESP32Marauder/pull/1669) |
| [Picoware](https://github.com/jblanked/Picoware) | board port [#361](https://github.com/jblanked/Picoware/pull/361), audio [#373](https://github.com/jblanked/Picoware/pull/373), Wi-Fi and timer fixes [#372](https://github.com/jblanked/Picoware/pull/372) [#374](https://github.com/jblanked/Picoware/pull/374) [#360](https://github.com/jblanked/Picoware/pull/360) | |
| [Launcher](https://github.com/bmorcelli/Launcher) | board port [#458](https://github.com/bmorcelli/Launcher/pull/458) | |
| [PorkChop](https://github.com/Xombi3/Porkchop-cyd-Port) | board port [#11](https://github.com/Xombi3/Porkchop-cyd-Port/pull/11), WarDriveGo bridge [#14](https://github.com/Xombi3/Porkchop-cyd-Port/pull/14) | |
| [umbravox](https://github.com/Em3ritus/umbravox) | board support [#1](https://github.com/Em3ritus/umbravox/pull/1), handheld UI and browser installer [#2](https://github.com/Em3ritus/umbravox/pull/2) | |
| [GhostESP](https://github.com/GhostESP-Revival/GhostESP) | | board support [#433](https://github.com/GhostESP-Revival/GhostESP/pull/433) |
| [SquachWatch](https://github.com/skizzophrenic/SquachWatch-CYD) | | board support [#83](https://github.com/skizzophrenic/SquachWatch-CYD/pull/83) |
| [AWOKxDAG](https://github.com/dagnazty/awokxdag) | | board profile [#11](https://github.com/dagnazty/awokxdag/pull/11) |
| [Piglet](https://github.com/Hamspiced/piglet) | | board port and mesh node [#20](https://github.com/Hamspiced/piglet/pull/20) |

[All pull requests](https://github.com/pulls?q=is%3Apr+author%3Aslickrick773)
