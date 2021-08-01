Login logout functionality authentication system
1. Build routes - these are custom routes we will build for login and logout
2. Build login form, but won't be model backed form since there is no 'model'
   for logging in or out, we are simply simulating it.
## 
3. We will use : student_id of the student to identify them and start sessions
4. Some functions we will need to form
    - retrieve current user based on if someone is logged in
    - check if a user is currently logged in
    - require a logged in user to perform actions
    - make some of our methods available to views and controllers ##