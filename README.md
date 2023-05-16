
# Authorization Form - Practice


A client has contacted you with a request to improve their website. They love the website, but they want to hide their contact page behind a password form to protect their personal information.

To achieve this, you'll create a React component that sets up a simple authorization layer for the contact page.

If you encounter any difficulties during the project or would like to watch a video walkthrough by an experienced developer, you can click on "Get Unstuck" for assistance.

Let's begin!



## Objective: 

The objective of this task is to add password authorization functionality to the Contact.js component. The contact information should only be visible when the user enters the correct password.

## Instructions:

1. Open the Contact.js file in your code editor.
2. Inside the Contact.js file, locate the Contact function component. This component represents the Contact page.
3. In the Contact component, there is a function called `handleSubmit()` that handles user authorization.
4. Look at the title of the Contact page, displayed as a heading (`<h1>` element) in the return statement. Currently, it shows "Contact". Modify the heading to display "Enter the Password" if the user is not authorized. We will use conditional rendering for this.
5. Create a new variable named `login` just before the return statement. Assign it a JSX <form> element with the attribute `action="#"` to prevent redirection.
6. Inside the `<form>` element, add two input fields (<input> tags). The first input field should have the type attribute set to "password" and a placeholder attribute set to "Password". The second input field should have the type attribute set to "submit".
7. Declare another variable named `contactInfo` after the `login` variable. Assign it an empty pair of parentheses `()`.
8. Move the existing `<ul>` element from the return statement inside the `contactInfo` variable.
9. In the return statement, use a ternary operator to conditionally render either `contactInfo` or `login`. If the user is authorized, display the `contactInfo` variable, which contains the contact information. Otherwise, display the `login` variable, which contains the password entry form.
10. Add an `onSubmit` attribute to the `<form>` element and set its value to the `handleSubmit` function. This ensures that the `handleSubmit` function is called when the user clicks the submit button.
11. Save the changes to Contact.js.
12. Test the functionality by entering different passwords. When an incorrect password is entered and the submit button is clicked, nothing should happen. However, when the correct password "swordfish" is entered, the contact information should be revealed.

## Expected Result:
After completing the steps, the Contact page will prompt the user to enter a password. If the password is correct, the contact information will be displayed. If the password is incorrect, the password entry form will remain visible.

*Note: Remember to refer to the React documentation or other learning resources for guidance and assistance while completing this task.*
  
  Happy coding!


