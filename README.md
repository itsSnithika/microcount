# 🦠Microcount  
**Embedded microscopy system for identification and counting of marine microogranisms** 
---

## 🚀 Project at a Glance  
🔬 Capture microorganisms with a **microscope camera**  
🤖 Detect & classify them in **real time using Edge AI**  
🌍 Enable **biodiversity monitoring** without internet/cloud dependency  
💡 Low-cost, portable, and rugged design for **field researchers**  

---

## ✨ Features  
- 📸 **High-Resolution Imaging** – Sony IMX477 (Raspberry Pi HQ Camera)  
- ⚡ **AI on the Edge** – Jetson Orin Nano runs detection + classification locally  
- 🌐 **Offline-First** – Works without cloud/internet  
- 💾 **Fast Storage** – 128GB NVMe SSD  
- 🛡️ **Ruggedized Enclosure** – Waterproof & shock resistant (IP65/IP67)  
- 🔄 **Federated Learning Ready** – Models improve collaboratively  
- 💰 **Affordable** – 10x cheaper than commercial microscopes  

---

## 🛠️ Hardware Setup  
- 🟢 **Jetson Orin Nano (8GB)**  
- 🔵 **Raspberry Pi HQ Camera (Sony IMX477)**  
- 🔍 Microscope optics + LED illumination  
- 💽 128GB NVMe SSD  
- 🔋 Battery / power module  
- 🟤 Waterproof rugged enclosure  

---

## 💻 Software Stack  

### 🖥️ Frontend (User Interaction)  
- 🌐 **React.js** – Dashboard for live monitoring  
- 📊 **Plotly.js / Chart.js** – Visualization of organism counts  
- 🎨 **TailwindCSS** – Clean & modern UI  
- 📱 Responsive design for field tablets & laptops  

### ⚙️ Backend (AI & Processing)  
- 🐍 **Python** – Core pipeline  
- 🔶 **TensorFlow / PyTorch** – Detection + classification models  
- 📸 **OpenCV** – Image preprocessing & ROI extraction  
- 🟢 **Flask / FastAPI** – API to connect frontend with Jetson backend  
- 🟦 **SQLite / Local DB** – Metadata & species storage  
- 🔄 **Flower / PySyft** – Federated learning integration (optional)

 




