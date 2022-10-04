# HandTracking

Using [Mediapipe](https://google.github.io/mediapipe/solutions/hands.html) we calculate hand vector.<br />
Hand vector is used as the character movement.<br />
![image](https://user-images.githubusercontent.com/62733294/193873019-c27d632d-a68c-441b-bca5-db63491138f1.png)
Also, for making more stable movement, user's hand position is adjusted using the previous hand position. Moreover, user's hand position is set as the previous position to reduce the tracking failure problem.

