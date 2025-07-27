# Excel-Analysis-Platform
A full-stack MERN application that allows users to upload Excel files, analyze data, and generate dynamic 2D/3D charts with interactive visuals. Built for efficient data visualization and real-time insights.

> 🔐 Includes JWT-based authentication, file upload history, and admin controls.

---

## 🚀 Features

- ✅ Excel Upload (.xls/.xlsx) using Multer
- ✅ Excel Parsing with SheetJS (xlsx)
- ✅ Chart Rendering with Chart.js (2D) and Three.js (3D)
- ✅ Dynamic X & Y Axis Selection
- ✅ Export Charts to PNG/PDF
- ✅ JWT Authentication (User & Admin)
- ✅ Upload History Dashboard
- ✅ Responsive UI with Tailwind CSS
- ✅ Optional AI Integration (OpenAI)

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Tailwind CSS
- Chart.js & Three.js
- React Router
- Axios

### Backend
- Node.js
- Express.js
- MongoDB + Mongoose
- Multer for File Uploads
- SheetJS (xlsx) for Excel Parsing
- JWT for Authentication

---

## 📁 Project Structure

```

Excel-Analytics-Platform/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── server.js
├── frontend/
│   ├── src/components/
│   ├── src/pages/
│   └── App.js
├── .env.example
├── README.md

````

---

## ⚙️ Getting Started

### 1. Clone the Repo
```bash
git clone https://github.com/yourusername/Excel-Analytics-Platform.git
````

### 2. Setup Backend

```bash
cd backend
npm install
# Create .env from .env.example
npm start
```

### 3. Setup Frontend

```bash
cd ../frontend
npm install
npm run dev
```

### 4. Visit

```
Frontend: http://localhost:3000
Backend:  http://localhost:5000
```
