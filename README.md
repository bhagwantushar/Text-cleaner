# Text-cleaner

## 📌 Overview
This is a simple Python project that **cleans up messy text** by removing special characters, numbers, and extra spaces. It also converts the text to lowercase for consistency.  

👉 Example use case: preparing raw text for **AI/ML preprocessing** or cleaning user input in apps.  

---

## ⚡ Features
- Removes **special characters** (e.g., `! @ # $`)  
- Removes **digits** (e.g., `123`)  
- Converts text to **lowercase**  
- Removes **extra spaces**, keeping only single spaces between words  

---

## 🎯 Input vs Output

### Input:
Hello!!!

### Output:
hello

## 🛠️ How It Works
1. Loops through each character in the input.  
2. Keeps only alphabets and spaces.  
3. Converts the final result into lowercase.  
4. Collapses multiple spaces into one.  

---

## ▶️ How to Run
1. Clone/download the repository.  
2. Run the script with Python:  
   ```bash
   python text_cleaner.py
