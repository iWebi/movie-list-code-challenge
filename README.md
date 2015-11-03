# movie-list-code-challenge
A developer code challenge for a basic RESTful web API powered by Python and bottle.

This code challenge highlights an understanding of the following RESTful concepts:

 - HTTP methods
 - request & response handling
 - resources

## Background

You've joined a local amateur movie critic club. They're looking for a way to keep track of the movies being reviewed. There's already someone that will build a web application but need someone to implement the back end. You have offered to build a RESTful web api to handle the back end logic and data storage.

## Requirements
Design and implement a RESTful web API using Python (2.7), and Bottle (0.12) to maintain the watch list of movies to be reviewed. 

The API should have methods to:  
* Return a list of Movies
* Add a movie
* Update movie details
* Delete a movie

For full credit, all the responses can be hard coded (no data back end needed).

### Movie details

Each movie should contain the respective details:  
* Title
* Release Date
* Production Company

### Tests
The application should inlcude appropriate unit tests (unittest library is sufficient).
Anything over 75% code coverage is considered acceptable.

## Extra credit
1. Create API documentation using RAML spec (http://raml.org/)
2. Implement a real-time CRUD with a database back-end using either Redis or MongoDB.
2. Implement unit tests using the nose library.
  * Tests should not have a dependency on a database instance.

## Taking the challenge

1. Fork this repository
2. Implement the requirements
3. Document the installation instructions in the README.md
4. When completed, submit a pull request to this repository.
  * Note: PRs will never be merged, they are just used for review.

Tip: make sure to include a requirements.txt
