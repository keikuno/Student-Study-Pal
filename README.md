# Student-Study-Pal

## Application Description
Student Study Pal is a console-based Python application designed to help students manage and improve their academic performance by organizing study schedules, tracking deadlines, creating quizzes, and monitoring their weekly progress in one centralized system.

The application allows users to:

- Add and view study schedules with date, time, and task description.
-	Track academic tasks, deadlines, and mark if it is completed.
-	Create and take quiz manually by subject with automatic scoring.
-	Monitor the progress of student and the tasks needed to be done and already done.

Built with a clean console-based interface, the system follows a structured Input → Process → Output model and operates entirely offline. Data is saved and retrieved using a local JSON file, ensuring reliable performance without relying on external databases or internet connectivity.
Through this application, students can improve their time management, stay organized, and increase academic productivity.

## OOP Concepts Used
- Encapsulation - Data of each class (Schedule, Quiz, Deadline, StudyHour, DataProcessor) will be protected through private attributes and can only be controlled through methods. 
- Abstraction - IInputReader and IOutputWriter interfaces define standard methods for input and output operations.
- Polymorphism - Input and Output interfaces allow different implementations without modifying the entire code. 
- Loose Coupling - Components will be designed to run independently and easily replaceable by using dependency injection.

## Technologies Used
- Python (core programming language) 
-	Python (core programming language) 
-	unittest (built-in testing framework) 
-	JSON (file handling for data persistence)
-	JSON (file handling for data persistence)

# Project Structure
```
  student-study-pal/
│
└── Student Study Pal.py
    ├── Schedule Class
    ├── Deadline Class
    ├── Quiz Class
    ├── StudyHour Class
    ├── DataProcessor Class
    ├── IInputReader Interface
    ├── IOutputWriter Interface
    ├── ConsoleInputReader Class
    ├── ConsoleOutputWriter Class
    ├── StudentStudyPalApp Class
    └── Unit Tests
```

## How to Run
1.	Requirements: Python 3.x 
2.	Clone this repository:
	```bash
		git clone https://github.com/keikuno/Student-Study-Pal.git

## Navigate to the project folder:
	  ```bash
	  cd Student-Study-Pal
	  ```
	  
## Run the Application:
	```bash
	python "Student Study Pal.py"
	```
	
## Running Tests
- Tests run automatically on startup before the application launches. The terminal will display each test result.

## Author
Developed as a school project by:
- Keirsten M. Dipon (https://github.com/keikuno)
- Kath Mariela M. Borabo (https://github.com/kmb-1203)
- Bernadette G. Españo (https://github.com/quievous)

In Partial Fulfillment of the Requirements for the Subject CC103 Computer Programming 2 Under the Course of Bachelor of Science in Information Technology at Sorsogon State University Bulan Campus. With the Supervision of our Professor John Mark Gabrentina.
