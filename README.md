# nut-ups-power-notifications by Email and Telegram Bot
Simple script to notify you about power loss/restored by email and telegram using any generic usb UPS.

Remember to replace the placeholders ("your-email@example.com", "your-telegram-bot-token", and "your-telegram-chat-id") with your actual data. You can check your chat-id typing this url in your browser: https://api.telegram.org/botYOUR-TELEGRAM-API-BOT-TOKEN/getUpdates (change only YOUR-TELEGRAM-API-BOT-TOKEN where the word "bot" is required and without space with the telegram api key.

Also, be aware that /etc/msmtprc should contain your msmtp configuration (which should include your SMTP server and email details). Make sure the recipient email address specified in the script is configured to receive emails from the msmtp application.
