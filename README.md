# 📝 Task Manager (Python)

A simple **Python Task Manager** application.  
Features:
- Add a new task  
- View all tasks  
- Mark tasks as complete  
- Delete a task by ID  
- Delete all tasks  
- Save & load tasks from `task.txt`  

---

## 📦 Requirements
- Python 3.x  
- [PyInstaller](https://pyinstaller.org/) (only if you want to build a `.exe`)  

Install PyInstaller:
```bash
pip install pyinstaller
▶️ How to Run
1. Run with Python
python task_manager.py

2. Build into .exe

Inside the project folder, run:

pyinstaller --onefile task_manager.py


After building, your .exe will be inside:

dist/task_manager.exe


👉 You can just run task_manager.exe directly.
