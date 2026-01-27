# Emoji Crypt Tool

A zero-width steganography tool to hide secret messages inside emoji sequences.  
Optional AES encryption adds an extra layer of security.

## Features

- Hide messages inside emojis using invisible Unicode characters:
- Optional AES-256 encryption for extra security
- Copy encoded/decoded messages to clipboard
- Modern cyberpunk UI for an awesome user experience

## How to Use


### 1. Hiding a Secret Message

1. Open the tool.
2. Enter a sequence of **cover emojis** (e.g., `🔒🔐🗝️💎✨🌟⭐`).
3. Enter your **secret message** (e.g., `Meet me at 9 PM`).
4. Check **"Enable AES Encryption"** if you want to encrypt.
5. Enter a **password** if encryption is enabled.
6. Click **🔒 HIDE**.
7. Copy the **encoded emoji string**.
8. **Example Output:**

🔒🔐🗝️💎✨🌟⭐...



*(The hidden message is invisible inside the emojis.)*

---

### 2. Revealing a Hidden Message

1. Paste the **encoded emoji string** into the "Decode" section.
2. Check **"Message is Encrypted"** if encryption was used.
3. Enter the **password** if required.
4. Click **🔓 REVEAL**.

## Live Demo

https://chnk0x.github.io/emoji-crypt-tool/

##
