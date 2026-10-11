# Lisentra: AI-Based Emotion Detection with Adaptive Communication in Audio
Lisentra is an advanced Speech Emotion Recognition (SER) system that utilizes Artificial Intelligence to detect and classify human emotions based on raw audio input. By analyzing acoustic features such as intonation, pitch, and speech rate, the system can identify the user's emotional state, paving the way for more empathetic and adaptive human-computer interactions.

---

## About the Project
In today's digital era, many automated communication systems lack the ability to understand and respond to the emotional state of users. Lisentra bridges this gap by functioning not just as a passive detector, but as a foundation for empathetic communication systems. This technology has vast real-world applications, including:
- **Mental Health Services:** Detecting signs of distress, anxiety, or depression.
- **Customer Service:** Enabling more empathetic automated responses based on caller frustration or calmness.
- **Education:** Helping educators gauge student engagement and emotional well-being during online sessions.

## Model Architecture & Dataset
**Base Model:** Wav2Vec2 & Transformers Encoder. This architecture learns representations directly from raw audio waveforms, eliminating the need for manual feature extraction (like MFCCs).
**Datasets Used:**
- RAVDESS (The Ryerson Audio-Visual Database of Emotional Speech and Song)
- TESS (Toronto Emotional Speech Set)
- Total Dataset: 4,240 audio samples.
- Performance: The model achieved an outstanding final test accuracy of 98.58%.

## 8 Detected Emotion Classes:
- Neutral
- Calm
- Happy
- Sad
- Angry
- Fearful
- Disgusted
- Surprised

---

## How to Use the App
As outlined in the Instruction Manual, there are two ways to use the application:
**Option 1:** Upload an Audio File
- Navigate to the "Unggah File Audio" tab.
- Drag and drop a .wav file into the designated area.
- The system will process the audio and display the predicted emotion.

**Option 2:** Record Live Audio
- Navigate to the "Rekam Langsung" tab.
- Click the microphone icon and speak naturally.
- Once the recording stops, the system will analyze your voice and display the detected emotion.

**Note:** To stop the server when you are done, press Ctrl + C in your terminal/command prompt.
