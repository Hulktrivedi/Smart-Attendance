# Smart-Attendance

# 🎓 AI-Based Attendance Management System

> 📌 *Undergraduate Final Year Project (2020–21)*  
> 🔒 This project is archived and provided for academic/reference use only.

---

## 📖 Overview

The AI-Based Attendance Management System is a Python-powered project designed to automate the attendance-taking process using real-time video feeds. It aims to reduce manual errors and increase efficiency in both **physical** and **virtual** classrooms, and has potential future applications in **corporate**, **industrial**, and **manufacturing environments**.

---

## 🎯 Core Features

- 📸 **Face Detection** from real-time classroom camera feeds
- 🧠 **AI/ML Logic** to recognize and match student faces to a known dataset
- 🗃️ **Automatic Attendance Logging** into structured sheets
- 🖥️ **Virtual Mode Concept**: fetch live video stream from a host’s machine and mark attendance based on active camera participants (planned, not implemented)

---

## 🧰 Tech Stack

| Component          | Details                                  |
|-------------------|------------------------------------------|
| Programming Lang. | Python                                   |
| ML Tools          | OpenCV, NumPy, pandas                    |
| Environment       | Conda-based Python virtual environment   |
| Other Tools       | Tkinter (for UI), SQLite / CSV logging   |

> ⚠️ **Note**: This project was developed in an older Python environment. Several libraries used may now be deprecated or outdated in newer Python versions.

---

## 📷 How It Works

1. Load student face dataset
2. Launch real-time feed from classroom camera
3. Detect and match faces using OpenCV
4. Log presence with timestamp
5. Save attendance in structured format (CSV/SQLite)

---

## 🚧 Current Limitations

- Compatibility issues with modern Python packages
- Virtual classroom tracking logic not implemented due to lack of API access
- Face recognition limited by dataset quality and lighting conditions

---

## 🛠 Future Potential

- 🎯 Corporate and industrial adaptation
- 🔐 Biometric-grade accuracy
- ☁️ Cloud sync & real-time reporting dashboard
- 📱 Android APK for mobile viewing/admin use
- 🧑‍💼 HRMS integration

---

## 📁 Project Status

This repository is preserved as an archived academic reference. Development has not continued beyond the final university submission.

---

## 🧾 Attribution Note

This project was developed during my undergraduate studies as a learning and experimentation exercise in AI/ML.  
Some portions of the code were adapted or inspired by publicly available developer resources and tutorials.  
While every effort was made to credit contributors, I no longer have access to original sources.  
If any contributor identifies their work here and wishes to be credited or have it removed, please contact me via GitHub.

---

## 📜 License

[MIT License](LICENSE)

