# 🎂 WhatsApp Birthday Automation using n8n

This n8n workflow automates birthday greetings via WhatsApp!  
It checks a list of contacts daily and sends personalized birthday wishes.

## 💡 Features
- Hardcoded birthday list using a Code node (JSON format)
- Matches today's date with contact birthdays
- Sends WhatsApp messages using HTTP node (e.g., Twilio or WhatsApp Cloud API)

## ⚙️ How It Works
1. **Code Node**: Contains contact list with name, DOB (`MM-DD`), and phone.
2. **Filter Node**: Compares today's date with the `dob`.
3. **HTTP Node**: Sends WhatsApp message using formatted data.

## 📸 Workflow Screenshot
![Workflow Screenshot](C:\Users\dhana\OneDrive\Pictures\Screenshots\Screenshot 2025-05-15 224233.png)

## 🛠️ To Use
1. Import the `.json` workflow in your n8n instance.
2. Configure the HTTP node with your WhatsApp API (Twilio, etc.).
3. Run or schedule it daily.

---

Feel free to customize the birthday list and message style!

