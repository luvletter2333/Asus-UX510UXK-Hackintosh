# Asus ZenBook UX510UXK Hackintosh


### Specification

- CPU: i5 7200U

- GPU: HD620 and GTX950M(disabled)

- Wifi&Bluetooth: replaced with DW1560

- Audio: ALC256 with layout-id ~~13~~ 5 works prefectly!

- NVMe SSD: Intel 760p

- Type-C: works perfectly! both USB and DisplayPort!

- HDMI: Works well!

  Audio not tested. please open an issue if you pass it with AppleALC



## Clover (Deprecated)

Mainly From https://github.com/hieplpvip/ASUS-ZENBOOK-HACKINTOSH

Maybe some changes need to be emphasized:\

- Use HD617 to enable Type-C DisplayPort
- SMBIOS, MLB, UUID and so on are generated randomly
- Use OsxAptioFix3Drv.

- **Won't update anymore, moved to OpenCore**

### OpenCore

- OpenCore 0.6.6 with latest kexts
- **PLEASE FILL SMBIOS INFOMATION BY YOURSELF**
- Sleep works well (Fix [#1](https://github.com/luvletter2333/Asus-UX510UXK-Hackintosh/issues/1#issuecomment-708021869))

- Hibernation is still testing