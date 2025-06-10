# 🧠 Object Detection System using Gemini API

This is a web application built with **Streamlit** that allows users to upload an image and receive a concise, expert-level analysis using **Google's Gemini 1.5 Flash model**. The app is tailored for **Human Activity Recognition (HARC)** tasks, providing meaningful insights into settings, objects, and human movements.

---

## 🚀 Features

- Upload image files (`.jpg`, `.jpeg`, `.png`)
- Enter a custom prompt
- Generate a concise, 50-word expert description of:
  - Scene context  
  - Visible objects  
  - Human posture or actions
- Uses **Google Generative AI (Gemini 1.5 Flash)**

---

## 🛠️ Tech Stack

- [Streamlit](https://streamlit.io/) — UI & frontend
- [Google Generative AI](https://ai.google.dev/) — for image + prompt generation
- [Python-dotenv](https://pypi.org/project/python-dotenv/) — for loading API keys
- [Pillow (PIL)](https://python-pillow.org/) — for image handling

---

## 📦 Installation

1. **Clone this repository**

```bash
git clone https://github.com/your-username/object-detection-gemini.git
cd object-detection-gemini