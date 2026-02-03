<h1 align="right">🧠 AI SQL Generator</h1>

A simple AI-powered SQL generator built with React and Node.js.

---

## 📋 Table of Contents
- [General Info](#general-info)
- [Technologies](#technologies)
- [Setup](#setup)
- [Sources](#sources)

---

## 🧠 General Info
This project is an AI SQL Generator that connects to the OpenAI API and generates SQL queries from natural language input using a Node.js backend and a React frontend.

---

## 🛠️ Technologies
This project was built with:
- **JavaScript (ES6+)**
- **React**
- **Node.js**
- **Express**
- **HTML5**
- **CSS3**

---

## ⚙️ Setup
To run this project locally:

### 1️⃣ Clone the repo
```bash
git clone https://github.com/kpilszak/ai-sql-generator.git
```

### 2️⃣ Go into the project folder
```bash
cd ai-sql-generator
```

### 3️⃣ Install dependencies
```bash
npm install
```

### 4️⃣ Add your OpenAI API key to .env
```bash
touch .env
echo "API_KEY=your_api_key_here" > .env
```

### 5️⃣ Run the app
Start the backend and frontend (in **separate terminal windows** or **tabs**):
```bash
# Terminal 1
npm run start:backend
```
```bash
# Terminal 2
npm run start:frontend
```

The frontend will be available at http://localhost:3000 and the backend will run on http://localhost:8000
 (or your configured port).

---

## 📚 Sources
This project was inspired by and built with the help of  
**Ania Kubów’s tutorial** → [Code an AI SQL Generator! (super simple!) | React Node.js OpenAI API ChatGPT 4](https://www.youtube.com/watch?v=mb36Ny-VNgU)
