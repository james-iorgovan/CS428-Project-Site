# Running The Project
# Project 1:
- Download the project files
- Open with Unity 2019.4.1 (be sure to also have Vuforia Engine installed in your Unity)
- Run the webcam
- Hold up at the camera:
  - The Drone - to see an alarm clock that displays the time
  - The Astronaut - to see a calandar displaying the date
  - The Fissure - to see a thermometer that displays the temperature as well as the humidity outside (Fissure note: you will need to sign-up for free at openweathermap in order to generate your own API key. This will allow you to get relevant data to your surrounding via a JSON file that one of the scripts I created in the Unity project reads).
  - The Oxygen - to see a windsock that [is supposed to] display the wind in mphs as well as the direction of the wind 
  
 # Project 2 (The Humanoid Animation):
- Download the project files
- Open with Unity 2019.4.1 (be sure to also have Vuforia Engine installed in your Unity)
- Click "Add" and find the project on your PC. Open it.
- Make sure you are running with the latest Vuforia (9.4.6) otherwise, the script will not work.
- Hold up at the camera:
    - The Astronaut - you will see a humanoid of myself in a room setting. . 
    - Press the virtual button.
    - The typing sound should stop, and the humanoid should start talking.
    - Let go of the virtual button and the talking should stop and typing resumes.

Project 2 (The LifeSize): Because the apk file is too large, I will take you through how to open it up.

- Go to File > Build Settings > Platform > Android/iOS
- Select to build only the SecondScene
- Select Build
- After this, you will get an apk if you are using Android or an ipo if you are using an iPhone (also, make not that your Unity engine must be iOS compatable which you
can do by applying the module under your Installations).
- After this, connect you phone to the laptop and unlock your phone. You will get a folder with your phone storage.
- Find your downloads folder and drag and drop the apk/ipo file into there.
- Disconnect the phone and go to you downloads folder. When selecting to open the file, you will get a message.
- Select install.
- Point your phone's camera near the ground (at first you might need to get close to the ground until you see a focus box appear).
- The life-size humanoid will then appear. You can see it typing and it will not move even if you walk around it.

