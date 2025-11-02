<!-- PROJECT BANNER -->

<p align="center">
  <img src="C:\Multilingual Text Translator\assets\screenshots.png" alt="Multilingual Text Translator Banner" width="90%">
</p>

<h1 align="center">🌍 Multilingual Text Translator using Streamlit, mtranslate, and gTTS 🎧</h1>

<p align="center">
  <b>Translate text into 60+ languages, listen to speech, and download the audio — all in one Streamlit app!</b><br>
  <i>Built with Python, Streamlit, mtranslate, and Google Text-to-Speech.</i>
</p>

<p align="center">
  <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-3.9+-blue?logo=python"></a>
  <a href="https://streamlit.io/"><img src="https://img.shields.io/badge/Streamlit-App-red?logo=streamlit"></a>
  <a href="https://pypi.org/project/mtranslate/"><img src="https://img.shields.io/badge/mtranslate-Library-green"></a>
  <a href="https://pypi.org/project/gTTS/"><img src="https://img.shields.io/badge/gTTS-TTS-yellow"></a>
  <a href="#"><img src="https://img.shields.io/github/license/your-username/Multilingual-Text-Translator"></a>
</p>

---


## 🧠 Project Overview

Language barriers can slow down communication and collaboration.
This **Multilingual Translator App** solves that by allowing users to **translate text in real-time**, **listen to the pronunciation**, and **download the speech output** — all through an elegant **Streamlit interface**.

---

## 🚀 Features

✅ Translate text into **60+ languages**
✅ **Text-to-Speech** conversion using gTTS
✅ **Streamlit-based UI** for interactive use
✅ **Downloadable audio output**
✅ Handles **empty inputs and unsupported languages** gracefully

---

## 🧩 Problem Statement

In today’s globalized digital world, people interact across multiple languages daily — whether for learning, business, or travel.However, most translation tools are either **paid**, **lack speech output**, or are **difficult to customize**.

> 🧭 **Goal:** Create an open-source, user-friendly translator that performs multilingual translation with voice playback and download options.

---

## 🧰 Tech Stack

| Component              | Description                       |
| ---------------------- | --------------------------------- |
| **Python 3.9+**  | Core programming language         |
| **Streamlit**    | Web app framework                 |
| **mtranslate**   | Translation engine                |
| **gTTS**         | Google Text-to-Speech for audio   |
| **pandas**       | Language data management          |
| **base64**       | Encodes audio for downloads       |
| **language.csv** | Dataset containing language codes |

---

## 📦 Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/Multilingual-Text-Translator.git
   cd Multilingual-Text-Translator
   ```
2. **Install dependencies**

   ```bash
   pip install streamlit mtranslate gTTS pandas
   ```
3. **Run the Streamlit app**

   ```bash
   streamlit run lang_translation.py
   ```

---

## 🖥️ Usage Guide

1. Enter your text in the **input box**.
2. Choose your **target language** from the sidebar.
3. Click **“Translate”** to view the result.
4. Listen to the **audio playback** of the translated text.
5. Click **“Download Audio”** to save the MP3 file locally.

---

## 📊 Workflow Diagram

```
User Input → Language Selection → Translation (mtranslate)
→ Text-to-Speech (gTTS) → Audio Playback → Download
```

---

## 📂 Project Structure

```
📁 Multilingual-Text-Translator/
│
├── lang_translation.py        # Main Streamlit application
├── language.csv               # Dataset for languages and ISO codes
├── lang.mp3                   # Auto-generated output audio file
└── README.md                  # Project documentation
```

---

## 📸 Screenshots

| Input & Output                            |
| ----------------------------------------- |
| ![App Screenshot 1](assets/screenshot1.png) |


---

## ⚙️ Challenges Faced

| Challenge                            | Solution                                            |
| ------------------------------------ | --------------------------------------------------- |
| Some languages not supported by gTTS | Added validation for supported speech languages     |
| Handling empty text inputs           | Streamlit’s warning system (`st.warning()`) used |
| Audio download                       | Implemented Base64 encoding for downloadable files  |

---

## 🚀 Future Enhancements

- 🌐 **Automatic source language detection**
- 📚 **Batch translation** for files
- ☁️ **Deployment** on Streamlit Cloud / Hugging Face
- 🕶️ **Dark Mode & History Tracking**
- 🧩 Integration with **Google Translate API** for higher accuracy

---

## 🏁 Conclusion

This project demonstrates the effective combination of **Python, NLP, and TTS** technologies to break down communication barriers.
The app’s simplicity and efficiency make it ideal for **students, professionals, and language learners** worldwide.

---

## 📚 References

- [Streamlit Documentation](https://docs.streamlit.io/)
- [mtranslate Library](https://pypi.org/project/mtranslate/)
- [gTTS Library](https://pypi.org/project/gTTS/)
- [Pandas Documentation](https://pandas.pydata.org/)
- [Google Translate API](https://cloud.google.com/translate)

---

## 👨‍💻 Developer

**Tarun Kumar Rathore**
📅 *November 2025*
📧 *Open to collaboration & feedback*
🌐 *[LinkedIn Profile](https://www.linkedin.com/in/your-profile)*

---

<p align="center">
  ⭐ <b>If you like this project, don’t forget to star this repository!</b> ⭐
</p>
