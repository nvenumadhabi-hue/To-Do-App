# 📝 To-Do App (Google Colab - Simulated Full Stack)
This is a simple To-Do application that demonstrates full-stack logic using HTML, JavaScript, and Python in Google Colab—without any server, database, or ngrok tunnel. The frontend is built with HTML and JavaScript and rendered inside a Colab output cell. It communicates with a Python backend via `google.colab.output.register_callback`, simulating a real API call. Tasks are stored in Python memory (`tasks` list) and updated live in the frontend.
## 🚀 Features
- Add tasks dynamically via UI
- Tasks stored in Python backend
- Live updates without page reload
- No Flask, no deployment, no authentication tokens
## 📦 Technologies
- HTML + JavaScript (frontend)
- Python (backend logic)
- Google Colab `output.register_callback` for JS-Python communication
## ▶️ How to Run
1. Open [Google Colab](https://colab.research.google.com)
2. Paste the full code into a cell
3. Run the cell to launch the To-Do UI
4. Add tasks — they appear instantly and are stored in Python memory
## 📌 Limitations
- Tasks are not saved after runtime ends (no persistence)
- No delete/edit functionality (can be added easily)
- Runs only in Google Colab
## 💡 Extensions (Optional)
- Add delete functionality
- Save tasks to a `.txt`, `.json`, or SQLite file
- Use Google Sheets API for cloud storage
## 📂 File Structure
Single Python/Colab notebook containing:
- Python logic (backend)
- HTML+JS (frontend)
- Integrated execution via `display(HTML(...))`
✅ This project is ideal for learning frontend-backend interaction without deploying a server.
