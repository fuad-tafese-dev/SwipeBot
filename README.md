🚀 Tinder Auto-Liker Bot
📌 Overview
This bot uses Selenium with undetected-chromedriver to log into Tinder via Facebook and automatically click the Like button on profiles.
It’s mainly for educational purposes to demonstrate browser automation.

⚠ Disclaimer:

Using bots on Tinder can get your account banned.

This code is for learning purposes only. Use at your own risk.

🔧 Features
Logs into Tinder using Facebook credentials

Handles popups for location, notifications, and cookies

Auto-likes up to 100 profiles

Closes any match popups before continuing

📋 Requirements
Install dependencies:

bash
Copy
Edit
pip install selenium undetected-chromedriver
You’ll also need:

Google Chrome browser installed

Facebook account linked to your Tinder account

⚙️ Setup
Clone or download the script.

Open the .py file.

Replace the placeholders with your login info:

python
Copy
Edit
FB_EMAIL = "your_facebook_email_here"
FB_PASSWORD = "your_facebook_password_here"
▶️ How to Run
Run the script in your terminal:

bash
Copy
Edit
python tinder_bot.py
The bot will:

Open Tinder in Chrome

Click “Log in” → “Login with Facebook”

Enter your credentials in the Facebook popup

Allow location, dismiss notifications, accept cookies

Start clicking “Like” up to 100 times

🛠 Troubleshooting
Selectors not found: Tinder often changes HTML, update the XPaths in the script.

Facebook login issues: Make sure you have no extra security steps like OTP enabled.

Detected as a bot: Try adding random delays (sleep()) or human-like mouse movements.
