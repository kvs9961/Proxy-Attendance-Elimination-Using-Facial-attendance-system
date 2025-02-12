# Proxy Attendance Elimination Using Facial Attendance System

## Overview

This project aims to eliminate proxy attendance by implementing a facial recognition-based attendance system. The system captures and verifies individuals' faces in real-time and logs attendance with date and time, ensuring accuracy and transparency in attendance tracking.

## Features

- **Facial Recognition:** Uses machine learning models to detect and recognize faces.
- **Real-Time Attendance Tracking:** Automatically logs attendance with date and time.
- **Proxy Prevention:** Eliminates fraudulent attendance practices.
- **Scalability:** Can be adapted to different environments, including schools, offices, and events.

## Project Structure

```
|-- .gitattributes
|-- Face Attendence System Recog.. (1).ipynb  # Jupyter Notebook for facial recognition
|-- Face_Attendance_Model.joblib  # Serialized model file
|-- Face_Attendance_Model.pkl  # Another format of the trained model
|-- Untitled.ipynb  # Additional development notebook
|-- profiles1.csv  # Dataset containing user profiles and labels
|-- project.ipynb  # Main project notebook
|-- image/  # Directory containing sample images
|-- sample/  # Additional project-related samples
```

## Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/kvs9961/Proxy-Attendance-Elimination-Using-Facial-attendance-system.git
   cd Proxy-Attendance-Elimination-Using-Facial-attendance-system
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open and execute `project.ipynb` or `Face Attendence System Recog.. (1).ipynb`.

## Technologies Used

- **Python**
- **OpenCV**
- **scikit-learn**
- KNN, Logestic Regression, SVM(SVC) 
- **joblib** (for model serialization)
- **Pandas & NumPy**

## Usage

- Capture face data and register users in `profiles1.csv`.
- Train the model and save it using `Face_Attendance_Model.pkl` or `.joblib`.
- Run the recognition system to mark attendance.
- Export attendance logs for reporting and analysis.

## Future Enhancements

- Improve model accuracy with advanced deep learning techniques.
- Integrate with cloud services for better accessibility.
- Develop a user-friendly UI for seamless interaction.
- Implement mobile support for remote attendance tracking.

## Contributors

- **Kvs9961** - Project Developer

## License

This project is licensed under the MIT License

