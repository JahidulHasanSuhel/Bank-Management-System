# `Bank Management System`

A `Bank Management System` built using `Java`, `AWT`, `Swing`, and `MySQL`. This project simulates the functionalities of an ATM, allowing users to perform banking operations such as deposits, withdrawals, balance checks, and password changes.

## `Table of Contents`
- *About the Project*
- *Features*
- *Technologies Used*
- *Installation*
- *Usage*
- *File Descriptions*
- *Screenshots*
- *Contributing*

## `About the Project`
This project is a `Bank Management System` that simulates the functionalities of an ATM. It allows users to:

- `Create and manage bank accounts`.

- `Perform transactions such as deposits and withdrawals`.

- `Check account balance and view mini-statements`.

- `Change account PIN securely`.

- `Withdraw cash quickly using predefined amounts (Fast Cash)`.

The system is built using `Java` with `AWT` and `Swing` for the graphical user interface (GUI) and `MySQL` for database management. It is designed to provide a simple and intuitive user experience for managing banking operations.

## `Features`
**`User Authentication:`**
- Log in to access your account.
- Sign up to create a new account.

**`Account Management:`**
- Change account PIN securely.
- View account balance.

**`Transaction Operations:`**
- Deposit funds into your account.
- Withdraw funds from your account.
- Fast Cash withdrawal (predefined amounts like 100, 500, etc.).

**`Mini-Statement:`**
- View a summary of recent transactions.

**`Dashboard:`**
- Access all banking operations from a single interface.

## `Technologies Used`
- `Java` - Core programming language.

- `AWT (Abstract Window Toolkit)` - For basic GUI components.

- `Swing` - For advanced GUI components and enhanced user interface.

- `MySQL` - For database management (storing user accounts, transactions, etc.).

- `JDBC (Java Database Connectivity)` - For connecting the Java application to the MySQL database.

## `Installation`
Follow these steps to set up the project locally:
**`Prerequisites:`**
- `Java Development Kit (JDK)` - Installed on your machine.

- `MySQL` - Installed and running on your machine.

- `MySQL Connector/J` - JDBC driver for MySQL (included in the project or downloadable from MySQL's website).

Steps:
**`1. Clone the Repository:`**
```
git clone https://github.com/JahidulHasanSuhel/bank-management-system.git
```
**`2. Set Up the Database:`**
- Open MySQL and create a new database:
```
CREATE DATABASE bank_management_system;
```
- Import the provided SQL file (if any) to create the necessary tables:
```
USE bank_management_system;
```
**`3. Configure Database Connection:`**

- Open the Connect.java file in your project.

- Update the database connection details:
```
String url = "jdbc:mysql://localhost:3306/bank_management_system";
String username = "your-mysql-username";
String password = "your-mysql-password";
```
**`4. Run the Project:`**
- Import the project into your preferred IDE (e.g., IntelliJ IDEA, Eclipse).

- Locate the Main.java file (or the main class).

- Run the file to start the application.

## `Usage`
**`Log In:`**

- Use your credentials to log in to your account.

**`Sign Up:`**

- Create a new account by providing your details.

**`Main Interface:`**

`Access all banking operations:`

- `Cash Withdraw`: Withdraw custom amounts.

- `Fast Cash`: Withdraw predefined amounts (e.g., 100, 500).

- `Mini-Statement`: View recent transactions.

- `PIN Change`: Update your account PIN.

- `Balance Check`: View your current balance.

- `Deposit`: Add funds to your account.

**`Log Out:`**
- Securely log out of your account.

## `File Descriptions`

`Here’s a breakdown of the files in your project and their purposes:`

`Login.java`

- Handles user authentication (login).

`SignUp.java`

- Allows users to create a new account.

`SignUp2.java`

- Additional page for the signup process (e.g., collecting more user details).

`Connect.java`

- Manages the connection to the MySQL database.

`FastCash.java`

- Handles Fast Cash withdrawals (predefined amounts like 100, 500).

`BalanceCheck.java`

- Displays the user’s current account balance.

`Deposit.java`

- Handles deposit operations.

`mini.java`

- Displays a mini-statement of recent transactions.

`pin.java`

- Allows users to change their account PIN.

`withdraw.java`

- Handles custom cash withdrawals.

`Main.java`

- The main interface that provides access to all banking operations (Cash Withdraw, Fast Cash, Mini-Statement, PIN Change, Balance Check, Deposit).

## `Screenshots` 
`SingUp Screen:`

![Alt Text]()

`Login Screen:`

![Alt Text](https://github.com/JahidulHasanSuhel/Bank-Management-System/blob/master/loginPage.png)

`Main Interface:`

![Alt Text](https://github.com/JahidulHasanSuhel/Bank-Management-System/blob/master/MainInterface.png)

`Fast Cash:`

![Alt Text](https://github.com/JahidulHasanSuhel/Bank-Management-System/blob/master/FastCash.png)

`Mini-Statement:`

![Alt Text](https://github.com/JahidulHasanSuhel/Bank-Management-System/blob/master/MiniStatement.png)

`PIN Change:`

![Alt Text](https://github.com/JahidulHasanSuhel/Bank-Management-System/blob/master/ChangePIN.png)

## `Contributing`
**Contributions are welcome! If you'd like to contribute to this project, please follow these steps:**
1. `Fork the repository.`

2. `Create a new branch:`
```
git checkout -b feature/your-feature-name
```
3. `Commit your changes:`
```
git commit -m "Add your feature"
```
4. `Push to the branch:`
```
git push origin feature/your-feature-name
```
5. `Open a pull request and describe your changes.`
