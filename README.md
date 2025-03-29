# Hash

A modern, sleek, self-contained Base64 & AES-256 encoder/decoder with a terminal-inspired UI.

![image](https://github.com/user-attachments/assets/4070b7bd-7cd0-4314-9885-0a3a885ae8d1)

## 🌟 Features

### Core Functionality
- **Base64 Encoding/Decoding**: Convert any text to and from Base64 format
- **AES-256 Encryption/Decryption**: Military-grade encryption with password protection
- **Salt Management**: 
  - Generate random salts with one click
  - Set custom salts for consistent encryption
- **Password Protection**: Secure your encrypted content with strong password-based encryption
- **One-Click Copying**: Copy output to clipboard instantly
- **Toggle Between Modes**: Switch between Base64-only and Base64+AES modes
- **Large Input Support**: Efficiently handle substantial text inputs

### User Interface
- **Terminal-Inspired Design**: Dark theme with neon green accents (#00FF41)
- **Responsive Layout**:
  - Desktop: Two-panel layout with input on left, output on right
  - Tablet: Stackable panels
  - Mobile: Vertical layout with optimized controls
- **Smooth Animations**:
  - Transition effects for UI elements (300ms duration)
  - Loading animations during encryption/decryption
  - Success notifications for actions
- **Real-Time Feedback**:
  - Character and byte counters for input/output
  - Typing indicator animation
- **Educational About Page**:
  - Detailed explanations of encryption concepts
  - Comparison of Base64 vs AES security
  - Visual security meters with animations

## 🛠️ Technologies

- **Pure JavaScript**: No frameworks or backend dependencies
- **CryptoJS**: For AES-256 encryption implementation
- **PBKDF2**: For secure key derivation from passwords
- **Modern CSS Features**:
  - Flexbox/Grid for responsive layouts
  - CSS Variables for theming
  - CSS Animations and Transitions
  - Custom scrollbars
- **Font Awesome Icons**: For UI elements
- **JetBrains Mono**: Monospace font with programming ligatures

## 🔍 Implementation Details

### Encryption Process
- UTF-8 encoding support for international characters
- PBKDF2 key derivation with 1000 iterations for enhanced security
- AES-256 encryption implementation via CryptoJS
- Proper salt handling and storage

### Performance Optimizations
- Debounced input processing for better performance
- Efficient event handling for smooth UI experience
- Optimized animations with transform and opacity
- Minimal DOM manipulations

## 💻 Usage

1. Simply open the HTML file in any modern browser
2. Enter text in the input panel
3. Choose encoding or decoding mode
4. Toggle AES encryption if needed
5. View results in the output panel
6. Copy with one click

No installation, server, or internet connection required!

## 🔐 Security Notes

- This tool operates entirely in your browser - no data is sent to any server
- AES-256 is a recognized standard for secure encryption
- The strength of encryption depends greatly on password complexity
- Password and salt are never stored - they exist only during your session

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/Saganaki22/Hash.git

# Navigate to the directory
cd hash

# Open in browser
# Just open index.html in any modern browser
```

## 📜 Files

- `index.html` - Main encoder/decoder application
- `hash-about.html` - Educational content about encryption

## 📋 Browser Compatibility

- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+

## 📄 License

MIT License

---

![hash123](https://github.com/user-attachments/assets/e63ebc80-09b2-420d-8bbe-70abff6a5d7c)

Created with ♥ by [Saganaki22](https://github.com/Saganaki22)
