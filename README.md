# OpenCV-Mediapipe-with-Thread

OpenCV's screen capture is based on I/O, I move I/O to threads to get higher FPS.

This project can be linked to my senior project, so I made this project to compare the FPS difference of whether to move to the thread, and the implementation isMediaPipe Hand with Thread and MediaPipe Hand without Thread.

There is a significant difference in FPS between the two, since the coordinate point data of Mediapipe is updated according to each frame, as shown below, as the number of frames increases, the frequency of data generated to be passed to Unity will also increase, which can effectively reduce delays
