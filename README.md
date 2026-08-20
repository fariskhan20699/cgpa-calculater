# 🎓 Student GPA & CGPA Calculator

A console Based **Student GPA/CGPA Calculator** developed in **C++** using Object Oriented Programming (OOP) concepts.

The program allows users to enter a student's subjects, credit hours, and grades, then calculates the total credit hours and overall GPA/CGPA. It also displays scholarship eligibility based on the calculated GPA.

---

## 🚀 Features

- 👤 Enter student name
- 📚 Add multiple subjects
- ⏱️ Enter credit hours for each subject
- 📝 Enter grades for each subject
- 📊 Automatically calculate grade points
- 🧮 Calculate total credit hours
- 🎓 Calculate overall GPA/CGPA
- 🏆 Check scholarship eligibility
- 🎨 Colored console output
- 📋 Display a detailed subject-wise result

---

## 🛠️ Technologies Used

- **C++**
- **Object Oriented Programming (OOP)**
- **STL Vector**
- **Constructors**
- **Encapsulation**
- **Getters & Setters**
- **Loops**
- **Conditional Statements**
- **Functions**

---

## 🧱 OOP Concepts Used

### 1. Encapsulation

Student and subject data members are kept private and accessed through public member functions.

```cpp
class Subject {
private:
    string name;
    int creditHour;
    string grade;
};
