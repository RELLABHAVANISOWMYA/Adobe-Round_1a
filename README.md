# ✨ Adobe Hackathon 2025 — Document Intelligence Suite

Welcome to my submission for the **Adobe India Hackathon 2025**, where I present two innovative solutions built under the theme:

> **“Connect What Matters — For the User Who Matters”**

This repository contains two main components:
- ✅ **Round 1A: Intelligent File Categorizer**
- ✅ **Round 1B: Persona-Driven Document Intelligence System**

---

## 📁 Repository Structure

```bash
.
├── Round_1A/                         # Folder for Round 1A submission
│   ├── main.py
│   ├── utils.py
│   ├── sample_files/
│   └── ... (other dependencies)
│
├── Round_1B/                         # Folder for Round 1B submission
│   ├── app/
│   │   ├── main.py
│   │   ├── processor.py
│   │   └── ...
│   ├── input_docs/
│   ├── output/
│   ├── challenge1b_output.json
│   ├── Dockerfile
│   └── approach_explanation.md
│
└── README.md                        # You're here!
````

---

## 🧠 Round 1A: Intelligent File Categorizer

> **Objective:** Automatically classify files based on their content and structure using advanced document intelligence techniques.

### 🔍 Features:

* Scans unstructured documents and extracts metadata
* Identifies document types (Invoices, Resumes, Research Papers, etc.)
* Uses PDF parsing + layout analysis
* Lightweight and CPU-compatible

### 🚀 Tools & Tech:

* `PyMuPDF`, `pdfplumber`, `pdfminer`
* Regex, layout heuristics
* Pure Python, <1GB memory usage

---

## 🧑‍💼 Round 1B: Persona-Driven Document Intelligence

> **Objective:** Extract and prioritize the most relevant sections of documents based on a **persona** and their **job-to-be-done**.

### 🔖 Use Case Examples:

| Use Case          | Persona            | Job-to-be-Done                |
| ----------------- | ------------------ | ----------------------------- |
| Academic Research | PhD Researcher     | Create a literature review    |
| Business Analysis | Investment Analyst | Compare revenue & R\&D trends |
| Education         | Chemistry Student  | Extract key exam concepts     |

### 📦 Input:

* Persona definition (role, expertise, goals)
* Job-to-be-done (task to accomplish)
* 3-10 related PDFs

### 📤 Output:

* JSON with:

  * Metadata (persona, job, timestamp)
  * Extracted sections (with ranking)
  * Sub-section summaries

### 🧩 Constraints:

* Runs on **CPU only**
* Model size ≤ **1GB**
* Runtime ≤ **60 seconds**
* No Internet access allowed

### 🛠 Tools & Tech:

* `PyMuPDF`, `Transformers`, `Scikit-learn`
* Custom scoring engine for relevance
* JSON-based output for integration

---

## 📦 Deliverables

* 🧠 `Round_1A/`: Intelligent document classifier
* 📋 `Round_1B/`: Persona-driven analyzer with:

  * ✅ `challenge1b_output.json`
  * ✅ `approach_explanation.md`
  * ✅ Dockerized implementation

---

## 💡 What's Unique?

* ✅ **Human-Centric Design**: Tailors document insights based on user persona
* ✅ **Domain-Agnostic**: Works across education, business, research
* ✅ **Resource-Light**: Works offline with strict memory/runtime constraints

---

## 🧑‍💻 Team Members

**Mamatha Taneti**
🎓 B.Tech (IT), Shri Vishnu Engineering College for Women
🔗 [GitHub](https://github.com/Mamatha07-T) | 📧 [mamat7t@gmail.com](mailto:mamat7t@gmail.com)

**Bhavani Sowmya Rella**
🎓 B.Tech (IT), Shri Vishnu Engineering College for Women
🔗 [GitHub](https://github.com/RELLABHAVANISOWMYA) | 📧 [rellabhavanisowmya@gmail.com](mailto:rellabhavanisowmya@gmail.com)

**Prajwala Pilli**
🎓 B.Tech (IT), Shri Vishnu Engineering College for Women
🔗 [GitHub](https://github.com/PrajwalaPilli/) | 📧 [prajwalapilli@gmail.com](prajwalapilli@gmail.com)


---

## 📌 Final Note

> Built with curiosity, creativity, and a passion for solving real-world document processing problems using AI 🧠✨
> Thank you, Adobe, for the opportunity!

```

---


```
