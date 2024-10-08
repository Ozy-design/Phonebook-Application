# Phonebook-Application

### Project Overview

The project is aimed to perform efficient operations for a phonebook such as insert, 
search, display, update, delete, and sort.

### Insert Contacts

This process will enable the user to insert the contacts into the phonebook

## Algorithm for Inserting a Contact

Step 1: Define Constants
Set MAX_SIZE to 100 (the maximum number of contacts allowed in the phonebook).

Step 2: Initialize Phonebook
- Create an empty array called phonebook.

Step 3: Define the InsertContact Function
- Input: phonebook, name, phoneNumber
- Process: Check if Phonebook is Full

If the length of phonebook is greater than or equal to MAX_SIZE:
  Print "Phonebook is full. Cannot insert new contact."
  Exit the function.

- Create a New Contact: Create a new entry with fields for name and phoneNumber.

- Insert the Contact: Add the new contact to the end of the phonebook array.

- Print Confirmation: Print "Contact added: [name] - [phoneNumber]".

Step 4: Main Execution

Call the InsertContact function for each contact:
Insert "Amadhila V" with phone number "+264 81 221 7111".
Insert "Moses Erastus" with phone number "+264 81 209 7035".
Insert "Osvaldu Vasco" with phone number "+264 81 840 1588".
Insert "Mukete Shali" with phone number "+264 81 873 8758".
Insert "Beyonce Nghidamwasha" with phone number "+264 81 575 6425".
Insert "Andreia Panzo" with phone number "+264 81 256 0182".

This algorithm outlines the process for inserting a contact into a phonebook, detailing each step from initialization to the actual insertion and confirmation.



