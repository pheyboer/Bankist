# Bankist App
Bankist App is a banking application built using JavaScript, providing a seamless user experience for managing accounts, viewing transactions, making transfers, and more. This project is designed as a practice exercise to master modern JavaScript features such as ES6 syntax, DOM manipulation, and event handling. 

The app focuses on building a functional banking experience without relying on backend services, simulating the behavior of a real banking website with features like login authentication, money transfers, loan requests, and more.

## Features
- User Authentication: Secure login system for users to access their accounts.
- Account Management: View current balance, account movements (deposits, withdrawals), and account details.
- Money Transfers: Transfer funds between accounts with validation.
- Loan Requests: Apply for a loan, subject to account conditions.
- Sort Transactions: Sort transactions based on different criteria.
- Date Formatting & Time Zones: Display transactions and account information in a localized manner.
- Automatic Logout Timer: Ensures security by automatically logging out inactive users after a set period of inactivity, protecting account data.

## Technologies Used
- JavaScript (ES6+): For app logic and interactivity.
- HTML5: For creating the structure and layout of the app.
- CSS3: For styling the app and enhancing the user experience.
- Local Storage: For persisting user data (simulating backend storage).
- Babel: For ES6+ transpiling.

## Getting Started

### Installation
- Clone the repository: ```git clone git@github.com:pheyboer/Bankist.git```
- Open ```index.html``` in your browser to run the application.

### Useage
- Login: Use the following usernames and PINs to login:
  - User 1: Username: js, PIN: 1111
  - User 2: Username: jd, PIN: 2222

- Transactions:
  - Deposit or withdraw money by selecting the transaction type.
  - View transaction history, account balance, and available funds.

- Transfers:
  - Transfer money between users by selecting the recipient and amount.

- Loan Requests:
  - Apply for a loan with an amount greater than the requested threshold.

- Sorting Transactions:
  - Sort transactions by date or amount.

## Screenshots
![Home Page](https://github.com/pheyboer/Bankist/blob/main/bankist-app.png)

## Credits
This project is based on the Bankist App course by [Jonas Schmedtmann](https://www.udemy.com/course/the-complete-javascript-course/) on Udemy. Special thanks to Udemy for providing the platform and Jonas for the course content.

## License
This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).