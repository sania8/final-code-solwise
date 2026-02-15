# 🧮 MathSolver Pro: Advanced AI-Powered Math Learning Platform

🔗 **Live Demo:** [MathSolver Pro on Render](https://aiagent-math-gemini-7997.onrender.com/)  
📜 **Description:** MathSolver Pro is a comprehensive AI-powered mathematics learning platform that helps students master math through multiple learning approaches. Built with **Flask** and powered by **Groq's LLaMA 3.1**, it offers 12+ unique features including problem solving, step-by-step explanations, practice generation, real-world applications, and interactive visualizations.

---

## ✨ Key Features

### 🎯 Core Problem Solving
- **Instant Solutions** - Get quick answers to any math problem
- **Step-by-Step Explanations** - Detailed walkthrough of solution process
- **Alternative Methods** - Learn 2-3 different approaches to solve the same problem

### 🎓 Learning & Practice
- **Practice Similar Problems** - Generate 5 progressive difficulty problems
- **Common Mistakes** - Learn what students typically get wrong
- **Tutor Mode** - Receive hints instead of direct answers
- **Difficulty Ladder** - Get easier and harder versions of problems

### 🌍 Contextual Understanding
- **Real-World Applications** - See where math is used in actual professions
- **Explain Like I'm 5** - Super simple explanations with fun analogies
- **Difficulty Rating** - Understand problem complexity (1-10 scale)
- **Concept Map** - View prerequisites and what to learn next

### 📊 Advanced Tools
- **Generate Worksheets** - Create 10-problem practice sets
- **File Upload Support** - Extract math problems from PDF, DOCX, PPTX
- **Interactive Visualizations** - Function plots, geometric shapes, statistical charts
- **Split-Screen Interface** - Controls on left, results on right

---

## 🔑 How to Get Your Groq API Key

To use MathSolver Pro, you need a **free Groq API Key**. Follow these simple steps:

### **Step 1: Visit Groq Console**
🔗 Go to [console.groq.com](https://console.groq.com)

### **Step 2: Sign Up / Log In**
- Click **"Sign In"** or **"Get Started"**
- Use your Google account or email to create a free account
- No credit card required! ✅

### **Step 3: Create API Key**
1. Once logged in, navigate to **"API Keys"** in the left sidebar
2. Click **"Create API Key"**
3. Give it a name (e.g., "MathSolver Pro")
4. Click **"Submit"**

### **Step 4: Copy Your Key**
- Your API key will look like: `gsk_xxxxxxxxxxxxxxxxxxxxxxxxxx`
- **Important:** Copy it immediately and save it securely
- You won't be able to see it again!

### **Step 5: Paste in MathSolver Pro**
- Enter your API key when prompted on the homepage
- Start solving math problems instantly! 🚀

---

## 🛠 Installation & Setup

### **Prerequisites**
- Python 3.8 or higher
- pip (Python package manager)

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/your-repo/mathsolver-pro.git
cd mathsolver-pro
```

### **2️⃣ Install Dependencies**
```bash
pip install -r requirements.txt
```

**Required packages:**
```txt
flask
groq
plotly
sympy
numpy
PyPDF2
python-docx
python-pptx
```

### **3️⃣ Run the Application**
```bash
python app.py
```

### **4️⃣ Open in Browser**
Navigate to:
```
http://localhost:5000
```

### **5️⃣ Enter Your API Key**
- Paste your Groq API key when prompted
- Start using all 12+ features!

---

## 📖 How to Use

### **Basic Workflow**
1. **Enter your math problem** in the text box
2. **Choose an action** from 12 available options
3. **View results** on the right panel
4. **Interact with visualizations** (when applicable)

### **Feature Guide**

| Button | What It Does |
|--------|-------------|
| 🎯 **Solve** | Get direct answer with automatic visualization |
| 📖 **Explain** | Step-by-step solution breakdown |
| 🔄 **Alt Methods** | See 2-3 different solving approaches |
| 💪 **Practice** | Generate 5 similar problems (increasing difficulty) |
| ⚠️ **Mistakes** | Learn common errors students make |
| 👨‍🏫 **Tutor** | Get hints without seeing the full solution |
| 🌎 **Real Uses** | Discover real-world applications |
| 🧒 **ELI5** | Super simple explanation for beginners |
| 📊 **Difficulty** | See complexity rating and time estimate |
| 🪜 **Ladder** | Get easier/harder versions of the problem |
| 🗺️ **Concepts** | View prerequisites and next steps |
| 📝 **Worksheet** | Generate 10-problem practice sheet |

### **Example Questions to Try**

**Algebra:**
```
Solve x² + 5x + 6 = 0
```

**Geometry:**
```
Find the area of a circle with radius 7
```

**Calculus:**
```
What is the derivative of 3x² + 2x - 5?
```

**Statistics:**
```
Calculate the mean of: 12, 18, 24, 30, 36
```

---

## 🎨 UI Features

### **Split-Screen Design**
- **Left Panel (45%):** All controls and input
- **Right Panel (55%):** Results and visualizations
- **Responsive:** Works on desktop, tablet, and mobile

### **Interactive Elements**
- 📌 Step-by-step progress tracker
- 📊 Quick stats cards (difficulty, grade level, time)
- 💡 Smart tips and highlight boxes
- 🎯 Context-aware interactive features

### **Visual Feedback**
- Animated icons for each feature
- Color-coded result headers
- Smooth transitions and loading states

---

## 🔬 Technical Stack

### **Backend**
- **Framework:** Flask (Python)
- **AI Model:** Groq LLaMA 3.1 8B Instant
- **Math Engine:** SymPy
- **Visualization:** Plotly
- **File Processing:** PyPDF2, python-docx, python-pptx

### **Frontend**
- **HTML5 + CSS3** - Modern responsive design
- **Vanilla JavaScript** - No heavy frameworks
- **Plotly.js** - Interactive charts

---

## 🚀 Deployment

### **Deploy to Render**

1. Create `requirements.txt` with all dependencies
2. Push code to GitHub
3. Connect repo to Render
4. Auto-deploys on every commit

### **Alternative Platforms**
- **Vercel** - Serverless Python support
- **Railway** - One-click deployment
- **PythonAnywhere** - Free Flask hosting

---

## 🤝 Contributing

Contributions welcome! Open issues or submit PRs on GitHub.

---

## 📄 License

MIT License - Free to use and modify

---

🚀 **Let's make math learning smarter and more engaging!**

📚 **Happy Learning! 🎓**
