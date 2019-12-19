# command line team profile generator

When running node index, app will prompt the user with several questions - allowing them to create a html page that includes several team members and their ID #s. 

* Functionality 

1. Inquirer will begin by prompting the user to create a manager profile. It will ask the user to enter the manager's name, followed by an ID # & email address. 
2. Inquirer will then prompt the user to either select another type of team member to add, or to finish adding team members. 
3. If 'Intern' or 'Engineer' are selected, Inquirer will prompt the user to enter the employee name, followed by an ID # & email address. 
4. 2 If 'finished' is selected, team will be generated and added into HTML format by having the answer pushed to an array, and populated through the respective HTML templates. 