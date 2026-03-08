# 📄 Doc-Genie: Python Docstring Generator

Doc-Genie is an intelligent tool that automatically generates professional **Python docstrings** from source code.  
It analyzes Python functions using **AST (Abstract Syntax Tree)** and generates structured documentation in **Google Style** or **NumPy Style**.  

The project also provides an interactive **Gradio-based web interface** where users can paste Python code and instantly generate well-formatted docstrings.

---

## 🚀 Features

- 🔍 **AST-Based Code Analysis**  
  Automatically detects Python functions and extracts parameters and return types.

- 📝 **Automatic Docstring Generation**  
  Generates clear and structured docstrings for functions.

- 🎨 **Multiple Docstring Styles**
  - Google Style
  - NumPy Style

- 💻 **Interactive Web Interface**  
  Built using **Gradio** for easy usage.

- 📥 **Export Options**
  - Download generated documentation as **TXT**
  - Download as **PDF**

- 🎨 **Modern UI**
  - Purple themed interface
  - Simple and clean layout

---

## 🛠 Technologies Used

- **Python**
- **AST (Abstract Syntax Tree)**
- **Gradio**
- **ReportLab**
- **Autopep8 / Black (code formatting)**

---

## 📂 Project Structure

```
doc-genie
│
├── doc_genie.py          # Main application
├── requirements.txt      # Required libraries
├── README.md             # Project documentation
└── sample_code.py        # Example Python functions
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/doc-genie.git
cd doc-genie
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Application

Run the following command:

```bash
python doc_genie.py
```

Then open the browser link shown in the terminal:

```
http://127.0.0.1:7860
```

---

## 💡 Example

### Input Code

```python
def calculate_sum(a: int, b: int):
    return a + b
```

### Generated Docstring

```python
def calculate_sum(a: int, b: int):
    """
    Calculate the sum of two numbers.

    Args:
        a (int): First number.
        b (int): Second number.

    Returns:
        int: Sum of the two numbers.
    """
```

---

## 📊 Future Improvements

- Support for **class and module documentation**
- Integration with **AI models for smarter descriptions**
- Upload **.py files directly**
- Code quality suggestions

---

## 🎓 Use Case

This project is useful for:

- Python developers
- Students learning documentation
- Open-source contributors
- Software development teams

---

## 👨‍💻 Author

**Pranesh S**  
B.Sc Computer Science Student  

Project: *Final Year Academic Project*

---

## 📜 License

This project is released under the **MIT License**.

---
