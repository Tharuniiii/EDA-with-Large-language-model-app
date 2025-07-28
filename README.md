# 📊 LLM-Powered Exploratory Data Analysis (EDA) App

### 🚀 Overview

This is an AI-powered Exploratory Data Analysis (EDA) web application built using:

- 🐼 **Pandas** – for data processing
- 📈 **Seaborn & Matplotlib** – for visualizations
- 🤖 **Ollama + Mistral** – for generating AI-based data insights
- 🌐 **Gradio** – to create an interactive web interface
  

> Upload any CSV dataset and get an automated report with:
> - Cleaned data
> - Summary statistics
> - Visualizations
> - AI-generated insights from a local LLM

---

### 💡 Features

✅ Upload any `.csv` file  
✅ Auto handle missing values (median/mode)  
✅ Descriptive statistics and data summary  
✅ Histograms and correlation heatmap  
✅ AI-generated insights using Mistral LLM  
✅ Simple drag-and-drop UI built with Gradio  

---

### 🖼️ Demo Screenshot

![Demo Screenshot](<img width="1909" height="935" alt="demo_screenshot" src="https://github.com/user-attachments/assets/2f1427f5-cab0-40b7-ab8d-abe9ee237497" />
>
)

---

### 📁 Project File Structure
llm-eda-app/
├── app.py # Main Python application
├── README.md # Project overview and instructions
├── requirements.txt # Python dependencies
├── demo_screenshot.png # App screenshot
├── datasets/ # Folder for sample datasets
│ ├── sample.csv
│ └── titanic.csv
├── outputs/ # Folder where plots are saved
│ ├── column1_distribution.png
│ └── correlation_heatmap.png

> 🧠 You can include public datasets in the `datasets/` folder so others can try the app easily.
> You can also check list of LLM models to check which model you wanted to install and use

---

### 🔧 How to Run the App Locally

#### 1️⃣ Install Python Dependencies

Make sure you have Python 3.8+ installed, then run:

```bash
pip install -r requirements.txt
2️⃣ Install and Run Ollama (for LLM)
Go to https://ollama.com and follow the install instructions.
After installation, pull the Mistral model:
ollama run mistral
⚠️ Make sure you have at least 6GB of RAM free. If not, use a smaller model like llama2:7b.
3️⃣ Run the App
python app.py
📁 Sample Datasets
You can find sample datasets in the datasets/ folder:

sample.csv – Basic dummy dataset

titanic.csv – Classic survival prediction dataset

Feel free to replace these with your own datasets!
🤝 Connect With Me
https://www.linkedin.com/in/tharuni-teegala/


