# 🏦 ATM Banking System | OIBSIP Task 3

## 📌 Project Overview

The **ATM Banking System** is a Java-based desktop application developed as part of the Oasis Infobyte (OIBSIP) Java Development Internship.

It simulates basic ATM operations through a graphical user interface built with Java Swing. The application demonstrates Object-Oriented Programming (OOP), account management, transaction processing, and input validation.

## ✨ Features

- 🔐 User authentication using User ID and PIN.
- 🚫 Access denial after three incorrect login attempts.
- 💰 Withdraw money after checking the available balance.
- ➕ Deposit money and update the account balance.
- 🔄 Transfer funds between demo bank accounts.
- 📊 Display the current account balance.
- 📜 View transaction history during the current session.
- 🚪 Logout and exit options.
- ✅ Validate transaction amounts and available balances.

## 🛠️ Technologies Used

- **Programming Language:** Java
- **GUI Framework:** Java Swing
- **IDE:** Eclipse IDE
- **Data Structure:** ArrayList
- **Core Concepts:** Object-Oriented Programming, encapsulation, classes, objects, and event handling.

## 🔑 Demo Login Credentials

| User ID | PIN | Account ID | Initial Balance |
|---|---|---|---:|
| `user1` | `1234` | `1001` | ₹10,000 |
| `user2` | `5678` | `1002` | ₹5,000 |

**Note:** These are demonstration credentials for an educational project, not real banking accounts.

## 📂 Project Structure

```text
ATMProject/
├── src/
│   └── atm/
│       ├── Main.java
│       ├── ATMGUI.java
│       ├── ATM.java
│       ├── Account.java
│       ├── Bank.java
│       └── Transaction.java
└── README.md
```

## ⚙️ How to Run

1. Install the Java Development Kit (JDK).
2. Open Eclipse IDE.
3. Import or create the ATM Banking System project.
4. Ensure all Java files are inside the `atm` package.
5. Open `Main.java`.
6. Right-click and select **Run As → Java Application**.
7. Log in using one of the demo accounts.
8. Test deposits, withdrawals, transfers, and transaction history.

## 💳 How to Use

1. Launch the application.
2. Enter a valid User ID and PIN.
3. Access the ATM dashboard after successful authentication.
4. Select an operation such as balance inquiry, deposit, withdrawal, or fund transfer.
5. Enter the required transaction details.
6. Review the updated balance or transaction confirmation.
7. View transaction history or log out when finished.

## 🎯 Learning Outcomes

- Applied Object-Oriented Programming concepts.
- Practiced encapsulation using classes and objects.
- Used `ArrayList` to maintain transaction records.
- Implemented login validation and transaction processing.
- Developed a graphical interface using Java Swing.
- Learned to organize a Java application into multiple classes.
- Practiced balance validation and basic account management.

## ⚠️ Limitations

- Account balances and transaction history are stored in memory.
- Data is not permanently saved to a database.
- This application does not connect to a real banking network.
- The demo authentication system is not suitable for production use.

## 📸 Screenshots and Demonstration

Add screenshots or a demonstration video showing:

- Login screen
- ATM dashboard
- Balance inquiry
- Cash deposit
- Cash withdrawal
- Fund transfer
- Transaction history
- Invalid login or insufficient balance validation

## 👩‍💻 Developer

**Vaishnavi Satish Yadav**  
Java Development Intern | Oasis Infobyte (OIBSIP)

## 🙏 Acknowledgement

I thank Oasis Infobyte for providing the opportunity to strengthen my Java programming, GUI development, and Object-Oriented Programming skills through practical projects.

## 📄 Disclaimer

This project is intended for educational purposes only. It is not a real banking application. All accounts, credentials, balances, and transactions are simulated for demonstration.
