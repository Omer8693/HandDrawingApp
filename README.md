# Real-Time Gesture-Controlled Drawing Interface 🎨✋

This project is a real-time gesture-controlled drawing and screen control interface powered by **MediaPipe** and **OpenCV**. Users can draw, erase, change brush thickness, switch themes, save, load, clear the canvas, and navigate UI icons — all through predefined hand gestures.

 🚀 Features
- **9 predefined gestures** mapped to specific commands:
  - **Index finger up** → Drawing mode
  - **Index + middle fingers up** → Eraser mode
  - **Index + middle + ring fingers up** → Switch to drawing mode
  - **All fingers open** → Change theme (White, Gray, Black)
  - **Thumb up** → Adjust brush thickness
  - **Thumb + pinky up** → Save drawing
  - **Middle + ring + pinky up** → Load drawing
  - **Fist (all fingers closed)** → Clear canvas
  - **Index + middle fingers closed** → UI icon navigation (Click)

- **Real-time performance** (25+ FPS)
- **Tested under three lighting conditions** (Bright, Normal, Dim)
- **Optional keyboard controls** for saving, loading, and thickness adjustment

📂 Project Structure
- **HandDrawingApp.ipynb** → Interactive gesture-based drawing application
- **GestureTrainer.ipynb** → Performance testing under various lighting conditions
- **data/** → JSON files with performance measurements
- **saved_drawings/** → Stored drawings

 🛠 Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/username/repository-name.git
   cd repository-name
   ```
2. Install dependencies:
   ```bash
   pip install opencv-python mediapipe jupyter
   ```
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open and run `HandDrawingApp.ipynb`.

🎯 Usage
- Make sure your webcam is enabled.
- Hold your hand in front of the camera and perform a gesture.
- The drawing canvas will respond to your gesture in real-time.

📊 Performance
- **FPS**: 25–33 across all gestures
- **Fastest recognition**: 1.6s (Click gesture)
- **Stable performance** across bright, normal, and dim lighting conditions

