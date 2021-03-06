![cf](http://i.imgur.com/7v5ASc8.png) 36: Async Actions
===

## Submission Instructions
  * Work in a fork of this repository
  * Work in a branch on your fork
  * Write all of your code in a directory named `lab-` + `<your name>` **e.g.** `lab-duncan`
  * Submit a pull request to this repository
  * Submit a link to your pull request on canvas
  * Submit a question, observation, and how long you spent on canvas  

## Requirements  
#### Configuration  

##### backend/
  * copy your lab-14 or comparable api into into a backend directory

##### frontend/
* **README.md** -- with documention about your lab
* **.babelrc** -- with all dependencies and dev-dependencies 
* **.eslintrc.json** -- with the class .eslintrc.json file
* **.gitignore** -- with a robust .gitignore
* **.eslintignore** -- with the class .eslintignore
* **yarn.lock** -- with the yarn lockfile
* **package.json** -- with all dependencies and dev-dependencies 
* **webpack.config.js** -- with webpack config
* **src/** -- containing the frontend code
* **src/main.js** -- renders the app
* **src/style** -- containing your sass
* **src/style/main.scss** -- for importing and including reset and base
* **src/style/_vars.scss** -- sass variables
* **src/style/_reset.scss** -- sass reset 
* **src/style/_base.scss** -- base styles 
* **src/style/_layout.scss** -- layout styles 
 
#### Feature Tasks 
  * Create a frontend for your lab-18-oauth or most recent (non-project week) API project
    * If you are not comforable using yours, you may use our demo lab instead
      <https://github.com/DeltaVCode-cr-401js-2018/16-basic-authentication/tree/class-demo-react>
  * You can also choose to use a comparable RESTful api that does not have auth (must permit full CRUD)
  * You are only required to create CRUD operations for a single resource of your backend
  * Use react/redux best practices
  * Add validation in your redux routers
  * Add logger and thunk middleware to your redux store
  * make async action creators for making ajax request to your backend
  * make sync action creators from updating your app store

#### Test
  * Test your redux reducers 

## Stretch Goals
  * Create full crud for two resources 

#### Documentation  
Write a description of the project in your README.md, including detailed instructions for how to build your app. In your frontend README.md add a code block with your frontend .env vars, and in your backend README.md add a code block with your backend .env vars. 
