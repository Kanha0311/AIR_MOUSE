Air Mouse Project (Python)

This project turns your hand into a virtual mouse using a webcam. It tracks your hand in real time with MediaPipe and uses OpenCV to process the video feed. PyAutoGUI handles the actual mouse movements, clicks, and scrolling.

When you raise just your index finger, the cursor moves with your finger. Showing all five fingers performs a left-click, two fingers scroll down, and three fingers scroll up. The camera captures hand landmarks and maps their positions to screen coordinates for smooth control.

It’s a simple yet fun example of computer vision and automation — no physical mouse needed, just your hand and a webcam.
🖐️ Gesture Controls
Gesture	Fingers Up	Action
☝️ Index finger	1	Move mouse cursor
🖐️ All fingers	5	Left click
✌️ Index + Middle	2	Scroll down
🤟 Index + Middle + Ring	3	Scroll up
