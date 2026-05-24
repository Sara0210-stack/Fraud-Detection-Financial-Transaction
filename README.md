# 🤖 AI Code Reviewer (AST + LLM)

An AI-powered code review application built using Python, Streamlit, and Large Language Models (LLMs). The system analyzes Python code, detects syntax issues using Python AST, explains errors in simple language, and generates corrected code suggestions interactively.

---

## 🚀 Features

* 🔍 Syntax validation using Python AST
* 🤖 AI-powered code review using LLMs
* 🧠 Explanation of syntax and logical issues
* 🛠️ Suggested fixes and corrected code
* 💬 Interactive Streamlit interface
* ⚡ Real-time debugging workflow
* 📌 Structured feedback generation
* 🌙 Developer-focused dark UI

---

## 🛠️ Tech Stack

* Python
* Streamlit
* AST (Abstract Syntax Tree)
* LLM Integration (Groq / Local Model via LM Studio)
* Requests Library

---

## 🧠 Why This Project?

Debugging code can be difficult for beginners and time-consuming during development. This project combines deterministic syntax validation using Python AST with AI-generated explanations to create an interactive learning and debugging assistant.

The goal is to make debugging:

* easier to understand
* more interactive
* beginner-friendly
* AI-assisted

---

## ⚙️ System Workflow

1. User submits Python code through the Streamlit UI
2. Python AST validates syntax and detects parsing errors
3. Structured prompts are generated for the LLM
4. AI analyzes the code and generates explanations
5. The system returns:

   * syntax issues
   * explanations
   * fixes
   * corrected code
6. Results are displayed interactively in the UI

---

## 📂 Project Structure

```bash
ai-code-reviewer/
│
├── app.py              # Streamlit application
├── requirements.txt    # Project dependencies
└── README.md           # Documentation
```

---

## 📸 Screenshots

### 🔍 Syntax Error Detection

The application detects Python syntax issues using AST parsing before AI analysis.

![Syntax Check](assets/syntax-check.png)

---

### 🤖 AI-Powered Review

The AI model explains issues, suggests fixes, and generates corrected code interactively.

![AI Review](assets/ai-review.png)

---

## 💻 Example Workflow

### Input Code

```python
def analyze_code(code)
    if "error" in code
        print("Found error")
```

### AI Feedback

* Detects missing colon (`:`)
* Explains indentation issues
* Suggests corrected implementation
* Generates improved Python code

---

## ▶️ Run Locally

### 1. Clone Repository

```bash
git clone https://github.com/Sara0210-stack/ai-code-reviewer.git
cd ai-code-reviewer
```

### 2. Create Virtual Environment

```bash
python -m venv .venv
.venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run Application

```bash
streamlit run app.py
```

---

## 🔐 API Setup

If using an external LLM API:

Create a `.env` file:

```env
API_KEY=your_api_key_here
```

Or directly configure the API key in the application.

---

## 🧠 Technical Challenges

* Handling inconsistent LLM responses
* Improving prompt reliability for debugging tasks
* Detecting syntax vs logical errors separately
* Managing structured AI feedback generation
* Balancing deterministic parsing with generative AI outputs

---

## 🔮 Future Improvements

* Support for multiple programming languages
* Static analysis integration for deeper code review
* AI-powered complexity and performance suggestions
* VS Code extension integration
* Retrieval-based debugging examples using code embeddings
* Local offline inference optimization

---

## 🎯 Use Cases

* Python beginners learning debugging
* AI-assisted programming workflows
* Understanding syntax and logical errors
* Educational coding support
* Rapid debugging assistance

---

## 👩‍💻 Author

Sara Shaikh

---

## ⭐ Acknowledgment

Built as part of AI/ML learning and portfolio development focused on intelligent systems and AI-assisted developer tools.
