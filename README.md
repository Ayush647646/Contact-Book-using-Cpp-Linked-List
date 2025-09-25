## 📌 Overview  
This project is a **ContactBook Management System** built using **C++**.  
It allows users to efficiently **store, edit, delete, search, and display contacts**.  
Contacts are also saved **offline in a text file** so that the data persists even after the program is closed.  

---

## 🚀 Features  
- ➕ **Add Contact** – Store new contacts with name and phone number  
- 🔍 **Search Contact** – Search either by **name** or **phone number**  
- ✏️ **Edit Contact** – Update an existing contact’s details  
- ❌ **Delete Contact** – Remove a contact by searching via name/number  
- 🗑️ **Delete All Contacts** – Clear the entire contact book in one go  
- 📋 **Display Contacts** – View all saved contacts in alphabetical order (Bubble Sort applied)  
- 💾 **Offline Save** – Contacts are saved in a text file (`contactbook.txt`)  
- 📂 **Reopen Contacts** – Restore saved contacts when reopening the program  

---

## 🛠️ Technologies Used  
- **C++** (Core Language)  
- **File Handling** (`fstream`, `ofstream`, `ifstream`)  
- **Data Structures** (Doubly Linked List)  

---

## 📂 Project Structure  

ContactBook/
│-- contactbook.cpp     # Main C++ source code
│-- contactbook.txt     # File where contacts are saved
│-- README.md           # Project documentation

---

## ▶️ How to Run  
1. Clone this repository:
   git clone [https://github.com/your-username/ContactBook.git](https://github.com/Ayush647646/Contact-Book-using-Cpp-Linked-List)

2. Navigate into the project folder:
   cd ContactBook
   
3. Compile the program:
   g++ contactbook.cpp -o contactbook
  
4. Run the program:
   ./contactbook

---

## 📸 Sample Output

What is your name: Ayush
********************
 Ayush Welcome To ContactBook   
********************
 1. Add Contact
 2. Edit the Contact
 3. Delete Contact
 4. Search Contact
 5. Display All Contacts
 6. Delete All Contacts
********************
 Enter the Command: 

---

## 📌 Future Enhancements

* Add **CSV/JSON support** for better file handling
* Implement **case-insensitive search**
* Use **STL containers (map/vector)** for more efficient operations
* GUI version of the ContactBook

---

## 👨‍💻 Author

**Ayushman Gupta**

