# Duke Ignite Hackathon🔥: Live Glasses Filtering with Facial/Gesture Recognition in OpenCV

**The current Readme is generated by ChatGPT.**

## Info
This is a Flask web application that uses OpenCV to apply virtual glasses to a live video feed from a user's webcam, using facial recognition and gesture recognition.

## Members
- Developors: 1. Minghui Zhu; 2. Congcong Ma; 3. Thomas Barker.
- Mentor: JJ Je. (Shout out to Duke Ignite organizers and mentors!)

## Features
- Uses OpenCV to track the user's face in real-time, detecting facial landmarks such as the eyes and nose.
- Applies virtual glasses to the user's face in the video feed, based on the detected facial landmarks.
- Uses gesture recognition to allow the user to switch between different types of glasses by making specific hand gestures in front of the webcam.
- Supports multiple types of glasses, each with their own unique style and design.
- Resizes the video feed to half the original size to improve performance.
- Uses base64 encoding to efficiently transmit the video feed over HTTP.

## Installation
- Clone the repository to your local machine.
- Install the required Python packages listed in requirements.txt.
- Download the pre-trained facial landmark detection model from dlib here and place it in the root directory of the project.
- Run the application by executing python app.py.

## Usage
- Open a web browser and navigate to http://localhost:5000.
- Allow the application to access your webcam.
- The live video feed should now appear in the browser window with virtual glasses applied to your face.
- Make specific hand gestures in front of the webcam to switch between different types of glasses.

## Future Improvements
- Add support for detecting and tracking multiple faces at once.
- Improve the accuracy of the facial landmark detection by training a custom model on a larger dataset.
- Expand the range of available glasses to include more diverse styles and designs.
- Add support for other types of accessories, such as hats or earrings, that can be applied to the user's face in real-time.

