# 🧘 Posture Detection & AI Feedback System

An intelligent real-time posture monitoring system that uses **Computer Vision** to detect body alignment and provide **AI-driven feedback** to improve ergonomics and prevent long-term health issues.

## 🌟 Key Features

- **Real-time Detection:** High-speed pose tracking using MediaPipe.
- **Posture Classification:** Specifically identifies "Good Posture" vs "Warning/Bad Posture" based on shoulder and back alignment.
- **AI Feedback:** Integrated `ai_feedback.py` to provide intelligent suggestions for correction.
- **Visual Analytics:** Includes `analyze_results.py` to process session data and visualize improvements.
- **Web Demo:** Includes an HTML interface for easier interaction.

## 📂 Project Structure

- `main.py`: The entry point of the application.
- `detector.py`: Handles the core pose estimation and landmark detection.
- `posture_classifier.py`: Contains the logic for categorizing posture based on skeletal angles.
- `ai_feedback.py`: Processes detection data to generate user-friendly correction tips.
- `utils.py`: Helper functions for image processing and calculations.
- `analyze_results.py`: Tools for post-session data analysis and reporting.
- `web_demo.html`: A lightweight web interface to showcase the system.

## 🛠️ Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/merhanhossam-coder/posture-detection.git](https://github.com/merhanhossam-coder/posture-detection.git)
   cd posture-detection


