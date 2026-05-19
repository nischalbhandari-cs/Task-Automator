# ⚙️ Task Automator (AI-Powered Task Organizer)

Welcome to my Task Automator project! This Python application reads tasks from a text file and uses Google Gemini AI to automatically organize and generate responses for your tasks.

## 🎓 Learning Journey

As an aspiring AI Software Engineer, I built this project to gain hands-on experience with:

- API integration with Google Gemini
- Environment variables and security
- File handling in Python
- Prompt engineering
- Error handling

## 🚀 Features

- Password protected access
- Reads tasks from text file automatically
- Uses Google Gemini AI to organize tasks
- Secure API key storage using .env
- Error handling for missing files and API issues

## ⚙️ How to Setup & Run

### Step 1: Create .env file
```
GEMINI_API_KEY=your_actual_key_here
API_PASSWORD=your_password
```

### Step 2: Create tasks.txt
Add your tasks inside tasks.txt

### Step 3: Install dependencies
```
pip install google-generativeai python-dotenv
```

### Step 4: Run the program
```
python main.py
```

## 🧠 Code Breakdown

**load_dotenv**
Loads environment variables securely from .env file.

**os.getenv**
Retrieves API key and password securely.

**genai.configure**
Authenticates the Gemini API connection.

**generate_content**
Sends tasks to Gemini AI and receives organized response.

**try...except**
Handles errors gracefully and prevents crashes.

**File Handling**
Reads tasks automatically from tasks.txt file.

## 🔮 Future Improvements

- Add GUI interface
- Support multiple task files
- Export organized tasks to PDF
- Add task categories and priorities
- Build web version using Flask

## ⚠️ Note

This project was built for learning purposes.
Some parts of development were assisted using AI tools.

## 👨‍💻 Created By

Nischal Bhandari
GitHub: github.com/nischalbhandari-cs
