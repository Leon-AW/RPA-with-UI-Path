# RPA for Bookstore - UIPath Test

## Video Description:

### Overview:
This repository contains a test automation process using Robotic Process Automation (RPA) with UIPath. The purpose of the automation is to simulate the process of searching for and registering a book from the HU Library.

### Process Steps:

1. **Search for a Non-Existent Book:**
   - Enter a random string as a book title.
   - Click "OK" to initiate the search in the HU-Bibliothek.
   - A browser opens, attempting to find a book with the entered title.
  
2. **Handling No Results:**
   - If no book is found, the process prompts the user to enter another book title.
   - The browser closes.

3. **Search for an Existing Book:**
   - Enter the title of an existing book.
   - The browser opens again, and the title of the top book is copied.

4. **User Information Input:**
   - Prompt the user to enter their name.

5. **Date Entry:**
   - Prompt the user to enter the a date.

6. **Update Excel Database:**
   - The process updates an Excel file attached to the project.
   - The new book title, user name, and date are added to the last row of the Excel sheet.

### Simulation Details:

- The entire process simulates the online book selection and registration experience.
- The Excel file serves as a database, reflecting the library's records.

## How to Test RPA for Bookstore:

1. **Clone the Repository:**
   - Clone this repository to your local machine.

2. **Open UIPath:**
   - Navigate to the cloned repository.
   - Open the `Main.xaml` file in UIPath.

3. **Adjust Excel File Path:**
   - In the "Use Excel File" action, modify the path to the Excel sheet to match your local directory. This ensures UIPath can locate the Excel sheet.

4. **Run the Program:**
   - Click on "File," then choose either "Debug File" or "Run File" in the UIPath interface.
   - The program will execute the automation process.
