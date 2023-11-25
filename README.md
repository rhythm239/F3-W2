Description
This project is a simple web application that includes a signup page, profile page, and basic user authentication functionalities. The implementation adheres to the provided Figma design and includes features such as mandatory fields, local storage for user details, access control, a logout button, and success/error message displays.

Features
Signup Page:

Create a signup page following the design in Figma.
All fields on the signup page are mandatory.
User State:

Store user details, including a randomly generated 16-byte access token, in local storage upon successful signup.
Profile Page:

Develop a profile page based on the Figma design.
Display user details retrieved from local storage.
Logout:

Implement a "Logout" button on the profile page.
When clicked, clear the local storage and redirect the user to the signup page.
Access Control:

Use JavaScript to implement access control.
If a user attempts to manually navigate to the "Profile" page without an access token in local storage, redirect them to the signup page.
Similarly, if a user with a valid access token tries to manually navigate to the "Signup" page, redirect them to the profile page.
Success and Error Messages:

Display appropriate success and error messages according to the UI design.
Technologies Used
HTML
CSS
JavaScript
How to Run
Clone the repository: git clone https://github.com/your-username/repo-name.git
Open the project in your preferred code editor.
Launch the application by opening the index.html file in a web browser.
Additional Notes
Ensure a modern web browser is used for optimal performance.
The project has been designed to be responsive, but it is recommended to check on various devices for any specific adjustments.
Contributing
Feel free to contribute to the project by opening issues or creating pull requests. Your input is valuable in enhancing the functionality and usability of the system.
