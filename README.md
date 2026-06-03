# Only You - Cryptographic Android Application

**Only You** is a secure Android application designed to generate high-quality cryptographic artifacts, including One-Time Passwords (OTP), secure passwords, and cryptographic keys. 

The application is powered by a custom **Hybrid Pseudo-Random Number Generator (PRNG)** that combines a Linear Congruential Generator (LCG), a Blum Blum Shub (BBS) generator, and a dynamic Henon chaotic map to ensure both high performance and cryptographic robustness.

---

## Features

- **Dynamic OTP Generation:** Generates secure 6-digit One-Time Passwords that refresh automatically every 30 seconds.
- **Background Persistence:** The OTP countdown tracks real-time elapsed time, even if the application is closed or placed in the background.
- **High Security (Anti-Screen Capture):** The OTP screen is fully protected using Android's `FLAG_SECURE`, preventing unauthorized screenshots or screen recordings.
- **Easy Clipboard Copy:** Tap on the generated OTP code to copy it instantly to your clipboard.
- **Secure Password Generator:** Creates strong, shuffled passwords containing uppercase letters, lowercase letters, numbers, and special symbols.
- **Cryptographic Key Generator:** Generates high-entropy alphanumeric random keys for encryption purposes.

---

## Built With

- **Language:** Java & XML
- **Development Environment:** Android Studio / Eclipse IDE
- **Statistical Validation:** Tested and verified using the **NIST Statistical Test Suite (STS)** to ensure optimal randomness and compliance with cryptographic standards.

---

## Installation

You can install the application directly on your Android device using the provided APK file.

### Option 1: Direct Download
1. Go to the **[Releases](https://github.com/[Your-GitHub-Username]/Only-You/releases)** section of this repository.
2. Download the `OnlyYou.apk` file.
3. Open the file on your Android smartphone and install it (make sure to allow installation from unknown sources if prompted).

### Option 2: Clone and Build
If you want to view or modify the source code, you can build it yourself:
```bash
# Clone this repository
git clone [https://github.com/](https://github.com/)[Your-GitHub-Username]/Only-You.git

# Open the project in Android Studio and click 'Run'
