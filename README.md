# SQL Exercise 4

sql pdf: https://drive.google.com/file/d/1d6qZTlxu_g44G1RraEx_snEtDkgQVbQz/view?usp=sharing

---
## Exercises
1. Create a table called Students with the following columns:

		StudentID (INTEGER, PRIMARY KEY)
		FirstName (VARCHAR(50))
		LastName (VARCHAR(50))
		TutorGroup (VARCHAR(10))

2. Create a table called Classes:

ClassID (VARCHAR(10), PRIMARY KEY)

Subject (VARCHAR(50))

3. Create a table called Enrollment:

StudentID (INTEGER)

ClassID (VARCHAR(10))

4. Alter the Students table:

Add a new column:

Email (VARCHAR(100))

✏️ PART B — DML (Data Manipulation Language)
5. Insert the following students:

(1, 'Alice', 'Brown', '11A')

(2, 'John', 'Smith', '11B')

(3, 'David', 'Tan', '10A')

(4, 'Anna', 'Khan', '11A')

6. Insert the following classes:

('CS1', 'Computer Science')

('MA1', 'Mathematics')

('EN1', 'English')

7. Insert enrollments:

(1, 'CS1')

(1, 'MA1')

(2, 'CS1')

(3, 'EN1')

(4, 'MA1')

8. Update student emails:

Alice → 'alice@gmail.com
'

John → 'john@gmail.com
'

9. Delete the student with StudentID = 3
🔍 PART C — SELECT (Queries)
10. Display all students’ first and last names.
11. Display all students in tutor group '11A'.
12. Display all students sorted by LastName.
13. Display students whose first name starts with 'A'.

👉 Must use LIKE

14. Display students whose last name contains 'an'.
15. Display:

FirstName

Subject

👉 Use JOIN across all tables

16. Display the names of students who take 'Mathematics'.
17. Display:

FirstName

Subject
Sort by Subject.

18. Display all students enrolled in 'CS1'.
19. Challenge 🔥

Display:

FirstName

LastName

Subject

ONLY for students:

in '11A'

AND subject contains 'Math'

👉 Must use:

JOIN

WHERE

LIKE

🧨 PART D — ADVANCED (Exam Push)
20. Delete all students in tutor group '11B'.
21. Drop the Enrollment table.
---



 
