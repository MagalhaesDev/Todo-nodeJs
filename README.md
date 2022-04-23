# Todo
This system consists of an API for a todoList, using CRUD(create,read,update,delete) with HTTP methods, having the functionality to create a new user, create a todo, update the todo, display and remove them.


## Technology 

Here are the technologies used in this project.

* NodeJS 16.14.0
* Express 4.17.1
* Uuid 8.3.2
* Nodemon 2.0.7

## Services Used

* Github

## Getting started
 
1 - Run the command yarn in the terminal to download the dependencies.

2 - Use insomnia to make the requisitions.

## Functionalities

### Creating new users

* Create new users, giving as response a status of type 201(createad), if the user already exists it will have a response with a status of type 400(Bad request).

### Creating todo

* this post type functionality will create a post as a list containing title, end date, start date, and an ID. if all goes well it returns a 201(created) status and a JSON with the items.

### Show todos

* This functionality is of type GET and will display to the client the lists created by the user, passing through a middleware that will check if it is an existing account, if not it will return the status 404(not found)

### Update todo

* allows you to update the name and end date of todo. giving the code 400 (bad request) if the user is non-existent, and returning a JSON if everything is fine.

### Completed task

* This feature will set the todo to completed, returning the JSON of the task

### Delete todo 

* This functionality of the HTTP delete method, will delete an existing todo, if all goes well it will return a JSON with the todo that remain, otherwise a 404 (Not Found) if the user does not exist

## Links
  - Repository: https://github.com/MagalhaesDev/Todo-nodeJs
    - In case of sensitive bugs like security vulnerabilities, please contact
      mateusmagalhaesemidio@gmail.com directly instead of using issue tracker. We value your effort
      to improve the security and privacy of this project!

  ## Versioning

  1.0.0.0


  ## Authors

  * **Mateus Magalhaes Emidio** 

  Please follow github and join us!
  Thanks to visiting me and good coding!
