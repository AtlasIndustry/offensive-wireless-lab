# RF & Wireless Red Teaming – Learning Log

##  Wi-Fi Attacks (Completed)

Captured and cracked a WPA2 handshake using:
- `airmon-ng`, `airodump-ng`, `aireplay-ng`, `aircrack-ng`
- Cracked pre-shared key using `rockyou.txt`
- Tools tested on personal Wi-Fi network using ALFA USB adapter
- Planning to automate process via Bash wrapper (`wifi_crack_helper.sh`)

##  Near-Term Roadmap

- Automate capture + crack process with advanced options
- Test handshake cracking using `hashcat` + GPU
- Research WPS attacks (Pixie Dust, Reaver)

##  BLE (Bluetooth Low Energy) Exploration

- [ ] Set up BLE sniffing using `bleah`, `gatttool`, or `btmon`
- [ ] Capture GATT characteristics and replay BLE advertisements
- [ ] Attempt spoofing of BLE beacon payloads

##  SDR & Sub-GHz (Planned)

- [ ] Order HackRF One or RTL-SDR
- [ ] Install `SDRSharp`, `GNU Radio`, and `rtl_433`
- [ ] Scan 433 MHz / 315 MHz for IoT or garage openers
- [ ] Attempt replay attacks on recorded signals

##  Hardware

-  ALFA AWUS036ACH (Wi-Fi testing)
-  BLE dongle (HCI support)
-  HackRF One or RTL-SDR v3 (SDR)

---
**This lab will grow from basic Wi-Fi attacks into BLE spoofing and SDR-based signal testing.**
