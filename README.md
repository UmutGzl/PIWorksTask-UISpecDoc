# PIWorks Technical Assignment Q5-UI Specialization Document
# User Management Page
**User Table:** 
- The user table is on the left side of the screen.
- There are 4 column:
	- ID: ID must be an integer and given by the system.
	- Username: Shows user name of every user.
	- email: Shows email addresses of all users.
	- enabled: Indicates if a user enabled or not.
- All columns have order button. Contents on a column can be ordered by high to low or low to high.
- When a user clicked, user's info appears on the field at the right of the screen. "New User" text changes to "Update User". 

**Input Area:**
- Input Area is on the right half of the screen.
- There are 6 component:
	- Username Text Field: Username can have blank space and limited with 6-25 character long.
	- Display Name Text Field: Display name can have blank space and limited with 6-25 character long.
	- Phone Text Field: String field with maximum 12 character long
	- email Text Field: Must pass domain check
	- User Role Dropdown Menu: This menu must have 3 choices as guest, admin and super admin.
	- Enabled Checkbox: Sets a flag that indicates if a user enabled or not.
- In this field, users can be created or updated.
- When "New User" button pressed, Input fields are empty and title is "New User".
- When any user chosen from table, Input fields filled with the information of chosen user and informations can be updated.

**New User Button:** 
- The new user button is on de top-left of the page.
- When this button pressed, Input area set "New User" format.

**Save User Button:** 
- The new user button is on de top-right of the page.
- If input area on "New User" form, Adds new user to the database and shows it in table.
- If input area on "Update User" form, informations of the user can be changed.
- Username, email and phone must be filled to operate. Otherwise, gives an error message.

**Hide Disabled User CheckBox:**
- Alongside of the new user button.
- If it is on "true" mode, Checks the flag of all users and only the users that have enabled flag 1 are shown.
