# 🏷️ whitetap demo app

This test web application is designed for a client to consolidate all his social links in one place like Linktree. Even though this is such a simple application, it has high potential. Once the coding is done, the client can then host it and write the URL to a MIFARE Classic NFC card. Then all his social links can be shared with just a tap on NFC-enabled devices.

---

## 🌟 Features

- **Save Contact**: Download the client's contact as a vCard (.vcf).
- **Share Contact**: Open WhatsApp with a prewritten message.
- **Direct Links**: Quick access to various social media profiles and contact options.

---

## 🛠️ Technologies Used

- **HTML**: Structure
- **CSS**: Styling
- **JavaScript**: Interactivity

---

## 📋 Usage

1. **Save Contact**: Click "Save Contact" to download vCard.
2. **Share Contact**: Click "Share Contact" to open WhatsApp.
3. **Social Media**: Click icons to open respective platforms.

---

## 🧩 Code Overview

### HTML

- Structured layout with profile card, contact buttons, and social media links.

### CSS

- Styled using external CSS (`styles.css`).

### JavaScript

- **`shareContact`**: Opens WhatsApp with a prewritten message.
- **`openURL`**: Handles URL redirection based on the protocol.
- **`generateVCard`**: Creates and downloads a vCard with contact info.

---

The finished version is now available for purchase at [www.thewhitetap.com](https://www.thewhitetap.com). You can also view a sample profile at [www.thewhitetap.com/profile/1](https://www.thewhitetap.com/profile/1).

---

<style>
    body {
        font-family: Arial, sans-serif;
        line-height: 1.6;
        background-color: #f4f4f9;
        color: #333;
    }
    h1 {
        color: #4CAF50;
        text-align: center;
    }
    h2 {
        color: #2196F3;
    }
    h3 {
        color: #FF5722;
    }
    a {
        color: #FF9800;
        text-decoration: none;
    }
    a:hover {
        text-decoration: underline;
    }
    ul, ol {
        padding-left: 20px;
    }
    li {
        margin-bottom: 10px;
    }
    code {
        background-color: #e0e0e0;
        padding: 2px 4px;
        border-radius: 4px;
    }
</style>
