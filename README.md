# ATM Project in Assembly

This ATM project is implemented in Assembly language for the 8086 architecture. It simulates a basic ATM machine with functionalities such as withdrawing money, checking the account balance, and closing the ATM.

## Features

- PIN Code Verification: Users are required to enter a PIN code to access the main menu.
- Withdrawal: Users can enter the amount they want to withdraw from their account balance.
- Account Balance: Users can check their current account balance.
- Closing the ATM: Users can choose to close the ATM and end the program.

## Getting Started

To run the ATM project, you need an assembly environment or emulator that supports the 8086 architecture. One popular option is the Emu8086 emulator.

1. Install an assembly environment or emulator that supports the 8086 architecture.
2. Clone this repository or download the source code file.
3. Open the project in your assembly environment or emulator.
4. Assemble and run the code.

## Usage

1. Upon running the program, you will be prompted to enter your PIN code.
2. Enter the PIN code (default: 1234) using the keyboard.
3. After successful verification, the main menu will be displayed.
4. Choose an option by entering the corresponding number from the menu.
5. Follow the prompts to perform the selected action.
6. You can go back to the main menu or exit the program after completing an action.

## Customization

- PIN Code: You can customize the PIN code by modifying the `password` variable in the `.data` section.
- Default Balance: You can set the default account balance by modifying the `p` variable in the `.data` section.

## Contributing

Contributions to this project are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## Author

This ATM project was made by Ahmad as part of the BS-DFCS (Digital Forensics and Cyber Security) program.

## License

This project is licensed under the [MIT License](LICENSE).
