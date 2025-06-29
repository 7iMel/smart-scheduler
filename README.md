# Smart Scheduler 
The Smart Scheduler is a Python console application designed to help students, teachers, and administrators efficiently schedule exams while avoiding time conflicts. It provides an intuitive interface for adding, editing, deleting, and viewing exams, complete with automatic duration calculation and conflict detection.

## Features
- Add exams with unique exam code, exam name, exam date
- Start and end time (with automatic duration calculation)
- Exam room
- Automatic detection of scheduling conflicts
- Edit existing exam details
- Delete exams
- View all scheduled exams in a clear, organized formatValidates date and time inputs for accuracy

## Technologies Used
- Python 3.x
- Standard Python libraries (datetime)
- No external dependencies required

## How to Run the Application
1. Clone the Repository
   git clone https://github.com/7iMel/smart-scheduler.git

   cd smart-scheduler
3. Run the Program
   python smart_scheduler.py
   Follow the On-Screen Menu

## Project Structure
smart-scheduler/

├── smart_scheduler.py    

├── README.md                       


## Example Interaction
=== SMART SCHEDULER ===
1. Add Exam
2. View Exams
3. Edit Exam
4. Delete Exam
5. Exit

- Enter a number from (1–5): 1 
- Enter exam code (Ex. MATH112): COMP101 
- Enter exam name: Computer Science Fundamentals 
- Enter exam date (YYYY-MM-DD): 2025-07-10 
- Enter start time (HH:MM): 09:00 
- Enter end time (HH:MM): 11:00 
- Enter exam room: Room 101 
- Exam added successfully! Duration: 2h 0m 

## Future Improvements
- Persistent storage using files (e.g., JSON or CSV)
- Graphical User Interface (GUI) version using Tkinter or PyQt
- Web-based version with Flask or Django
- Advanced conflict detection across multiple dates

## Contributions
Contributions, suggestions, and improvements are welcome! Feel free to:
- Fork the repository
- Open issues
- Submit pull requests

## License
This project is licensed under the MIT License.

## Authors
1. Imelda Pauline M. Pailande
2. Rio M. Samuray
3. Stiffi Joyce Tumandao 
4. Elton John O. Porbus
