# Task Master
## Simple and Slim

[![N|Solid](https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

TaskMaster is a simple and slim web app hostable on Heroku.
It is great as a beginner app to host on Heroku and learn the ways of Flask

- Flask
- Python
- SQLite
- Heroku

## Features

- Simple form for entering data
- Table for viewing tasks
- CRUD Operations for tasks
- SQLite database
- Simple HTML&CSS pages

## Prerequisites

- Python 3
- Heroku Account
- Heroku CLI
- Git

Follow the same structure, later on when deploying the application, based on the build pack you inted to use, you will need a specific set of files.
For instance, python build pack needs the requirements.txt

## Installation
After verifying and checking all the prerequisites, the intallation step should be problem-free.

- Navigate to the root directory and initialize the git repo
```sh
git init
```

- Use heroku login, and login to your account through the CLI
```sh
heroku login
```

- Create the Heroku Application, and specify the buldpack which will be used later when pushing the application to Heroku
    see all the buildpacks here: [build packs](https://devcenter.heroku.com/articles/buildpacks)

```sh
heroku create <application_name> --buildpack <heroku/python>
```

- Add all files to staging
```sh
git add .
```

- Commit the changes, and then push them to the master branch and await the final result
```sh
git commit -m "Initial Application Deployment"
git push heroku master
```



## License

**Free Software, use it as you see fit.**
