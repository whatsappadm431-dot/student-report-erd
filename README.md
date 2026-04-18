# 📘 Student Report System ERD

## 📖 Introduction
This project presents an Entity Relationship Diagram (ERD) for a Student Report System. The ERD shows how different entities in the system are structured and related.

## 🌐 Use of GitHub
The system design was based on analysis of a GitHub repository containing database migration files. The tables were identified from the `database/migrations` directory.

## 🧱 Entities
The following entities were identified:
- Students
- Class Forms
- Subjects
- Exams

## 🔑 Attributes
Each entity contains important attributes:
- Students: id, name, email, class_form_id  
- Class Forms: id, form_name  
- Subjects: id, subject_name  
- Exams: id, exam_type, exam_date, subject_id  

## 🔗 Relationships
The relationships between entities are:
- One Class Form has many Students (1:M)
- One Subject has many Exams (1:M)

## 🗺️ ERD Diagram
![ERD Diagram](./your-image-name.png)

## 🧠 Explanation
The ERD diagram shows how data is organized in the system. Foreign keys are used to connect tables, ensuring data integrity and reducing redundancy.

## 🚀 Tools Used
- GitHub (for analysis and submission)
- draw.io (for ERD diagram creation)

## 🏁 Conclusion
The ERD provides a clear structure of the Student Report System. It shows how entities are connected and how data flows within the system.
