
 PhysioPal — AI-Powered Remote Physiotherapy Assistant

PhysioPal brings professional physiotherapy guidance directly to users’ homes through AI-powered exercise analysis. Using computer vision and pose estimation, PhysioPal provides real-time feedback on posture, joint angles, and movement accuracy, helping users perform rehabilitation exercises safely without in-person supervision.

Designed for accessibility, PhysioPal works with a standard webcam and requires no additional sensors or wearables, making high-quality physiotherapy guidance available to anyone, anywhere.

Project Overview

PhysioPal analyzes human movement using pose estimation and biomechanical tracking to:
	•	Detect joint positions and angles
	•	Evaluate range of motion and symmetry
	•	Track repetitions and exercise quality
	•	Deliver real-time corrective feedback

By integrating Google’s Gemini API, PhysioPal also provides personalized exercise recommendations and adaptive progression guidance tailored to each user’s performance.

Key Features

	•	Real-time form correction using pose estimation
	•	Automatic rep tracking and movement segmentation
	•	Intelligent feedback based on joint-angle and biomechanical analysis
	•	Personalized exercise progression and recommendations
	•	Lightweight web interface for seamless user interaction
	•	No wearables or external sensors required

Technology Stack

	•	Python
	•	Streamlit — Web interface
	•	OpenCV — Video processing
	•	MediaPipe — Pose estimation and landmark detection
	•	Google Gemini API — Personalized feedback and recommendations

System Workflow

	1.	Webcam captures user exercise video
	2.	MediaPipe extracts body landmarks and joint positions
	3.	OpenCV processes frames and movement data
	4.	Joint angles and motion patterns are analyzed
	5.	Gemini API generates intelligent feedback and guidance
	6.	Streamlit displays real-time overlays, feedback, and recommendations

Project Goals

PhysioPal aims to:
	•	Improve adherence to home physiotherapy programs
	•	Reduce injury risk from improper exercise form
	•	Increase accessibility to supervised rehabilitation
	•	Demonstrate applied AI in healthcare technology

Devpost Link: https://devpost.com/software/physiopal-w89i2z
