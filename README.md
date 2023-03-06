# Virtual-Mouse
A machine learning project based on python libraries, mediapipe and opencv. A virtual hand gesture mouse, that allows users to control a computer mouse using hand gestures instead of a physical mouse. 

# Description
The system uses computer vision and motion tracking technology to interpret the movements of the user's hand and translate them into mouse commands. It can also be used in situations where a physical mouse is not available or practical, such as in virtual reality or augmented reality environments.

# Hand Landmark Model
A hand landmark model is a machine learning model that is trained to identify and locate specific points or landmarks on a human hand in an image or video. These landmarks correspond to anatomical features of the hand such as the fingertips, knuckles, and wrist, and their precise locations can be used to track the movements and gestures of the hand.

![image](https://user-images.githubusercontent.com/116565203/223192726-9504f04f-7461-40a6-b00e-a179e7a6f321.png)

# Features
1. Click or select files.
2. Drag and drop operation.
3. Increase or decrease volume.
4. Scroll pages, file or folders vertically
5. Zoom in and out webpages.

# How to use
1. Install the following libraries from [requirements](https://github.com/Sampreet-cell/Virtual-Mouse/blob/main/requirements.txt).
1. Run the file named [master](https://github.com/Sampreet-cell/Virtual-Mouse/blob/main/master.py).
2. The camera will open and then we can make different hand gestures to operate the cursor.
## Hand Gestures
1. This gesture will keep the cursor at rest.

![rest](https://user-images.githubusercontent.com/116565203/223194105-ef1bd390-a32f-448d-a4ec-daf5851a2b79.jpg)

2. This gesture will move the cursor, when we move our hand.
3. We can perform the left click or single click function by lowering our index finger, while doing this hand gesture.
4. We can perform the right click function by lowering our middle finger, while doing this hand gesture.
5. We can perform double click function by closing the gap between the two fingers or joining the index and middle finger, while doing this hand gesture.

![control and click](https://user-images.githubusercontent.com/116565203/223197255-434f7bd5-baeb-41ea-a6f8-c4477d7d691e.jpg)

6. When we do this gesture and move our hand, while our cursor is on any selected file(s). It will move the file(s), for eg. drag and drop operation. This is used to copy any file or folder from one place to another.

![grab](https://user-images.githubusercontent.com/116565203/223200008-cc3d104c-5639-4b1f-98de-e372c058a6bc.jpg)

7. To increase or decrease the system volume, we can do this gesture with our right hand and move it vertically (upward-increase or downward-decrease).
8. To scroll, we can do this gesture with our left hand and move it vertically(upward-scroll up or downward-scroll down).
9. To zoom in or out any page, we can do this gesture with our left hand and move it horizontally(left-zoom in and right-zoom out).

![vertical scroll, change volume   zoom in-out](https://user-images.githubusercontent.com/116565203/223200155-b962d635-1bbf-4210-a333-27c26277f615.jpg)

# Things needed to be fixed
1. Cursor sensitivity and reaction time.
2. Gesture to ncrease or decrease the system brightness.
3. Resolving the bug in the volume operation

P.S:- The following python programming is referenced from multiple resources including the mediapipe documentation.
