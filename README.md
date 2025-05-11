# 🚑 Dev-Dut  -- Real-time Accident Alert & Rescue System

SwiftAid is a real-time platform where anyone can quickly report accidents by uploading a photo 📸 and sharing their location 🌍. Nearby rescue teams are alerted instantly ⛨️ to respond faster and save lives. Users earn reward points 🏆 for every genuine report they make!

---

## ✨ Features
- 📸 Upload accident images
- 📍 Auto-capture current location
- 🛡️ Notify nearest rescue teams
- 📈 Earn and track reward points
- 📅 Admin dashboard for verification
- 🛍️ Rescue team dashboard with live map

---

## 📚 Tech Stack (All Free Resources)
- Frontend: React.js + Tailwind CSS
- Backend: Node.js (Express)
- Authentication: Firebase Auth
- Image Storage: Firebase Storage
- Database: MongoDB Atlas
- Maps API: Mapbox
- Hosting: Vercel (frontend) + Render (backend)

---

## 💡 How It Works
1. User signs up/login via Firebase Auth.
2. Uploads accident photo + auto-location capture.
3. Backend stores report in MongoDB + image in Firebase.
4. Rescue teams view incidents on their dashboard map.
5. Admin verifies reports; points awarded to users.

---

## ⚡ Installation

### Frontend Setup
```bash
cd frontend
npm install
npm start
```

### Backend Setup
```bash
cd backend
npm install
npm run dev
```

### Environment Variables (.env)
```
MONGO_URI=your_mongodb_connection
FIREBASE_API_KEY=your_firebase_api_key
FIREBASE_PROJECT_ID=your_firebase_project_id
MAPBOX_ACCESS_TOKEN=your_mapbox_access_token
```

---

## 🔧 Deployment
- Frontend deployed on Vercel
- Backend deployed on Render
- MongoDB Atlas and Firebase Hosting (Free tiers)

---

## 📊 Future Improvements
- 🔹 Mobile App (Flutter)
- 🔹 Blockchain Reward System
- 🔹 AI Fake Report Detection
- 🔹 Emergency SMS Alerts

---

## 👨‍💻 Author
- Developed with passion by Rajdeep Das
- Connect with me on [LinkedIn](https://www.linkedin.com)

---

## ❤️ Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 💪 License
This project is licensed under the MIT License.

