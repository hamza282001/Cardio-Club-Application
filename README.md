CARDIO CLUB FITNESS APPLICATION

Cardio Club is a fitness app that helps user calculate runs. The app tracks the runner’s location and calculates steps & pace once the user clicks the start button. The run scores are saved automatically in a database when the end run button is pressed. The app let users create personal ID’s as well. All the runs, user details and body parameters can be viewed in the users menu.


FEATURES

 Live Tracking:
The app keeps tracking the user’s location once the run has been started. The location is updated every second and a marker shows the runner’s position on the map.

 Steps Counter:
The app calculates the number of steps that user has covered and later converting them into kilometers using the value. Both the steps and kilometers are updated frequently while the run is active.

 Pace Calculator:
The app also records the pace of the runner. It is calculated using the steps covered. The pace is updated every second while the run is active.

 Minimalist Interface:
The app holds a modest but interactive interface. The interface of all the activities follows a similar fashion.

 Personal ID’s:
Users are provided with an option to create personal ID’s to record the user activity. The ID’s are accessible only when there’s an internet connection connected to the device.

 Run Logs:
Once the user ends the run, the statistics are automatically saved only if the user has a personal ID. All the runs can be accessed from the user menu.

 User Details:
The user with an ID can access their details by clicking the user detail button. It includes the username, email ID, height and weight of the user.

 Background Activity:
The app runs smoothly on the foreground and background as well. If the device screen is closed or if the app is resumed it will still keep working.

 Cardio Workout:
Cardio Workout is a list of precisely picked exercises for extra calorie loss. This will help user while the exercising.


DESIGN

 IDE:
The application is written in Android Studio using Java programming language.

 User Interface:
The user interface is designed using Adobe XD.

 Database:
Realtime Firebase database is used as the database in the application. It is connected to register and access personal ID’s. Run logs and all the statistics are directly fed into the database once the user ends the run.

 Services:
1. Google Play:
Google maps API is used to integrate Google maps in the application using GPS. This tracks the location of the user when the run begins.
2. Motion Sensor:
Step Detector is used as the motion sensor. This sensor is hardware based which uses the accelerometer and gyroscope of the device. We increment the value when the sensor detects a motion.
