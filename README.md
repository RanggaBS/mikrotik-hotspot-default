# MikroTik Hotspot Default Page

This repository contains the default hotspot web page files provided by MikroTik RouterOS.  
These files are typically used when hosting a local captive portal for MikroTik Hotspot.

No modifications were made to these files.  
They are uploaded as-is for backup, reference, or deployment purposes.

## 📁 Directory Structure

```plaintext
hotspot/
├── css/
│   └── style.css
├── img/
│   ├── password.svg
│   └── user.svg
├── xml/
│   ├── alogin.html
│   ├── error.html
│   ├── flogout.html
│   ├── login.html
│   ├── logout.html
│   ├── rlogin.html
│   └── WISPAccessGatewayParam.xsd
├── alogin.html
├── error.html
├── login.html
├── logout.html
├── radvert.html
├── redirect.html
├── rlogin.html
├── status.html
├── favicon.ico
├── md5.js
└── errors.txt
```

> 📦 Note: File list may vary depending on RouterOS version or export method.

## 🛠️ How to Use

1. Copy the `hotspot/` folder to your MikroTik router via FTP or Winbox.
2. Upload the files to:  
   `Files > hotspot`
3. Enable the Hotspot service on your MikroTik router.

## ⚖️ License

This repository is provided **as-is** without any license, since the files are originally from MikroTik and not authored by me.

> ⚠️ Redistribution or commercial use may be subject to MikroTik's terms.
