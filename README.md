# Automata Practical Exam - Section 5

## 👤 Student Info
- **Section Number:** 5
- **Tasks Solved:**
  1. DFA that accepts binary strings containing the substring `101`
  2. Turing Machine that recognizes binary numbers divisible by 3

---

## 📁 Project Structure

automata_practical_exam_<4549>/
│
├── dfa_101.py # DFA implementation (substring '101')
├── test_dfa_101.py # Unit tests for DFA
│
├── tm_divisible_by_3.py # Turing Machine implementation (div by 3)
├── test_tm_divisible_by_3.py# Unit tests for TM
│
├── 
└── README.md # This file


---

---

## 🧪 How to Run & Test

> ✅ These steps assume Python is installed on your machine.

### Step 1️⃣ – Open terminal and navigate to project folder:
```bash
cd automata_practical_exam_<4549>
```
--------------------------------------------------------

Step 2️⃣ – ▶️ How to Run Manually:

 ---


✅ Run DFA Manually:
1-python
2-from dfa_101 import DFA
3-dfa = DFA()
4-print(dfa.accepts("010101"))  # True
5-print(dfa.accepts("0100"))  # False

 -------------------------------------------------------------

✅ Run Turing Machine Manually:
1-python
1- from tm_divisible_by_3 import TuringMachine
2- tm = TuringMachine("110")  # 6 in binary or "111"
3- print(tm.run())
4-print(tm.accepts("110"))  # True
5-print(tm.accepts("111"))  # False
 
 -------------------------------------------------------------

🧪 Run Unit Tests (Optional):

>>>>pip install pytest
1-pytest
----or-----
2-python -m pytest test_dfa_101.py
3-python -m pytest test_tm_divisible_by_3.py






