# 🕵️‍♂️ Mystery Unfolds – Detective Game

## 📖 Overview
**Mystery Unfolds** is a Windows Forms detective game built with **C# and OOP concepts**.  
The player takes on the role of a detective investigating a mysterious murder in an old mansion.  
Through interrogation, puzzle-solving, and evidence collection, the detective must uncover the truth and identify the criminal.

---

## 🎮 Storyline
An old man has been found murdered in his mansion.  
Five suspects are under investigation:
- The Butler  
- The Jealous Nephew  
- The Ex-Wife  
- The Secretive Housemaid  
- (One more hidden suspect revealed later...)  

The detective explores the mansion rooms (Kitchen, Library, Garden, Study Room, Guest Room), collects clues, solves puzzles, and records notes in the diary to uncover the culprit.

---

## 🛠 Features
- **Character Selection**: Choose detective (male or female).  
- **Narration**: Story introduction with crime scene investigation.  
- **Suspect Interrogation**: Ask questions and log answers in the detective’s diary.  
- **Room Exploration**: Each room has clues, puzzles, and riddles to solve.  
- **Inventory System**: Collected evidence is stored in the inventory.  
- **Diary System**: Notes and findings are automatically recorded.  
- **Decision Making**: At the end, the player must identify the criminal.  
  - ✅ Correct choice → Detective gets promoted.  
  - ❌ Wrong choice → Detective gets fired.  

---

## 🧩 Example Puzzles & Riddles
Each room contains:
- **2 puzzles** (unlock safes, decode clues, solve logic problems)  
- **2 riddles** (to reveal hidden hints)  

Example:  
- *"I speak without a mouth and hear without ears. I have nobody, but I come alive with wind. What am I?"* → Answer: **Echo**

---

## 💻 Technologies Used
- **Language:** C#  
- **Framework:** .NET (Windows Forms)  
- **Paradigm:** Object-Oriented Programming (OOP)  
- **Design:** Forms, Buttons, Textboxes, Panels for GUI  

---

## 📂 Project Structure
- **DetectiveGameForm.cs** – Main GUI form  
- **Classes:**  
  - `GameItem` (abstract) → `Evidence`, `Puzzle`  
  - `Suspect` → `Criminal`  
  - `Detective`  
  - `Inventory`  
  - `Diary`  
  - `Location`  
  - `GameManager`  

---# 🔮 Future Improvements
- Add animations and sound effects.  
- Introduce more suspects and branching storylines.  
- Save/Load game functionality.  
- Difficulty levels (Easy, Medium, Hard).  

---
