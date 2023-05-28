![image](https://github.com/Linf0rd/random-password-generator/assets/122806756/6ab8404c-4ba5-4d7e-bae6-6068a5050a80)


# Random Password Generator
This is a Bash script that generates random passwords and allows the user to store them in a password manager.

## Features
- Generate random passwords of any length between 8 and 48 characters.
- Progress bar display during password generation.
- Option to add the generated password to a password manager.
- Option to launch the password manager.
- Menu-driven interface.

## Usage
1. Clone the repository.
2. Open a terminal and navigate to the cloned repository directory.
3. Run the script using the following command: ./RPG
4. Follow the on-screen instructions to generate passwords and/or manage them using the password manager.

## Options
1. Generate random passwords: Allows the user to generate random passwords of any length between 8 and 48 characters. The generated password can be added to the password manager if desired.
2. Launch Password Manager: Allows the user to launch the password manager.
3. Exit: Exits the script.


#

![image](https://github.com/Linf0rd/random-password-generator/assets/122806756/4d06cf84-1bfc-4f40-a6a3-cc18f05c56b1)

# Random Password Manager
The password manager is a separate Bash script that allows the user to view and manage the passwords they have generated using the password generator script. The password manager provides the following options:

1. View passwords: Displays a list of all stored passwords.
2. Search passwords: Allows the user to search for a specific password by account name.
Delete password: Allows the user to delete a password by account name.
3. Exit: Exits the password manager.

## Dependencies
The script requires/uses the following dependencies:

OpenSSL

## Security
The passwords are stored in plaintext in a file called passwords.txt. For better security, you can encrypt the file using a tool like GPG and ask the user to unlock it using their own key. Additionally, you can modify the script to use a more secure method of generating passwords, such as using the pwgen command or generating passwords using a cryptographically secure random number generator.

## Contributing

Contributions are welcome! If you have any suggestions, please feel free to create an issue or submit a pull request.

## License

This project is licensed under the [MIT License](https://github.com/Linf0rd/random-password-generator/blob/main/LICENSE).
