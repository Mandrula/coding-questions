We need to create a web app in which users can rent and watch movies.
This app has the following requirements:

- Users only have a name and email address.
- Renting a movie is free, there is no subscriptions or payments of any kind.
- Users can only rent up to 2 movies per day.
- We are interested in keeping a history of all movies rented by users, which has the following information for each entry:
  - when they rented them
  - when they watched them
  - whether they finished them or not.
- After watching a movie, users may rank the movie with a number score from 1 to 10.

Given these requirements, we ask you to do the following tasks:

1. Assume this project will be implemented with PostgreSQL. Design the ERD for this system, documenting all non-trivial considerations taken.3
2. Now assume that we also want to expand our app, so not only movies can be rented, but tv shows as well. What needs to change (if anything) to support this new feature?
3. After accumulating a huge debt in our first quarter, we decided to implement a subscription service, so now users need to pay 8 dollars per month to continue having the same features, and users that choose not to pay anything, can only rent 1 movie or tv show per week. What would need to change in this case?
