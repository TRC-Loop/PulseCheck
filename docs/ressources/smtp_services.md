# Email Services and Their SMTP Domains

This table provides an overview of popular email services and their SMTP servers. It is especially helpful for configuring email clients or troubleshooting email sending issues.

## Services and SMTP Domains

| **Service**        | **SMTP Domain**                | **Port** | **Encryption** | **Additional Notes**                                                                 |
|--------------------|--------------------------------|----------|-----------------|---------------------------------------------------------------------------------------|
| [Gmail](https://support.google.com/a/answer/176600?hl=en)           | smtp.gmail.com                 | 465 / 587 | SSL / TLS       | App password required. ([support.google.com](https://support.google.com/a/answer/176600?hl=en)) |
| [Outlook.com](https://support.microsoft.com/en-us/office/pop-imap-and-smtp-settings-for-outlook-com-d088b986-291d-42b8-9564-9c414e2aa040) | smtp-mail.outlook.com          | 587      | STARTTLS        | IMAP/POP must be enabled in the settings. ([support.microsoft.com](https://support.microsoft.com/en-us/office/pop-imap-and-smtp-settings-for-outlook-com-d088b986-291d-42b8-9564-9c414e2aa040)) |
| [Yahoo Mail](https://help.yahoo.com/kb/pop-access-settings-instructions-yahoo-mail-sln4724.html) | smtp.mail.yahoo.com            | 465 / 587 | SSL / TLS       | SSL/TLS required. ([help.yahoo.com](https://help.yahoo.com/kb/pop-access-settings-instructions-yahoo-mail-sln4724.html)) |
| [AOL Mail](https://help.aol.com/articles/how-do-i-use-other-email-applications-to-send-and-receive-my-aol-mail) | smtp.aol.com                   | 465      | SSL             | SSL required. ([help.aol.com](https://help.aol.com/articles/how-do-i-use-other-email-applications-to-send-and-receive-my-aol-mail)) |
| [Zoho Mail](https://www.zoho.com/mail/help/zoho-smtp.html)           | smtp.zoho.com                  | 465 / 587 | SSL / TLS       | SSL/TLS required. ([zoho.com](https://www.zoho.com/mail/help/zoho-smtp.html)) |
| [ProtonMail](https://proton.me/support/smtp-submission)              | smtp.protonmail.com            | 465      | SSL             | SMTP token required. ([proton.me](https://proton.me/support/smtp-submission)) |
| [iCloud Mail](https://support.apple.com/en-us/102525)                | smtp.mail.me.com               | 587      | STARTTLS        | App-specific password required. ([support.apple.com](https://support.apple.com/en-us/102525)) |
| [Mailgun](https://documentation.mailgun.com/docs/mailgun/user-manual/smtp-protocol/) | smtp.mailgun.org               | 587      | STARTTLS        | SMTP username and password required. ([documentation.mailgun.com](https://documentation.mailgun.com/docs/mailgun/user-manual/smtp-protocol/)) |
| [SendGrid](https://www.twilio.com/docs/sendgrid/for-developers/sending-email/integrating-with-the-smtp-api) | smtp.sendgrid.net              | 587      | STARTTLS        | API key required. ([twilio.com](https://www.twilio.com/docs/sendgrid/for-developers/sending-email/integrating-with-the-smtp-api)) |
| [FastMail](https://www.fastmail.help/hc/en-us/articles/1500000279921-IMAP-POP-and-SMTP) | smtp.fastmail.com              | 465 / 587 | SSL / TLS       | SSL/TLS required. ([fastmail.help](https://www.fastmail.help/hc/en-us/articles/1500000279921-IMAP-POP-and-SMTP)) |
| [GMX Mail](https://serversmtp.com/smtp-gmx/)                         | mail.gmx.com                   | 465 / 587 | SSL / TLS       | SSL/TLS required. ([serversmtp.com](https://serversmtp.com/smtp-gmx/)) |
| [Yandex Mail](https://yandex.com/support/mail/mail-clients/others.html) | smtp.yandex.com                | 465 / 587 | SSL / TLS       | SSL/TLS required. ([yandex.com](https://yandex.com/support/mail/mail-clients/others.html)) |
| [Office 365](https://learn.microsoft.com/en-us/exchange/mail-flow-best-practices/how-to-set-up-a-multifunction-device-or-application-to-send-email-using-microsoft-365-or-office-365) | smtp.office365.com             | 587      | STARTTLS        | Authentication required. ([learn.microsoft.com](https://learn.microsoft.com/en-us/exchange/mail-flow-best-practices/how-to-set-up-a-multifunction-device-or-application-to-send-email-using-microsoft-365-or-office-365)) |
| [Strato Mail](https://www.strato-hosting.co.uk/faq/product/the-strato-email-server/) | smtp.strato.de                 | 465      | SSL / TLS       | SSL/TLS required. ([strato-hosting.co.uk](https://www.strato-hosting.co.uk/faq/product/the-strato-email-server/)) |
| [Tutanota](https://www.reddit.com/r/tutanota/comments/12chg0m/imap_and_smtp_settings_of_an_account_tutanota/) | No SMTP support               | -        | -               | Web client only. ([reddit.com](https://www.reddit.com/r/tutanota/comments/12chg0m/imap_and_smtp_settings_of_an_account_tutanota/)) |
| [Rackspace Email](https://learn.microsoft.com/en-us/exchange/mail-flow-best-practices/how-to-set-up-a-multifunction-device-or-application-to-send-email-using-microsoft-365-or-office-365) | secure.emailsrvr.com           | 465 / 587 | SSL / TLS       | Authentication required. ([learn.microsoft.com](https://learn.microsoft.com/en-us/exchange/mail-flow-best-practices/how-to-set-up-a-multifunction-device-or-application-to-send-email-using-microsoft-365-or-office-365)) |
| [Bluehost Mail](https://www.bluehost.com/help/article/email-application-setup) | mail.smtp.bluehost.com         | 465 / 587 | SSL / TLS       | Authentication required. |
| [HostGator Mail](https://www.hostgator.com/help/article/email-connection-settings) | mail.hostgator.com             | 465 / 587 | SSL / TLS       | Authentication required. |

## Important Notes
- **Authentication**: Most email services require authentication to send emails. Make sure you use your full email address (e.g., `name@domain.com`) and corresponding password.
- **Encryption**: Always use SSL/TLS encryption when available to secure your email transmission.
- **Port Numbers**:
  - Port 465: Commonly used for SSL connections.
  - Port 587: Commonly used for TLS connections.
- **Tutanota**: Tutanota does not support SMTP. You must use their web client or mobile app for email access.
- **App Passwords**: Some services, like Gmail and iCloud, require app-specific passwords for authentication in email clients.

## Further Resources
- [Gmail Help Center](https://support.google.com/a/answer/176600?hl=en)
- [Outlook.com Settings](https://support.microsoft.com/en-us/office/pop-imap-and-smtp-settings-for-outlook-com-d088b986-291d-42b8-9564-9c414e2aa040)
- [Yahoo Mail Help](https://help.yahoo.com/kb/pop-access-settings-instructions-yahoo-mail-sln4724.html)
- [Zoho Mail Help](https://www.zoho.com/mail/help/zoho-smtp.html)
- [ProtonMail Support](https://proton.me/support/smtp-submission)
- [Mailgun Documentation](https://documentation.mailgun.com/docs/mailgun/user-manual/smtp-protocol/)
- [SendGrid Documentation](https://www.twilio.com/docs/sendgrid/for-developers/sending-email/integrating-with-the-smtp-api)
- [FastMail Help](https://www.fastmail.help/hc/en-us/articles/1500000279921-IMAP-POP-and-SMTP)
