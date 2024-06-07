# Contact Manager

## Setup Instructions

1. Open the solution file (`ContactManager.sln`) in Visual Studio.
2. Build the solution to restore any missing NuGet packages.
3. Run the application.

## Tasks
1. **Fix the Bugs**:
	- Fix existing bugs in the application
	- Ensure Contact Listing and Add Contact both work properly

2. **Implement an Edit Feature**:
	- Need a new button on the Contact Listing to open a new Edit Form
	- This will open an edit form for the selected Contact 
	- The new form will have fields for all the Contact properties along with a save button
	- When the save is complete it will return to the listing and refresh the grid 
	
3.  **Implement a Contact Import**
	- Create a Contact file import that can be triggered from the Contact Listing form
	- The format of the file can be CSV or JSON, you can choose
	- Add some basic validation to ensure the file is valid
	- Provide a confirmation of the import to the user 

## Extra Optional Tasks

1. **Implement a Search Feature**:
	- Add a way of filtering the Contacts on the Contact Listing Form
   
2. **Implement an active flag for Contacts**:
	- Need to be able to filter the contact listing so it only displays contacts that are active

3. **Implement Error Handling and Validation**:
	- Currently none of the forms have any error handling or validation, implement this throughout

