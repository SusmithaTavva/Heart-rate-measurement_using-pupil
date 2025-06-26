# Heart_rate_measurement_using_pupil
=======
📌 Project Overview
This project detects heart rate (BPM) by analyzing pupil dilation and facial blood flow through a webcam or pre-recorded video. Unlike traditional methods (stethoscope, pulse sensors), this approach uses AI-based signal processing to estimate heart rate non-invasively.

Key Features
✅ Real-time & Offline Analysis – Works with live webcam feed or uploaded videos.
✅ Non-Contact Monitoring – No physical sensors required.
✅ Random Forest & CNN-Based Prediction – Combines signal processing and deep learning for accuracy.
✅ Interactive GUI – Built with PyQt5 for smooth user experience.
✅ Data Visualization – Graphs & signal analysis using Matplotlib & PyQtGraph.

🛠 Tech Stack
Category	Technologies Used
Programming	Python
Frameworks	Flask, TensorFlow, PyTorch
ML/DL Models	CNN (Convolutional Neural Network), Random Forest Algorithm (RFA)
Computer Vision	OpenCV, Dlib (facial landmark detection)
Data Processing	NumPy, SciPy, Pandas
Visualization	Matplotlib, PyQtGraph
GUI	PyQt5
🚀 How It Works?
Input Source Selection

Choose between live webcam or upload a recorded video.

Pupil & Facial Signal Extraction

Dlib detects facial landmarks.

OpenCV tracks subtle pupil dilation and blood flow changes.

Signal Processing

Scipy & NumPy filter noise and extract pulse signals.

Heart Rate Prediction

Random Forest (RFA) estimates BPM from signal patterns.

CNN (optional) improves accuracy with deep learning.

Output Visualization

Real-time BPM display & signal graphs (PyQtGraph).

⚙️ Installation & Setup
Prerequisites
Python 3.8+

Visual Studio Build Tools (for dlib compilation)

CMake (pip install cmake)

Install Required Libraries
bash
pip install opencv-python dlib numpy scipy imutils PyQt5 pyqtgraph matplotlib pandas scikit-learn tensorflow torch
Run the Application
bash
python GUI.py  # Launches the PyQt5 interface
(or)

bash
python app.py  # If using Flask backend
📊 Expected Output
Real-time BPM estimation (e.g., Heart Rate: 72 BPM)

Signal graphs (PPG, frequency analysis)

Video feed with facial landmarks (if using webcam)

📂 Project Structure
text
├───data/                # Sample videos & test datasets  
├───models/              # Pre-trained CNN/RFA models  
├───src/  
│   ├───signal_processing.py  # Filters & BPM calculation  
│   ├───face_detection.py     # Dlib/OpenCV pupil tracking  
│   └───ml_model.py           # RFA & CNN prediction  
├───GUI.py               # PyQt5 Main Application  
├───app.py               # Flask API (optional)  
└───requirements.txt     # Dependencies  
🔍 Future Improvements
Improve accuracy with GenAI-based signal enhancement.

Mobile app integration (Android/iOS).

Cloud-based heart rate analytics for long-term monitoring.

🙏 Credits & References
Dlib (http://dlib.net/) - Facial landmark detection

OpenCV (https://opencv.org/) - Real-time video processing

Scikit-learn (https://scikit-learn.org/) - Random Forest implementation

📜 License
This project is open-source under the MIT License.

💡 Contact
Sushmitha
📧 t.susmitha7989@gmail.com
🔗 LinkedIn: https://www.linkedin.com/in/susmitha-tavva-897655266/ 

🌟 Thank You for Your Interest in This Project!
"Innovating healthcare with AI-driven solutions." 🚀



