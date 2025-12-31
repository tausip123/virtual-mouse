# virtual-mouse
operate your mouse using your hand gestures

A gesture-controlled virtual mouse that allows users to control cursor movement, clicks, scrolling, and zooming using hand gestures captured via a webcam. This project uses MediaPipe Hands for real-time hand tracking and PyAutoGUI to simulate mouse actions.

*Features:*
1. Real-time hand tracking
2. Smooth cursor movement using index finger
3. Left click, right click & double click
4. Scroll using finger movement
5. Zoom in / Zoom out gestures
6. Click cooldown to prevent false clicks
7. Works on any screen resolution

*How It Works:*
1. Captures video using webcam
2. Detects hand landmarks using MediaPipe
3. Maps finger positions to screen coordinates
4. Identifies gestures using finger distance & clenched state
5. Executes mouse actions using PyAutoGUI
6. Applies smoothing & timing logic for stability.

*Limitations:*
1. Requires good lighting
2. Single-hand tracking only
3. Webcam latency may affect smoothness.

*Future Improvements:*
1. Multi-hand support
2. Custom gesture mapping
3. Gesture calibration mode
4. On-screen gesture indicators
5. AI-based gesture classification

pip install -r requirements.txt

