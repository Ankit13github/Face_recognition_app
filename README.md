# 🔍 Talaash - Real-Time Missing Person Detection System

Talaash is a real-time, AI-powered missing person detection system using **DeepFace**, **OpenCV**, and **MySQL**. It identifies individuals from live camera feeds by comparing detected faces with a pre-stored database of missing persons. It can handle multiple facial recognition models to improve accuracy, even with occlusions like beards or masks.

---

## 📌 Key Features

- **Real-Time Detection** - Identifies people in real-time using a webcam.
- **Multi-Model Support** - Utilizes both **Facenet512** and **ArcFace** for better accuracy.
- **Voice Alerts** - Announces person details when a match is found.
- **WhatsApp Notifications** - Sends alerts to specified numbers (optional).
- **Easy Database Management** - Connects directly to MySQL for person records.

---

## 🚀 Technologies Used

- **Python**
- **DeepFace**
- **OpenCV**
- **MySQL**
- **UltraMsg API** (for WhatsApp alerts)
- **pyttsx3** (for text-to-speech)
- **React** (Frontend)
- **Tailwind CSS** (Frontend styling)

---

## 🛠️ Prerequisites

Before running this program, make sure you have installed the following packages:

```bash
pip install deepface
pip install mysql-connector-python
pip install opencv-python
pip install pyttsx3
pip install ultramsg
You will also need to set up the following configurations:

MySQL Database: Create a database named talaash_db and update the db_config in the code.

UltraMsg API: Update your UltraMsg instance ID and token in the code for WhatsApp alerts.

Frontend: Use React and Tailwind CSS for the frontend if you are building the full stack.

📦 Setup and Installation
Clone the Repository:

bash
Copy
Edit
git clone https://github.com/ThisAkshat/VISION_TALAASH_INNOTHON2.0.git
cd VISION_TALAASH_INNOTHON2.0
Install Required Packages:

bash
Copy
Edit
pip install deepface opencv-python mysql-connector-python pyttsx3 ultramsg
Database Setup:

Create a MySQL database named talaash_db.

Import the required tables and data.

Configure Database:

Update your MySQL credentials in the db_config section of the code.

UltraMsg Configuration (Optional):

Update the UltraMsg API credentials if you want to use WhatsApp alerts.

📝 Usage
Run the main script to start real-time detection:

bash
Copy
Edit
python talaash.py
Press 'q' to quit the live detection.

🤝 Contributing
Backend: Developed by Akshat Sharma.

Frontend (React & Tailwind CSS): Developed by Ankit Malviya.

Database Management: Handled by Jay Thepe.

Special Thanks: Radhika Warude for her valuable help.

Contributions are welcome! Please fork the repo and create a pull request.

📧 Contact
For any queries, reach out to Ankit Malviya at am6374310@gmail.com

🌐 License
This project is licensed under the MIT License.

⭐ Support
If you like this project, please give it a star! 😊
