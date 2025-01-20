# Gemini Cryptography Application
# [Gemini](https://elkmire.github.io/Gemini/ "Gemini Web Version") <- Click Here

*Because sometimes you want your messages to be as incomprehensible as your worklife*
![Gemini](https://github.com/user-attachments/assets/8f653efd-dfdc-45af-b99f-729fe6c57576)



## Overview
GEMINI is a browser-based cryptographic toolkit that combines classical ciphers, modern encryption, and various encoding methods. Think of it as a digital Enigma machine that had a wild night out with modern web standards.

## Core Features

### 1. Entry Methods
* **Caesar Cipher**: The OG of encryption. If it was good enough for Julius Caesar, it's good enough for your lunch plans.
  - Customizable shift value (default: 3)

* **Vigenère Cipher**: Like Caesar cipher, but it went to college.
  - Requires a key word/phrase
  - Case-insensitive, non-alpha characters are preserved

* **Atbash**: Reverses the alphabet. A becomes Z, B becomes Y, etc. It's like alphabet yoga.

* **Reverse**: Literally just reverses the text. Not encryption, but surprisingly effective against lazy adversaries.

* **Morse Code**: Because sometimes you want to communicate like it's 1844.

### 2. Encoding Methods
* **URL Encoding**: Turns spaces into %20s and makes your text URL-safe. Perfect for when your message needs to travel the information superhighway.

* **Unicode**: Escapes Unicode characters. Useful when your message includes emojis that you don't want to explain to your crypto-professor.

* **Binary**: Converts text to binary. For when you want to roleplay as a computer or really annoy your friends.

* **Base85**: Like Base64, but with a superiority complex.

* **Base64**: The industry standard for making readable text unreadable.

* **Base32**: Base64's less popular cousin. Uses fewer characters but takes up more space.

* **Hex**: Converts text to hexadecimal. Because sometimes you want your message to look like a memory dump.

### 3. Encryption
* **AES-256**: Military-grade encryption for your cat memes.
  - Requires a password
  - Uses CBC mode with PKCS7 padding
  - Includes salt and IV for maximum security

## Usage Tips

1. **Mode Toggle**: Switch between encryption and decryption with the big button at the top. It's color-coded because cryptographers need visual aids too.

2. **Chaining Operations**: Operations are applied in sequence:
   - Encryption: Top to bottom
   - Decryption: Bottom to top
   - Think of it like a cryptographic sandwich

3. **Save/Load Keys**:
   - Export configuration to disseminate to your cronies
   - Password-protected , AES encrypted; because trust issues are healthy in cryptography
   - Export as `GEMINI-KEY.txt`

4. **Performance Features**:
   - Handles large texts through chunked processing
   - Automatic updates as you type

## Best Practices

1. **For Maximum Security**:
   - Use AES-256 with a strong password (+12 chars, multi sign)
   - Combine with encoding methods for additional layers

2. **For Maximum Confusion**:
   - Chain every single option
   - Use random keys
   - Watch the world burn

3. **For Actual Usability**:
   - Pick one or two methods
   - Document your settings
   - Don't forget your passwords

## Error Handling
* Invalid Base64? It will let you know.
* Wrong AES password? It will let you know.
* Life choices? You're on your own.

## Mobile Support
* Responsive design
* Touch-friendly controls
* Pull-to-refresh functionality (because sometimes you need a clean slate)

## Dark/Light Mode
Automatically matches your system preferences, because cryptographers need proper contrast ratios.

## Remember
* The security of your message is inversely proportional to your need to decrypt it later
* All encryption is breakable given enough time, computing power, or determination
* This tool is for educational purposes and personal use; for proffesionally-sensitive data, use established encryption tools
* If you forget your password, get crackin'

## Easter Eggs
There aren't any. Or are there? You'll need to decrypt that information yourself.

## Notes
- The application is designed for educational and practical purposes
- Multiple encryption methods can be chained together
- Configuration files are themselves encrypted
- All operations are performed locally

