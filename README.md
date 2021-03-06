# MERN Social Site




A MERN stack social network application with MVP features implemented: user authentication, profile viewing, posting, commenting, and following/unfollowing.

## I am working on a ML algortihm which can be used to detect cuss words, threats , trolls and other such things using NLP. It will be added soon.




Signup                     |  Feed
:-------------------------:|:-------------------------:
![Signup](https://github.com/theinmate4587/MERN-Social-Site/blob/master/demo/signup.png)  |  ![Feed](https://github.com/theinmate4587/MERN-Social-Site/blob/master/demo/feed.png)

Comment                    |  Discover
:-------------------------:|:-------------------------:
![Comment](https://github.com/theinmate4587/MERN-Social-Site/blob/master/demo/comment.png)  |  ![Discover](https://github.com/theinmate4587/MERN-Social-Site/blob/master/demo/discover.png)



## User Stories

- [x] As a user, I can create account and log in.
- [x] As a user, I can view my home page.
- [x] As a user, I can view posts so that I know what people I’m following are up to.
- [x] As a user, I can create a post so that I can share my current status.
- [x] As a user, I can delete my posts so that people can no longer see them.
- [x] As a user, I can edit my posts so that I can correct or clarify my thoughts.
- [x] As a user, I can like/unlike a post so that I can approve posts I am fond of.
- [x] As a user, I can comment on a post so that I can share additional thoughts.



## Setup instructions (tested on macOS 10.14 Mojave)
To run server:
1. Clone the repository.
2. `cd` into the directory and run `npm install`.
3. Run `cd client && npm install`.
4. Back in the main directory, run `npm start`.

To set up your own database:
1. Log into or create an [mLab](https://mlab.com/) account.
	1. Create a new MongoDB deployment.
  ![Deployment](https://github.com/jm-shi/MERN-Social-Network/blob/master/demo/deployment.png) 
	![Select Provider](https://github.com/jm-shi/MERN-Social-Network/blob/master/demo/provider.png) 
	2. Enter the database and create a new user.
  ![Add User](https://github.com/jm-shi/MERN-Social-Network/blob/master/demo/addUser.png)
	3. Replace the dbURI in "secrets.js" (located in backend folder) with your MongoDB URI. Replace `<dbuser>` and `<dbpassword>` with the user and password you just created respectively.
  ![URI](https://github.com/jm-shi/MERN-Social-Network/blob/master/demo/uri.png) 
	![Sample](https://github.com/jm-shi/MERN-Social-Network/blob/master/demo/sample.png) 
2. Log into or create a [Heroku](https://heroku.com/) account. 
	1. Create a new app in Heroku.
	![Heroku](https://github.com/jm-shi/MERN-Social-Network/blob/master/demo/heroku.png)
	2. In settings, add config vars for REACT_APP_DB_URI and REACT_APP_JWT_KEY.
![Heroku Config](https://github.com/jm-shi/MERN-Social-Network/blob/master/demo/herokuConfig.png)
3. Back in the main directory, run `npm start`.

## Built With

- [Express.js](https://expressjs.com/) - Backend web framework
- [Heroku](http://heroku.com/) - Platform to deploy web applications
- [JSON Web Token](https://jwt.io/) - A standard to securely authenticate HTTP requests
- [Material-UI](https://material-ui.com/) - UI library for React
- [MongoDB](https://www.mongodb.com/) - Database to store document-based data
- [Mongoose](https://mongoosejs.com/) - Object-modeling tool for Node.js
- [Node.js](https://nodejs.org/en/) - Runtime environment to help build fast server applications
- [React](https://reactjs.org/) - JavaScript library for building user interfaces
- [Redux](https://redux.js.org/) - JavaScript library to help better manage application state



