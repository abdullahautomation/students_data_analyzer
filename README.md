# 🎓 Student Result Analyzer

A Python tool that reads student marks from a CSV file and generates a professional color-coded Excel report automatically.

Built with **Python**, **Pandas**, and **openpyxl**.

---

## 🖥️ Output Preview

![Messy Data](screenshots/messy.png)
![Clean Report](screenshots/clean.png)

---

## ✨ Features

- Reads student marks from CSV file
- Auto-calculates average for each student
- Pass/Fail decision based on average
- Color-coded output — Green = Pass, Red = Fail
- Professional borders and formatting
- Yellow header row for clarity

---

## 📦 Requirements

```bash
pip install pandas openpyxl
```

---

## 🚀 How to Use

1. Clone the repository:
```bash
git clone https://github.com/abdullahautomation/student-result-analyzer.git
```

2. Add your CSV file in this format:
Name,Math,English,Science
Ahmed,75,60,80
Sara,45,30,55
3. Run the script:
```bash
python main.py
```

---

## 📁 Project Structure
student-result-analyzer/
│
├── main.py          # Main script
├── students.csv     # Sample input file
├── README.md        # Documentation
└── screenshots/     # Output previews
---

## 🛠️ Built With

- [Python](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/)
- [openpyxl](https://openpyxl.readthedocs.io/)

---

## 👨‍💻 Author

**Abdullah**  
🔗 [GitHub](https://github.com/abdullahautomation)  
🌐 [Fiverr](https://www.fiverr.com/abdullah7514)

---

## 📃 License

This project is open source and available under the [MIT License](LICENSE).