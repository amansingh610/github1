# Student Record Management System in C

A simple **console-based application** written in C to manage student records.  
It provides functionalities to add, view, search, modify, and delete student details.  
The project uses file handling (`record.txt`) to store data for persistence.

---

## 📌 Features
- Add new student records
- View all records in a structured format
- Search a student by name
- Modify an existing student’s details
- Delete a student record
- Data persistence using file handling

---

## 🛠️ Technologies Used
- **C Programming Language**
- **File Handling** (`record.txt`)
- **Windows Console Functions** (`gotoxy` for cursor positioning)

---

## 🚀 Getting Started

### Prerequisites
- A C compiler (e.g., GCC, MinGW, Turbo C)
- Windows OS (for `conio.h` and `windows.h` support)

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/student-record-management.git
   cd student-record-management
   ```
2. Compile the program:
   ```bash
   gcc program.c -o student.exe
   ```
3. Run the executable:
   ```bash
   ./student.exe
   ```

---

## 📂 File Structure
```
student-record-management/
│── program.c     # Source code
│── record.txt    # File where student data is stored (auto-created/updated)
│── README.md     # Documentation
```

---

## 📖 Usage
1. Run the program.
2. Use the menu options:
   - `1` : Add Record
   - `2` : View Record
   - `3` : Search Record
   - `4` : Modify Record
   - `5` : Delete Record
   - `6` : Exit

---

## ⚠️ Note
- This project uses `gets()` which is unsafe in modern C standards.  
- Recommended to replace with `fgets()` for safety in future updates.

---

## 🤝 Contributing
Contributions are welcome! Feel free to fork the repository and submit pull requests.

---

## 📜 License
This project is licensed under the MIT License.
