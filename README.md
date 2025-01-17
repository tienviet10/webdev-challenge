
<h1 align="center">
  <br>
  <a href="https://nri-challenge.netlify.app"><img src="https://user-images.githubusercontent.com/70352144/207425372-29b575f3-2ddf-4929-bde5-40c1ca08a648.png" alt="NRI Challenge" width="200"></a>
  <br>
    NRI Challenge Express REST API
  <br>
</h1>

<h4 align="center">This backend application is written in Node.js (<a href="https://expressjs.com/">Express.js</a>) and deployed automatically to <a href="https://railway.app//">Railway</a> on merges to the main branch. PostgreSQL database hosted by Railway is used for this application. The frontend made in <a href="https://reactjs.org/">React.js</a> can be accessed at this <a href="https://github.com/tienviet10/webdev-challenge-frontend/">link.</a></h4>

<p align="center">
  <a href="#key-features">Tech Stack & Features</a> •
  <a href="#running-locally">Running Locally</a> •
  <a href="#todo">TODO</a> •
  <a href="#demo">DEMO</a> •
  <a href="#discussion">DISCUSSION</a>
</p>



## Tech Stack & Features

* [Express](https://expressjs.com)
* Automatically restarting Node application when there are file changes using [Nodemon](https://nodemon.io)
* Easy connection to database using [pg](https://node-postgres.com/)
* A simple middleware for backend [router](https://github.com/pillarjs/router)
* Automatically load environment variables from a .env file into the process using [dotenv](https://github.com/motdotla/dotenv#readme)
 
## Running Locally

**Prerequisites**

The following applications should be installed in your system:
* [Git](https://git-scm.com) 
* [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com))
* PostgreSQL

**API**

1. Create a folder and clone this repository

```sh
$ git clone https://github.com/tienviet10/webdev-challenge.git
```

2. Move to the correct directory

```sh
$ cd webdev-challenge
```

3. Install dependencies

```sh
$ npm install
```

4. Fill out variables in .env file.

5. Run the application

```sh
$ npm run dev
```

The API will run locally at: http://localhost:8000/


## TODO

* Add support for editing table data


## DEMO

* [Website](https://nri-challenge.netlify.app/)
* [Demo link](https://www.youtube.com/watch?v=Fw4aGFjmGTI)


## DISCUSSION


As a React.js and Node.js developer, I am proud of my takehome work for a few reasons.
First, I successfully implemented Ant Design, which I have yet to try to create a beautiful and intuitive user interface (UI) and user experience (UX) for the application. I decided to use Ant Design because I had heard a lot of great reviews regarding the framework. Ant Design is a perfect UI framework for developing organizational apps and dashboards. The frontend
was deployed to Netlify, allowing continuous application deployment through GitHub.

Second, I was able to leverage my knowledge of React.js and Node.js to build a robust and
scalable backend for the application. The backend and PostgreSQL were deployed to Railway, allowing continuous development and deployment through GitHub. I tested the application to ensure it was free of bugs and errors. 

Finally, writing a logic to identify the columns without column names poses some challenges. I have to know more about the data to develop a better logic that fits all cases. Overall, I am proud of my work on this project, and I believe it showcases my skills and abilities as a Reacts and Node.js developer.


