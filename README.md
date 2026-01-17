# ESP32 Drone Control Board (KiCad)

Custom ESP32-based drone control PCB designed in KiCad.
This board is made for embedded drone/robotics applications with onboard power + sensor + control headers.

---

## 🔥 Key Features
- ESP32 microcontroller (WiFi/Bluetooth)
- USB-C power input
- LiPo charging circuit
- 3.3V power regulation
- IMU sensor interface (example: MPU6050)
- Motor/servo output headers
- Debug / programming interface
- Status LEDs

---

## 🧠 What I worked on
✅ Schematic design  
✅ PCB layout and routing  
✅ Power section design (USB + battery + regulation)  
✅ Sensor + interface planning  
✅ Connectivity + headers for expansion

---

## 📷 PCB Preview
![PCB Layout](docs/images/pcb-layout.png)

## 📄 Schematic Preview
![Schematic](docs/images/schematic.png)

---

## 📂 Repository Structure
- `hardware/kicad/` → KiCad project files
- `docs/images/` → PCB + schematic images
- `fabrication/` → Gerbers/BOM (optional)
- `firmware/` → Flight firmware (future update)

---

## 🛠 Tools Used
- KiCad
- ESP32 ecosystem

---

## 🚀 Future Improvements
- Add barometer (BMP/BME)
- Add better power filtering
- Add ESC signal conditioning
- Add full ArduPilot / custom firmware integration

