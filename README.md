#  Real‑Time Voice Translator

Real‑Time Voice Translator is a **desktop AI application** that enables **instant speech‑to‑speech translation** between different languages. The system captures a user’s voice, converts it to text, translates it into the target language, and then converts it back into speech — allowing smooth, natural communication across language barriers.

This project is designed for **real‑time usage**, making it suitable for demonstrations, academic projects, and basic real‑world translation scenarios.

---

##  Features

*  **Real‑Time Speech Translation** – Translate spoken language instantly
*  **Voice Input Support** – Uses microphone input for live speech
*  **Audio Output** – Plays translated speech automatically
*  **Multi‑Language Support** – Supports multiple source and target languages
*  **Desktop Application** – Runs locally on your system
*  **Simple & Clean Architecture** – Easy to understand and extend

---

##  How It Works

The application follows a simple but effective pipeline:

1. **Speech Capture** – Takes live audio input from the microphone
2. **Speech‑to‑Text** – Converts spoken words into text
3. **Translation** – Translates the text into the selected target language
4. **Text‑to‑Speech** – Converts the translated text back into audio
5. **Audio Playback** – Plays the translated voice output

---

##  Tech Stack

* **Python** – Core programming language
* **SpeechRecognition** – For speech‑to‑text conversion
* **deep‑translator** – For language translation
* **gTTS (Google Text‑to‑Speech)** – For speech synthesis
* **PyAudio / playsound** – For audio input and output

---

##  Project Structure

```
 Real-time-voice-translator
 ┣ 📁 build/
 ┣ 📁 dist/
 ┣ 📄 main.py
 ┣ 📄 setup.py
 ┣ 📄 requirements.txt
 ┣ 📄 icon.ico
 ┣ 📄 icon.png
 ┗ 📄 README.md
```

---

##  Installation & Setup

###  Clone the Repository

```bash
git clone https://github.com/1sarthak7/Real-time-voice-translator.git
cd Real-time-voice-translator
```

###  Create a Virtual Environment (Recommended)

```bash
python -m venv env
source env/bin/activate   # macOS / Linux
env\Scripts\activate      # Windows
```

###  Install Dependencies

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

###  Run the Application

```bash
python main.py
```

Make sure your **microphone** and **speakers/headphones** are properly connected before running the app.

---

##  Requirements

* Python **3.10 or below** (recommended for compatibility)
* Working microphone
* Audio output device (speakers or headphones)

---


##  License

This Project in open sourced and can be used for educations 

---

##  Author

**Sarthak Bhopale**
Engineering Student at MIT

---


