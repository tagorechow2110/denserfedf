# 🚚 Denser SCM Platform  
### AI-Powered Global Logistics Comparison, Tracking & Analytics

The **Denser SCM Platform** is a modern, AI-driven logistics interface that allows users to:

- Compare 100+ carriers with Denser AI Score  
- Track shipments with real-time timeline simulation  
- Generate logistics documents using AI  
- View carrier performance analytics  
- Book shipments with Firebase-backed storage  

This project uses **TailwindCSS**, **Firebase**, and **Gemini AI API** to deliver an intuitive, high-performance logistics platform.

---

## 🌟 Features

### 🔎 1. Multi-Carrier Comparison Engine  
- Enter pickup pin, delivery pin & package type  
- Compare carriers based on:
  - Cost  
  - Speed  
  - Reliability  
  - **Denser AI Score (weighted ranking)**  
- AI Recommendation using Gemini API  
- Auto-generated insight card for best option  

---

### 📦 2. Shipment Booking  
- Books shipment inside Firestore:
  - User ID  
  - Carrier  
  - Cost  
  - Speed  
  - Route details  
  - Timestamp  
- Auto-generates **unique Denser Tracking ID**

---

### 🚛 3. Universal Tracking System  
- Track any shipment by entering ID  
- Displays:
  - Current status  
  - Carrier  
  - Predicted ETA  
  - Timeline with events  
- Mocked live update simulation for demo mode  

---

### ✨ 4. AI Document Drafting  
- Generates:
  - Delay emails  
  - Customs descriptions  
  - Logistics communication drafts  
- Uses Gemini AI API  
- Clean formatting & responsive UI  

---

### 📊 5. Analytics Dashboard  
Shows summary metrics:
- Overall OTD (On-Time Delivery) rate  
- Average cost per shipment  
- Performance scorecard of carriers  
- Monthly comparison insights  

---

## 🛠️ Technologies Used

| Technology | Purpose |
|-----------|---------|
| **HTML5 + TailwindCSS** | UI & responsive design |
| **JavaScript (Modules + ES6)** | Core logic |
| **Firebase Auth** | Anonymous / Custom Token authentication |
| **Firebase Firestore** | Storing shipment data |
| **Google Gemini API** | AI recommendations & drafting |
| **Google Fonts (Inter)** | Typography |

---

## 📁 Project Structure

