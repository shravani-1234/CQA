# Community Question Answer

This is a web-based project designed to mimic a community question-answer website.

## Author

- [@Shravani-1234](https://www.github.com/Shravani-1234)

## Tech Stack

**Frontend:** HTML, CSS, JavaScript

**Backend:** JavaScript (Node.js)

**Database:** PostgreSQL

## Installation, Usage, and Maintenance

### Installing the Project

Clone the CQA project files into your local directory using `git clone`. Run:

```bash
git clone https://github.com/M-Charith/CQA
```
### Prerequisite

Your local Machine must have PostgreSQL installed and pgAdmin(preferably for excuting .sql scripts, or you could execute them from the terminal too.)

Create a Local PostgreSQL connection of SQL server in your machine with :

    username: "postgres"
    password: "1234"
    Hostname: "localhost"
    port: 5432
    Connection name: "cqadb"

Run the following script to set up the database with tables:

    script.sql

Run the following script to populate the initially necessary tables:

    populate.sql

Note: This population only corresponds to the possible tags. If you feel more tags are necessary, you could add more with the same syntax as the others.

Run the following script to delete all the tables in the database:

    delete.sql

### Installing the required node modules

On cloning the project in to your local machine, change your directory into the 'backend' directory and run the following code:

    npm install

Change your directory into the 'client' directory and run the following code: 

    npm install

This will install all the required node modules for frontend as well as the backend.

### Usage

Run the following code in the 'backend' directory to start the backend.

    nodemon index.js

You would be able to see a message on terminal 'server up!' conforming the same.

Now run the following code in the 'frontend' directory to start the application.

    npm start

If you don't see a webpage open up, open a browser and browse for "localhost:3000".
