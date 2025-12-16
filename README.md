# Student_perfomance_ML_project
<img width="1269" height="513" alt="Screenshot 2025-12-16 213012" src="https://github.com/user-attachments/assets/8a9b395e-c036-49ac-a6b0-3bcb3cd0c6f6" />


# 🎓 Student Performance Classification (Decision Tree & Random Forest)

A front-end only machine learning simulation project that classifies students based on their **CGPA / SGPA up to V semester** using **Decision Tree rules** and a **Random Forest-style voting mechanism**.

This project is ideal for **academic mini projects**, **ML concept demonstrations**, and **front-end based data classification**.

---

## 📌 Features

- Clean and responsive UI
- Student data entry (Name, Roll No, Branch, Sem I–V CGPA)
- Automatic average CGPA calculation
- Decision Tree based classification
- Random Forest-style classification (3 trees + majority voting)
- Color-coded performance badges:
  - Outstanding
  - Good
  - Average
  - At Risk
- Delete individual student entries
- Clear all student data
- Duplicate roll number validation
- Mobile-friendly design
- No backend required

---

## 🧠 Classification Logic

### Decision Tree
A rule-based approach using:
- Average CGPA
- Latest semester performance

Example:
- `avg ≥ 8.5` → Outstanding / Good
- `7 ≤ avg < 8.5` → Good / Average
- `avg < 6` → At Risk

---

### Random Forest (Simulated)
- Simulates 3 independent decision trees
- Each tree uses:
  - Average CGPA
  - Last semester CGPA
  - Performance trend
- Final classification is selected using **majority voting**

> ⚠️ This is a conceptual simulation, not a trained ML model.

---

## 🛠️ Tech Stack

- **HTML5** – Structure
- **CSS3** – Styling & responsiveness
- **JavaScript (Vanilla)** – Classification logic
- **No backend**
- **No external libraries**

---

## 📂 Project Structure

