# Ups power notifications by Email and Telegram Bot using NUT server

Simple script to notify you about power loss/restored by email and telegram using any generic usb UPS with NUT server: https://networkupstools.org/ 

Remember to replace the placeholders ("your-email@example.com", "your-telegram-bot-token", and "your-telegram-chat-id") with your actual data. You can check your chat-id typing this url in your browser: https://api.telegram.org/botYOUR-TELEGRAM-API-BOT-TOKEN/getUpdates (change only YOUR-TELEGRAM-API-BOT-TOKEN where the word "bot" is required and without space with the telegram api key.

Also, be aware that /etc/msmtprc should contain your msmtp configuration (which should include your SMTP server and email details). Make sure the recipient email address specified in the script is configured to receive emails from the msmtp application.

Tested on Ddebian 12 with Proxmox.


# Disclaimer of Liability

This repository is provided "as-is". The author(s) disclaim any liability for any direct, indirect, incidental, consequential, special, exemplary, punitive, or other damages whatsoever, or for any damages for loss of profits, interruption, loss of business information, or loss of data, arising out of or in connection with the use or inability to use this repository, even if the author(s) has been advised of the possibility of such damages. 

The author(s) make no warranties, express, implied or statutory, as to any matter whatsoever. In no event shall the author(s) be liable for any indirect, incidental, special, punitive or consequential damages, or damages for loss of profits, revenue, data or use, incurred by you or any third party, whether in an action in contract or tort, arising from your access to, or use of, this repository.

The usage of this repository indicates your agreement with this disclaimer. 

Use at your own risk.
