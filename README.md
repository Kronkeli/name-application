# Name application

Basic functionalities include listing names in alphabetical and popularity order. REST API with HTTP-requests, graphical interface implemented with React. Back-end is handled with Node.js and Express framework. 

## Running application in Heroku

You can find a running application in Heroku. Notice, that it is most likely in a sleep state, and will need time to wake up (both the client and the server sides). Here is a link to the client site: [https://name-application-client.herokuapp.com/](https://name-application-client.herokuapp.com/). Here is a link to the server side: [https://name-application-server.herokuapp.com/](https://name-application-server.herokuapp.com/).

## Local development

Easiest way to build and run the project is to use Docker, as the application is containerized. Run the following commands in the root directory:


```bash
docker-compose build
docker-compose up
```

After these commands you can view the React-app in [http://localhost:3001/](http://localhost:3001/). 
