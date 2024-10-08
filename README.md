
# Hand Tracking Volume Control(Computer Vision Project)
This project utilizes computer vision techniques to track hand movements using the MediaPipe library and OpenCV in Python. It allows controlling system volume by changing the distance between specific hand landmarks detected in real-time.
![image](https://github.com/user-attachments/assets/9bff3405-d77e-4876-bba4-9fb7b9ab3347)


![image](https://github.com/user-attachments/assets/4dca3db3-3704-49d8-9d92-bc5ff2b1e36a)


The program continuously captures video frames from the webcam and processes them to detect hand landmarks using the MediaPipe Hands model. It calculates the distance between two specific landmarks on the hand (e.g., thumb tip and index finger tip) to adjust the system volume accordingly.



##Requirements

Python 3.x

OpenCV

MediaPipe

PyAutoGUI (for macOS)

NumPy


**Usage**

Ensure your webcam is connected and functioning properly.
Run the Python script, and the webcam window will open, showing your hand with landmarks detected.
Adjust the volume by moving your hand closer or further apart, controlling the distance between specific landmarks.
Press the 'Esc' key to exit the program
