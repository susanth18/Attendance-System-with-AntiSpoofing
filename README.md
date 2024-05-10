# Facial Recognition Attendance System with Antispoofing
This project is a Python-based facial recognition attendance system with an added layer of antispoofing functionality. The system allows users to log in and log out using their facial features and maintains an attendance log. It utilizes the Silent Face Anti-Spoofing model developed by MiniVision AI for enhanced security and reliability.
![Real](https://drive.google.com/uc?id=1LFtmArv5PPcFUUTa5SwO_WmVTia3fc23)
![Spoof](https://drive.google.com/uc?id=1Dfhpn6D2c6Gln3LkIU8ZsW2DynwCfvti)


# Introduction
The main purpose of silent face anti-spoofing detection technology is to distinguish between real and fake faces presented to the system. This includes various spoofing methods such as printed photos, electronic displays, masks, and 3D images. The Silent Face Anti-Spoofing model employs Fourier spectrum analysis as an auxiliary supervision method to detect spoofing attempts.
For more details on the Silent Face Anti-Spoofing model and its training architecture, data preprocessing method, and performance, please refer to the Silent Face Anti-Spoofing GitHub repository.
# Features
- Facial Recognition: The system uses the face_recognition library to recognize registered users based on their facial features.
- Antispoofing: Antispoofing functionality is implemented to detect and prevent spoofing attacks, ensuring that only genuine users can access the system.
- Attendance Logging: The system logs user attendance, recording the time and date of each login and logout event.
# Installation and usage
1. Clone the repository to your local machine.
2. Install the required dependencies using pip.
3. If you face errors while installing dlib library refer this youtube video: https://www.youtube.com/watch?v=pO150OCX-ac
4. Run the main.py script: python main.py
# File Structure
- main.py: The main script that implements the user interface and controls the functionality of the system.
- util.py: Contains utility functions used by the main script, such as creating buttons, labels, and handling messages.
- test.py: Script for testing antispoofing models.
# Acknowledgements
- This project utilizes the Silent Face Anti-Spoofing model developed by MiniVision AI. For more information on the model architecture, performance, and usage, please refer to https://github.com/minivision-ai/Silent-Face-Anti-Spoofing
- This project utilizes the face_recognition library for facial recognition functionality.
