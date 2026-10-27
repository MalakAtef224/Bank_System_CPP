# Bank System (C++)

A console-based banking system written in C++ using structs, vectors and functions.

## Features
- Create an account with a name, a unique 14-digit ID, a password (6+ characters) and an opening deposit (1,000 minimum)
- Login with ID and password
- Deposit money
- Withdraw money (20 fee per withdrawal)
- Check balance and account details
- Transfer money to another account (50 fee per transfer)
- Close an account with a y/n confirmation
- Input validation for IDs, amounts and menu choices

## Technologies
- C++
- Standard library: vector, string, algorithm

## How to Run
1. Download `main.cpp`
2. Compile it: `g++ main.cpp -o bank`
3. Run it: `bank` (Windows) or `./bank` (Linux/Mac)

You can also open `main.cpp` in Code::Blocks or Visual Studio and run it.

## Limitations
- Accounts are stored in memory only, so data is lost when the program exits
- Uses `system("color 8F")`, which works on Windows only

## Future Improvements
- Save accounts to a file or a database
- Hash passwords
- Add transaction history
