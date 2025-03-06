### **📚 LearnLab – The Ultimate Online Learning Platform**   

### **🌟 Overview**  

LearnLab is a cutting-edge **online learning platform** that offers a seamless experience for students to explore, purchase, and master courses in various fields. Designed with a **user-friendly interface, secure payment integration, and powerful admin tools**, LearnLab enables educators to effortlessly **create, manage, and sell courses**, while learners can access high-quality content anytime, anywhere.

---
🚀 **Live Demo:** [LearnLab](https://learn-lab-two.vercel.app/)  
---

## **✨ Features**  
### **👨‍🎓 User Features**
✅ Browse and search for courses  
✅ Secure signup & login with JWT authentication  
✅ Purchase courses via an integrated payment gateway  
✅ Track enrolled courses  
✅ Responsive design (works on mobile & desktop)  

### **🔑 Admin Features**
✅ Add, edit, and delete courses  
✅ Manage users and payments  
✅ Dashboard for tracking revenue & enrollments  

---

## **🛠️ Tech Stack**
### **Frontend (React + Vite)**
- ⚛️ **React.js** – Component-based UI  
- 🎨 **Tailwind CSS** – Modern styling  
- ⚡ **Vite** – Fast build tool  
- 🌍 **Axios** – For API calls  

### **Backend (Node.js + Express)**
- 🛢️ **MongoDB + Mongoose** – NoSQL Database  
- 🔒 **JWT Authentication** – Secure login/signup  
- 🚀 **Express.js** – Fast & scalable backend  
- 🔗 **CORS Enabled** – To allow frontend-backend communication  

### **Deployment**
- 🌐 **Frontend:** Vercel  
- 🖥️ **Backend:** Render  
- ☁️ **Database:** MongoDB Atlas  

---

## **🚀 Installation & Setup**
### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/Shubh-Raj/LearnLab.git
cd LearnLab
```

### **2️⃣ Backend Setup**
1. Navigate to the backend folder:
   ```sh
   cd backend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Create a `.env` file and add:
   ```env
   PORT=4002
   MONGO_URI=your_mongodb_uri
   JWT_SECRET=your_secret_key
   FRONTEND_URL=https://learn-lab-two.vercel.app
   ```
4. Start the backend:
   ```sh
   npm start
   ```
   The API will run at **`http://localhost:4002`**.

### **3️⃣ Frontend Setup**
1. Navigate to the frontend folder:
   ```sh
   cd ../frontend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Create a `.env` file:
   ```env
   REACT_APP_API_URL=https://learnlab.onrender.com/api/v1
   ```
4. Start the frontend:
   ```sh
   npm run dev
   ```
   The website will run at **`http://localhost:5173`**.

---

## **🚀 Deployment**
### **Frontend (Vercel)**
1. Push your code to GitHub.
2. Connect your repository to [Vercel](https://vercel.com/).
3. Set the **Output Directory** to `dist` (for Vite).
4. Deploy and get your live URL!

### **Backend (Render)**
1. Push your backend code to GitHub.
2. Connect your repository to [Render](https://render.com/).
3. Add **Environment Variables** (from `.env`).
4. Deploy and get your live API URL.

---


## **🤝 Contributing**
Want to improve LearnLab? Follow these steps:  
1. **Fork the repository**  
2. **Create a new branch** (`git checkout -b feature-name`)  
3. **Commit changes** (`git commit -m "Added new feature"`)  
4. **Push to GitHub** (`git push origin feature-name`)  
5. **Open a Pull Request**  

---

## **📞 Contact & Support**
💡 Have questions? Want to report an issue?  
- Open an **issue** in GitHub  
- Contact me on **[LinkedIn](https://www.linkedin.com/in/shubhraj62/)**  
- Email: **btech10068.23@bitmesra.ac.in**  

---