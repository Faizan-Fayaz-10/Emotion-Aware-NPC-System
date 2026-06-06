# 🎭 Emotion-Aware NPC System

This project demonstrates **how AI-powered NPCs can detect human emotions in real time using a webcam feed and respond using speech**. It showcases how emotional intelligence can be integrated into virtual agents — an essential innovation for metaverse avatars, gaming, and human-AI interaction systems.

---

# 🔥 Features

| Feature                              | Status | Description                                           |
| ------------------------------------ | ------ | ----------------------------------------------------- |
| **Real-time webcam input**           | ✅      | Captures video of the user.                           |
| **Emotion detection (FER + OpenCV)** | ✅      | Detects happy, sad, angry, neutral, fear, surprise.   |
| **NPC response system**              | ✅      | NPC replies emotionally based on detected expression. |
| **Voice output (macOS say)**         | ✅      | NPC speaks responses.                                 |
| **Basic UI (bounding box)**          | ✅      | Displays face detection & emotion label.              |

---

# 🧠 Technologies Used

- Python 3
- OpenCV
- TensorFlow + Keras
- FER (Facial Emotion Recognition)
- pyttsx3 / macOS say voice

---

# 🧩 Project Structure

emotion_npc/
├── npc_emotion.py        # Main file
├── requirements.txt      # Package list
├── README.md

---

# 🚀 How to Run

**1️⃣ Clone the repository**
git clone https://github.com/YOUR_USERNAME/emotion_npc.git
cd emotion_npc

**2️⃣ Create and activate virtual environment**
python3 -m venv venv
source venv/bin/activate          # On macOS/Linux

**3️⃣ Install dependencies**
pip install -r requirements.txt

**4️⃣ Run the project**
python3 npc_emotion.py

---

# 🔮 Future Improvements

- Animated 2D/3D avatars
- Multifacial detection
- VR/metaverse integration
- Emotion memory tracking

---

# 🎯 Outcome

✔️ Successful demonstration of AI-driven emotional interaction
✔️ Fully working prototype
✔️ Valid implementation under “AI-Driven Innovation in the Metaverse”

---

# 📊 Results & Conclusion

- The system successfully detects user facial emotions in real-time using the webcam.
- NPC responses are emotion-aligned and spoken clearly via voice output, enhancing user interaction.
- The bounding box and emotion label display help visually confirm detection.
- Response timing is managed using a cooldown mechanism, which prevents over-sensitivity or rapid speech.
- Works smoothly for front-facing users under normal lighting conditions, showing practical performance.
- The project effectively demonstrates how AI-driven emotional intelligence can be integrated into virtual NPCs to provide a more natural and immersive interaction.

---

## 👤 Author

**Name**: FAIZAN FAYAZ 

🔗 [LinkedIn](https://www.linkedin.com/in/faizan-fayaz-464723326/)  
🌐 [GitHub](https://github.com/Faizan-Fayaz-10)

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

⭐ If you found this project useful, consider giving it a star.
