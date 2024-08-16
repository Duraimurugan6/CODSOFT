# Password Generator - Python Application

## Overview

This is a simple Python application that generates secure and random passwords. The generated passwords can be customized by length and can include letters, numbers, and special characters. This tool is useful for creating strong, unique passwords for various online accounts to enhance security.

## Features

- **Custom Length**: Generate passwords of any specified length.
- **Character Set Customization**: Choose to include lowercase letters, uppercase letters, digits, and special characters.
- **Randomized**: Ensures passwords are random and secure.
- **Copy to Clipboard**: Option to automatically copy the generated password to the clipboard (optional).

## Prerequisites

Make sure you have Python installed on your system. You can download it from [python.org](https://www.python.org/).

Some additional packages might be required:
```bash
pip install pyperclip  # Required for copying to clipboard (optional)
```

## How to Run

1. Clone the repository or download the script to your local machine:
    ```bash
    git clone https://github.com/yourusername/password-generator-python.git
    cd password-generator-python
    ```

2. Run the Python script:
    ```bash
    python password_generator.py
    ```

3. Follow the prompts to generate a password based on your preferences.

## Usage

Once you run the application, you'll be prompted to customize your password:

```
Enter the desired length of your password: 12
Include lowercase letters? (y/n): y
Include uppercase letters? (y/n): y
Include numbers? (y/n): y
Include special characters? (y/n): y
Your generated password: g7&Sn2#hA9!P
```

If the clipboard functionality is enabled, the password will automatically be copied to your clipboard after generation.

## Example

```
Enter the desired length of your password: 16
Include lowercase letters? (y/n): y
Include uppercase letters? (y/n): y
Include numbers? (y/n): y
Include special characters? (y/n): y
Your generated password: Xd4!zQw6&9Mb2Y$N
Password has been copied to clipboard!
```

## File Structure

- `password_generator.py`: The main script containing the logic for generating random passwords.

## Future Improvements

- Add the ability to save generated passwords to a file or password manager.
- Add the option to exclude ambiguous characters (e.g., O, 0, l, 1) for better readability.
- Create a graphical user interface (GUI) for easier usage.
- Add strength analysis for generated passwords (e.g., entropy score).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributions

Feel free to fork this repository and submit pull requests for any improvements or bug fixes!
