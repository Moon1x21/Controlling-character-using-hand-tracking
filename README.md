# HandTracking

Using [Mediapipe](https://google.github.io/mediapipe/solutions/hands.html) we calculate hand vector.<br />
Hand vector is used as the character movement.<br />
Also, for making more stable movement, user's hand position is adjusted using the previous hand position. Moreover, user's hand position is set as the previous position to reduce the tracking failure problem.

