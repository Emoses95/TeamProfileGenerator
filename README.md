# TeamProfileGenerator

## User Story

A manager
WANTS to generate a webpage that displays his team's basic info
SO THAT he has quick access to their emails and GitHub profiles


## Acceptance Criteria

GIVEN a command-line application that accepts user input
WHEN a user is prompted for their team members and their information
THEN an HTML file is generated that displays a nicely formatted team roster based on user input
WHEN a user clicks on an email address in the HTML
THEN a default email program opens and populates the TO field of the email with the address
WHEN a user clicks on the GitHub username
THEN that GitHub profile opens in a new tab
WHEN a user starts the application
THEN a user is prompted to enter the team manager’s name, employee ID, email address, and office number
WHEN I enter the team manager’s name, employee ID, email address, and office number
THEN a user is presented with a menu with the option to add an engineer or an intern or to finish building my team
WHEN a user selects the engineer option
THEN a user is prompted to enter the engineer’s name, ID, email, and GitHub username, and I am taken back to the menu
WHEN a user selects the intern option
THEN a user prompted to enter the intern’s name, ID, email, and school, and I am taken back to the menu
WHEN a user decides to finish building their team
THEN a user exits the application, and the HTML is generated


