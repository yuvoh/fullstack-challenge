# CopoFi Full-stack Challenge
## Movie Database Manager

Thank you for taking the time to do our technical test.

You will be building a small app that integrates into a movies database. You will be building the front-end and an API that integrates with the database.

### Product Specifications
Your app should satisfy the following four user stories:

**As a** user running the application
**I can** search for movies by their title
**So that** I can find the movie I'm looking for

**As a** user running the application
**I can** view the rank of each movie
**So that** I know which movies are highly rated

**As a** user running the application
**I can** see the director, and the list of actors with the roles they played for each movie
**So that** I am able to check the cast of a movie

**As a** user running the application
**I can** add a new movie and set the genre
**So that** I keep the movie database up-to-date

**As a** user running the application
**I can** assign a director and actors with their roles to a movie
**So that** I am able to update the cast of new movies

#### Optional Extension

**As a** user running the application
**I can** see the highest ranking movie of each decade
**So that** I know which was the best movie each decade.

## Technical Specification

### Database

The database runs on MySQL in a Docker container. It follows the following schema:

![schema](https://relational.fit.cvut.cz/assets/img/datasets-generated/imdb_ijs.svg)

To run the database on your local machine:

```$ docker run -p 3306:3306 copofidev/moviedb```

The database should now be accessible at ```localhost:3306```.

To connect:

database=```imdb```,
username=```copofi```,
password=```copofi```


### Platform choice
- The API should be built using Node.js. You may use a framework on top (such as Express) if you wish.

- The front-end should be built using a modern web framework (e.g React, Angular)

## Guidelines
- Spend as much or as little time as you wish, but try to complete the core functionality if possible!
- Focus on good development practices rather than flashy features.
- Feel free to implement functionality in the way you think is best, as long as the user stories are satisfied.

## Submission
Your project should contain everything needed to run your app, *excluding* your ```node_modules``` folder.

Please include a README file explaining the step(s) needed to run your app.

Place your project in a ZIP file and email it us when complete, along with the answers to the following questions (you may place the answers in the ZIP file):

1. How long did you spend on the test?
2. What would you add to your solution if you had more time?
3. Is there anything about the full-stack challenge you did not like?
4. Any other comments!
