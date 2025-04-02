# Fuel-Station-Alert-System
Fuel Station Alert System is a Python-based application that suggests the three nearest fuel stations to users. It provides pop-up notifications and voice alerts for quick assistance, ensuring a smooth refueling experience.
<h3>Logic of project</h3>
The project includes direct working with the 68 facial landmark detector and also the face detector of the Dlib library.
The 68 facial landmark detector is a robustly trained efficient detector which detects the points on the human face using which 
we determine whether the eyes are open or they are closed.</br></br>
<center><img src="Avilable_fuelstations.png" align="center" height="350"></center>
<b>The 68-landmark detector data (.dat) file can be found <a href="http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2"> By clicking here</a></B>

<h3>The working of the project</h3>
<ul><li>As you can see the<b> above screenshot</b> where the landmarks aredetected using the detector.
<li>Now we are taking the ratio which is described as <i>'Sum of distances of vertical landmarks divided by twice the distance between horizontal landmarks'</i>.
<li>Now this ratio is totally dependent on your system which you may configure accordingly for the thresholds of sleeping, drowsy, active.</ul>
<p><img src="Fuel_Alert.png" align="center" height="350">
<img src="https://raw.githubusercontent.com/infoaryan/Driver-Drowsiness-Detection/master/screenshots/drowsy.jpg" align="center" height="350">
<img src="https://raw.githubusercontent.com/infoaryan/Driver-Drowsiness-Detection/master/screenshots/sleepy.jpg" align="center" height="350">
