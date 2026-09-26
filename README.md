# Presence_Light_Sensor

A wire-free, ultra-compact presence and ambient light sensor carrier board built for smart home automation. The design utilizes a double-sided "sandwich" arrangement 
to keep the overall physical dimensions as small as possible while eliminating point-to-point jumper wires.

The front face houses optical and millimeter-wave (mmWave) sensors facing into the room, while the back houses the ESP32-C3 SuperMini controller board and power delivery.

---

## 🔧 Components

| Component | Stack | Repo |
|---|---|---|---|
| 🧠 **OS** | Home Assistant OS | HAOS | [PLS-ESPHome](https://github.com/dangnguyen06-ee/willbeupdated) |
| 🔌 **Firmware** | ESP32-C3, C++ | [PLS-firmware](https://github.com/dangnguyen06-ee/Presence_Light_Sensor_Firmware) |
| ⚡ **PCB** | KiCad | [PLS-pcb](https://github.com/YOUR_USERNAME/Presence_Light_Sensor_PCB) |
| 🧊 **3D Model** | Fusion 360, STL | [PLS-3d](https://github.com/YOUR_USERNAME/Presence_Light_Sensor_3D) |

---

## ✨ Features

- Multi-Target 24GHz mmWave Presence Detection: Integrated Hi-Link HLK-LD2450 module tracks position X, Y, speed, and micro-motion to track presence with zone mapping. 
- Precision Light Sensing: Onboard VEML7700 digital ambient light sensor.
- Zero Jumper Wires: Custom 2-layer carrier PCB bridges all sensor power and communication signals through clean, routed traces.
- Transient Voltage Stabilization: Integrated 10uF SMD capacitor near the LD2450 power pins buffers peak current surges.
- Seamless Home Assistant Integration: Natively supported in ESPHome out of the box.

---

## 🧱 Hardware

| Part | Model |
|---|---|
| MCU | ESP32-C3 |
| Mmwave Sensor | HLK-LD2450 |
| Light Sensor | VEML7700 |
| IMU | MPU6050 |

---

## 📜 License

MIT — see individual repos for details.
