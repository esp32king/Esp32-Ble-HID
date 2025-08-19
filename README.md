# 🚀 ESP32-BLE-HID

Turn your ESP32 into a Bluetooth Low Energy Human Interface Device (BLE HID).
Flash the provided .bin file from <a href="https://github.com/esp32king/Esp32-Ble-HID/releases/tag/Esp32-BLE-HID">Releases"</a> directly And Flash it here 👉 <a href="https://esptool.spacehuhn.com">esptool.spacehuhn.com</a> — no need to compile!

---

# 📱 Controll by Android
<img src="https://raw.githubusercontent.com/esp32king/Esp32-Ble-HID/refs/heads/main/Files/Ss.jpg"></img>

---

# ✨ Features

This project allows your ESP32 to act as a remote HID controller for Windows, macOS, and Android.
You can send various commands via Serial Monitor or the GUI Monitor App.


---


## 💻 Available Serial Commands

Use these commands via the Serial Monitor or GUI Monitor App:

| Command | Action |
|--------|--------|
| `notepad` | Open Notepad |
| `youtube <search>` | Search & open YouTube |
| `google <search>` | Search & open Google |
| `whatsapp <no> <msg>` | Send WhatsApp message |
| `wp-ss <no>` | Send screenshot via WhatsApp |
| `cmd` | Open Command Prompt |
| `shutdown` | Shutdown PC in 5 seconds |
| `run` | Open Run dialog (Win + R) |
| `url <command>` | Execute command in Run box |
| `lock` | Lock the PC |
| `close` | Close current app |
| `ENTER` | Press Enter key |
| `screenshot` | Take a screenshot |
| `CTRL+<key>` | Press CTRL with a key (e.g., `CTRL+A`) |
| `WIN`, `LEFT`, `RIGHT`, `UP`, `DOWN` | Arrow or Win keys |
| `WiFi` | Dump saved Wi-Fi passwords |
| `Fake` | Show fake system update |
| `Spam` | Display spam alert box |
| `help` | Show all commands |
| `About` | Show creator info |



---

# 🔥 Flashing the .bin File

No need for Arduino IDE! You can flash directly from your browser:

1. Download the .bin file from the Releases section.


2. Open 👉 <a href="https://esptool.spacehuhn.com">esptool.spacehuhn.com</a>.


3. Connect your ESP32 via USB.


4. Click Connect → select your ESP32 COM port.


5. Choose the .bin file and click Program.


6. Wait until flashing completes ✅.


7. <a href="https://github.com/esp32king/Esp32-Ble-HID/releases/download/Esp32-BLE-HID/bootloader.bin">bootloader.bin</a> → 0x1000

 8. <a href="https://github.com/esp32king/Esp32-Ble-HID/releases/download/Esp32-BLE-HID/partitions.bin">partitions.bin</a> → 0x8000

 9. <a href="https://github.com/esp32king/Esp32-Ble-HID/releases/download/Esp32-BLE-HID/ESP32-BLE-HID.bin">ESP32-BLE-HID.bin</a> → 0x10000

---

# 🛠 Usage

1. Connect ESP32 via USB and open Serial Monitor (115200 baud). You Can Use Android App <a href="https://play.google.com/store/apps/details?id=com.bluino.esp32loader">Esp32 Loader </a> or any serial monitor App.


2. Type `help` and hit Enter to see All Commands.


3. The ESP32 will execute the corresponding HID action on the connected PC.




---

# 🤝 Contribution

Want to improve this project? PRs are welcome!

Add more commands 🆕

Improve documentation 📖

Share new use-cases 💡



---

# 📜 License

This project is open-source under the MIT License.


---

# 👨‍💻 Author

Created By Krishna Rajput UP61


---


