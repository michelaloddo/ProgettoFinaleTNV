# ProgettoFinaleTNV
Web application for sorting and reviewing movies

The primary objective of this web application is to offer an interactive user interface that allows for viewing, sorting, and reviewing movie posters.

Retrieval and display of movies:
The application retrieves 10 movies using an external API, showcasing their respective posters to the user in a random order.

User interaction:
Users must order the posters based on a criterion randomly generated by the system (e.g., ranking, release year, etc.).
Once ordered, the user confirms the selection by clicking on a button.

Scoring and leaderboards:
10 points are awarded for each movie placed correctly.
The user leaderboard, based on the points secured, is updated and made accessible within the application.

Saving and reviewing movies:
Users have the option to save movies to a favorites list, rate them, and insert a brief review (max 160 characters).
Movies can be removed from the favorites list.

Authentication: Access to the system is through a backend (BE) service implemented with Springboot.
Review Submission: The insertion of reviews is managed through a BE service developed in Node.js.

--------------------------------------------------------------------------------------------------------------------------------------------------------

Technologies implemented

Backend:
Springboot, that manages user authentication and the communication interface with the external API for retrieving movie data.
Interacts with the frontend for managing the ordering process and for the allocation of points.
Node.js, that manages CRUD operations related to user reviews, including the insertion, reading, and deletion of reviews.


Frontend:
Angular, responsible for displaying the posters, the ordering interface, and general user interactions.

External API:
Utilized to retrieve information about movies and their respective posters.

Database:
MySQL to store user information and reviews.
