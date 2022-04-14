## Image-Recognition_and_Augmented-Reality_System
This is a system that uses Image Recognition and Augmented Reality to identify a landmark and then provide description about it using AR.<br>
<br>
Libraries and dependencies required to run this project : <br>
&nbsp; &nbsp; 1. Python Interpreter<br>
&nbsp; &nbsp; 2. OpenCV<br>
&nbsp; &nbsp; 3. Geocoder<br>
&nbsp; &nbsp; 4. JSON<br>
<br>
This project has been made using **python3.97** with **OpenCV Library**. It is a system that works on real-time data. It fetches the user's current location (latitude and londitude) from their IP address and compares it with the database (JSON file in ths case as the project is small scale for now but, it can be hosted on cloud and use databases like Firebase Firestore to store large number of data-set) and checks if there is any tourist destination near the user. If the condition is true then it shows all nearby location (within 0.02 to 0.03 degree variation is the latitube and longitude).<br>
The user can then pick location and go there. The application opens the camera (webcam in this case) and if the user points it towards the landmark, it will recognize the landmark and show a video in Augmented Reality to the user which describes the place, its history and significance.<br>
The augmentation has been done via masking layers on top of each other. No APIs have been used. This project is all Python with OpenCV library. Image recognition is beng done using Edge Point Detection. The system fetches real-time feed from the webcam and is doing all the comparison with the continuous frames coming from the webcam.<br>