# HandGestureVolumeControl
Control your system's volume by only using your hand gestures.


save both the files in the same folder as HandTrackingModule will be imported in the VolumeHandControl

Instructions :- This code will work for commands given from right hand as the mediapipe library gives landmarks for the right hand

AIM :- In this project, we will change the volume level of our system using our 3 fingers.

Procedure :- When we will lift our little finger and change the distance between Thumb and it's adjacent finger, system volume will start changing
             TO CHANGE VOLUME :- Lift your little finger up, move your thumb and it's adjacent finger
             TO FIX VOLUME    :- Down your little finger then the volume will not change.
             
Here little finger acts like a switch.

WORKING IN BRIEF :- 

We imported mediapipe library for direct hand landmarks ( 20 points on palm ).
Mediapipe is a ML based framework, which gives us directly the hand landmarks from the image captured from webcam

The distance between 2 specific landmarks is calculated
Those 2 landmarks are tip of thumb and tip of it's adjacent finger, and based on that distance, volume ratio is adjusted

I have mentioned everything in form of comments in my code.

Working in light
![IMG1](https://user-images.githubusercontent.com/75074493/176865650-9b60d847-476d-4102-ad18-b161caab9ff6.jpeg)

Working in dark 
![Test_3](https://user-images.githubusercontent.com/75074493/176866020-339df4d2-b99a-4ae6-b6f6-9220b88976ef.jpeg)
