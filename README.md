## STUDENT DATA ORGANIZER AND MANUPULATER
#📌 Project Overview

Student Data Organizer is a Python-based menu-driven application that manages student records using Python collection data types such as List, Tuple, Set, and Dictionary.

This project demonstrates:

String formatting and manipulation

Collection data types

Mutability and immutability

Type casting

Use of the del keyword

Menu-driven programming


## 🔗 Project Links

- 🌐 Live Demo:https:https://drive.google.com/file/d/1mvUkrDcd_8G9XNgWkXM9Q1rMlLZlyv3v/view?usp=drivesdk
- 📧 Email:nigamchandan543@gmail.com


## SOME SREEN SHOT OF THIS CODES 
<img width="1080" height="529" alt="image" src="https://github.com/user-attachments/assets/cddb1d61-8f26-4e23-9120-bbf95a12de56" />
<img width="1080" height="511" alt="image" src="https://github.com/user-attachments/assets/b9b3784b-4319-4392-b3c2-65f6d5741edc" />
<img width="573" height="576" alt="image" src="https://github.com/user-attachments/assets/112011c6-6357-41c5-9d44-38f4e823dcc7" />
<img width="1376" height="768" alt="image" src="https://github.com/user-attachments/assets/ef4c3585-1d43-4058-9ecd-7c497b887534" />


---

🎯 Objective

The objective of this project is to create a system that stores, manages, updates, and deletes student records while demonstrating the use of Python collection data types and basic data management operations.


---

🛠️ Features

1. Add Student

Users can add a new student record by entering:

Student ID

Name

Age

Grade

Date of Birth

Subjects


2. Display All Students

Shows all student records in a formatted and user-friendly manner.

3. Update Student Information

Allows updating mutable information such as:

Age

Grade

Subjects


4. Delete Student

Deletes a student record using the student ID and the del keyword.

5. Display Unique Subjects

Displays all unique subjects using a Set to avoid duplicates.

6. Exit Program

Closes the application with a thank-you message.


---

📚 Python Concepts Used

List

Stores multiple student records.

Example:

students = []

Tuple

Stores immutable student information:

(student_id, dob)

Set

Stores unique subjects:

subjects_set = set()

Dictionary

Stores student details:

student = {
    "name": name,
    "age": age,
    "grade": grade,
    "subjects": subjects
}


---

🔄 Type Casting

Used to convert user input into required data types.

Example:

age = int(input("Enter Age: "))
student_id = int(input("Enter Student ID: "))


---

🗑️ Use of del Keyword

Example:

del students[index]

Used to remove a student record from the list based on Student ID.


---

📂 Project Structure

Student-Data-Organizer/
│
├── student_data_organizer.py
├── README.md
└── screenshots/


---

▶️ How to Run

Step 1

Install Python 3.

Step 2

Clone the repository:

git clone https://github.com/nigamchandan543-netizen/project_3.git)

Step 3

Navigate to the project folder:

cd student-data-organizer

Step 4

Run the program:

python student_data_organizer.py


---

📋 Sample Menu

===== STUDENT DATA ORGANIZER =====

1. Add Student
2. Display All Students
3. Update Student
4. Delete Student
5. Display Subjects
6. Exit

Enter your choice:


---

💡 Assumptions

Student ID must be unique.

Age and Student ID are numeric values.

Subjects are entered as comma-separated values.

Date of Birth is entered in DD/MM/YYYY format.

Student ID and Date of Birth remain unchanged after creation.



---

🚀 Future Improvements

File handling for permanent data storage.

Search student by ID.

Sort students by name or grade.

Export records to CSV file.

Graphical User Interface (GUI).



---

👨‍💻 Author

Chandan Nigam

Python Collection Manipulator Project


---

🙏 Thank You

Thank you for using Student Data Organizer. This project demonstrates practical usage of Python collection data types and data management techniques. ⭐
