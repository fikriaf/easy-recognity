# Easy Recognity 🎙️

Easy Recognity is a real-time, browser-based speech recognition app. It leverages the built-in Web Speech API for speech-to-text and uses Python (with Selenium) for automation.

## ✨ Features
- Live Speech-to-Text via browser
- Web automation using Python + Selenium
- Auto-stop when speech is detected
- Clean and responsive user interface

## 📁 Project Structure
- `recognity.html` — Web interface using HTML + JavaScript (Web Speech API)
- `recognity.py` — Python automation script to simulate user interaction using Selenium
- `webdriver/` — (Optional) Directory for WebDriver binaries (if not using webdriver-manager)

## 🚀 How to Run

1. Clone the Repository
   ```
   git clone https://github.com/fikriaf/easy-recognity.git
   cd easy-recognity
   ```

2. Install Python Dependencies
   ```
   pip install selenium webdriver-manager
   ```

3. Run the Script
   ```
   python recognity.py
   ```

This script will:
- Launch Chrome in headless mode
- Open `recognity.html`
- Simulate clicking the "Start" button to start speech recognition
- Display the transcribed speech in terminal output

## 📋 Sample Output
```
Listening...
Hello world this is a test
```

## ⚙️ Notes
- Chrome is required (with Web Speech API support)
- The script uses `--use-fake-ui-for-media-stream` and `--use-fake-device-for-media-stream` to simulate mic access
- The function `SpeechRecognitionModel()` can be integrated with other automation or voice-control systems

## 🔧 Compatibility

| Component               | Status        |
|------------------------|---------------|
| Chrome (WebSpeech API)  | ✅ Supported   |
| Firefox                 | ❌ Not supported |
| Linux / macOS / Windows | ✅            |
| Python 3.7+             | ✅            |

## 👤 Author
Made with ❤️ by [fikriaf](https://github.com/fikriaf)
