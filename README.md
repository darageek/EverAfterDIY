# **EverAfterDIY** 🎉  
*A smart and customizable wedding planner for small DIY weddings.*  

## 🌟 About the Project  
EverAfterDIY is a wedding planning app designed for couples who want a **small, personalized, and budget-friendly wedding**. It provides tools to **design invitations, manage guests, track budgets, and create DIY gifts**, all in one place.  

## 🚀 Key Features  
- ✅ **Custom Invitations** – Create and send digital or printable wedding invites.  
- ✅ **Budget Tracker** – Smart suggestions to save money on every aspect of your wedding.  
- ✅ **Guest Management** – Automate RSVP tracking and seating arrangements.  
- ✅ **DIY Gift & Experience Registry** – Create your own wedding gift list with DIY ideas or experiences instead of traditional gifts.  
- ✅ **Second-hand Marketplace** – Buy, sell, or trade wedding decorations and outfits.  
- ✅ **AI-Powered Planning** – Get recommendations based on your wedding size, budget, and preferences.  

---

## 🛠 Tech Stack (Python Version)  
### **Frontend:**  
- **React (Next.js) + TailwindCSS** *(for a modern and fast UI)*  
- **Flutter / React Native** *(for mobile applications)*  

### **Backend:**  
- **FastAPI** *(for fast and efficient RESTful APIs, async support)*  
- **Django Rest Framework (DRF)** *(for a robust backend with built-in admin panel)*  

### **Database:**  
- **PostgreSQL** *(structured data, scalable)*  
- **MongoDB** *(flexible data handling, NoSQL option)*  
- **SQLite** *(lightweight database for local development)*  

### **Additional Services:**  
- **Celery + Redis** *(for background tasks like email notifications)*  
- **Docker** *(for easy deployment and scalability)*  

---

## 📂 Project Structure  
```
/EverAfterDIY
│── /frontend  # (React / Next.js)
│── /backend   # (FastAPI or Django)
│   │── /app
│   │   │── models.py
│   │   │── routes.py
│   │   │── services.py
│   │   │── database.py
│   │── main.py  # (FastAPI entry point)
│── /docs  # (Project documentation)
│── README.md
│── .gitignore
│── requirements.txt  # (Python dependencies)
│── docker-compose.yml  # (Docker orchestration)
│── LICENSE
```

---

## 🎯 How to Get Started  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/darageek/EverAfterDIY.git
cd EverAfterDIY
```

### 2️⃣ Install Dependencies  

#### Backend  
```bash
cd backend
pip install -r requirements.txt
```  

#### Frontend  
```bash
cd frontend
npm install  # or yarn install
```  

### 3️⃣ Run the Project  

#### Backend (FastAPI)  
```bash
cd backend
uvicorn main:app --reload
```  

#### Frontend  
```bash
cd frontend
npm run dev  # or yarn dev
```  

---

## 🛤 Roadmap  
- [ ] Set up project architecture  
- [ ] Develop invitation editor  
- [ ] Implement guest RSVP tracking  
- [ ] Integrate budget calculator  
- [ ] Launch MVP  

---

## 🤝 Contributing  
Contributions are welcome! Please follow the contribution guidelines in `CONTRIBUTING.md`.  

---

## 📜 License  
This project is licensed under the **MIT License** – see the [`LICENSE`](LICENSE) file for details.  

---

## 📬 Contact  
📩 Email: Darandreslopez@proton.me  
🌐 Website: [Coming Soon]  
🚀 Follow us on [GitHub](https://github.com/darageek/EverAfterDIY)  
