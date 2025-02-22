# AI-7
How Far AI Change The World 


**Object Detection Navigation Aid for Visually Impaired People**

This project is a real-time object detection navigation assistant designed to help visually impaired individuals move safely. It uses a smartphone’s back camera to detect objects in the environment and provides audio guidance based on detected obstacles.

**Features**

Real-Time Object Detection: Uses TensorFlow.js and the COCO-SSD model to detect objects instantly.

Directional Guidance: Provides instructions like "Turn left," "Turn right," or "Obstacle ahead, be careful!" based on object positions.

Voice Feedback: Uses text-to-speech (TTS) to inform users about detected obstacles.

Optimized Performance: Uses requestAnimationFrame() for faster and smoother object detection without delay.

Works on Mobile: Designed to run directly in a web browser on a smartphone, using the rear camera.


**How It Works**

1. The device accesses the camera and starts detecting objects in real time.


2. The AI determines whether obstacles are on the left, right, or center.


3. If an object is blocking the path, the system announces a safe direction to move.


4. Users hear clear audio guidance for safe navigation.



**Usage**

Simply open the web page on a smartphone, allow camera access, and start moving. The system will guide you safely based on detected objects.

This tool is developed to improve accessibility and assist visually impaired individuals in navigating their surroundings safely.




