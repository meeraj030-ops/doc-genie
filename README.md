# 📄 Doc-Genie: Python Docstring Generator

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Framework](https://img.shields.io/badge/Framework-Gradio-orange.svg)

Doc-Genie is an intelligent tool that automatically generates **Python docstrings** from source code.

It analyzes Python functions using **AST (Abstract Syntax Tree)** and produces structured documentation in **Google Style** or **NumPy Style**.

The project includes a **Gradio web interface** where users can paste Python code and instantly generate professional documentation.

---

# 🚀 Live Project

GitHub Repository:

👉 https://github.com/meeraj030-ops/doc-genie

Example:

👉 https://github.com/meeraj030-ops/doc-genie

---

# ✨ Features

- 🔍 **AST-Based Code Analysis**
- 🧠 Detects Python functions automatically
- 📝 Generates professional **docstrings**
- 📚 Supports **Google & NumPy docstring styles**
- 🎨 Clean **Gradio UI**
- 📥 Export documentation as:
  - TXT
  - PDF
- ⚡ Fast and lightweight

---

# 🛠 Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Core programming language |
| AST | Code structure analysis |
| Gradio | Web interface |
| ReportLab | PDF generation |
| Autopep8 / Black | Code formatting |

---

# 📂 Project Structure

```
doc-genie
│
├── doc_genie.py
├── requirements.txt
├── README.md
└── sample_code.py
```

---

# ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/meeraj030-ops/doc-genie.git
```

### 2️⃣ Go to Project Folder

```bash
cd doc-genie
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Run the Project

```bash
python doc_genie.py
```

Then open in browser:

```
http://127.0.0.1:7860
```

---

# 💡 Example

### Input Code

```python
def add_numbers(a:int, b:int):
    return a + b
```

### Generated Output

```python
def add_numbers(a:int, b:int):
    """
    Add two numbers.

    Args:
        a (int): First number
        b (int): Second number

    Returns:
        int: Sum of the numbers
    """
```

---

# 📊 Future Improvements

- 📂 Upload `.py` files
- 🤖 AI-powered description generation
- 📊 Code complexity analysis
- 🧠 Support for classes and modules
- ☁ Deploy as web application

---

# 🎓 Academic Use

This project was developed as a **Computer Science Final Year Project** to demonstrate:

- AST based code analysis
- Automated documentation
- Python web interface development

---

# 👨‍💻 Author

** **  
B.Sc Computer Science Student

---

# 📜 License

This project is licensed under the **MIT License**.

---

# ⭐ Support

If you like this project, please consider giving it a ⭐ on GitHub!
