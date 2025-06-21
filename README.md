# 🧠 Mind-Wandering Detection using YOLOv8

This project is part of my research internship at **IIT Roorkee**, focusing on detecting mind-wandering (MW) and attention-related visual cues using **YOLOv8**. It leverages real-time video input to identify behavioral indicators of distraction such as eye closure, gaze deviation, and head tilting.

---

## 🎯 Project Goal

To develop a non-invasive, real-time visual system for identifying cognitive states like:
- **Mind-Wandering (MW)**
- **Focused Attention**

This is the first stage of a larger project, which includes Transformer-based temporal modeling in later phases.

---

## 🔧 Tech Stack

| Component     | Details                          |
|---------------|----------------------------------|
| Model         | YOLOv8 (Ultralytics)             |
| Language      | Python                           |
| Frameworks    | PyTorch, OpenCV                  |
| Dataset       | Roboflow (Drowsy Driver Dataset) |
| IDE           | VS Code                          |
| Versioning    | Git + GitHub                     |

---

## 📁 Dataset

- Source: Roboflow
- Classes: `eye_closed`, `looking_away`, `head_down`
- Format: YOLOv5 PyTorch
- Preprocessed using Roboflow export tools

📦 Dataset Link : [Google Drive Dataset](https://drive.google.com/drive/folders/1FnoCi-zglkQdI-HNdjWcg1_wbU_G6fOt?usp=sharing)

---

## 🚀 How to Run

### 1. Clone the repo and set up your environment

```bash
git clone https://github.com/mimansa566/mindwandering-yolo.git
cd mindwandering-yolo
python -m venv venv
venv\Scripts\activate
pip install ultralytics opencv-python
