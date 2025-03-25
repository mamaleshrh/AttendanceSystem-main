# Attendance System using Facial Recognition

## 🎓 Project Overview

An advanced attendance system leveraging facial recognition technology, combining deep learning models, computer vision techniques, and machine learning algorithms for accurate identification and attendance recording.

## 👥 Team Members

- Anant Jain (21095014)
- Mamalesh Rajkumar Hake (21095071)
- Rajat Shukla (21095090)
- Shrirang Brajesh Agarwal (21095109)

## 👨‍🏫 Supervisor

Dr. Priya Ranjan Muduli

## ⚙️ Features
- **User Registration:** Captures and stores student images with unique IDs.
- **Face Recognition:** Identifies students and marks attendance automatically.
- **Liveliness Detection:** Prevents proxy attendance by detecting eye blinks.
- **Image Training:** Processes captured images and saves encodings for recognition.
- **Attendance Records:** Securely stores and retrieves attendance data.
- **Text-to-Speech Feedback:** Provides audio responses for better user interaction.

## 🏗️ Project Structure
```
Smart-Attendance-System/
│── Attendance_Records/      # Stores attendance records in CSV format
│── StudentDetails/          # Stores student images and details
│── BlinkDetect.py           # Liveliness detection using eye blinks
│── Capture.py               # Captures student images
│── Trainer.py               # Encodes and trains face images
│── voicer2.py               # Converts text to speech
│── main.py                  # Main script with user menu
│── security.txt             # Stores passwords for record access
```

## 🚀 Installation & Usage
### 🔧 Requirements
- Python 3.x
- OpenCV (`cv2`)
- `face_recognition` library
- `numpy`
- `pyttsx3`

### 🔨 Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/Smart-Attendance-System.git
   cd Smart-Attendance-System
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the main script:
   ```sh
   python main.py
   ```

## 🎯 How It Works
1. **New User Registration:**
   - Enter ID and Name.
   - System captures face and stores image.
   - Details are saved in `StudentDetails.csv`.
2. **Train Image:**
   - Encodes and stores face data for recognition.
3. **Record Attendance:**
   - Matches face with stored data.
   - Attendance is marked if match >70%.
   - Liveliness detection ensures authenticity.
4. **Check Attendance Status:**
   - Users can check their attendance via CLI.
5. **Admin Access to Records:**
   - Requires a password to view attendance records.

## 👨‍💻 Technologies Used
- **Python**
- **OpenCV** (Face detection)
- **Face Recognition API**
- **Raspberry Pi Camera**
- **NumPy**
- **CSV for Data Storage**
- **Text-to-Speech (pyttsx3)**

## 🎥 Demo

- [Live Demo](https://github.com/mamaleshrh/AttendanceSystem-main/assets/101654909/8cf5d6ee-fa16-4d8a-89e4-c83672b9125b)

https://github.com/mamaleshrh/AttendanceSystem-main/assets/101654909/8cf5d6ee-fa16-4d8a-89e4-c83672b9125b

## 📜 Presentation

[explo-G21-presentation.pdf](https://github.com/mamaleshrh/AttendanceSystem-main/files/11463855/explo-G21-presentation.pdf)

## 🤝 Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

## 📜 License
This project is licensed under the MIT License.

## 💡 Future Improvements
- Implement a **web-based UI** for better accessibility.
- Integrate **cloud storage** for attendance records.
- Use **deep learning** for improved accuracy.

## 📞 Contact
For any issues or suggestions, feel free to reach out!

