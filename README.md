# Snake Water Gun Game 🐍💧🔫

This is a simple **Snake–Water–Gun game** written in **Python**.  
The user plays against the computer, which makes a random choice.

---

## 🎮 Game Rules

- **Snake (s)** beats **Water (w)**
- **Water (w)** beats **Gun (g)**
- **Gun (g)** beats **Snake (s)**
- Same choices result in a **Draw**

---

## 🧠 Choices Mapping

| Input | Meaning |
|------|--------|
| s | Snake |
| w | Water |
| g | Gun |

---

## 🛠 How the Program Works

1. The computer randomly chooses:
   - `1` → Snake  
   - `-1` → Water  
   - `0` → Gun  

2. The user enters their choice (`s`, `w`, or `g`)

3. The program compares both choices and:
   - Declares **Win**, **Lose**, or **Draw**

---

## ▶️ How to Run the Program

1. Make sure Python is installed
2. Open terminal in the project folder
3. Run:
   ```bash
   python main.py
