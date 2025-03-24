

---

# **Brain Tumor Detection using CNN**

## **Description**  
This project is a **Brain Tumor Detection System** using **Convolutional Neural Networks (CNNs)**. It processes **MRI images** to classify them as **Tumor** or **No Tumor**, assisting in early diagnosis.  

### **Key Features**
- Accepts **MRI images** as input.  
- Uses a **CNN model** for classification.  
- Provides **high accuracy** in detecting brain tumors.  
- Can be deployed as a **desktop or web application**.  

---

## **Installation**  

### **1. Clone the repository**
```bash
git clone https://github.com/prachimahindrakar1/braintumor.git
cd braintumor
```

### **2. Create a virtual environment (optional but recommended)**
```bash
python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate  # On Windows
```

### **3. Install dependencies**
```bash
pip install -r requirements.txt
```

### **4. Run the model**
```bash
python predict.py --image sample_mri.jpg
```

---

## **Usage**
- Upload an MRI image to the system.  
- The model will classify it as **Tumor** or **No Tumor**.  
- The result will be displayed along with a **confidence score**.  

---

## **Future Enhancements**
- **Multi-class classification** (detect different types of tumors).  
- **Web-based deployment** for easy accessibility.  
- **Integration with hospital databases** for real-world application.  

---

### **Contributions**
Feel free to open **issues** or **pull requests** for improvements.  

---

This README provides all necessary details for anyone to install and use your project. 
