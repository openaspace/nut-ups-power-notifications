# UPS Power Notifications by Email and Telegram Bot Using NUT Server with System PowerOff

This simple script sends notifications about power loss/restoration via email and Telegram, utilizing any generic USB UPS with the NUT server: https://networkupstools.org/

Before using this script, ensure that the NUT server is properly configured and correctly recognizes your USB or network UPS.

Remember to replace the placeholders ("your-email@example.com", "your-telegram-bot-token", and "your-telegram-chat-id") with your actual data. You can verify your chat ID by typing this URL into your browser: https://api.telegram.org/botYOUR-TELEGRAM-API-BOT-TOKEN/getUpdates. Replace only YOUR-TELEGRAM-API-BOT-TOKEN in the URL, ensuring the word "bot" is included (with no spaces) along with your Telegram API key.

Note that /etc/msmtprc should contain your msmtp configuration, which should include details of your SMTP server and email. Ensure the recipient email address specified in the script is configured to receive emails from the msmtp application.

This script has been tested on Debian 12 with Proxmox.


# Disclaimer of Liability

This repository is provided "as-is". The author(s) disclaim any liability for any direct, indirect, incidental, consequential, special, exemplary, punitive, or other damages whatsoever, or for any damages for loss of profits, interruption, loss of business information, or loss of data, arising out of or in connection with the use or inability to use this repository, even if the author(s) has been advised of the possibility of such damages. 

The author(s) make no warranties, express, implied or statutory, as to any matter whatsoever. In no event shall the author(s) be liable for any indirect, incidental, special, punitive or consequential damages, or damages for loss of profits, revenue, data or use, incurred by you or any third party, whether in an action in contract or tort, arising from your access to, or use of, this repository.

The usage of this repository indicates your agreement with this disclaimer. 

Use at your own risk.
