# Viona's WADS LAB Week 8 Assignment

## Signing up a user using the POST /service/user/signup to create a new account
![image alt](Screenshots/signup request.png)
![image alt](Screenshots/signup response.png)

Once the signup is successful, the OTP is sent to the user's email. 
![image alt](Screenshots/email otp.jpg)

Then, the user can verify their email using the POST /service/user/verify-otp
![image alt](Screenshots/verify email request.png)
![image alt](Screenshots/verify email response.png)

## Signing in to an account using the POST /service/user/signin
![image alt](Screenshots/signin request.png)
![image alt](Screenshots/signin response.png)

## Complete authorization by inserting the token given in the signin response 
![image alt](Screenshots/authorization.png)

## Update a user detail with PATCH /service/user/update-user
![image alt](Screenshots/update user request.png)
![image alt](Screenshots/update user response.png)

## Delete a user with DELETE /service/user/delete-user
![image alt](Screenshots/delete user request.png)
![image alt](Screenshots/delete user response.png)

## Add a todo with POST /service/todo/add_todo
![image alt](Screenshots/add todo request.png)
![image alt](Screenshots/add todo response.png)

## Update a todo with PATCH /service/todo/update_todo/{id}
![image alt](Screenshots/update todo request.png)
![image alt](Screenshots/update todo response.png)

## View all todo saved by an authenticated user with GET /service/todo/get_all
![image alt](Screenshots/get all todo request.png)
![image alt](Screenshots/get all todo response.png)

## Delete a todo saved by an authenticated user with DELETE /service/todo/delete_todo/{id}
![image alt](Screenshots/delete todo request.png)
![image alt](Screenshots/delete todo response.png)


## Docker
Docker was set up for the project and can be monitored in the Docker Desktop
![image alt](Screenshots/docker.png)
