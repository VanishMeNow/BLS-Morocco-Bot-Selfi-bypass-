
# 🎯 BLS Morocco Appointment Bot

<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&pause=1000&color=00C2FF&center=true&vCenter=true&width=900&lines=Smart+Automated+Visa+Booking+System;Fast+%7C+Accurate+%7C+Stealth+Automation;Python+%7C+Selenium+%7C+TeleBot;Real-Time+Appointment+Monitoring" />

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:007CF0,100:00DFD8&height=120&section=header&text=BLS%20Morocco%20Bot&fontSize=35&fontColor=ffffff&animation=fadeIn"/>

<br/>

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge)
![Selenium](https://img.shields.io/badge/Selenium-Automation-brightgreen?style=for-the-badge)
![TeleBot](https://img.shields.io/badge/Telegram-Bot-blueviolet?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-BLS%20Morocco-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Stable-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-Educational-yellow?style=for-the-badge)
## 🧠 Overview

**BLS Morocco Appointment Bot** is an intelligent automation system for monitoring and booking visa appointments automatically.

Built with **Python**, **Selenium**, and **TeleBot** to provide:

- Real-time slot detection
- Instant booking execution
- Telegram notifications
- Human-like browser automation

---

# 📸 Booking Process Visualization 

## 1️⃣ Login Stage

```mermaid
flowchart LR
A[Open BLS Website] --> B[Enter Email]
B --> C[Enter Password]
C --> D[Login Success]
```

---

## 2️⃣ Slot Scanning

```mermaid
flowchart TD
A[Calendar Load] --> B[Scan Dates]
B --> C{Slot Found?}
C -->|No| D[Refresh & Retry]
C -->|Yes| E[Select Slot]
```

---

## 3️⃣ Auto Booking

```mermaid
flowchart TD
A[Fill Appointment Form] --> B[Confirm Data]
B --> C[Submit Booking]
C --> D[Reservation Success]
```

---

## 4️⃣ Telegram Notification

```mermaid
flowchart LR
A[Booking Completed] --> B[Generate Alert]
B --> C[Send Telegram Message]
C --> D[User Receives Confirmation]
```

---

## ⚙️ Key Features

✅ Real-Time Slot Monitoring  
✅ Auto Booking Logic  
✅ Smart Retry System  
✅ Telegram Notifications  
✅ Human Behavior Simulation  
✅ Anti-Detection Delays  
✅ Session Persistence  
✅ Fast Execution Engine  

---

## 🏗 System Architecture

```mermaid
graph TD
A[Selenium Engine] --> B[Slot Scanner]
A --> C[Form Automation]
B --> D[Booking Core]
C --> D
D --> E[TeleBot Alerts]
D --> F[Logger]
D --> G[Session Manager]
```

---

## 🔍 Full Workflow

```mermaid
sequenceDiagram
participant User
participant Bot
participant BLS
participant Telegram

User->>Bot: Start Bot
Bot->>BLS: Login
Bot->>BLS: Scan Calendar
BLS-->>Bot: Available Slot
Bot->>BLS: Book Slot
Bot->>Telegram: Send Confirmation
Telegram-->>User: Appointment Booked
```

---

## 💻 Quick Setup

```bash
git clone https://github.com/OnlineUnknowns/BLS_Morocco_Appointment_Bot.git

cd BLS_Morocco_Appointment_Bot

pip install -r requirements.txt

python Appointment_Bot.py
```

---

## 🔧 Configuration

Edit:

```python
BOT_TOKEN = "YOUR_TELEGRAM_BOT_TOKEN"
EMAIL = "YOUR_BLS_EMAIL"
PASSWORD = "YOUR_BLS_PASSWORD"
```

---

## 🛠 Tech Stack

| Technology | Purpose |
|---|---|
| Python | Core Programming |
| Selenium | Browser Automation |
| TeleBot | Notifications |
| Requests | HTTP Handling |
| Logging | Debugging |
| Undetected ChromeDriver | Anti Detection |

---

## 📊 Live Status

```diff
+ Bot Running
+ Monitoring Slots
+ Waiting for Availability
+ Ready to Book
```

---

## 📘 Disclaimer

This project is for educational and research purposes only.

Use responsibly and respect official BLS platform rules.

---

<div align="center">

## ⭐ Star the Repository if you like it

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00DFD8,100:007CF0&height=100&section=footer"/>

</div>
--

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge)
![Selenium](https://img.shields.io/badge/Selenium-Automation-brightgreen?style=for-the-badge)
![TeleBot](https://img.shields.io/badge/Telegram-Bot-blueviolet?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-BLS%20Algeria-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Stable-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-Educational-yellow?style=for-the-badge)

---

## 🧠 Overview  
**BLS Morocco Appointment Bot** is an intelligent automation tool designed to book **visa appointments** on the official **BLS Algeria** website automatically.  

Using **Selenium WebDriver** and **Telegram API (TeleBot)**, the system simulates human behavior to:  
- Detect available appointment slots in real time  
- Reserve them instantly  
- Send confirmation and alerts via Telegram  

This project was created for **educational and research purposes only**, to demonstrate how browser automation works responsibly with dynamic and secure systems.

---

## ⚙️ Key Features  
- 🕒 **Real-Time Slot Monitoring** – Continuously checks BLS Morocco for open appointments.  
- 🤖 **Auto Booking Logic** – Handles login, calendar navigation, and form submission automatically.  
- 💬 **Telegram Notifications** – Instantly informs you when a slot is found or booked.  
- 🔐 **Human-Like Behavior** – Randomized delays and interaction patterns to avoid detection.  
- ⚡ **Fast & Reliable** – Built for stability even under high server load.  

---

## 🏗️ System Architecture

+-------------------------------------------------------+ |               BLS Morocco Appointment Bot             | +-------------------------------------------------------+ |  Selenium Engine |  TeleBot Integration |  Core Logic | +-------------------------------------------------------+ |  Slot Scanner    |  Form Filler         |  Scheduler  | +-------------------------------------------------------+ |  Telegram Alerts |  Session Manager     |  Logger     | +-------------------------------------------------------+

Each module works independently — ensuring the system remains modular, stable, and easy to maintain.

---

## 🔍 Workflow  
1. **Login Phase** – The bot logs into your BLS Morocco account.  
2. **Scan Phase** – It monitors for available appointment slots.  
3. **Detection Phase** – When a slot is found, the bot instantly reserves it.  
4. **Notification Phase** – A Telegram message confirms the booked slot.  

---

## 💻 Quick Setup  
1. Clone the repository:  
   ```bash
   git clone https://github.com/OnlineUnknowns/BLS_Morocco_Appointment_Bot.git
   cd BLS_Morocco_Appointment_Bot

2. Edit config.py or Appointment_Bot.py to set:

Your Telegram BOT_TOKEN

Your BLS credentials

Path to your WebDriver (.exe)



3. Run the bot:

python Appointment_Bot.py




---

🧠 Tech Stack

Language: Python 3.10+

Automation: Selenium WebDriver

Notifications: TeleBot (Telegram Bot API)

Scheduler: Custom event-driven loop

Logging: Built-in Python logger

Platform: BLS Algeria



---

📘 Disclaimer

This project is for educational and non-profit use only.
I am not responsible for misuse, abuse, or violations of BLS systems.

> ⚠️ Use responsibly — respect visa systems and official rules.




---

🧩 Learn More

Detailed tutorial (English):
🔗 Booking a Visa Appointment using Selenium & TeleBot


---

💰 Purchase the Private Version

Want the advanced private build with:
✅ Auto Calendar Navigation
✅ Anti-Captcha & Anti-Block
✅ 24/7 Background Monitoring
✅ Multi-Account Support

👉 Buy Now on WhatsApp


---

🧑‍💻 Developer

Crafted with ❤️ by a passionate automation developer.
For private projects, collaborations, or inquiries:
📞 wa.me/+201286669272


---

⭐ If this project inspires you, don’t forget to star the repo!
