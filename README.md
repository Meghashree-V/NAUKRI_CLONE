# Naukri.com Clone

A modern, full-stack job portal web application inspired by [Naukri.com](https://www.naukri.com/). This project enables users to search and apply for jobs, while employers can post and manage job listings—emulating the core features of a real-world job marketplace.

---

## 🚀 Features
- User registration & authentication (Job seekers and Employers)
- Job posting, editing, and deletion for employers
- Job search with advanced filtering for seekers
- Application submission and tracking
- User profile management (resumes, company info, etc.)
- Responsive, modern UI

## 🛠️ Tech Stack
- **Frontend:** React.js
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Styling:** CSS3, Chakra UI/Bootstrap/Material-UI/Tailwind CSS

## 🏗️ Project Structure
```
root/
├── client/         # React frontend
├── server/         # Node.js backend
├── models/         # Database models
├── routes/         # API routes
├── controllers/    # Route controllers
├── utils/          # Utility functions
└── README.md
```

## ⚙️ Getting Started

### Prerequisites
- Node.js & npm
- MongoDB

### Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/naukri-clone.git
   cd naukri-clone
   ```
2. **Install dependencies:**
   ```bash
   npm install
   cd client
   npm install
   cd ..
   ```
3. **Set up environment variables:**
   - Create a `.env` file in the root and add necessary variables (e.g. MongoDB URI, JWT secret, etc.)

4. **Run the application:**
   ```bash
   # In the root directory
   npm start
   ```
   This will start both the backend and frontend servers.

5. **Open your browser:**
   - Visit `http://localhost:3000` (or as configured) to use the app.

## 🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## 📄 Author
Meghashree.V

## 📄 License
[MIT](LICENSE)
