# 🦁 Wild Mimic: AI Pose Recognition System
**Wild Mimic** is a real-time computer vision application that bridges the gap between biological motion and digital response. Built with a high-fidelity "Cyber City" interface, it utilizes deep learning to map human facial expressions and body gestures to a database of wild animal reactions instantly.


## 📖 About The Project
This project explores **Human-Computer Interaction (HCI)** through the lens of non-verbal communication. By leveraging Google's **MediaPipe Holistic** pipeline, the application performs simultaneous pose, face, and hand tracking directly in the web browser.
Unlike traditional applications that rely on mouse or keyboard inputs, Wild Mimic creates a **Zero-Touch Interface**, translating the user's physical state into digital commands in real-time. It demonstrates how complex AI models can be optimized for client-side performance, ensuring privacy by keeping all video processing local to the user's machine.


## 🔮 Why This Project? (The Vision)
While currently deployed as an interactive pose-matching engine, the core architecture of Wild Mimic serves as a **Proof of Concept for Touchless Ambient Computing**.

**The Future Application:**
As we transition into the era of **Smart Cities** and **Augmented Reality (AR)**, physical touchscreens will become obsolete. We are moving toward an "Invisible Interface" where our environment reacts to our natural movements.
Imagine a hospital where surgeons control robotic arms via hand gestures to maintain sterility, or a smart home where looking at a light and raising a hand adjusts the brightness. Wild Mimic demonstrates the foundational technology required for this future: **interpreting human intent from raw video data without wearable hardware.** This project is a step toward making the "Jarvis-like" interfaces of science fiction a reality.


## 🛠️ Tech Stack
* **Core Logic:** JavaScript (ES6+)
* **Computer Vision:** MediaPipe Holistic (Deep Learning Landmark Detection)
* **Frontend UI:** HTML5 & CSS3 (Custom Cyberpunk/Glassmorphism Design)
* **Rendering Engine:** HTML5 Canvas API (Vector Skeleton Drawing)
* **Mathematics:** Euclidean Geometry & Vector Analysis (For gesture calculation)


## 🚀 Key Features
* **Multi-Modal Tracking:** Simultaneously tracks 543 distinct landmarks (33 body, 21 per hand, 468 face).
* **Zero-Latency Response:** Optimized algorithm ensures instant feedback (<15ms processing time).
* **Privacy-Centric:** No backend server required; video data never leaves the user's device.
* **Dynamic Visuals:** Futuristic UI with CRT scanline effects, neon glow, and holographic panels.


## ⚙️ How to Run on Your System
Since this project requires access to the **Webcam API**, modern browsers enforce security protocols (CORS) that prevent it from running by simply double-clicking the HTML file. You must serve it via a local host.


### Prerequisites
1.  A modern web browser (Chrome, Edge, Firefox).
2.  A working webcam.
3.  **Python** installed on your system (Recommended for the easiest setup).


### Execution Steps
**Step 1: Clone or Download**
Download the project folder to your local machine.
**Step 2: Open Terminal**
Open your Command Prompt (Windows) or Terminal (Mac/Linux) and navigate to the project directory:
cd path/to/your/folder
**Step 3: Start Local Server**
Run the following command to start a simple Python HTTP server:
python -m http.server 8000
(If that command doesn't work, try python3 -m http.server 8000)
**Step 4: Access the Interface** 
Open your web browser and type the following address into the URL bar:
http://localhost:8000
The application should load, and your browser will ask for camera permission. Click Allow to begin.


### 🕹️ Gesture Guide
The system utilizes a geometric logic engine to detect specific pose combinations. Try these gestures to trigger the AI:
I will first tell pose name:how to make it work(action required):-
1. Peace: Show a peace sign (V) with one hand.
2. Double Peace: Show peace signs with both hands.
3. Play Time: Raise both hands high above your head.
4. Smiling: Smile widely (ensure teeth are visible or maybe no need in some cases).
5. Funny: Stick your tongue out (medium mouth opening).
6. Yawn: Open your mouth vertically wide.
7. Scared: Put hands on cheeks and open your mouth.
8. Sorry: Hold your ears (or place hands near ears).
9. Stop: Show an open palm extended toward the camera.
10. Cutie: Place one hand gently against your cheek.

Contact: For questions, feedback, or collaboration inquiries, you can reach out to me!!!