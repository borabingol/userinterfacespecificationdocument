#	 Overview
With User Management Screen admins can manage users. This interface provides functions to create, edit, filter users and enable/disable accounts.
# Requirements
## Add New User
This function gives authorization to add users with details like username, display name, phone, email, roles, and enabled status.
## Filter and Search
Each column in the user list (ID, Username, Email, Enabled) includes a filter option to allow searching and sorting.
## Rename a file
You can rename the current file by clicking the file name in the navigation bar or by clicking the **Rename** button in the file explorer.
## Hide Disabled Users
Option to hide users who have been disabled.
## Edit and Save User
Option to edit user details and save changes.
# UI Components
## New User Button
###	 Label
"+ New User"
### 	Position
Top-left of the user table.
###	 Action
Opens the "New User" form on the right side, where user details can be added.
## Hide Disabled User Checkbox
###	 Label
"Hide Disabled User"
### 	Position
To the right of the "+ New User" button.
###	 Action
Filters out users with the "Enabled" status set to `false` in the user table.
## User Table
###	 Columns
#### 	ID
Displays the user's unique identifier.
####	 Username
Shows the username of each user. Has a search filter.
####	 Email
Shows the user’s email address. Has a search filter.
#### 	Enabled
Indicates if the user account is active (true/false). Has a filter option.
### 	Filter Options
Each column includes a filter dropdown to filter based on specific values or criteria.
### Sort Option
Columns can be sorted in ascending or descending order.
## New User Form
### Position
Right side of the screen when "+ New User" is clicked.
### Fields
#### Username
Text field to input the username.
#### Display Name
Text field for the display name.
#### Phone 
Text field to input the phone number.
#### Email
Text field for email input.
#### User Roles
Dropdown selection with options (e.g., Guest, Admin, SuperAdmin).
#### Enabled 
Checkbox to set the account as active/inactive.
### Save Button
#### Label
"Save User"
#### Action
Saves the user details, either creating a new user or updating an existing one.
# User Actions
## Add New User
Click on "+ New User".
Fill in the form on the right side.
Click "Save User" to create the new user.
## Edit User
Select a user from the table.
Modify the details in the form that appears on the right.
Click "Save User" to save changes.
## Hide/Show Disabled Users
Check or uncheck the "Hide Disabled User" checkbox to filter disabled users.
## 	Filter and Sort
Use filter options in each column header to narrow down search results.
Click on column headers to sort by ID, Username, Email, or Enabled status.

