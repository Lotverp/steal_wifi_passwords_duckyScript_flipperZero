# 🦆 8-Second Smart WiFi Password Stealer

This project contains a DuckyScript compatible with all Ducky USB and Flipper Zero devices.  
Follow the instructions below to set up and use the script effectively.

> ⭐ Don't forget to star the project so I can see it's helpful!

---

## 📋 How the Program Works

This DuckyScript is designed to retrieve WiFi passwords saved on a target PC within 8 seconds. Here's how it works:

1. Start: Plug in the USB device or activate the script from your Flipper Zero.  
2. Minimized CMD: The command prompt will run in minimized mode to avoid detection.  
3. Collect Data: The script retrieves all saved SSIDs and passwords.  
4. Send to Webhook: Data is sent to a private webhook server in JSON format.  
5. Exit Cleanly: The script closes CMD and leaves no trace of activity.

> 💡 Important Note: The script needs only 8 seconds to execute, making it quick and discreet.

---

## 🚀 Quick Setup Guide

### 1. Get Your Webhook Link
- Go to [webhook.site](https://webhook.site/) and create a free account.
- Copy your unique webhook URL.

### 2. Configure the Script
- Download or copy the duckyScript.txt file from this repository.
- Search `https://webhook.site/<YOUR_WEBHOOK_LINK_CODE_HERE>` 
- Replace all with your own link `https://webhook.site/xxxxxxxxxxxxxxxxxx`
- Remember to save it

### 3. Load the Script
- Ducky USB: Copy the duckyScript.txt file to your USB device. Simply plug it into the target PC to execute.  
- Flipper Zero: Copy the duckyScript.txt file to the Bad USB directory in the system files. Run the script from the Flipper Zero interface.

### 4. View Results
- Open your webhook link at [webhook.site](https://webhook.site/).
- You'll see new data with the target PC's SSIDs and passwords in JSON format.

---

## 💻 Compatibility

- Windows 10: Fully supported.  
- Windows 11: Not tested (but should work).

---

## ⚠️ Important Disclaimer

> This project is intended for educational purposes only.  
> Misuse of this script for illegal activities is strictly prohibited.  

## ❌ Responsibility
>The author and collaborators assumes no responsibility for any damage caused by improper use.
---

## 📞 Contact

If you encounter any problems or have questions, feel free to reach out. 💬  
