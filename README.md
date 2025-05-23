# esp8266-smart-fan-controller
🌬️ Control a 12V fan with an ESP8266 via hotspot, WebSocket UI, and rotary encoder. Speed, direction, and analytics — no internet needed!

# 🌬️ ESP8266 Smart Fan Controller

Control a 12V DC fan using an ESP8266, rotary encoder, and WebSocket-based web UI. This project allows you to control **fan speed**, **direction**, and **track usage analytics** — all through a clean mobile-friendly webpage hosted by the ESP8266 itself (no internet required).

## 🚀 Features

- ESP8266 in hotspot mode – access from your phone directly
- Control fan speed with a rotary encoder
- Reverse fan direction
- Web UI with real-time updates (WebSockets)
- Simple and responsive HTML/CSS/JS frontend
- Fully open-source 🔓

## 🧰 Components Required

| Component             | Quantity |
|----------------------|----------|
| ESP8266 (NodeMCU)     | 1        |
| L298N Motor Driver    | 1        |
| Rotary Encoder        | 1        |
| 12V DC Fan            | 1        |
| Jumper Wires          | A few    |
| Breadboard (optional) | 1        |
| 12V Power Supply      | 1        |

## 🔌 Wiring Diagram

![Wiring Diagram]([images/circuit-diagram.png](https://content.instructables.com/FFR/JSR2/MB0T9XX8/FFRJSR2MB0T9XX8.png?auto=webp&width=1600&height=900&fit=bounds&md=RnJpIE1heSAyMyAxMzowMDoyOCBQRFQgMjAyNQ==))

📥 Full instructions and photos on **Instructables**: [🔗 Click here](https://www.instructables.com/your-project-link)

## 🧠 How It Works

1. ESP8266 creates a Wi-Fi hotspot.
2. Rotary encoder adjusts PWM signal to L298N for fan speed control.
3. Web interface sends commands to ESP8266 via WebSocket.
4. You can reverse fan direction and track session duration.

## 🖥️ Web UI Preview

![Web UI Screenshot](images/ui-screenshot.png)

## 📂 Folder Structure

- `code/` – Arduino source code for ESP8266
- `web/` – Web UI files served to the browser
- `images/` – Circuit diagrams and screenshots

## 🧪 Getting Started

1. Install Arduino IDE
2. Add the ESP8266 board via Board Manager
3. Install necessary libraries (`ESPAsyncWebServer`, `AsyncTCP`)
4. Upload `esp8266_fan_controller.ino`
5. Connect to ESP8266 Wi-Fi → open browser → type `192.168.4.1`

## 💻 License

MIT License – feel free to use and modify this project.

## 🙌 Author

Made with ❤️ by [Your Name]

🔗 Also check out the **video tutorial** on YouTube: [Your YouTube link]

