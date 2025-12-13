### 3D Hand Tracking

![3D hand tracking screenshot](./3d_hand_tracking.png)


A ```threejs``` / ```WebGL``` / ```MediaPipe```-powered interactive web-application that allows user to control a 3D sphere using hand gestures.


#### Gestures

- **Left hand gesture control:** Pinch thumb and index finger to resize the 3D sphere
- **Right hand interaction:** Touch the sphere with your index finger to change its color

### Setup for Development

Navigate to the project sub-folder in terminal:
```bash
cd 3d_hand_tracking
```

In the terminal, type below command:
```bash
python3 -m http.server
```
Use the browser and go to:
```bash
http://localhost:8000
```
Note: Please clear your browser cache before entering the address.


## Requirements

- Modern web browser with WebGL support
- Camera access

## Technologies

- **Three.js** for 3D rendering
- **MediaPipe** for hand tracking and gesture recognition
- **HTML5 Canvas** for visual feedback
- **JavaScript** for real-time interaction