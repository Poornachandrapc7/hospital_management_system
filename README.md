**Hospital Management System in C**

**Introduction:**

This is a simple Hospital Management System written in C programming language. It provides basic functionalities like adding patient information, viewing patient information, searching for patients, editing patient information, and deleting patient information.

**Features:**

1. **Add Information:** Allows adding information for new patients including their name, disease, age, cabin number, and phone number.

2. **View Information:** Displays all the information of the patients currently stored in the system.

3. **Search:** Enables searching for patients based on different criteria such as serial number, name, disease, cabin number, phone number, and age.

4. **Edit Information:** Allows editing information of existing patients. Information such as name, disease, age, cabin number, and phone number can be modified.

5. **Delete Information:** Provides options to delete patient information. Users can choose to delete the entire record or specific fields like name, disease, age, cabin number, or phone number.

**Usage:**

1. **Compile:** Compile the code using a C compiler like GCC.

   gcc hospital_management_system.c -o hospital_management_system

2. **Run:** Execute the compiled program.

   ./hospital_management_system

3. **Options:** Upon running the program, users will be presented with a menu to perform various operations such as adding, viewing, searching, editing, or deleting patient information.

**File Handling:**

Patient information is stored in a file named "patient.txt". The program utilizes file handling functions to read data from and write data to this file. Upon execution, if the file does not exist, the program creates an empty file.

**Notes:**

- Ensure proper input format to avoid unexpected behavior.
- Take regular backups of the patient data file to prevent data loss.
- This system is designed for educational purposes and may require further enhancements for practical use in real-world scenarios.

**Contribute:**

Poornachandra (poornachandrapc777@gmail.com)