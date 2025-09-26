# contact_app_Application

The application allows users to perform standard CRUD (Create, Read, Update, Delete) operations on a list of contacts, where each contact has a name, phone number, and email address.


## ✨ Features

* **List All Contacts**: Display the names of all contacts stored in the application.
* **Add a New Contact**: Add a new person with their name, phone number, and email to your contact list.
* **View a Contact**: Search for a contact by name to see their full details.
* **Delete a Contact**: Remove a contact from the list using their name.
* **Update a Contact**: Modify the information of an existing contact.

## 🛠️ Project Breakdown

* `show_contacts(contacts)`: Prints the names of all contacts.
* `add_contact(contacts)`: Prompts the user for a new contact's details and adds them to the list.
* `delete_contact(contacts, name)`: Finds and removes a contact by their name.
* `update_contact(contacts, name)`: Finds a contact by name and updates their details with new user input.
* `open_contact(contacts, name)`: Searches for a contact and displays their information.

The main application logic runs inside a `while` loop, presenting a menu to the user and calling the appropriate function based on their choice.

## 🔮 Future Improvements

The notebook also outlines several key improvements to make the application more robust and real-world ready. This is a great place to continue developing the project!

* **Persistent Storage**:
    * Modify the code to save the contacts to a text file (e.g., `contacts.txt`).
    * This will ensure that the contact data is not lost every time the program restarts.
    * Each contact can be stored on a new line with fields separated by commas (CSV format).

* **Input Validation with Regex**:
    * Use **Regular Expressions** to validate all user inputs before saving them.
    * **Name**: Should only contain alphabets and spaces.
    * **Phone Number**: Must be exactly 10 digits long.
    * **Email**: Must follow a valid email format (e.g., `name@domain.com`).
    * **Date of Birth (DOB)**: Add a new `DOB` field and ensure it follows the `YYYY-MM-DD` format with valid day and month values.

## 💻 Technologies Used

* **Language**: Python 3
* **IDE**: Jupyter Notebook
