# Lab 4

## Your Objective

Complete [this tutorial][express-rest]
--if you face a problem with unmet peer deficiency running npm start after editing the package.json:-
--use the following dependancies: 
    "mongodb": "~1.4",
    "mongoskin": "1.4.13",
    "monk": "~1.0.1"
--When you install the mongoose module by npm, it does not have a built bson module in it's folder. In the file --node_modules/mongoose/node_modules/mongodb/node_modules/bson/ext/index.js, change the line
--  bson = require('../build/Release/bson');
--  to
--  bson = require('bson');
--and then install the bson module using npm.

## Tutorial Expected Objective

- Review node modules
    - node module syntax (require/export)
    - npm package manager install
- Create package.json
    - read package.json
    - npm install from package and adding dependency
    - npm test
    - npm run [script]
- Continue with our git repo.
- How to write unit tests using mocha BDD.
- Start an express server.
- Send a request to the server with jQuery
- Google your way

After this tutorial you should have build a very simple To-DO list tested restful app.

## Requires

- Internet
- Google chrome
- A plain text editor (preferably sublime)
- mongodb
- nodejs
- git
- A github account
- npm packges mocha, chai, superagent? Istanbul

## Pre

- If you haven't yet fill this [form][student-form] while creating a github account
- Complete [this tutorial][express-rest]
- Learn JQuery
  -  [see try jquery course](http://try.jquery.com/) should take 3 hours to fully complete.

## Tutorial Guide

- Complete building the [restful app][express-rest] in the pre lab test
- Push your work as a github rep and send a link to your TA on your slack group
    - If you're still not on slack you did not fill this [form][student-form]
    - You should have a slack group per lab for communicating with each other and the TA as a tutorial.

- Once you setup your rep and send it to your TA while you do your work you will be sent some issues on github to do (you will understand later). otherwise just proceed.

- Learn about testing
    + you keywords are mocha testing instanbul tutorial.
    + 
- Test the app you should have completed in the pre test.
- Work on your assignment.
- Have enriching philosophical discussions with your TA on life and ant logic, or octocats.

## Post Tutorial

For more on jQuery [checkout](http://www.w3schools.com/jquery/)
Done with your assignment Try building a TO-Do app with [jQuery or angular](http://todomvc.com/)




[student-form]: https://docs.google.com/forms/d/1p2NTsF4bZSSeTwakwAbNJaePHwL1VmSQMR0GESy7j2A/viewform
[fork]: https://help.github.com/articles/fork-a-repo/
[sync]: https://help.github.com/articles/syncing-a-fork/
[pull-request]: https://help.github.com/articles/using-pull-requests/
[express-rest]: http://cwbuecheler.com/web/tutorials/2014/restful-web-app-node-express-mongodb/
