# Card-Project-localstorage
## Hosted Link: [Click Here](https://bagheladarsh007.github.io/Card-Project-localstorage/)

## UI:
<img width="836" alt="Screenshot 2023" src="https://github.com/bagheladarsh007/Card-Project-localstorage/assets/142333682/33052bc5-7a8c-4a2e-9e18-acae945858bd">


---
## Explanation:

`HTML:`

* You have a basic HTML structure with a title, link to a CSS file, and two scripts, one for Font Awesome icons and one for your custom JavaScript.
* The user interface consists of a button for toggling the dark theme and a card that displays user information fields.

`CSS:`

* You've applied some styling to create a visually appealing user information card.
* You have implemented a dark theme toggle feature with styles for both light and dark themes.

`JavaScript:`

* You define an object called fields that contains labels for user information fields.
* You have functions to:
* `fillDetails():` To populate the user details in the card, with the option to edit or add new details.
* `changeField(key):` To change a specific field by removing it from localStorage.
* `resetAll():` To clear all user details.
* `toggleDarkTheme():` To toggle the dark theme and update the button icon.

Your code is well-structured and functional, creating a user-friendly interface for managing user information with a toggleable dark theme. However, there's a minor issue with your dark theme button not properly updating the icon. I noticed you are trying to toggle the button content based on the flag variable, but it seems the toggle variable is not defined. To fix this, you should declare the toggle variable, which is the button element, at the beginning of your JavaScript code:

`let toggle = document.querySelector("#toggle");`

Once you make this adjustment, your dark theme toggle should work correctly.

Overall, your code is nicely organized, and your user interface is visually appealing. It allows users to manage their information effectively and switch between light and dark themes.
