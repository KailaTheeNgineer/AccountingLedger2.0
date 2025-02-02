Accounting Ledger CLI Application

Overview:

      The Accounting Ledger CLI Application is a Java-based tool designed for tracking 
      financial transactions. It provides a command-line interface (CLI) for users to 
      manage deposits, payments, and view transaction history efficiently.

Features:

      Transaction Management:
      
            o	Add deposits with details such as date, time, description, 
                vendor, and amount.
            o	Record payments with similar detailed information.
            
	Ledger Display:
 
            o   View the entire transaction history.
            o	Custom search.
            o	Filter to view only deposits or payments.
            o	Improved display for a more user-friendly experience.

Financial Reports:

      Generate predefined reports for:
      
            -	Month-to-date
            -	Previous month
            -	Year-to-date
            -	Previous year

Error Handling:

            o	Updated error catch mechanisms to ensure smooth and accurate 
                transaction management.
            o	Clear error messages to guide users in correcting issues.

Code Highlights

      Comparable Interface:
            The implements keyword in Java allows access to an interface, 
             such as Comparable.
      
            o	Similar to a class but contains empty methods to be defined with @Override.
            o	The compareTo method, part of the Comparable interface, enables object comparison.
            
      compareTo Method:
      
            The compareTo method is used for sorting Transactions objects by date.
            •	Utilizes the compareTo method from LocalDate for date comparison.
            •	Compares the current object's date with the next object's date:
            o	Returns -1 if the current object's date is before the next object's date.
            o	Returns 0 if the dates are equal.
            o	Returns 1 if the current object's date is after the next object's date.
This method ensures that Transactions objects are sorted in chronological order.

Getting Started:

      Prerequisites
            •	Java Development Kit (JDK) installed

Usage:

      1.	Clone the repository.
      2.	Navigate to the project directory.
      3.	Compile and run the application.
      4.	Use the CLI to add deposits, record payments, and view the ledger.

License:

      This project is licensed under the MIT License.

![UpdatedLedgerDisplay](src/main/resources/UpdatedLedgerDisplay.PNG)
![Payment](src/main/resources/Payment.PNG)
![AccountLedgerError](src/main/resources/AccountLedgerError.PNG)
![Ledger](src/main/resources/Ledger.PNG)
![Reports](src/main/resources/Reports.PNG)
![Goodbye](src/main/resources/Goodbye.PNG)

## Team members
### Courtezz Johnson
- [GitHub](https://github.com/courtezz)
### Erika Rodriguez
- [GitHub](https://github.com/Erikarod27)
### Katherine Colon
- [GitHub](https://github.com/KatherineColon)
### Kaila McAlpine
- [GitHub](https://github.com/KailaTheeNgineer)
### Yordiana Rodriguez
- [GitHub](https://github.com/Yordiana0912)

