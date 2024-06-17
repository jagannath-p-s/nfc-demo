# whitetap demo app

This test web application is designed for a client to consolidate all his social links in one place like linktree . Even though this is such a simple application it have high ptential , once the coding is done the client then host it and write the url to a mifare classic NFC card , then all his social links can be shared with just a tap on the nfc enabled devices 

## Features

- **Save Contact**: Download the client's contact as a vCard (.vcf).
- **Share Contact**: Open WhatsApp with a prewritten message.
- **Direct Links**: Quick access to various social media profiles and contact options.

## Technologies Used

- **HTML**: Structure
- **CSS**: Styling
- **JavaScript**: Interactivity

## Usage

1. **Save Contact**: Click "Save Contact" to download vCard.
2. **Share Contact**: Click "Share Contact" to open WhatsApp.
3. **Social Media**: Click icons to open respective platforms.


## Code Overview

### HTML

- Structured layout with profile card, contact buttons, and social media links.

### CSS

- Styled using external CSS (`styles.css`).

### JavaScript

- **`shareContact`**: Opens WhatsApp with a prewritten message.
- **`openURL`**: Handles URL redirection based on the protocol.
- **`generateVCard`**: Creates and downloads a vCard with contact info.

