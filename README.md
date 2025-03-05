


Gesture Controlled Virtual Mouse makes human computer interaction simple by making use of Hand Gestures and Voice Commands. The computer requires almost no direct contact. All i/o operations can be virtually controlled by using static and dynamic hand gestures along with a voice assistant. This project makes use of the state-of-art Machine Learning and Computer Vision algorithms to recognize hand gestures and voice commands, which works smoothly without any additional hardware requirements. It leverages models such as CNN implemented by [MediaPipe](https://github.com/google/mediapipe) running on top of pybind11. It consists of two modules: One which works direct on hands by making use of MediaPipe Hand detection, and other which makes use of Gloves of any uniform color. Currently it works on Windows platform.


# Getting Started

  ### Pre-requisites
  
  Python: (3.6 - 3.8.5)<br>
  Anaconda Distribution: To download click [here](https://www.anaconda.com/products/individual).
  
  ### Procedure
  ```bash
  git clone https://github.com/xenon-19/Gesture-Controlled-Virtual-Mouse.git
  ```
  For detailed information about cloning visit [here](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository-from-github/cloning-a-repository).
  
  Step 1: 
  ```bash
  conda create --name gest python=3.8.5
  ```
  
  Step 2:
  ```bash
  conda activate gest
  ```
  
  Step 3:
  ```bash
  pip install -r requirements.txt
  ```
  
  Step 4:
  ```bash 
  conda install PyAudio
  ```
  ```bash 
  conda install pywin32
  ```
  
  Step 5:
  ``` 
  cd to the GitHub Repo till src folder
  ```
  Command may look like: `cd C:\Users\.....\Gesture-Controlled-Virtual-Mouse\src`
  
  Step 6:
  
  For running Voice Assistant:
  ```bash 
  python Proton.py
  ```
  ( You can enable Gesture Recognition by using the command "Proton Launch Gesture Recognition" )
  
  Or to run only Gesture Recognition without the voice assisstant:
  
  Uncomment last 2 lines of Code in the file `Gesture_Controller.py`
  ```bash 
  python Gesture_Controller.py
  ```
  

  
