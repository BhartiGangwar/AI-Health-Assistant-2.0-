# 🤖 AI Doctor with Vision and Voice

This is a cutting-edge AI health assistant that provides medical insights based on a combination of voice and image inputs. Acting as a professional doctor, it analyzes images, transcribes spoken queries, and responds with a concise, spoken diagnosis and suggested remedies.

---

### ✨ Key Features

* **Multimodal Input:** Accepts both voice input from a microphone and an image for comprehensive analysis.
* **Speech-to-Text (STT):** Utilizes an advanced model (`whisper-large-v3`) to accurately transcribe patient queries.
* **Vision-Powered AI:** Employs a multimodal large language model to analyze images for medical conditions.
* **Text-to-Speech (TTS):** Generates a natural-sounding, synthesized voice response, mimicking a real doctor.
* **Interactive Interface:** The entire process is integrated into a user-friendly Gradio web application for instant accessibility.

### 🛠️ Tech Stack

* **Core Frameworks:** Python, Gradio
* **AI Services & APIs:** Groq API (for transcription and vision model), ElevenLabs API (for voice generation)
* **Python Libraries:** `speech_recognition`, `pydub`, `groq`, `elevenlabs`, `base64`

### ⚙️ How It Works

The application operates through a seamless workflow:

1.  **Voice & Image Input:** The user speaks into a microphone and uploads an image (e.g., of a skin condition).
2.  **Transcription:** The spoken audio is transcribed into text using the Groq Whisper model.
3.  **AI Analysis:** The AI model receives the transcribed text and the encoded image, analyzing both to form a medical opinion.
4.  **Voice Response:** The AI's text response is converted into natural-sounding speech using the ElevenLabs API, which is then played back to the user.

## 🖼️ Demo

![AI Health Assistant Interface](images/pro_demo.png)

