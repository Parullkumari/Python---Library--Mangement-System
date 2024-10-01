# LIBRARY-MANAGEMENT-PYTHON

## SYNOPSIS
A simple Library Management System project in Python designed for college students, utilizing basic programming constructs.

## DESCRIPTION
v~ 1.
The Library Management System is a Python console-based program that includes major modules such as librarian, admin, borrowing, and returning books. It facilitates essential library tasks like borrowing books on specific dates, returning books, and managing book inventories.

#### FEATURES 
-	User-friendly interface with options for admins, new sign-ins, and librarians.
-   Allows users to borrow books, return books, add new users, and manage fines for overdue returns.
-   Persistent storage of data, including book lists and user details, maintained in text files.

#### OUTCOME 
-	The entire outcome is accomplished in interpreter mode, where the user has many different choices to select such as being an admin, new sign in, librarian, booklist in text file, etc…
-	Based on choices the user can navigate through various parts like borrowing a book, adding new user, paying fine, if delayed returns and a lot more.

#### STRUCTURE TO TAKE INPUT AND DISPLAY OUTCOME 
-	It is based on choice of entry. The entire input revolves around, entering numbers, strings and date.
-	Numbers corresponds to choices and string does to name of books, etc…
-	The output resembles the actual Library Management System where the user can experience various features as mentioned.

#### PYTHON MODULE AND APPLICATION USED 
-	The most common python module used is if, elif, and else to check various conditions to achieve the objective of the program.
-	Also the while loop construct used here helps to iterate through some particulars in the code such as execution of choices, etc…
-	The try method is also used the provide the smooth running of code instead of getting crashed.

#### FILES WITH THEIR MEANING
- Amem.txt stores the details of the admin.
- Borrower.txt stores the details of borrower.
- Stock.txt stores the details of all the books in the library.
- Additionally Borrow-Borrower_name.txt stores the exclusive details of borrower and his list of books taken with date of issue.
- Also Return-Borrower_name.txt stores the exclusive details of borrower and his list of books returned with date of return and fine accumulated.


## INSTRUCTIONS
- Should have ```Python3``` installed.
- Download the project, or enter the following in terminal ```if you have git installed``` :-
```
- Select the SRC folder.
- Run the following command in the terminal :-
```bash 
py Librarian_main.py

```
## USAGE

Upon running the program, users will be prompted to select an option corresponding to their role (admin, librarian, borrower, etc.). Follow the on-screen instructions to navigate through the library management functionalities.
