# README

Define CRUD.
C: Create
R: Read
U: Update
D: Delete
Define MVC.


Model, View, Controller. Is the basic structure most web applications are based on.
-Controller handles incoming request, 
-Model the place where request are put together.
- View is the final product.

- What three files would you need to create/modify for a Rails application to respond to a GET request to /tasks, assuming you have a Task model.
1.index
1.show 
1.edit

-What are params? Where do they come from?
-Params come from the inputed information in broswer(at least for Task Manager). They are formatted as hashes in Rails.

-Check out your routes. Why do we need two routes each for creating a new Task and editing an existing Task?
get/read information for task.
post/create the task
