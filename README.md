## A Web login/sign-up page with Flask and Python

This is a personal project I am working on to refresh my memory on how to use Flask and Python for web development. I built a sign-up and a login page that allow users to log in and access protected pages. Also, I used information from the User model and displayed it on the protected pages when the user logs in to simulate what a profile would look like.

## Project outcome
In this project, I:

* Used the Flask-Login library for session management
* Used the built-in Flask utility for hashing passwords
* Added protected pages to the app for logged in users only
* Used Flask-SQLAlchemy to create a User model
* Created sign-up and login forms for the users to create accounts and log in
* Flashed error messages back to users when something goes wrong
* Used information from the user’s account to display on the profile page


## Improvement
What I created in this tutorial will be sufficient for smaller apps, but to have more functionality from the beginning, I will need to learn how to use either the Flask-User or Flask-Security libraries, which are both built on top of the Flask-Login library.


## Reference(s)
To implement this project, I followed this [tutorial](https://www.digitalocean.com/community/tutorials/how-to-add-authentication-to-your-app-with-flask-login)
