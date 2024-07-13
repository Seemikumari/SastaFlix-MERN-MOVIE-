<H1 align ="center" > BertFlix (MERN MOVIE)  </h1>
<h5  align ="center"> 
Fullstack open source movie application made with MongoDB, Express, React & Nodejs (MERN) </h5>
<br/>

  * [Configuration and Setup](#configuration-and-setup)
  * [Key Features](#key-features)
  * [Technologies used](#technologies-used)
      - [Frontend](#frontend)
      - [Backend](#backend)
      - [Database](#database)
      - [API](#api)
  * [📸 Screenshots](#screenshots)
  * [Author](#author)
  * [License](#license)

## Configuration and Setup

In order to run this project locally, simply fork and clone the repository or download as zip and unzip on your machine.

- Open the project in your prefered code editor.
- Go to terminal -> New terminal (If you are using VS code)
- Split your terminal into two (run the client on one terminal and the server on the other terminal)

In the first terminal

```
$ cd client
$ npm install (to install client-side dependencies)
$ npm run  start (to start the client)
```

In the second terminal

- cd server and Set environment variables in .env
- Create your mongoDB connection url, which you'll use as your MONGO_URL
- Supply the following credentials

```
#  --- .env  ---

MONGODB_URL
PORT =5000
TOKEN_SECRET=
TMDB_BASE_URL=
TMDB_KEY=
```

```
# --- Terminal ---

$ npm install (to install server-side dependencies)
$ npm start (to start the server)
```

##  Key Features

- User registration and login
- Authentication using JWT Tokens
- Add Favorites
- Delete Favorites
- Leave a Reviews
- Delete Reviews
- Password Update
- Search Live
- Watch the trailer on Youtube
- 404 Page and many more
- Skeleton loading effect
- DarkMode
- Responsive Design

<br/>

##  Technologies used

This project was created using the following technologies.

####  Frontend 

- [React js ](https://www.npmjs.com/package/react) - JavaScript library that is used for building user interfaces specifically for single-page applications
- [React Hooks  ](https://reactjs.org/docs/hooks-intro.html) - For managing and centralizing application state
- [react-router-dom](https://www.npmjs.com/package/react-router-dom) - To handle routing
- [axios](https://www.npmjs.com/package/axios) - For making Api calls
- [Material UI](https://mui.com/) - For User Interface
- [CK-Editor](https://ckeditor.com/docs/ckeditor5/latest/builds/guides/integration/frameworks/react.html) - Rich Text Editor 
- [Formik](https://formik.org/) - Manage status and validation of data on forms efficiently
- [React Redux](https://react-redux.js.org/) - manage application state efficiently and provide a more structured mechanism for managing data
- [React Toastify](https://www.npmjs.com/package/react-toastify) - To display interactive and responsive notifications (toasts) in web applications
- [Swiper](https://swiperjs.com/) - To create responsive and interactive sliders or carousels on web pages

####  Backend 

- [Node js](https://nodejs.org/en/) -A runtime environment to help build fast server applications using JS
- [Express js](https://www.npmjs.com/package/express) -The server for handling and routing HTTP requests
- [Mongoose](https://mongoosejs.com/) - For modeling and mapping MongoDB data to JavaScript
- [axios](https://www.npmjs.com/package/axios) - For making Api calls
- [jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken) - For authentication
- [cookie-parser](https://www.npmjs.com/package/cookie-parser) - Middleware module used in Node.js web applications to manage cookies
- [cors](https://www.npmjs.com/package/cors) - Provides a Connect/Express middleware
- [Dotenv](https://www.npmjs.com/package/dotenv) - Zero Dependency module that loads environment variables
- [express-validator](https://www.npmjs.com/package/express-validator) - Used in Node.js applications with the Express framework to validate data submitted by users (user input)
- [nodemon](https://nodemon.io/) - Development utility for Node.js applications. Node.js is a runtime platform that allows you to run JavaScript on the server side.t

####  Database 

 - [MongoDB ](https://www.mongodb.com/) - It provides a free cloud service to store MongoDB collections.
 
####  Api 

 - [TMDB API](https://developer.themoviedb.org/docs) - An application programming interface that provides access to a database of movies, television shows, and related information from The Movie Database platform.
 
 ##  Screenshots 
 
![img-1](https://res.cloudinary.com/dup3vhxmo/image/upload/v1720893950/sf-cover_qmkgyb.jpg)
---- -
![img-2](https://res.cloudinary.com/dup3vhxmo/image/upload/v1720893937/sf-11_jrh80l.jpg)
--- - 
![img-3](https://res.cloudinary.com/dup3vhxmo/image/upload/v1720893925/sf10_o2lgmx.jpg)
--- - 
![img-4](https://res.cloudinary.com/dup3vhxmo/image/upload/v1720893906/sf9_afjjez.jpg)
--- - 
![img-5](https://res.cloudinary.com/dup3vhxmo/image/upload/v1720893891/sf8_opn22t.jpg)
--- - 
![img-6](https://res.cloudinary.com/dup3vhxmo/image/upload/v1720893878/sf7_fbsbma.jpg)
--- - 
![img-7](https://res.cloudinary.com/dup3vhxmo/image/upload/v1720893864/sf6_j2mok5.jpg)
--- - 
![img-8](https://res.cloudinary.com/dup3vhxmo/image/upload/v1720893853/sf5_urpjxe.jpg)
--- - 
![img-9](https://res.cloudinary.com/dup3vhxmo/image/upload/v1720893864/sf6_j2mok5.jpg)
--- - 
![img-10](https://res.cloudinary.com/dup3vhxmo/image/upload/v1720893824/sf3_igfosv.jpg)

## Author
- Portfolio: [seemikumari](https://portfolio-website-v2-five.vercel.app/)
- Github: [seemikumari](https://github.com/Seemikumari)
- Linkedin: [seemikumari](https://www.linkedin.com/in/seemi-kumari-126479152/)
- Email: [seemisingh0@gmail.com](mailto:seemisingh0@gmail.com)


