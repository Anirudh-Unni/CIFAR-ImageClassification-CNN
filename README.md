# 🧠 Image Classification with CNN and Transfer Learning

This project explores **image classification** on the **CIFAR-10 dataset** using two approaches:  
1. A **Custom CNN built from scratch**  
2. **Transfer Learning** with pre-trained models  

We compare performance, training times, and trade-offs between the two approaches.  

---

## 📂 Project Structure
- `ProjectCifar.ipynb` → Main notebook with all experiments  
- `README.md` → Project documentation (this file)  

---

## 📊 Dataset
- **CIFAR-10**:  
  - 60,000 color images (32×32 pixels)  
  - 10 categories: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck  
  - Train set: 50,000 images, Test set: 10,000 images  

---

## ⚙️ Methods
1. **Custom CNN**  
   - Several convolutional + pooling layers  
   - Flatten → Dense → Output  
   - Trained from scratch  

2. **Transfer Learning**  
   - Used pre-trained models (e.g., MobileNet with different training layers)  
   - Fine-tuned on CIFAR-10 dataset  
   - Faster convergence and improved accuracy  


## 📦 Requirements
Install dependencies with:  
```bash
pip install -r requirements.txt
