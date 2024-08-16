# Contact Book - Python Application

## Overview

This is a simple Contact Book application built using Python. It allows users to add, search, update, and delete contact details. The contact details include a person's name, phone number, email address, and other optional information. The contacts are stored persistently in a file, so they remain available between sessions.

## Features

- **Add Contacts**: Add new contact information including name, phone number, email, and address.
- **Search Contacts**: Search for a contact by name or phone number.
- **Update Contacts**: Edit contact details such as phone number, email, or address.
- **Delete Contacts**: Remove unwanted contacts.
- **View All Contacts**: Display the list of all contacts.
- **Persistent Storage**: Contact data is stored in a file (e.g., CSV or JSON) for later retrieval.

## Prerequisites

Make sure you have Python installed on your system. You can download it from [python.org](https://www.python.org/).

## How to Run

1. Clone the repository or download the script to your local machine:
    ```bash
    git clone https://github.com/yourusername/contact-book-python.git
    cd contact-book-python
    ```

2. Run the Python script:
    ```bash
    python contact_book.py
    ```

3. Follow the prompts to manage your contacts.

## Usage

Once you run the application, you will be shown a menu with options to manage your contacts:

```
1. Add a new contact
2. Search for a contact
3. Update a contact
4. Delete a contact
5. View all contacts
6. Exit
```

You can select an option by entering the corresponding number.

### Example

```
1. Add a new contact
2. Search for a contact
3. Update a contact
4. Delete a contact
5. View all contacts
6. Exit

Enter your choice: 1
Enter contact name: John Doe
Enter phone number: +1234567890
Enter email address: john@example.com
Enter address (optional): 123 Main St, Cityville
Contact added!

Enter your choice: 2
Enter the name or phone number of the contact to search: John Doe
Found contact:
Name: John Doe
Phone: +1234567890
Email: john@example.com
Address: 123 Main St, Cityville
```

## File Structure

- `contact_book.py`: The main script containing the logic for managing contacts.
- `contacts.json` (or `contacts.csv`): A file where contact information is saved.

## Future Improvements

- Add support for sorting contacts alphabetically or by other criteria.
- Implement categories for contacts (e.g., Work, Family, Friends).
- Add data validation for phone numbers and email addresses.
- Create a graphical user interface (GUI) for easier management.
- Encrypt contact details for better privacy and security.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributions

Feel free to fork this repository and submit pull requests for any improvements or bug fixes!
