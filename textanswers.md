Part 1:
Step 1.
Follows has 2 foreign keys one for the the users being followed and one for the users that follow the current user.

Step 6.
The user logged in is being tracked of through session and then the g object.
g object is a global object that can be accessed by other routes and functions.
add_user_to_g stores the current logged in user in g so it can be accessed globally where needed.
The before request function runs before the every landing point on a website.