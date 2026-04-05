![{04027814-D10C-4C92-B7D4-7B0AD97ACF89}](https://github.com/user-attachments/assets/85d9529d-54cc-49e1-bcb3-600384ebf0e8)

# SecurePass

<div align="center">

**Advanced Entropy-Based Password Generator**

A secure, privacy-focused password generator that uses mouse movements to collect entropy and generate cryptographically strong passwords.

[Live Demo](#) | [Report Bug](https://github.com/aisurf3r/Securepass/issues) | [Request Feature](https://github.com/aisurf3r/Securepass/issues)

</div>

---

## Overview

SecurePass is an advanced password generator that uses entropy collected from mouse movements (or touch interactions on mobile devices) to create secure and unique passwords. The application focuses on security, usability, and privacy, ensuring that your passwords are robust and tailored to your preferences.

## Key Features

### 1. Entropy-Based Password Generation
- Collects entropy through mouse movements or touch gestures
- Generates cryptographically secure passwords using `crypto.getRandomValues()` for true randomness
- Real-time entropy collection with visual progress indicator

### 2. Password Customization
- Adjust password length between 8 and 32 characters
- Include or exclude uppercase letters, lowercase letters, numbers, and symbols
- Real-time strength calculation ensures your password meets security standards

### 3. Password Strength Analysis
Evaluates password strength based on:
- **Length** - Longer passwords score higher (up to 30%)
- **Character variety** - Mix of uppercase, lowercase, numbers, and symbols (up to 40%)
- **Character distribution** - Even distribution of characters (up to 30%)
- **Penalties** - Deductions for repeating characters and sequential patterns
- Displays strength as a percentage and categorizes it as Weak, Fair, Good, or Strong

### 4. Password History
- Saves up to 10 recently generated passwords with timestamps and strength scores
- Accessible via a history modal for quick reference
- Local storage only - no data sent to external servers

### 5. Keyboard Shortcuts
Streamline your workflow with keyboard shortcuts:
- `Shift+C` - Copy password to clipboard
- `Shift+D` - Download password as a text file
- `Shift+R` - Reset the generator
- `Shift+H` - Toggle password history
- `Shift+K` - Show keyboard shortcuts

### 6. Dark Mode Support
- Toggle between light and dark themes
- System preference detection
- Smooth transitions and optimized contrast

### 7. Mobile-Friendly Design
- Fully responsive design optimized for all screen sizes
- Touch-based entropy collection on mobile devices
- Intuitive interface for smartphones and tablets

### 8. Privacy and Security
- All password generation happens locally in your browser
- No data is sent to external servers
- Built with security best practices
- Open source for transparency

## How to Use

1. **Set Your Preferences**
   - Adjust the password length using the slider
   - Select the character types you want to include (uppercase, lowercase, numbers, symbols)

2. **Collect Entropy**
   - Move your mouse outside the generator box (or swipe on mobile) to collect entropy
   - A progress bar will indicate how much entropy has been collected (up to 100%)

3. **Generate Password**
   - Once sufficient entropy is collected, a secure password will be generated
   - The password strength will be displayed as a percentage and categorized

4. **Copy or Download**
   - Click the copy icon to copy the password to your clipboard
   - Click the download icon to save the password as a `.txt` file

5. **Access History**
   - View previously generated passwords by clicking the history button or using `Shift+H`

6. **Reset and Regenerate**
   - Click the "Generate New Password" button or use `Shift+R` to start over

## Installation

To run this project locally:

```bash
# Clone the repository
git clone https://github.com/aisurf3r/Securepass.git

# Navigate to the project directory
cd Securepass

# Install dependencies
npm install

# Start the development server
npm run dev

# Build for production
npm run build
```

The application will be available at `http://localhost:5173`.

## Technologies Used

- **React** - For building the user interface
- **TypeScript** - For type safety and enhanced developer experience
- **Vite** - For fast build tooling and development server
- **Tailwind CSS** - For responsive and modern styling
- **Lucide React Icons** - For clean and modern icons
- **Web Crypto API** - For generating cryptographically secure random values

## Contributing

Contributions are welcome! If you encounter any issues or have suggestions for improvement:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Security

If you discover a security vulnerability, please send an email to the maintainer instead of using the issue tracker. All security vulnerabilities will be promptly addressed.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Built with security and privacy as top priorities
- Inspired by the need for truly random password generation
- Thanks to the open source community for the amazing tools and libraries

---

<div align="center">

Built with care by [aisurf3r](https://github.com/aisurf3r)

Copyright © 2025 SecurePass
"Strong passwords made simple"
