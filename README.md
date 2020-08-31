# Sign-In Saver
**[NOT FINISHED]**
Sign-In Saver is a python 3 program that was created by Tommy Truong and allows users to add, edit, and save sign-in information to a JSON file. Users can easily and safely save sign-in information for many different websites/applications to an encrypted JSON file on their personal computer.

**Security Note:**

Since the JSON file is *only* saved on your computer and *not* sent to any online server/database, your information *isn't* accessible/editable by anyone else *unless* your physical *hard drive/ssd* that stored the JSON file was *stolen* from your computer.

~~The JSON file is currently *not* encrypted by the program. So, your information *is* readable to others if they open the JSON file on your personal computer. The program currently *doesn't* have a password feature as well, which would only allow the user to see the saved information if the correct password was entered.~~

The program encrypts the JSON file so that the information is completely unintelligible unless the file's contents are decrypted within the program after the user enters the correct password.

## Setup:
Before running the program, make sure to install the modules in the *requirements.txt* file.

## All Options:
After signing into program with the program password the user set up, users can easily *add* new sign-in information (website/application, email, password, username, and phone number), select and *delete* specific sign-in information from the file, *edit* specific parts of selected saved data, *print* all saved data to console, *change the password* used by the program to access user data, and *exit* the program.
