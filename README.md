# QR Productions — manufacturing prototype

Password-protected, interactive prototype of a manufacturing system on Odoo 18.

`index.html` contains the prototype **encrypted** (AES-256-GCM, key derived from each account's password with PBKDF2-SHA256, 600,000 iterations). It is decrypted in the browser after sign-in; nothing is sent to a server. Accounts are issued privately.
