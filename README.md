# Hackintosh Catalina Installation Guide for Gigabyte Z390 Aorus Pro WiFi

### Hardware

Type|Item
:----|:----
**CPU** | [Intel - Core i5-9400](https://shopee.com.my/product/18799831/1830724338)
**CPU Cooler** | [Cooler Master Hyper 212](https://shopee.com.my/product/27186464/1049199653) 
**Motherboard** | [Gigabyte - Z390 AORUS PRO WiFi](https://shopee.com.my/product/18799831/1830724338)
**Memory** | [Kingston HyperX FURY 16GB](https://shopee.com.my/product/44965307/1790719113)
**Storage (macOS)** | [ADATA XPG SX8200 Pro 512GB](https://shopee.com.my/product/84969687/1883571808)
**Storage (Windows)** | [KINGSTON A400 256GB](https://shopee.com.my/product/29242218/1103855234)
**Video Card** | [SAPPHIRE PULSE RX 5700 XT OC](about:blank)
**WiFi + Bluetooth** | [BCM943602CS](about:blank) + [PCI-E Adaptor](https://shopee.com.my/product/162227071/3405707076)
**Case** | [ECLIPSE P400A](https://shopee.com.my/product/1422162/6808915755)
**Power Supply** | [Cooler Master V1000 80+ Gold Modular](https://shopee.com.my/product/47928376/3300926225)
**Monitor 1** | DELL U2718Q
**Monitor 2** | DELL U2312HM

### What's Working/What's Not

##### Working
- Ethernet
- Onboard Audio
- HDMI Audio
- IGPU in headless mode
- App Store
- Wake/Sleep
- USB (Correct SS/HS speed)
- All DP and HDMI port
- Dual monitor from boot

##### Not Tested
- DP Audio
- Apple Music (iTunes)
- Power Nap
- Handoff
- Airdrop
- AirPlay
- Continuity
- Apple Music (iTunes)
- FileVault
- iMessage
- Facetime

##### Not Working
- Built-in WiFi and Bluetooth. This will never work, dont even waste time here. If you absolutely need Bluetooth and WiFi, get the BCM94360CS2 card.

### Caveat
- If you're stuck at `About 2 minutes remaining` in installer, add `EmuVariableUefi.efi` to your USB efi and redo the installation
- After first reboot, the installer might be stuck at `About 13/15 minutes remaining...`. Don't be alrmed, just give it 5 ~ 10 min, it will eventually work again. Your mouse and keyboard most probably wont be working in this installation stage
