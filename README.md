
# NeuralRoute 🧠

### Prompt-Driven AI Routing System

![NeuralRoute Banner](https://img.shields.io/badge/AI-Powered-2dd4a0?style=for-the-badge) ![Gemini](https://img.shields.io/badge/Gemini-1.5--Flash-4285F4?style=for-the-badge) 
---

## 📌 Overview

**NeuralRoute** is an intelligent AI application that demonstrates **prompt engineering** by routing user queries to the optimal response method. Instead of using traditional if-else logic, the system uses AI itself to decide how to handle each query through carefully engineered prompts.

Built as a portfolio project to showcase prompt engineering skills, NeuralRoute features a stunning glassmorphism UI and real-time AI decision-making.

## 🏗️ Built with Prompt Engineering

This entire project was built using AI-powered development tools through carefully engineered prompts:

- **UI Design:** Generated using [Stitch](https://stitch.new) with detailed glassmorphism design prompts
- **Application Logic:** Wired using [Antigravity](https://antigravity.new) to add AI routing functionality
- **See `/prompts/build_ui_prompt.txt` and `/prompts/build_logic_prompt.txt`** for the exact prompts used to create this application

The app itself demonstrates prompt engineering, and was also *built entirely* through prompt engineering — proving the concept at every level.

---

## 🎯 The Core Concept

Traditional chatbots follow hardcoded rules:
```javascript
if (query.includes("latest")) {
    searchWeb();
}
```

**NeuralRoute** uses prompts to make decisions:
```
"You are a query router. Classify this query as LLM, WEB, or RAG..."
```

The AI decides the routing strategy — **that's prompt engineering in action.**

---

## 🚀 Features

### Intelligent Query Routing
- **LLM Mode** 🧠 — Handles general knowledge, concepts, and explanations
- **WEB Mode** 🌐 — Processes queries about current events and real-time information
- **RAG Mode** 📚 — Answers from a curated knowledge base

### Visual Intelligence Panel
- Real-time routing decision visualization
- Live confidence metrics (88-98%)
- Process stepper showing query flow
- Active prompt inspector displaying the actual prompts used

### Premium UI/UX
- Dark green + teal glassmorphism design
- Smooth animations and transitions
- Responsive chat interface
- Ambient glow background effects

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3 (Tailwind CSS), Vanilla JavaScript
- **AI Model:** Google Gemini 1.5 Flash
- **Architecture:** Single-page application (SPA)
- **Styling:** Glassmorphism + Material Design icons

---

## 📂 Project Structure

```
NeuralRoute/
├── index.html          # Complete application (UI + Logic)
├── README.md           # Project documentation
└── prompts/            # Prompt engineering documentation
    ├── router_prompt.txt
    ├── llm_prompt.txt
    ├── web_prompt.txt
    ├── rag_prompt.txt
    └── generator_prompt.txt
```

---

## 🔧 How to Run Locally

### Prerequisites
- Python 3.x installed
- A free Google Gemini API key

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/NeuralRoute.git
   cd NeuralRoute
   ```

2. **Start a local server**
   ```bash
   python -m http.server 8000
   ```

3. **Open in browser**
   ```
   http://localhost:8000/index.html
   ```

4. **Get your free Gemini API key**
   - Visit [Google AI Studio](https://aistudio.google.com)
   - Click "Get API Key"
   - Copy your key

5. **Enter API key in the app**
   - Paste your key in the launch screen
   - Click "Launch"
   - Start chatting!

---

## 💡 How It Works

### Step 1: Router Prompt (Decision Layer)
When you send a query, the system calls Gemini with a **routing prompt**:
```
You are a query router. Classify the user's query into:
- LLM: General knowledge questions
- WEB: Current events, latest news
- RAG: Questions about stored documents

Return only JSON: {"route": "LLM"}
```

### Step 2: Handler Prompt (Processing Layer)
Based on the route, one of three handler prompts executes:

**LLM Handler:**
```
Answer directly and accurately. Use **bold** for key terms.
Use bullet points. Do not say "as an AI assistant".
```

**WEB Handler:**
```
Answer with the most current information you know.
Give specific facts and recent developments.
```

**RAG Handler:**
```
Answer based ONLY on the provided document context.
If not found in documents, say so explicitly.
```

### Step 3: Generator Prompt (Formatting Layer)
```
Lightly format this response. Fix markdown structure.
Do not change content. Return polished output.
```

### Step 4: Display
The formatted response is shown with a mode indicator (LLM/WEB/RAG).

---
## 🌐 Live Demo
   
   **[Try NeuralRoute Live →](https://yourusername.github.io/NeuralRoute-Prompt-Engineering/)**
   
   *Note: You'll need to enter your own Gemini API key to use the app.*
---

## 🎓 Prompt Engineering Techniques Used

| Technique | Purpose | Example |
|-----------|---------|---------|
| **Role Assignment** | Focus AI behavior | "You are a query router..." |
| **Output Constraints** | Control response format | "Return ONLY JSON, no markdown" |
| **Few-Shot Learning** | Guide by example | Showing input-output pairs |
| **Chain-of-Thought** | Structured reasoning | Breaking tasks into steps |
| **Negative Prompting** | Avoid unwanted behavior | "Do not say 'as an AI assistant'" |
| **Two-Stage Prompting** | Separate generation from formatting | Router → Handler → Generator |

See `/prompts` folder for full prompt documentation and reasoning.

---

## 📊 Knowledge Base Topics (RAG Mode)

The system includes detailed information on:
- Prompt Engineering
- Neural Networks
- Large Language Models (LLMs)
- RAG (Retrieval Augmented Generation)
- Machine Learning
- Deep Learning

Each topic contains 3-4 paragraphs of comprehensive content.

---

## 🧪 Example Queries

### LLM Mode
```
"What is machine learning?"
"Explain neural networks"
"What is NLP?"
```

### WEB Mode
```
"Latest AI news today"
"Recent developments in AI"
"Current trends in technology"
```

### RAG Mode
```
"Explain prompt engineering from my notes"
"What is RAG from my knowledge base?"
"Tell me about LLMs from my documents"
```

---

## 🔒 Security

- ✅ No API keys hardcoded in source code
- ✅ API key entered by user at runtime
- ✅ Safe to upload to public GitHub
- ✅ Each user provides their own key

---

## 🎨 Design Philosophy

The UI draws inspiration from:
- Glassmorphism for depth and premium feel
- Dark mode for reduced eye strain
- Ambient glows for a "living" interface
- Material Design for familiar iconography

Color palette: Deep greens and teals create a tech-forward, trustworthy aesthetic.

---

## 👨‍💻 Author

**Harshitha Karthikeyan**
- GitHub:https://github.com/harshithakarthikeyan
- LinkedIn:www.linkedin.com/in/harshitha-karthikeyan-hk
