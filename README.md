
# 🎵 Audio Spoof Detection App

This is a Streamlit-based web application that uses advanced machine learning models to detect whether an audio file is **bonafide** (real) or **spoofed** (fake). The application leverages Facebook's Wav2Vec2 for feature extraction and a TensorFlow-based CNN model for classification.

---

## 📋 Features

- Upload `.wav` audio files for classification.
- Provides predictions (`bonafide` or `spoof`) with confidence scores.
- Displays class probabilities with a visually appealing bar chart.
- Easy-to-use interface built with Streamlit.

---

## 🛠️ Setup Instructions

### **1. Clone the Repository**
```bash
git clone https://github.com/your-username/audio-spoof-detection.git
cd audio-spoof-detection
```

### **2. Create a Virtual Environment (Optional but Recommended)**
```bash
python -m venv env
source env/bin/activate  # On Windows, use `env\Scripts\activate`
```

### **3. Install Dependencies**
Install the required Python libraries using the `requirements.txt` file:
```bash
pip install -r requirements.txt
```

### **4. Run the Application**
Launch the Streamlit app using:
```bash
streamlit run app.py
```

---

## 🔗 How to Use

1. **Open the App**:
   After running the above command, Streamlit will provide a local URL (e.g., `http://localhost:8501`). Open it in your browser.

2. **Upload an Audio File**:
   - Click on the "Browse files" button or drag and drop a `.wav` file.
   - Ensure the file is in WAV format and meets the required specifications (e.g., 16kHz sampling rate).

3. **View Results**:
   - The app will process the audio and display the following:
     - **Prediction**: Whether the file is "bonafide" or "spoof."
     - **Confidence Score**: How confident the model is in its prediction.
     - **Class Probabilities**: Probabilities for each class (visualized as a bar chart).

---

## 🛠️ Troubleshooting

### **Common Issues**

1. **Dependency Errors**:
   - Ensure you have the correct versions of `torch`, `transformers`, `tensorflow`, and `torchaudio`. Use the provided `requirements.txt` to avoid version mismatches.

2. **File Format Errors**:
   - Ensure the uploaded file is in `.wav` format and is not corrupted.

3. **GPU Not Detected**:
   - If using a GPU, ensure CUDA is installed and the `torch` version matches your CUDA version.

4. **Permission Issues (Windows)**:
   - Run Command Prompt as Administrator to resolve file permission issues.

---

## 📂 Project Structure

```plaintext
.
├── app.py                # Main Streamlit application
├── saved_cnn_MMS_model   # Trained TensorFlow CNN model directory
├── requirements.txt      # Python dependencies
├── README.md             # Project documentation
```

---

## 🌐 Live Application (Optional)

If deployed online (e.g., via Streamlit Cloud, AWS, or Heroku), provide the link here:

[**Access the Live Application**](https://your-app-link.com)

---

## 🤝 Contributing

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m "Add feature"`).
4. Push the branch (`git push origin feature-name`).
5. Open a pull request.

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 💬 Contact

For questions or feedback, feel free to contact:
<!-- 
- **Your Name**: [your-email@example.com](mailto:your-email@example.com)
- **GitHub**: [Your GitHub Profile](https://github.com/your-username) -->

