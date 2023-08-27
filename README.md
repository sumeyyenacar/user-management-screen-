## Requirements

The user management screen should allow users to:

* View a list of all users
* Search for users by name or email address
* Create new users
* Edit existing users
* Delete users

## UI Components

The user management screen should have the following UI components:

* **Header:** The header should contain the title of the screen, the user's name, and the user's profile picture.
* **Table:** The table should display a list of all users. The table should show the following information for each user:
The screen should be evenly divided into two. There should be a table on the left side of the screen where the information about the added users can be displayed.A filtering option should be added for each section.
    * Name
    * User Name
    * Email
    * Enabled
 
* **New User:** A new user can be added or user details can be edited.
    * Name (text input)
    * Display Name (text input)
    * Email (text input)
    * User Roles (Guest, Admin, Super Admin) (dropdown select)
    * Enabled (tick box)
* **Buttons:** Buttons for creating new users, editing existing users, and deleting users.
   * There is a blue add "new user" button at the top left of the page.
   * In the upper right part of the page, the "save user" button is used to save the changes made.
  
## Behavior

When the user management screen is first loaded, it should show a list of all users. The user can then search for users by name or email address. If the user finds the user they are looking for, they can click on the user's name to view their details.

To create a new user, the user must fill out the form and click on the "Create User" button. To edit an existing user, the user must click on the user's name and then fill out the form. To delete a user, the user must click on the user's name and then click on the "Delete User" button.

## Initial State

The user management screen should initially show a list of all users. The user should be able to search for users by name or email address.

## Error Handling

The user management screen should handle the following errors:

* The user enters an invalid search term.
* The user tries to create a new user with a duplicate email address.
* The user tries to edit an existing user with a duplicate email address.
* The user tries to delete a user who does not exist.

## Accessibility

The user management screen should be accessible to users with disabilities. The following features should be implemented to make the screen accessible:

* The table should be navigable using the keyboard.
* The search bar should be navigable using the keyboard.
* The buttons should be navigable using the keyboard.
* The form should be navigable using the keyboard.
* The error messages should be clear and concise.

## Documentation

The user management screen should be well-documented. The documentation should include the following information:

* A description of the screen's purpose.
* A description of the screen's features.
* Instructions on how to use the screen.
* Error messages.
* Accessibility features.

## Testing

The user management screen should be tested to ensure that it meets all of the requirements. The following tests should be performed:

* The screen should be tested with different search terms.
* The screen should be tested with different values for the user's name, email address, role, department, and manager.
* The screen should be tested for errors.
* The screen should be tested for accessibility.

## Deployment

The user management screen should be deployed to a production environment. The screen should be monitored to ensure that it is working properly.

## Additional Notes

* The user management screen should be designed to be consistent with the rest of the Microsoft Office 365 user interface.
* The user management screen should be designed to be easy to use, even for users with limited technical skills.
* The user management screen should be designed to be secure, protecting user data from unauthorized access.
