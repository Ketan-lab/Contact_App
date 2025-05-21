# 📇 Contact Management System

A simple Python-based contact management system that allows you to **add**, **view**, **delete**, **update**, and **search** contacts from a list. The program also allows exporting contacts to a CSV file.

---

## 📌 Overview

This project is a beginner-friendly Python console application to manage contacts using a dictionary-based structure. It includes a command-line interface to interact with users and persistently update the in-memory contact list. CSV export functionality is included for saving data.

---

## 🎯 Features

- Add new contacts (name, number, email)
- View all contacts
- Open and view individual contact details
- Delete a contact
- Update contact information
- Interactive menu system
- Export contacts to a `.csv` file

---

## 🖥️ How to Run

1. Clone the repository or download the Python file.
2. Ensure Python 3 is installed on your system.
3. Run the script using:

```bash
python contact_manager.py

🛠️ Code Structure
contacts: The main list storing contact dictionaries.

show_contacts(): Displays names of all contacts.

add_contact(): Adds a new contact to the list.

delete_contact(name): Removes a contact by name.

update_contact(name): Allows updating contact details.

open_contact(name): Displays details of a single contact.

opens_contact(name): Lets user choose to delete or update.

CSV export logic to contacts.csv.

📦 Sample Data Structure

contacts = [
    {'name':'ketan', 'number':9604663983, 'email':'ketantalware@gmail.com'},
    {'name':'ashvin', 'number':123456789, 'email':'ashivin@gmail.com'},
    {'name':'aiadventure', 'number':987654321, 'email':'aiadventure@gmail.com'}
]

💡 Example Usage

Press 'a' - add contact, 'o' - open contact, 's' - search contact, 'q' - quit: a
Enter the name: John
Enter the mobile number: 1234567890
Enter the email ID: john@example.com

✅ Contact added!


📁 Output
Contacts will be exported to:
contacts.csv

Sample content:
name,number,email
ketan,9604663983,ketantalware@gmail.com
ashvin,123456789,ashivin@gmail.com
...

✍️ Contributors
Ketan Talware – Developer & Documentation

📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

🧠 Future Enhancements
GUI using Tkinter or PyQt

Persistent storage using SQLite

Search feature enhancement

Input validation and error handling

📬 Feedback
If you find any issues or have suggestions, feel free to open an issue or submit a pull request.
