# 🚫 Attack-Defender 🔒

**Purpose**:  
Prevents HID (Human Interface Device) attacks or keystroke injection attacks performed by pre-programmed physical thumb drives (e.g., **Rubber Ducky**). 🦆💻

---

## 💡 How it Works

- The software detects and blocks the **Rubber Ducky** before any severe damage occurs to the system. 🚫🔌
- Once the attack is detected, an **email alert** is sent to the administrator with the **log file**. 📧📄
- The log file contains the registered keystrokes of the Rubber Ducky for monitoring. ⌨️🔍
- The blocked keyboard can be unblocked by pressing a specific combination of hotkeys:  
  **'Esc + E + M'**. ⏯️

---

## 🛠️ Instructions

1. **Email Configuration**:  
    - Open the `mailto.py` file and change the sender's email address to your organization's email ID. 📧  
    - Ensure that the email ID used in the source code has third-party access enabled and multi-factor authentication **disabled**. 🔑🚫
    - In the `detect_keys.py` file, change the administrator's email address. Replace `'admin@axample.com'` with the actual email ID of the administrator. 👤

2. **Customizing Hotkeys**:  
    - If you wish to change the hotkeys used to unblock the keyboard, you can modify the corresponding section in the source code. 🔄  
    - By default, the hotkey combination is: **'Esc + E + M'**. 🖱️

---

## 🔓 How to Unblock the Keyboard

- To unblock the keyboard after it has been disabled, **press and hold** the specified hotkey combination for a few seconds. ⏳🔑

---

## ⚠️ Notes

- Ensure that the email configuration is properly set up to receive alerts. 📧✅
- The system blocks the input from the Rubber Ducky device. Be sure to have an alternative way to interact with the system or use the hotkey combination to regain control. 🖥️
- This software is specifically designed to prevent attacks before any damage is done, making it an effective solution against Rubber Ducky-based payloads. 🛡️

---
