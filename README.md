Friend Finder - 
Node and Express Servers

Compatibility based application
The application will take in results from users' surveys then compare their results against all other users who have completed it. The application will then display the name and picture of the user with the best match overall.

The survey has 10 questions, answers to the survey questions are on a scale of 1-5 based on how much the user agrees or disagrees.

Technical details
The application uses Express to handle routing

The server.js file uses the npm packages: express, body-parser, path.

The logic.js file should include two routes:

A USE route that leads to f-f.html which displays the home page.
The api-routes.js file includes two routes:

A GET route with the url /api/friends. This will be used to display a JSON of all possible friends
A POST route /api/friends. This will be used to handle incoming survey results. This route will also be used to handle the compatibility logic.
Compatibility will be determined based on the following.

Each user's results is converted into a simple array of numbers (ex: [5, 1, 4, 4, 5, 1, 2, 5, 4, 1]