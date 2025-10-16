# Brain Tumor Detection Using Deep Learning on MRI Images

### Project Overview
This project focuses on **automatic detection of brain tumors** using deep learning techniques applied to **MRI images**.  
It leverages both a **custom-built Convolutional Neural Network (CNN)** and **transfer learning** with **ResNet50** and **EfficientNetB0** to classify MRI scans as either **Tumor** or **No Tumor**.

The project demonstrates how **AI and medical imaging** can work together to support radiologists, accelerate diagnosis, and improve accuracy in early-stage tumor detection.

---

## Dataset

**Source:** [Brain MRI Images for Brain Tumor Detection (Kaggle)](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection)  
**Creator:** Navoneel Chakrabarty  

The dataset contains MRI images categorized as:
- `Tumor`
- `No_Tumor`

**Dataset Structure:**
```bash
dataset/
│
├─ BT_training/
│ ├─ Tumor/
│ └─ No_Tumor/
│
├─ BT_validation/
│ ├─ Tumor/
│ └─ No_Tumor/
│
└─ BT_testing/
├─ Tumor/
└─ No_Tumor/
```
**Total Images:** 192  
- Training: 152 images  
- Validation: 20 images  
- Testing: 20 images  

---

## 💻 How to Run the Project

### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/brain-tumor-detection.git
cd brain-tumor-detection
```
2. Install Dependencies
```bash
pip install -r requirements.txt
```
3. Prepare Dataset
Download the dataset from Kaggle and organize it as per the directory structure shown above.

4. Run Training Script
```bash
python main.py
```

---

🧑‍💻 Author
👩‍🎓 Tanisha Thakur
📧 tanishaselfthakur@gmail.com


