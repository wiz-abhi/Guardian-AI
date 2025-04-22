# 🛡️ GuardianAI – Smart AI-Powered Surveillance System  
**Real-time Detection | Women Safety | Emergency Alerts | Deep Learning Intelligence**

---

## 🚨 About GuardianAI
GuardianAI is an AI-powered smart surveillance system built to transform traditional security cameras into real-time, proactive safety agents.  

From detecting emergencies like falls, violence, and stalking to ensuring women’s safety through intelligent gesture and sound detection, GuardianAI automates vigilance and sends instant alerts — potentially saving lives.

---

## 💡 Core Features

### 🎥 Live Video Stream Integration
- Supports Webcams, IP Cameras (RTSP/HTTP), and Mobile Streaming apps (DroidCam / IP Webcam).
- Robust stream handling, connection retries, and error logging.

---

### 🧍‍♂️ Real-Time Person Detection & Tracking
- Detects humans using **YOLOv8** for high-speed precision.
- Tracks individuals with **Deep SORT** across frames.
- Assigns unique IDs for event logging.

---

### ⚠️ Emergency Detection Suite
- **Fall Detection:** Uses **MediaPipe Pose** to identify falls and motionless postures.
- **Basic Violence Detection:** Heuristic-based movement and bounding box analysis.
- **Distress Sound Detection:** Recognizes sounds like:
  - Screams
  - Gunshots
  - Glass breaking  
*(via Librosa + VGGish or TensorFlow Audio models)*

---

### 🔍 Suspicious Behavior Analysis
- **Loitering Detection:** Alerts if a person lingers too long in a sensitive zone.
- **Unattended Object Detection:** Identifies new static objects like abandoned bags.
- **Unusual Movement Detection:** Flags erratic pacing and unnatural movement patterns.
- **Stalking/Approach Detection:** Warns if someone persistently follows another individual.

---

### 🧡 Women Safety Features
- **Panic Gesture Detection:** Identifies emergency hand signals like the silent "Help me" sign.
- **Distress Audio Detection:** Detects urgent calls for help.
- **Geo-Fence Alert:** Optional zone-based escape detection.
- **Snapshot-Enabled Alerts:** Attaches images to every alert for quick verification.

---

### 🌍 Advanced AI Intelligence (Post-MVP Expansion)
- **Deep Learning-Based Violence Recognition:**  
Leverages action recognition models like **I3D** or **SlowFast** trained on surveillance datasets to accurately distinguish real fights from casual movements.
  
- **Crowd Panic and Stampede Prediction:**  
Detects sudden crowd surges, rapid group movement, and possible panic situations using heatmaps and flow analysis.

---

### 📢 Smart Alerts & Event Logging
- Real-time notifications via:
  - 📧 Email (SendGrid)
  - 📱 SMS (Twilio)
  - 💬 WhatsApp (optional).

- Event logs include:
  - Timestamp
  - Camera ID
  - Event Type
  - Snapshot Evidence.
  
- Storage:
  - Local Files
  - SQLite / PostgreSQL Database.

---

### 💻 Web Dashboard
- Live video feed viewer.
- Event logs with search & filter.
- Video snippet playback.
- Mobile-friendly + Dark Mode.

---

## 🧑‍💻 Tech Stack
- **Language:** Python  
- **Libraries:** OpenCV, YOLOv8, Deep SORT, MediaPipe, PyTorch, TensorFlow.  
- **Notifications:** Twilio, SendGrid.  
- **Dashboard:** Flask + Bootstrap / React + FastAPI.  
- **Database:** SQLite / PostgreSQL.

---

## 🔥 Use Cases
- Women’s Hostels & PGs  
- Offices & Workspaces  
- Schools, Hospitals & Public Spaces  
- Apartments, Malls, Parking Lots.

---

## 📌 Project Status
| Stage | Feature                             | Status  |
|-------|-------------------------------------|---------|
| 1     | Camera Integration & Streaming      | ✅ Completed |
| 2     | Person Detection & Object Tracking  | ✅ Completed |
| 3     | Emergency Detection Suite           | ⚡ In Progress |
| 4     | Suspicious Behavior Detection       | ⚡ In Progress |
| 5     | Smart Alerts & Logging              | ⚡ In Progress |
| 6     | Deep Learning Violence Detection    | 🧠 Planned |
| 7     | Crowd Panic Prediction              | 🧠 Planned |

---

## 🤝 Contributing
Pull requests and feature suggestions are welcome! Whether you're improving detection, enhancing the dashboard, or expanding real-time alerts — collaboration is the heart of this project.

---

## 📸 Demo Ready
Record test scenarios like falls, fights, and suspicious behaviors with a smartphone as a CCTV input.  
Includes offline video support for hackathon presentations.

---

## 🏆 Mission
_“GuardianAI is not just about security — it's about creating a safer world for everyone, especially women, when human eyes can't watch.”_

---

