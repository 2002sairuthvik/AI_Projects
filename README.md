# AI Multi-Project Repository

This repository contains **three AI-powered projects**, organized into subfolders:

1. **[project-1](project-1/): AI Assistant with Basic Calculator & Greeting Tools**  
2. **[project-2](project-2/): AI-Powered Resume Critique App**  
3. **[project-3](project-3/): AI Image Classifier**

---

## **Repository Structure**
```
.
├── project-1/
│   └── main.py              # AI assistant with LangChain tools
├── project-2/
│   └── app.py               # Resume critique Streamlit app
├── project-3/
│   └── app.py               # Image classifier Streamlit app
└── README.md                # Documentation for all projects
```

---

## **Project 1: AI Assistant with Calculator & Greeting**

### Overview
A console-based **ReAct agent** built using **LangChain** and **LangGraph** with custom tools:
- **Calculator** – Performs basic arithmetic.
- **Say Hello** – Greets the user.

### Key Technologies
- **LangChain** and **LangGraph** for agent orchestration.
- **OpenAI GPT Models** for reasoning.
- **dotenv** for secure API key management.

### How to Run
1. Navigate to the project folder:
   ```bash
   cd project-1
   ```
2. Install dependencies:
   ```bash
   pip install langchain langgraph langchain-openai python-dotenv
   ```
3. Create a `.env` file with your OpenAI API key:
   ```
   OPENAI_API_KEY=your_openai_key_here
   ```
4. Run the app:
   ```bash
   python main.py
   ```
5. Type natural commands (e.g., `What is 3 + 5?`) or `quit` to exit.

---

## **Project 2: AI-Powered Resume Critique App**

### Overview
A **Streamlit web app** that analyzes resumes:
- Upload `.pdf` or `.txt` resumes.
- Enter a **target job role**.
- Receive **AI-powered feedback** on content clarity, skills, and improvements.

### Key Technologies
- **Streamlit** for the web UI.
- **OpenAI GPT-4o-mini** for analysis.
- **PyPDF2** for text extraction from PDFs.

### How to Run
1. Navigate to the project folder:
   ```bash
   cd project-2
   ```
2. Install dependencies:
   ```bash
   pip install streamlit openai PyPDF2 python-dotenv
   ```
3. Create a `.env` file:
   ```
   OPENAI_API_KEY=your_openai_key_here
   ```
4. Launch the app:
   ```bash
   streamlit run app.py
   ```

---

## **Project 3: AI Image Classifier**

### Overview
An interactive **image classification web app**:
- Uses **MobileNetV2 (PyTorch)** trained on ImageNet.
- Predicts top-3 categories with confidence scores.

### Key Technologies
- **Streamlit** for the web UI.
- **PyTorch** and **Torchvision** for deep learning.
- **Pillow (PIL)** for image handling.

### How to Run
1. Navigate to the project folder:
   ```bash
   cd project-3
   ```
2. Install dependencies:
   ```bash
   pip install streamlit torch torchvision pillow
   ```
3. Start the app:
   ```bash
   streamlit run app.py
   ```

---

## **Global Setup**

### Clone the Repo
```bash
git clone <repo_url>
cd <repo_name>
```


## **Future Enhancements**
- Add **Dockerfiles** for each project.
- Merge all apps into a **multi-page Streamlit dashboard**.
- Expand toolset for Project 1 (e.g., advanced math solver).

---

## **License**
This repository is licensed under the **MIT License**.
