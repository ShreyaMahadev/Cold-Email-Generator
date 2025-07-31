<h1 align="center">📧 Cold Email Generator 🚀</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Streamlit-Enabled-brightgreen?logo=streamlit" alt="Streamlit">
  <img src="https://img.shields.io/badge/Python-3.8+-blue?logo=python" alt="Python">
  <img src="https://img.shields.io/badge/AI-Powered-ff69b4?logo=OpenAI" alt="AI">
</p>

---

## ✨ Project Description

**Cold Email Generator** is an AI-powered web app that helps you generate personalized cold emails for job applications. Just paste a job URL, and the app will:

- 🔍 Scrape and analyze the job description
- 🧠 Extract required skills
- 📂 Match your portfolio links to those skills
- ✉️ Generate a tailored cold email draft for you to use

---

## 🛠️ Features

- Easy-to-use Streamlit interface
- Automatic job description parsing
- Portfolio-to-job skill matching
- AI-generated email drafts
- Customizable and extendable

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone <your-repo-url>
cd Cold-Email-Generator
```

### 2. Create and activate a virtual environment (optional but recommended)

```bash
python -m venv venv
venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Set environment variables (optional, for advanced users)

Create a `.env` file in the root directory and add:

```
USER_AGENT=ColdEmailGenerator/1.0
```

### 5. Run the app

```bash
streamlit run app\main.py
```

The app will open in your browser at [http://localhost:8501](http://localhost:8501) 🌐

---

## 📁 Project Structure

```
app/
  chain.py
  main.py
  portfolio.py
  utils.py
  resource/
    my_portfolio.csv
requirements.txt
.env (optional)
```

---

## 📝 Notes

- Make sure your `my_portfolio.csv` is filled with your tech stack and links.
- If you see missing module errors, install them with `pip install <module-name>`.
- For best results, keep your dependencies up to date.

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 📧 Contact

Made with ❤️ by [Your Name]
