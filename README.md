## SIGNLY
The integration of a real-time sign language recognition system within a translation interface, aimed at bridging communication gaps for the hearing and speech-impaired through automated gesture-to-text conversion.
## About
Signly: AI-Powered Sign Language Translation Interface is a project designed to integrate a real-time gesture recognition system that leverages advanced computer vision and large language models (LLMs) to bridge the communication gap between sign language users and non-signers.

Traditional communication for the hearing and speech-impaired often relies on human interpreters or written notes, which can be slow and inaccessible in spontaneous environments. This project seeks to overcome these challenges by creating an easy-to-use, camera-based interface that assists users in translating signs into natural, contextually accurate text.

By utilizing MediaPipe for precise skeletal tracking and the Gemini 3 Flash model for linguistic interpretation, Signly streamlines the translation process, offering a fluid user experience that transforms visual gestures into meaningful conversation.

## Features
Implements Advanced Computer Vision & LLM Integration: Combines real-time skeletal tracking via MediaPipe with the generative power of the Gemini 3 Flash model for high-accuracy translation.

A Framework-Based Application for Seamless Deployment: Developed using the Streamlit framework, allowing the system to be deployed as a responsive web application accessible from any browser.

High Scalability & Real-Time Performance: Engineered to process video frames and landmark data efficiently, making it scalable for various sign language datasets and real-time usage.

Optimized Time Complexity: Utilizes lightweight, high-speed models (Gemini 3 Flash and MediaPipe) to ensure near-instantaneous translation with minimal processing lag.

## Requirements
### HARDWARE REQUIREMENT
Processor: Intel Core i5 (10th Gen) or Apple M1 Silicon for real-time video processing.
Memory: 8GB DDR4 RAM to handle multiple concurrent tracking threads.
Input Device: Integrated web cam of laptop , For PC external web cam or mobile phone connected via Camo cam/ Droid cam.
Storage: 500MB of local storage for the trained classifier and Python environment.
Connectivity: WiFi or Ethernet connection for real-time Gemini API communication.

### SOFTWARE REQUIREMENT
Operating System: Windows 10/11 or macOS Monterey+.
Language: Python 3.9 or higher for framework compatibility.
Core Libraries: OpenCV for video handling and MediaPipe for landmark extraction.
Development Environment: VS Code or PyCharm with a Virtual Environment.
Web UI: Streamlit for hosting the interactive translator dashboard.


## System Architecture

<img width="315" height="628" alt="image" src="https://github.com/user-attachments/assets/013ea914-d5b1-4072-8247-d0864a946731" />
<img width="700" height="366" alt="image" src="https://github.com/user-attachments/assets/daf893f1-ceeb-48d1-9f4f-75b4b57c5e6c" />
<img width="674" height="277" alt="image" src="https://github.com/user-attachments/assets/7aaa35f1-7d62-496b-a9c7-4b35a7ae557e" />
<img width="357" height="410" alt="image" src="https://github.com/user-attachments/assets/b18e11eb-5d3a-4b70-8387-aa5aed7a7008" />
<img width="651" height="287" alt="image" src="https://github.com/user-attachments/assets/51544e76-d36b-4959-85c8-93235d0b3b0b" />



## Output

<!--Embed the Output picture at respective places as shown below as shown below-->
#### Output1 - Name of the output

![Screenshot 2023-11-25 134037](https://github.com/<<yourusername>>/Hand-Gesture-Recognition-System/assets/75235455/8c2b6b5c-5ed2-4ec4-b18e-5b6625402c16)

#### Output2 - Name of the output
![Screenshot 2023-11-25 134253](https://github.com/<<yourusername>>/Hand-Gesture-Recognition-System/assets/75235455/5e05c981-05ca-4aaa-aea2-d918dcf25cb7)

Detection Accuracy: 96.7%
Note: These metrics can be customized based on your actual performance evaluations.


## Results and Impact
The Signly: Sign Language Translation Interface successfully bridges the communication gap by providing a real-time, automated bridge between visual gestures and spoken language. By converting complex signs into grammatically accurate text, the system enhances accessibility for individuals with hearing and speech impairments, providing a valuable tool for inclusive and independent communication in everyday settings.

The project’s integration of MediaPipe holistic tracking and the Gemini 3 Flash large language model showcases the immense potential for intuitive human-computer interaction. It demonstrates how modern AI can move beyond simple pattern recognition to provide context-aware, meaningful assistance that promotes digital and social inclusion.

This project serves as a foundation for future developments in assistive technologies and contributes to creating a more inclusive and accessible digital environment.

## Articles published / References
1.  B. Alsharif, E. Alalwany, A. Ibrahim, I. Mahgoub, and M. Ilyas, “Real-Time American Sign Language Interpretation Using Deep Learning and Keypoint Tracking,” Sensors, vol. 25, no. 7, p. 2138, Apr. 2025. DOI: 10.3390/s25072138.
2.  V. Ravikiran, “Real-Time Sign Language Recognition and Translation using MediaPipe and LSTM-Based Deep Learning,” International Journal of Computer Applications, vol. 187, no. 25, pp. 10–14, Jul. 2025.





