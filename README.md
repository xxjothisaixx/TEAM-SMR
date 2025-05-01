# Team SMR – Student Team Member Management App

This is a Full Stack MERN project built by:
- V V Jothi Sai Raaja (Roll No: RA2211056010074)
- John Maximas (Roll No: RA2211056010077)
- Rubeswaran (Roll No: RA2211056010131)

## 📋 Project Description

A web application to manage team members, allowing users to:
- Add team members with image upload
- View all members
- View detailed info of each member

## 🛠️ Technologies Used

- React.js (Frontend)
- Node.js + Express (Backend)
- MongoDB (Database)
- Axios, Multer

---

## 🧪 API Endpoints

### POST `/api/members`
- Adds a new team member
- Accepts `name`, `role`, `email`, and `image` (multipart form)

### GET `/api/members`
- Retrieves all team members

### GET `/api/members/:id`
- Fetches details of a specific member by ID

---

## 🚀 How to Run the App

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/Team-SMR.git
cd Team-SMR



Start the Backend
bash
Copy
cd backend
npm install
node server.js


Start the Frontend
bash
Copy
cd ../frontend
npm install
npm start

Team-SMR/
├── backend/
│   ├── server.js
│   ├── uploads/
│   └── package.json
├── frontend/
│   ├── src/
│   │   ├── App.js
│   │   ├── index.js
│   │   └── pages/
│   │       ├── Home.js
│   │       ├── AddMember.js
│   │       ├── ViewMembers.js
│   │       └── MemberDetails.js
│   ├── public/
│   │   └── index.html
│   └── package.json
├── .gitignore
└── README.md
