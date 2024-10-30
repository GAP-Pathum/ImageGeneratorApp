
# 🌌 AI Image Generator App  

![MERN](https://img.shields.io/badge/Stack-MERN-informational?style=flat&logo=javascript&logoColor=white)  
![API](https://img.shields.io/badge/API-RapidAPI-blue?style=flat)  
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)  

A **MERN stack application** that transforms your text prompts into stunning, AI-generated images via **RapidAPI**. Whether you want to generate surreal landscapes, abstract art, or anything in between, this app has you covered! 🚀✨

---

## 🚀 Demo

🌐 **[Live Demo](#)** (Coming Soon!)

---

## 📋 Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [API Integration](#api-integration)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

---

## ✨ Features

- **AI-powered Image Generation** using RapidAPI models.  
- **Responsive UI** with **React.js** for a smooth user experience.  
- **History Tracking** to view previously generated images.  
- **Secure Backend** with Express.js and MongoDB for data storage.  
- **Real-time Rendering** of images based on text prompts.  

---

## 🛠️ Tech Stack

- **MongoDB** – NoSQL database for storing user history and prompts.  
- **Express.js** – Backend framework for handling API requests.  
- **React.js** – Frontend library for building a dynamic UI.  
- **Node.js** – Server-side runtime for backend logic.  
- **RapidAPI** – AI-powered APIs for generating images.  
- **Axios** – HTTP client for API requests.  

---

## 📦 Installation

Follow these steps to set up the project locally.

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Pathum-Pasindu/Image-Generator.git
cd Image-Generator
```

### 2️⃣ Install Dependencies

#### Backend:
```bash
cd backend
npm install
```

#### Frontend:
```bash
cd ../frontend
npm install
```

### 3️⃣ Configure Environment Variables  
Create a `.env` file inside the **backend** directory and add the following:

```plaintext
MONGO_URI=<your-mongodb-uri>
RAPIDAPI_KEY=<your-rapidapi-key>
PORT=5000
```

### 4️⃣ Start the App

#### Run the backend:
```bash
cd backend
npm start
```

#### Run the frontend:
```bash
cd ../frontend
npm start
```

The app will be accessible at **http://localhost:3000**.

---

## 🔧 Usage

1. Visit **http://localhost:3000**.
2. Enter a creative prompt (e.g., “A glowing dragon flying over a neon city” 🐉).  
3. Click **Generate** to see the magic happen.  
4. Browse your **history** to revisit previous generations.  

---

## 🌐 API Integration

This app leverages **RapidAPI** to generate images from text inputs.  

- **Authentication:**  
  Add your **RAPIDAPI_KEY** in the `.env` file to authorize API requests.  

For detailed information, refer to [RapidAPI documentation](https://rapidapi.com/).

---

## 🗂️ Project Structure

```plaintext
Image-Generator/
│
├── backend/                 # Backend server (Node.js + Express)
│   ├── controllers/         # Route handlers
│   ├── models/              # MongoDB models
│   ├── routes/              # Express routes
│   └── server.js            # Entry point for backend
│
├── frontend/                # React-based frontend
│   ├── src/
│   │   ├── components/      # UI components
│   │   ├── pages/           # App pages
│   │   ├── App.js           # Main React component
│   │   └── index.js         # React DOM entry point
│
├── README.md                # Project documentation
└── .env                     # Environment variables
```

---

## 🤝 Contributing

Contributions are welcome! If you have ideas for new features or find any bugs, feel free to submit an issue or pull request.  

### How to Contribute:
1. **Fork** the repository.  
2. **Clone** your fork:
   ```bash
   git clone https://github.com/your-username/Image-Generator.git
   ```
3. Create a **new branch** for your changes:
   ```bash
   git checkout -b feature/your-feature-name
   ```
4. **Commit** your changes and push the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a **pull request** on GitHub.

---

## 📄 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.

---

## 📧 Contact

If you have any questions or feedback, feel free to reach out at **your-email@example.com**.

---

## 🌟 Acknowledgments

Special thanks to:  
- **RapidAPI** for providing the AI models.  
- The **MERN Stack** community for their amazing resources and support.

---

Let your creativity run wild! 🎨🚀
