# Visitor’s Notification and Smart Locking System 🔐📸

An IoT-based smart security system that notifies the user about visitors in real time and allows remote door lock/unlock using a Telegram Bot. The system uses an ESP32-CAM to capture visitor images and send them directly to the user’s mobile phone.

---

## 📌 Project Overview

In homes, hostels, and offices, users are often away and unable to respond immediately when someone visits. Traditional door locks do not provide remote access or visitor awareness.

This project solves that problem by:
- Capturing the visitor’s image
- Sending the image instantly via Telegram
- Allowing remote locking and unlocking of the door
- Displaying custom messages for visitors outside the room

---

## 🎯 Objectives

- Capture visitor images when a push button is pressed or when `/photo` command is sent  
- Send images to the user via Telegram Bot  
- Enable remote door locking and unlocking  
- Display custom messages on an external LCD  
- Build a low-cost and reliable IoT-based security system  

---

## 🛠️ Hardware Components

- ESP32-CAM  
- 12V Solenoid Lock  
- TIP122 Transistor  
- 7805 Voltage Regulator  
- Push Button  
- 1N4007 Diode  
- 16×2 LCD Display  
- 10kΩ Potentiometer  
- Resistors (1kΩ, 10kΩ)  
- 12V Power Supply  
- Jumper Wires and Breadboard / PCB  

---

## 💻 Software & Libraries Used

### Software
- Arduino IDE  
- Telegram App  

### Libraries
- WiFi.h  
- WiFiClientSecure.h  
- esp_camera.h  
- UniversalTelegramBot.h  
- ArduinoJson.h  
- soc/soc.h  
- soc/rtc_cntl_reg.h  

---

## ⚙️ Working Principle

1. A visitor presses the push button.  
2. ESP32-CAM captures the visitor’s image.  
3. The image is sent to the user via Telegram Bot.  
4. The user can send commands through Telegram:  
   - `/photo` – Capture image  
   - `/lock` – Lock the door  
   - `/unlock` – Unlock the door  
5. The solenoid lock is controlled using a transistor-based circuit.  
6. The LCD displays visitor messages such as user availability or return time.  

---

## 📂 Project Structure

## ✅ Results

- Visitor images are captured successfully  
- Images are sent in real time via Telegram  
- Door locking and unlocking works remotely  
- LCD displays user-defined messages  
- System operates reliably over Wi-Fi  

---

## 🏠 Applications

- Home Security Systems  
- Office Cabins  
- Hostels  
- Remote Monitoring Systems  
- Smart Room Automation  

---

## 🚀 Future Scope

- Face recognition-based automatic unlocking  
- Cloud storage for visitor images  
- Mobile application integration  
- Voice assistant support  

---

## 👨‍🎓 Project Team

- **Ganit Yadav** (23BAC10033)  
- **Abhinav Narayan** (23BAC10037)  
