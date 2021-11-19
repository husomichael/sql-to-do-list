[x]Think through table structure.
    -- Design on app.dbdesigner.net
    -- Actually make some CREATE TABLE statements.
    Database: to-do-list
    Table: todo
[x]Make a branch for initializing stuff.

#### Front-End

Front end Initialization:
[x]File folders
[x]Build boilerplate HTML
[x]Source style.css
[x]Source client.js
[x]Source jQuery.js
[x]Project structure
[x]Create database.sql
[x].gitignore

Database planning:
[x]Name database. 
[]xName table/s. 
[x]Figure out structure of column names. 
[x]Write up SQL statements for building table. 
[x]Write up statements to put in some dummy data.

#### Back-End

Server setup:
[]run npm init --y
[]make sure "start" script exists in package.json
[]npm install express
[]npm install body-parser
[]npm install pg
[]
[]create server.js
[]create todoRouter.js in routers folder in server folder
[]create pool.js
[]wire up todoRouter.js export router
[]wire up pool.js and link to DB and export pool
[]write server code in server.js

# FEATURES

[]Create a task *POST ROUTE*
    store in db
    re-render DOM *GET ROUTE*

[]delete a task *DELETE ROUTE*
    remove task from DB
    re-render DOM *GET ROUTE*

[]task should be completeable
    update task in DB *PUT ROUTE*
    should be "checked off"
    CSS to differentiate "complete" tasks
    re-render DOM *GET ROUTE*

[]task could have a mark important button
    sort tasks in SQL query from DB to be importance first *PUT ROUTE*
    CSS to differentiate importance of tasks. (DEFCON level colors lol)
    re-render DOM *GET ROUTE*

[] CSS! Make it pretty. 