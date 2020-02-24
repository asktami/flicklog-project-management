# flicklog-project-management

[View Live](https://asktami.github.io/flicklog-project-management/)

Issues, Project, User Stories and Wireframes for FlickLog - 2nd Bloc.io Fullstack Capstone.

## App Name: FlickLog

## Descripton
### APP NAME: FlickLog 
### Movie diary and watchlist

-   use TheMovieDb API (https://www.themoviedb.org/)
-   1st screen shows instructions and buttons to browse / login / register
-   browse: search form to search for movies by title + list of moview noew playing in theatres
-   anyone can register and login
-   anyone can search for a movie and see movie details and reviews added by other users
-   only after logging in can users can add/update/delete a movie review; they can only edit/delete a review they created

- after logging in a user can search for movies, and:
	- can click on movie to:
		- add a review
		- add that movie to their ‘watch list’
	- can click on their 'watch list' to view a list of movies they want to see

## Top 5 Wireframes
  1. [Landing Page](https://asktami.github.io/flicklog-project-management/index.html)
  2. [Registration Form](https://asktami.github.io/flicklog-project-management/registration-form.html)
  3. [Login Form](https://asktami.github.io/flicklog-project-management/login-form.html)
  4. [Movie List](https://asktami.github.io/flicklog-project-management/movie-list.html)
  5. [Movie Detail](https://asktami.github.io/flicklog-project-management/movie-detail.html)

## Top 5 User Stories
### 1. As a new user I want to sign up for an account

REGISTRATION FORM
- user enters valid email & password and clicks submit -----> LOGIN FORM

- user enters invalid email/password and clicks submit -----> error message appears to supply valid email/password

- user enters an email that's already in the system -----> message appears that an account already exists with that email, login if its your account

-----
### 2. As a new user I want to log in to my account

LOGIN FORM
- user enters valid email & password and clicks submit -----> BROWSE page showing all movies +  "Watchlist", "Reviews" and "Logout" buttons

- user enters invalid email/password and clicks submit -----> error message appears to supply valid email/password

-----
### 3. As a new user I want to search for movies (can search for movies without logging in)
### 4. As a new user I want to see movie details

MOVIE LIST
- user, that has NOT logged in, searches for movies -----> sees MOVIE LIST page with movies that match the search criteria

- user, that HAS logged in, searches for movies -----> sees MOVIE LIST page with movies that match the search criteria + "Watchlist", "Reviews" and "Logout" buttons

-----
### 5. As a new/returning user I want to see movie details

MOVIE DETAILS
- user, that has NOT logged in, clicks on Movie Name (link) -----> MOVIE DETAILS page with list of MOVIE REVIEWS, and "Add to Watchlist" and "Review" buttons

- user, that has NOT logged in, if they click on the "Add to Watchlist" or "Review" button, they are taken to the login form

- user, that HAS logged in, clicks on Movie Name (link) -----> MOVIE DETAILS page with list of MOVIE REVIEWS, and the ADD REVIEW FORM, and if an existing REVIEW was created by the user, that REVIEW has UPDATE REVIEW and DELETE REVIEW buttons

- user, that HAS logged in, clicks on the "Add to Watchlist" button -----> movie is added to the user's WATCHLIST, and movie details screen will show text saying "in watchlist" instead of the "add to watchlist" button

- user, that HAS logged in, sees an "Add Review" form below the MOVIE REVIEWS instead of a "Review" button
