# Gemini Cryptography Application
# [Gemini](https://elkmire.github.io/Gemini/ "Gemini Web Version") <- Web-Version
### (Web-version limited compared to release version)

A versatile encryption/decryption and encoding/decoding tool built with PyQt5 (and converted to HTML for the webversion), designed for both educational purposes and practical security applications.
![Gemini](https://github.com/user-attachments/assets/9ac3f85d-2d9e-4f5f-9831-80d90c0a326e)



## Features
#### Basic Encryption
1. **Caesar Cipher**
   - Classical substitution cipher
   - Customizable shift value (default: 3)
   - Preserves case and special characters
   - Suitable for educational purposes

2. **Vigenère Cipher**
   - Polyalphabetic substitution cipher
   - Custom keyword-based encryption
   - Case-preserving implementation
   - Enhanced security compared to Caesar cipher

3. **Atbash Cipher**
   - Simple substitution cipher
   - Reversible encryption (self-reciprocal)
   - No key required
   - Preserves case and spacing

4. **Text Reversal**
   - Simple string reversal
   - Maintains all characters
   - Useful for basic encoding

5. **Morse Code**
   - Complete implementation of International Morse Code
   - Supports letters, numbers, and punctuation
   - Space-separated output
   - Bidirectional conversion

#### Encoding Methods
1. **Base85 (ASCII85)**
   - Efficient binary-to-text encoding
   - Higher density than Base64
   - Suitable for technical applications

2. **Base64**
   - Standard binary-to-text encoding
   - Widely compatible
   - URL-safe implementation

3. **Base32**
   - Alternative binary-to-text encoding
   - Case-insensitive
   - Suitable for case-sensitive systems

4. **Hexadecimal**
   - Binary-to-hex conversion
   - Two-character representation per byte
   - Technical and debugging applications

#### Advanced Encryption
1. **AES-256**
   - Industry-standard encryption
   - 256-bit key strength
   - Password-based key derivation (PBKDF2)
   - Secure for sensitive data

2. **ChaCha20-Poly1305**
   - Modern stream cipher
   - High-performance encryption
   - Built-in authentication
   - Suitable for high-security applications
  
3. **NovelCrpyt**
   - CPU intensive, complex layering

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

### Token Management
- **Generate Token (Encrypt Mode)**
  - Creates a text file of encrypted content
  - Choose save location
  - Automatic .txt extension

- **Import Token (Decrypt Mode)**
  - Load generated token
  - Automatic content loading
  - Immediate decryption with selected methods

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

## Keyboard Shortcuts

### Mode Control
- Ctrl+E: Switch to Encrypt mode
- Ctrl+R: Switch to Decrypt mode

### View Control
- Ctrl+D: Toggle Dark Mode
- Ctrl+0: Increase Font Size
- Ctrl+9: Decrease Font Size

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

   (The python script is wrapped by auto-py-to-exe for easy deployment)


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

