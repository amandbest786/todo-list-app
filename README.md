# todo-list-app
This is a simple To-Do list application built using Node.js, MongoDB, and React. It allows users to create and manage tasks, as well as sort and filter tasks based on their completion status or priority.

##Features
###The application has the following features:

1. User Authentication: Users can create an account and log in using their email and password.
2. Task Management: Users can create new tasks, mark tasks as completed, and delete tasks. Users can also edit the task details such as title, description, due date, and priority.
3. Sorting and Filtering: Users can sort tasks by due date, priority, or completion status. Users can also filter tasks based on their completion status or priority.
4. Real-time updates: The application provides real-time updates to users whenever a task is added, updated, or deleted.
5. Responsive Design: The application is responsive and works well on different devices such as desktops, laptops, tablets, and smartphones.

##Technologies Used
###The application is built using the following technologies:

Node.js: A JavaScript runtime for building server-side applications.
MongoDB: A NoSQL database used to store and manage data.
React: A JavaScript library for building user interfaces.
Express: A minimal and flexible Node.js web application framework used to build the REST API.
Socket.io: A JavaScript library used to implement real-time updates.

##Here are the APIs that you could build for your To-Do list application:

GET /api/tasks: This API should return a list of all the tasks for the logged-in user.

GET /api/tasks/:id: This API should return the details of a specific task.

POST /api/tasks: This API should create a new task for the logged-in user.

PUT /api/tasks/:id: This API should update the details of a specific task.

DELETE /api/tasks/:id: This API should delete a specific task.

GET /api/tasks?completed=true: This API should return a list of completed tasks for the logged-in user.

GET /api/tasks?completed=false: This API should return a list of incomplete tasks for the logged-in user.

GET /api/tasks?priority=high: This API should return a list of tasks with high priority for the logged-in user.

GET /api/tasks?priority=medium: This API should return a list of tasks with medium priority for the logged-in user.

GET /api/tasks?priority=low: This API should return a list of tasks with low priority for the logged-in user.
