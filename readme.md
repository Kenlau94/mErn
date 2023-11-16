# MERN Challenge: Book Search Engine

## Tasks

Your Challenge this week is emblematic of the fact that most modern websites are driven by two things: data and user demands. This shouldn't come as a surprise, as the ability to personalize user data is the cornerstone of real-world web development today. And as user demands evolve, applications need to be more performant. This assignment was probably the most difficult, mainly the deployment to heroku.

## Challenges

The biggest headache was trying to get this application using mongo atlas. Creating the db and linking it to heroku which was then to link to github was a nightmare. I spent hours trying to deploy but to no avail. The first issue was deploying it to heroku, my file structure was not optimal and caused issues pushing and creating from develop and from a seperate mErn file i created. Then after that was creating the mongo atlas and linking it to heroku using the credentials. After that, there where errors in actually running the app through the terminal. I created another repo and tried to run it off of that repo but that caused further issues that i was unable to solve even with with chat gtp, senior devs, tutors and other classmates. After messing with it for hours, feeling like i was causing more issues then solutions, and having such a limited time constraint, called it. Working with other classmates and seeing their project up and running, hurts that my final challenge did not run properly. If you have any feed, please let me know via comments or email at kenlauwork94@gmail.com.

## Acceptance Criteria

- GIVEN a book search engine
- WHEN I load the search engine
- THEN I am presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button
- WHEN I click on the Search for Books menu option
- THEN I am presented with an input field to search for books and a submit button
- WHEN I am not logged in and enter a search term in the input field and click the submit button
- THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site
- WHEN I click on the Login/Signup menu option
- THEN a modal appears on the screen with a toggle between the option to log in or sign up
- WHEN the toggle is set to Signup
- THEN I am presented with three inputs for a username, an email address, and a password, and a signup button
- WHEN the toggle is set to Login
- THEN I am presented with two inputs for an email address and a password and login button
- WHEN I enter a valid email address and create a password and click on the signup button
- THEN my user account is created and I am logged in to the site
- WHEN I enter my account’s email address and password and click on the login button
- THEN I the modal closes and I am logged in to the site
- WHEN I am logged in to the site
- THEN the menu options change to Search for Books, an option to see my saved books, and Logout
- WHEN I am logged in and enter a search term in the input field and click the submit button
- THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site and a button to save a book to my account
- WHEN I click on the Save button on a book
- THEN that book’s information is saved to my account
- WHEN I click on the option to see my saved books
- THEN I am presented with all of the books I have saved to my account, each featuring the book’s title, author, description, image, and a link to that book on the Google Books site and a button to remove a book from my account
- WHEN I click on the Remove button on a book
- THEN that book is deleted from my saved books list
- WHEN I click on the Logout button
- THEN I am logged out of the site and presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button

## Grading Requirements

### Technical Acceptance Criteria: 40%

Satisfies all of the preceding acceptance criteria plus the following:

Has an Apollo Server that uses GraphQL queries and mutations to fetch and modify data, replacing the existing RESTful API.

Use an Apollo Server and apply it to the Express.js server as middleware.

Include schema settings for resolvers and typeDefs as outlined in the Challenge instructions.

Modify the existing authentication middleware to work in the context of a GraphQL API.

Use an Apollo Provider so that the application can communicate with the Apollo Server.

Application must be deployed to Heroku.

### Deployment: 32%

Application deployed at live URL.

Application loads with no errors.

Application GitHub URL submitted.

GitHub repository contains application code.

### Application Quality: 15%

User experience is intuitive and easy to navigate.

User interface style is clean and polished.

Application resembles the mock-up functionality provided in the Challenge instructions.

### Repository Quality: 13%

Repository has a unique name.

Repository follows best practices for file structure and naming conventions.

Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.

Repository contains multiple descriptive commit messages.

Repository contains a high-quality README file with description, screenshot, and link to the deployed application.

## Heroku

[Heroku no Work](https://newmern-8fe69d722ee4.herokuapp.com/)

## Repositories

I created another repo and tried to move my code over to try to correct structural errors. No Go =/

[Main Repo](https://github.com/Kenlau94/mErn)

[Second Test Repo](https://github.com/Kenlau94/newMerN)


![last project =(](https://github.com/Kenlau94/mErn/assets/134185724/2769f5b0-f1c5-4112-a381-770421d508bb)

