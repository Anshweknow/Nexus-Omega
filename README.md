🚀 Nexus Omega — Speech Intelligence Platform

Nexus Omega is an advanced Speech Intelligence Platform designed to analyze human speech and extract meaningful insights such as emotions, sentiment, toxicity, speech clarity, and conversational intelligence.
The system combines automatic speech recognition, deep learning–based emotion analysis, NLP pipelines, and report generation into a unified platform.

🔍 Key Features

🎙️ Speech-to-Text (ASR) using Whisper

🎭 Emotion Detection using Wav2Vec2 (SUPERB Emotion Recognition)

🧠 Sentiment Analysis

☣️ Toxicity Detection

🌍 Multilingual Translation Support

📊 Speech Analytics

Words per minute (WPM)

Filler word detection

Grammar score estimation

Signal-to-noise ratio (SNR)

📈 Emotion Timeline Visualization

☁️ Word Cloud Generation

🧾 Automatic PDF Report Generator

📂 Supports audio upload and live recording

🎨 Modern UI with clean and modular design

🏗️ Tech Stack
Backend

Python

Flask

PyTorch

Transformers (HuggingFace)

Whisper ASR

Wav2Vec2 (Emotion Recognition)

NLP Pipelines

Frontend

HTML

CSS

JavaScript

Jinja Templates

Libraries & Tools

torch

transformers

speechrecognition

pydub

gTTS

matplotlib

wordcloud

reportlab

📁 Project Structure
Speech_Intelligence/
│
├── app.py
├── analyzers.py
├── audio_processor.py
├── models.py
├── report_generator.py
├── config.py
│
├── templates/
│   └── index.html
│
├── static/
│   ├── css/
│   └── js/
│
├── requirements.txt
└── README.md

⚙️ Installation & Setup
1️⃣ Clone Repository
git clone https://github.com/Anshweknow/Nexus-Omega.git
cd Nexus-Omega

2️⃣ Create Virtual Environment
python -m venv venv

3️⃣ Activate Environment

Windows

venv\Scripts\activate


Linux / macOS

source venv/bin/activate

4️⃣ Install Dependencies
pip install -r requirements.txt

▶️ Run the Application
python app.py


Then open browser:

http://127.0.0.1:5000

📊 Output Includes

Transcribed speech text

Detected emotions

Sentiment polarity

Toxicity score

Speech analytics metrics

Emotion timeline graph

Word cloud

Downloadable PDF report

👥 Team & Contribution

This project was built collaboratively as part of a team project:

Ansh Kulshreshtha — Developer

Ashutosh Singh — Developer

Both contributors worked jointly on system design, backend logic, and model integration.

🎯 Use Cases

Interview analysis

Call center analytics

HR screening

Public speaking evaluation

Customer sentiment monitoring

AI-based communication assessment

🔮 Future Enhancements

Real-time streaming speech analysis

Speaker diarization

Emotion fusion (text + voice)

Dashboard analytics

Cloud deployment

SaaS-based architecture

📜 License

This project is developed for educational and research purposes.

⭐ If you like this project

Give it a ⭐ on GitHub — it motivates further development!
THANKYOU
