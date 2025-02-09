# nodejs-app-starter-package

🚀 **A CLI tool to quickly and easily create Node.js project structures.**

## 📌 Installation
To install the package globally on your machine, use the following command:
```bash
npm i -g nodejs-app-starter
```

## 🚀 Usage
After installation, you can create a new project easily by running:
```bash
create-nodejs name-project
```
🔹 The project name must be in lowercase, with words separated by dashes (`-`).
🔹 A new folder will be created containing a complete Node.js project structure.

## 📁 Project Structure
After execution, the following project structure will be created:
```
name-project/
│── src/
│   ├── config/
│   │   └── db.js
│   ├── controllers/
│   │   └── user.controller.js
│   ├── middlewares/
│   │   └── auth.middleware.js
│   ├── models/
│   │   └── user.model.js
│   ├── routes/
│   │   └── user.routes.js
│   ├── utils/
│   │   └── helper.js
│   └── index.js
│── .gitignore
│── config.env
│── package.json
│── README.md
```

## ▶️ Running the Project
### Step-by-Step Guide
1. **Create a new project**
   ```bash
   create-nodejs my-project
   ```
2. **Start the development server**
   ```bash
   npm run dev
   ```
3. **Your server is now running on** `http://localhost:5000`

## 📋 Requirements
✔ **Node.js** ≥ 14  
✔ **NPM** ≥ 6  

## 🤝 Contribution
If you want to contribute or report issues, feel free to open an **Issue** or submit a **Pull Request**.

## 📄 License
📜 This project is available under the **MIT License**.

---

👨‍💻 **Created by Abdelrahman Mahmmed**  
🔗 Package: [npmjs.com/package/nodejs-app-starter](https://www.npmjs.com/package/nodejs-app-starter)  
🔗 LinkedIn: [linkedin.com/in/abdelrahman2mahmmed](https://www.linkedin.com/in/abdelrahman2mahmmed/)
