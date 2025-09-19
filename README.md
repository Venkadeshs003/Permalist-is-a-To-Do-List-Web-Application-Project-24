screenshots:
![adding the new item in the list](./screenshots/adding%20the%20new%20item%20in%20the%20list.png)
![interface for this page](./screenshots/interface%20for%20this%20page.png)
![sucessfully runing](./screenshots/sucessfully%20runing.gif)

Frontend (EJS Templates):
Uses EJS views (index.ejs, header.ejs, footer.ejs) to dynamically display tasks and forms for editing or deleting.

Backend (Express.js):
Handles HTTP requests (GET, POST) to add, edit, and delete tasks.

Database (PostgreSQL):
Stores tasks in a table called items, where each task has an id and title.

Flow:

When the app loads, it fetches all tasks from the database and displays them.

New tasks can be added through the input box.

Tasks can be edited inline.

Tasks can be deleted by checking the checkbox.

This makes it a simple but complete CRUD (Create, Read, Update, Delete) application.

project structure:Permalist
├── index.js              # Main server file
├── views/
│   ├── index.ejs         # Main template
│   └── partials/
│       ├── header.ejs    # Header partial
│       └── footer.ejs    # Footer partial
├── public/
│   ├── styles/           # CSS files
│   └── assets/icons/     # Icon images
├── package.json
└── README.md