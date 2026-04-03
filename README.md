# Microsoft-Access-Database-Project-Student-Result-Management-System
Microsoft Access-based database system designed to manage student academic records efficiently
This project is a Microsoft Access-based database system designed to manage student academic records efficiently.

It captures student information, assigns subjects, records CA and exam scores, and automatically generates total scores and grades.

---

## 🚀 Features

- Student registration and class assignment  
- Multi-subject score entry per student (via subform)  
- Combo boxes for user-friendly data selection  
- Automated total score calculation  
- Grade generation using conditional logic (IIf)  
- Structured and grouped student report  

---

## 🧱 Database Structure

Tables used:
- Students  
- Classes  
- Subjects  
- Results  

Relationships:
- Students → Results (one-to-many)  
- Subjects → Results (one-to-many)  
- Classes → Students  

---

## 🛠 Implementation Process

1. Designed relational tables with primary and foreign keys  
2. Created relationships to maintain data integrity  
3. Built queries to calculate total and grade  
4. Developed forms and subforms for data entry  
5. Used combo boxes to replace IDs with readable names  
6. Generated reports grouped by student  

---

## 📊 Sample Output

The system generates a structured report showing:
- Student details  
- Subjects offered  
- CA score  
- Exam score  
- Total score  
- Grade  

---

## 💡 Skills Demonstrated

- Relational database design  
- Data normalization  
- Query building and calculated fields  
- Form and subform development  
- Report design and formatting  