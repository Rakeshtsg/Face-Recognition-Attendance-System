# Face-Recognition-Attendance-System
The Real-Time Face Recognition Attendance System is an efficient Python-based solution designed to streamline attendance management. By harnessing the capabilities of OpenCV and the face_recognition library, this system automates the attendance tracking process by instantly recognizing individuals through a webcam feed.
![Screenshot (556)](https://github.com/Rakeshtsg/Face-Recognition-Attendance-System/assets/109905492/6ec1b426-1534-4369-b012-add236ad0e66)

Face Recognition Attendance System
This is a Python-based face recognition attendance system that uses the OpenCV and face_recognition libraries to detect and recognize faces in a webcam stream and mark attendance in a CSV file. The system captures live video from the webcam, detects faces in real-time, and compares them with a set of known faces to mark attendance for recognized individuals.

Features
Real-time Face Detection: The system uses OpenCV to capture live video from the webcam and face_recognition library to detect and recognize faces in real-time.

Attendance Marking: When a recognized face is detected, the system marks the attendance of the individual by recording their name and timestamp in a CSV file.

CSV Attendance Log: Attendance data is stored in a CSV file (Attendance.csv) that can be easily accessed and managed.

Usage
Clone the repository to your local machine:

bash
**git clone https://github.com/Rakeshtsg/Face-Recognition-Attendance-System.git**
Install the required libraries using pip:

bash
**pip install -r requirements.txt**
Prepare your training images: Place images of individuals you want to recognize in the Training_images folder. Each image should contain only one face.

python main.py
The system will start capturing video from your webcam and mark attendance when it recognizes a face.

Press Esc to exit the program.

Dependencies
OpenCV
face_recognition
numpy
datetime
