# Gemini Cryptography Application
![Gemini logo(1)](https://github.com/user-attachments/assets/7dd5799b-6411-4fd8-8e8b-edd2000e2527)

A versatile encryption/decryption and encoding/decoding tool built with PyQt5, designed for both educational purposes and practical security applications.

![Gemini](https://github.com/user-attachments/assets/2c573ed2-4bff-48e1-9ab5-87f7e6bf297f)



## Features

### Basic Encryption Methods
- **Caesar Cipher**: Classic substitution cipher with customizable shift value
- **Vigenère cipher**: Key-based polyalphabetic substitution.
- **Atbash cipher**: Reverse, monoalphabetic substitution.
- **Text Reversal**: Simple text transformation
- **Morse Code**: Convert text to and from Morse code

### Encoding Options
- **Base85**: Standard base85 encoding/decoding
- **Base64**: Standard base64 encoding/decoding
- **Base32**: Alternative encoding with a smaller character set
- **Hexadecimal**: Convert text to/from hexadecimal representation

### Advanced Encryption
- **AES-256**: Advanced Encryption Standard with 256-bit key length
- **ChaCha20-Poly1305**: Modern stream cipher with authentication

## Usage

### Interface Elements

#### Input Section
- Large text area for entering messages
- Character counter showing input length
- Placeholder text indicating current mode (encrypt/decrypt)

#### Options Panel
- Mode selector (Encrypt/Decrypt)
- Checkboxes for selecting encryption methods
- Password field for AES and ChaCha20
- Caesar shift value input
- Reset button to clear all selections
- Chain display showing applied transformations

#### Output Section
- Display area for processed text
- Character counter showing output length
- Copy button for easy clipboard access

### Workflow

1. **Basic Usage**:
   - Enter text in the input field
   - Select desired encryption/encoding methods
   - Choose Encrypt or Decrypt mode
   - View results in the output field

2. **Advanced Encryption**:
   - Enter a password when using AES-256 or ChaCha20-Poly1305
   - Same password required for decryption
   - Chain display shows encryption/decryption steps

3. **Configuration Management**:
   - Save current settings via File → Save Configuration
   - Load saved settings via File → Load Configuration
   - Configurations are encrypted with a password

### Visual Customization
- Dark/Light mode toggle in View menu
- Adjustable font sizes (Increase/Decrease options)
- Keyboard shortcuts for font size adjustment

## Help and Documentation
- Built-in encryption guide accessible via Help menu
- Detailed explanations of all encryption methods
- About section with version information

## Security Features
- Password-based key derivation (PBKDF2)
- Secure random number generation
- Salt usage for enhanced security
- Authentication in ChaCha20-Poly1305

## Technical Details

### Encryption Implementations
- AES-256 uses CBC mode with PKCS7 padding
- ChaCha20-Poly1305 provides authenticated encryption
- Secure key derivation from passwords
- Random salt generation for each encryption

### Data Handling
- UTF-8 encoding for text processing
- Base64/Base32 for binary data representation
- Automatic input validation
- Error handling and user feedback

## Requirements
- Windows operating system.
- (the application is a single python script wrapped in an .exe.)

## Installation

No installation needed, just:

1. Run the application.


## Best Practices
- Always use strong passwords for AES and ChaCha20
- Keep stored configurations secure
- Use advanced encryption for sensitive data
- Verify decryption results match expected format

## Notes
- The application is designed for educational and practical purposes
- Multiple encryption methods can be chained together
- Configuration files are themselves encrypted
- All operations are performed locally

