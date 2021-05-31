#### <a name="top"></a> This repo is a clone of the group project that encloses front-end and back-end modules of the [Trybe](https://www.betrybe.com/) junior developer course.
##### https://www.betrybe.com/ (in Portuguese)
  
# TryBeer v2

![!project status](https://img.shields.io/badge/status-development-f4a201?logo=visual-studio-code)
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-4-informational.svg?style=flat&logo=github)](#contributors)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

- [Requisites](#requisites)
- [Instructions](#instructions)


## Requisites <a name="requisites"></a>

**This is a second version:** this version follows up an initial project, in which students are expected to develop, from scratch, the back-end API and front-end website to sell... yes, you guessed it: beer. 🍺

- *Back-end:* usage of [**mySQL**](https://www.mysql.com/) was required. The group decided to use a services layer in architecture and [**Express**](https://expressjs.com/) to handle routes. We also use [**JWT**](https://jwt.io/) for login management, [**BCrypt**](https://www.npmjs.com/package/bcrypt)) to encrypt passwords before storing in DB, and log and error handling middleware (developed by Phelipe Ohlsen, see contributors below). **Documentation** is available thanks to [**Swagger**](https://swagger.io), at default path `localhost:3001/documentation`.

- *Front-end:* all elements built up using [**React**](https://reactjs.org/) and *React Context*, along with [*React Router*](https://reactrouter.com/). Visual design was not a requirement in itself but we agreed in using a colour scheme and a nice logo was created by *Daniel Jesus* (see contributors below).
  
**Set-up for current version:** the current version required a migration from mySQL to [**Sequelize**](https://sequelize.org/) to start with, so we had to create all Sequelize models and migrations before moving on to the actual requisites of the project.

#### What did I do?
Pretty much a bit of everything. Worked on back-end features, refactoring and improvements, the whole front-end React build (and several refacts), a fair bulk of the back-end tests as well as the current styling (*work in progress*, by the way). I intend to keep improving the visuals and change slight details in the project overall, such as user profile definitions and roles.

##### [back to top](#top)

**Requisites sum-up:**

- Improve existing features to allow clients to see their orders' status and admin users to change that status among three possible values
- Create a chat feature for clients to chat with the store:
  - each client only chats with the 'store' and all chats are private
  - admin users can see all chats and send messages to clients
  - mongoDB is required to store chats
- Back-end unit tests (we mainly used endpoint tests with Jest and Supertest to track coverage across architecture layers)

## Instructions <a name="instructions"></a>

**Clone** the repo or **download** the zip.

Go to the project folder and run `npm install`. (which means *Node.js* must be installed in your machine)

To start the **back-end**: go to *back-end* project folder and run `npm start`.   
(**bonus**: check out the sexy documentation for the API at `localhost:3001/documentation`)

To start the **front-end**: go to *front-end* project folder and run `npm start`.  

To run **back-end tests** (with coverage report): go to *back-end* project folder and run `npm run test-coverage`.  

#### Important: mongoDB and mySQL services must be installed and active in your machine in order for DBs (thus the whole project) to work.

##### [back to top](#top)

## Thanks to the team! ✨ <a name="contributors"></a>

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/danieljs-dev"><img src="./public/github-daniel.png" width="100px;" alt=""/><br /><sub><b>danieljs-dev</b></sub></a></td>
    <td align="center"><a href="https://github.com/PedimEduardo"><img src="./public/github-pedro.png" width="100px;" alt=""/><br /><sub><b>Pedro Eduardo </b></sub></a></td>
    <td align="center"><a href="https://github.com/phelipe-ohlsen"><img src="./public/github-phelipe.png" width="100px;" alt=""/><br /><sub><b>Phelipe Ohlsen</b></sub></a></td>
    <td align="center"><a href="https://github.com/cyranowebdev"><img src="./public/github-madsen.png" width="100px;" alt=""/><br /><sub><b>Cyrano</b></sub></a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->
##### [back to top](#top)
