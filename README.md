# Viona's Todo App

## User
1. Sign up a new user with POST /service/user/signup
![](signup request.png)
![](signup response.png)

2. OTP sent to the user's email
![](otp email.jpg)

3. Verify email with POST /service/user/verify-otp
![](verify email request.png)
![](verify email response.png)

4. Sign in with POST /service/user/signin
![](signin request.png)
![](signin response.png)

5. Update user details of an authenticated user with PATCH /service/user/update-user
![](update user request.png)
![](update user response.png)

6. Get user info of an authenticated user with GET /service/user/user-infor
![](user info request.png)
![](user inforesponse.png)

7. Delete a user of an authenticated user with DELETE /service/user/delete-user
![](delete user.png)

## Authorize
Authorize the account by inserting the token from the response when signing in.
![](authorization.png)

## Todo
1. Add a todo saved in an authenticated user’s account with POST /service/todo/add_todo
![](add todo request.png)
![](add todo response.png)

2. Update a todo saved in an authenticated user’s account with POST /service/todo/update_todo/{id}
![](update todo request.png)
![](update todo response.png)

3. Retrieve all the saved todos of an authenticated user’s with GET /service/todo/get_all
![](get all todo request.png)
![](get all todo response.png)

4. Delete a todo of an authenticated user with DELETE /service/todo/delete_todo/{id}
![](delete todo request.png)
![](delete todo response.png)

