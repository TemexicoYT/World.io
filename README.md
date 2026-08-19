#World.io
Releasing Dec 26, 2026
# 🎮 world.io

Here is the JavaScript code used to add the pictures and videos into the game:

```javascript
// 1. THIS ADDS THE PICTURE INSIDE THE CODE
const myPicture = new Image();
myPicture.src = 'IMG_4077.jpeg'; 
document.body.appendChild(myPicture);

// 2. THIS ADDS THE VIDEO INSIDE THE CODE
const myVideo = document.createElement('video');
myVideo.src = 'ScreenRecording_08-17-2026 13-43-19_1.mov'; 
myVideo.controls = true;
document.body.appendChild(myVideo);
```
