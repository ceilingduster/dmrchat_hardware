# Handheld Smart Microphone for DMR818S & DMR818S-5W

![Mockup of handheld microphone](mockup.png)

This project is an open hardware design for a **handheld smart microphone** built around the **DMR818S radio module** and **ESP32-S3**. It features a user-friendly form factor modeled after traditional handheld microphones, with modern enhancements including a color display, onboard speaker and mic, rotary encoders, and USB-C connectivity.  Yes, it is essentially a DMR Transceiver but as it contains a ESP32 MCU, it will provide wireless and bluetooth connectivity to mobile devices for programming, and operation.  Specifically, it will provide a bluetooth connected device with the ability to send and receive DMR SMS messages.

---

## 🔧 Features

- 📡 **DMR818S radio module** (5W TX)
- 🧠 **ESP32-S3** MCU running LVGL + MicroPython
- 🎛️ Three rotary encoders with push buttons (Channel, Volume/Mute, Squelch)
- 🔊 Onboard I2S speaker amplifier + electret microphone
- 🎧 3.5mm TRRS headset jack (auto-switch)
- 🖥️ 2.4” ILI9341 SPI TFT display
- 🔋 5000mAh Li-ion battery with:
  - IP5306 charge + boost circuit
  - MAX17048 fuel gauge and battery protection
- 🔌 USB-C for charging and firmware upload
- 📶 SMA antenna connector on top
- 🚨 TX/RX LEDs, classic PTT side button

---

## 📄 Schematic

See [`Handheld_Mic_Schematic.pdf`](Handheld_Mic_Schematic.pdf) for the full annotated schematic.

---

## 📷 Mockup

The physical form factor is designed to mimic classic handheld microphones, with:
- **Right-side PTT button** for thumb operation
- **Top-mounted SMA** and speaker grille
- **Side-mounted rotary encoder wheels**
- **USB-C and headset jack on the bottom**

Image reference: [`mockup.png`](mockup.png)

---

## ⚖️ License

This project is licensed under the **CERN Open Hardware License v2 - Strongly Reciprocal (CERN-OHL-S)**.

You may freely use, modify, and share the design for **non-commercial amateur radio purposes**.  
Modifications and derived works must be shared under the same license.

See [LICENSE](https://ohwr.org/cern_ohl_s_v2.txt) for full terms.

---

## 🚀 Status

- ✅ Schematic complete
- ⏳ PCB layout (in progress)
- ⏳ Firmware scaffold (coming soon)

---

## 🤝 Contributing

Pull requests and community feedback are welcome! Please ensure any contributions follow the license terms.

---

# NICERF

See [DMR818S-5W Page](https://www.nicerf.com/walkie-talkie-module/dmr818S-5w.html) for more information on the main module used in this project.
