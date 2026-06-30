# 🧠 Kimi K2.6 Chat (Windows)

A simple AI chatbot powered by Moonshot AI's Kimi K2.6 model through Hugging Face Router.

## What You Need

Before running the project, make sure you have:

* Windows (this guide)
* Python 3.9 or newer
* A Hugging Face account
* A Hugging Face Access Token
  
---

## Quick Start

### 1. Get a Hugging Face Token
1. Sign in to Hugging Face.
2. Go to **Settings → Access Tokens**.
3. Create a new token.
4. Copy your token.
   
---

### 2. Download the Project
Place these files inside a folder:
```text
app.py
index.html
requirements.txt
```
---

### 3. Open Command Prompt
Open Command Prompt inside your project folder.

---

 Create a Virtual Environment

```cmd
python -m venv venv
```

Activate it:

```cmd
venv\Scripts\activate

```
---
 Install Dependencies

```cmd
pip install -r requirements.txt

```
---
 Set Your Hugging Face Token

Replace `your_token_here` with your actual Hugging Face token.

```cmd

set HF_TOKEN=your_token_here

```
---

 Run the Chatbot

```cmd

python app.py

```
---

## Open the Application

Open your browser and visit:

```text

http://127.0.0.1:7860

```

You can now chat with Kimi K2.6 and upload images for analysis.

---

## Model

```text

moonshotai/Kimi-K2.6:fireworks-ai

```

Used through Hugging Face Router.

---

## Troubleshooting

### HF_TOKEN not found

Make sure you ran:

```cmd

set HF_TOKEN=your_token_here

```

before starting the application.

### Port already in use

Close the application using port 7860 or restart your computer.
 

### Invalid Token

 Generate a new Hugging Face token and try again.
 
---

## License

MIT License

Made with Python, FastAPI, Gradio, and Kimi K2.6.

---
Made with ☕ and Python for developers who just want things to work.
