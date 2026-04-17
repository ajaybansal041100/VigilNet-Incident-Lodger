🚨 VigilNet: Real-Time Women Safety Alert & Incident Logger
📌 Overview

VigilNet is an intelligent Android-based emergency response system designed to provide instant assistance during critical situations. It enables users to trigger SOS alerts, share real-time location, and automatically record audio/video evidence.

The system works even in low or no internet conditions using SMS-based alerts, making it highly reliable in emergencies.

🎯 Key Features
🚨 SOS Trigger Mechanisms
One-tap SOS button
Home screen widget
Shake gesture detection
📍 Real-Time Location Tracking
Sends GPS location via SMS
Includes Google Maps link for tracking
📩 Offline Emergency Alert
SMS-based alert system (works without internet)
🎥 Automatic Evidence Collection
Continuous audio recording
Segmented video recording using CameraX
☁️ Cloud Storage Integration
Firebase Firestore (incident logs)
Firebase Storage (audio/video files)
🔄 Live Incident Monitoring
Real-time location updates
Timestamped logs and metadata
🏗️ System Architecture
User → SOS Trigger → SOS Engine → Background Services → Firebase + SMS
Modules:
Frontend (Jetpack Compose)
SOS Engine (Core Logic)
Background Services:
SMS Service
Location Tracking
Audio Recording
Video Recording
Firebase Backend
🛠️ Tech Stack
📱 Frontend
Kotlin
Jetpack Compose
Android SDK
⚙️ Backend
Firebase Firestore
Firebase Storage
📦 Libraries & APIs
CameraX API
MediaRecorder
SMS Manager API
Fused Location Provider
📲 How It Works
User triggers SOS (button / widget / shake)
System generates unique incident ID
Sends SMS alert with location
Starts:
📍 Location tracking
🎤 Audio recording
🎥 Video recording
Uploads data to Firebase
Emergency contacts receive alert instantly
⚡ Performance Highlights
Feature	Performance
SMS Sending	< 0.5 sec
Location Fetch	< 200 ms
Firestore Write	~300–500 ms
Video Recording	60-sec segments
System Stability	No crashes
🔐 Permissions Required
Location (GPS)
SMS
Camera
Microphone
Contacts
⚠️ Challenges & Limitations
Android background restrictions
High battery consumption during SOS
Internet required for cloud uploads
Device-specific behavior variations
Cannot fully record video when device is locked
🔮 Future Scope
🤖 AI-based violence/sound detection
⌚ Wearable device integration
🧠 ML-based automatic SOS detection
🔐 End-to-end encryption
🚓 Police/emergency dashboard integration
👨‍💻 Contributors
Ajay Bansal
Anurag Singh Bhadoriya
Abhay Patel
Anuranjan Singh Chauhan
📌 Conclusion

VigilNet transforms smartphones into a powerful personal safety tool by combining:

Real-time alerts
Evidence collection
Cloud storage
Offline reliability
