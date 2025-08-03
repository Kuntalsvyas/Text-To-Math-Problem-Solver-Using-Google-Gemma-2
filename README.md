# 🧮 Text-to-Math Problem Solver using Google Gemma 2
This project uses Google’s Gemma 2 model to interpret math problems written in plain English and provide step-by-step solutions. The system leverages LangChain, Groq API, and a Streamlit interface to create a conversational math assistant that can solve algebra, arithmetic, and other basic problems directly from natural language input.

---

# 📌 Features
**Natural Language to Math Conversion**
- Enter a math problem in plain English, and the model will interpret and solve it.
**step-by-Step Reasoning**
- The LLM explains its thought process before arriving at the final answer.
**Google Gemma 2 Integration**
- Uses the latest Gemma 2 model via Groq API for accuracy and fast response.
**Interactive UI**
- Built with Streamlit for a clean and user-friendly interface.
**Lightweight & Fast**
- Optimized for quick responses without heavy computation overhead.

---

# 🚀Getting Started
 **1 Clone the Repository**
- git clone https://github.com/Kuntalsvyas/Text-To-Math-Problem-Solver-Using-Google-Gemma-2.git
- cd Text-To-Math-Problem-Solver-Using-Google-Gemma-2

**2 Create a Virtual Environment**
- python -m venv venv
- source venv/bin/activate     # For Linux/Mac
- venv\Scripts\activate        # For Windows

**3 Install Dependencies**
- pip install -r requirements.txt

**5️ Run the App**
- streamlit run app.py

---

# 🖥️ How to Use
**1 Enter your Groq API Key in the sidebar.**
**2 Type a math problem in plain English (e.g., What is the sum of 235 and 478?).**
**3 The app will:**
- Parse the problem
- Show step-by-step reasoning
- Display the final answer

 ---

# 🛠️ Tech Stack

 | Tool/Library  | Purpose                        |
| ------------- | ------------------------------ |
| **LangChain** | LLM orchestration              |
| **Groq API**  | Access to Google Gemma 2 model |
| **Streamlit** | Web UI framework               |
| **Python**    | Core programming language      |

---

# 📌 Notes
- The gemma-7b-it model has been deprecated; make sure to update to the latest Gemma 2 variant.
- Best suited for basic arithmetic & algebra; may not handle advanced symbolic computation perfectly.

---

# 🙌 Author
Built by Kuntal Vyas If you found this useful, ⭐ the repo and share!
