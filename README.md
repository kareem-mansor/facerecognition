# Face Recognition System

## 🔍 Project Overview
This is a real-time face recognition system built using **OpenCV** and **Face_Recognition** for detecting, encoding, and comparing faces. It features a **GUI built with PyQt5** for easy interaction, including user registration, data management, and live recognition. The system securely stores facial data using an **SQLite database**.

## 📌 Features
- **Real-time Face Recognition**: Detect and recognize faces from a live video stream.
- **GUI Interface**: Built with PyQt5 for smooth interaction.
- **User Management**: Register new users, delete stored data.
- **Database Storage**: Securely store face encodings using SQLite.

## 🛠️ Installation
### 1. Clone the repository
```bash
git clone https://github.com/yourusername/FaceRecognitionSystem.git
cd FaceRecognitionSystem
```

### 2. Set up a virtual environment (optional but recommended)
```bash
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the application
```bash
python main.py
```

## 🏗️ Technologies Used
- **Python**
- **OpenCV** - Image processing & real-time detection
- **Face_Recognition** - Face encoding & matching
- **PyQt5** - GUI development
- **SQLite** - Database storage

## 🌟 Challenges Faced
1. **Compatibility Issues**
   - Required specific Python and Numpy versions for compatibility.
   - Dlib installation required manual setup with CMake.
2. **GUI Development**
   - Integrated real-time video processing with PyQt5.
   - Used `QTimer` to handle periodic updates and avoid UI freezing.
   - Managed resources efficiently to release the camera feed properly.
3. **Dependency Installation**
   - Required specific build tools for some libraries.
   
## 🚀 Future Enhancements
- Upgrade to **FaceNet / VGGFace** for improved accuracy.
- Implement **attendance tracking system**.
- Enhance **security** using encryption.
- Add **voice control** and **pose estimation** features.

## 🤝 Contributing
Feel free to fork the repository and submit pull requests! If you find any issues, please open an issue in the GitHub repository.

## 📜 License
This project is licensed under the MIT License.
