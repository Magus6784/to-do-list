In this exam project, you have to implement a todo list site.

You should have such models:

1. Task - todo list is consist of tasks. Each task should have fields for:
  ![img.png](img.png)content - describes what you should do.
  datetime, when a task was created
  optional deadline datetime if a task should be done until some datetime
  the boolean field that marks if the task is done or not
  tags that are relevant for this task
2. Tag - a tag symbolizes the theme of the task and consists only of a name.
A task can have multiple tags and a tag can be in multiple tasks.

Create the home page. The home page is accessed by 127.0.0.1:8000/, where you should have:
![img_1.png](img_1.png)
![img_2.png](img_2.png)
1.Sidebar with the links to:
  Home page
  Tag list page the sidebar should be on all pages.
2.Todo list which is a list of tasks.
  Tasks should be ordered from not done to done and from newest to oldest
  All task information should be displayed.
  There should be a button to add a new task.
  For each task add links for updating and deletion.
  Also, add a button Complete if a task is not done and Undo if a task is done, this button changes the status of the task to the opposite and redirects to this page.


Create a tag list page. A tag list page is accessed by 127.0.0.1:8000/tags/, there you should have:

1.Table with tags names, links for updating, and deletion.
2.Button to add a new tag.
Of course, pages for adding tags and tasks must be also implemented.
 

Task
Create new GitHub public repo;
Switch to dev branch;
Implement Todo List project;
Create Pull Request from dev to main branch;
Attach images of your interface (all pages) to the PR (important!). Do not attach images as links, put them directly (also important);
Attach link to the PR as the solution for this task.
That's all
