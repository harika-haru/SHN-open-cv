![Open CV Github Frame](https://github.com/TH-Activities/saturday-hack-night-template/assets/90635335/78554b37-32b2-4488-a10c-5c68098d7776)



# Project Name: Face Detection 
A face detection project using OpenCV often starts by accessing frames from a video source, like a webcam or a video file. Once a face is detected, a common practice is to draw a green rectangle around the detected face region to visually highlight it.
## Team members
1. [Arathi Krishna A M](https://github.com/arathikrishnaam/arathikrishnaam)
## Link to product walkthrough
[link to video]([Link Here](https://drive.google.com/drive/folders/1UpM5eiwZMuaTgtIPczse3h9jQwFiEIUp?usp=drive_link))
## How it Works ?
1. In a face detection project using OpenCV, the initial phase involves setting up the video source, like a webcam or video file, for frame processing. Upon detecting a face, the system marks it by drawing a green bounding box around the detected face coordinates using OpenCV's drawing functions. The modified frame, now with highlighted faces, is displayed in a window, allowing real-time visualization of the face detection process.
2. Embed video of project demo: https://drive.google.com/drive/folders/1UpM5eiwZMuaTgtIPczse3h9jQwFiEIUp?usp=drive_link
## Libraries used
1. pip install opencv-python
2. pip install opencv-contrib-python
## How to configure
1. Install OpenCV: Use pip to install the OpenCV library. Run pip install opencv-python or pip install opencv-python-headless if you don't need GUI support.
2. Webcam Access: If using a webcam, ensure it's connected and recognized by your system. OpenCV typically accesses the default webcam with index 0. Check if the webcam works by running simple OpenCV scripts to access the webcam and display the feed.
3. Test and Debug: Run the code and test the face detection functionality.
## How to Run
python3 face-reco.py
