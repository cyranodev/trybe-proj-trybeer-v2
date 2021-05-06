##### This repo is a clone from the original group project for [Trybe](https://www.betrybe.com/) junior developer course. https://www.betrybe.com/
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-3-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

# TryBeer v2

## Requisites

**First version:** this version follows up an initial one where the whole project is built up>

- *Back-end:* usage of [mySQL](https://www.mysql.com/) was required. The group decided to use a services layer in architecture and [Express](https://expressjs.com/) to handle routes. We implemented basic security features such as [JWT](https://jwt.io/) for login management, as well as encryption of passwords (using [BCrypt](https://www.npmjs.com/package/bcrypt)) to store them in DB, and our own log middleware (developed by a group member) to write logs and handle errors in Express flow. 

- *Front-end:* all elements built up using [React](https://reactjs.org/) and *React Context*, along with [React Router](https://reactrouter.com/) to deal with routes and protected (logged in) routes. Visual design was not a requirement in itself
  
**Set-up for current version:** the current version required a migration to [Sequelize](https://sequelize.org/) beforehand, so the group had to set up Sequelize models and migrations in order to allow seeders for automated tests to work (tests provided by Trybe to assess students' performance).

**Requisites sum-up:**

- Improve existing features to allow clients to see their orders' status and admin users to change that status among three possible values
- Create a chat feature for clients to chat with the store:
  - each client only chats with the 'store' and all chats are private
  - admin users can see all chats and send messages to clients
  - mongoDB is required to store chats
- Back-end unit tests (we used mainly endpoint tests with Jest and Supertest to properly track coverage across 

## Instructions

Clone the repo or download the zip.

Run `npm install`. (which means *Node.js* must be installed in your machine)

To start the back-end: go to *back-end* project folder and run `npm start`.
To start the front-end: go to *front-end* project folder and run `npm start`.
## Important: mongoDB and mySQL services must be installed and active in your machine in order for DBs (and the whole project) to work.

## Contributors ✨

Thanks to the team:

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://www.linkedin.com/in/daniel-js/"><img src="https://avatars.githubusercontent.com/u/67609772?v=4?s=100" width="100px;" alt=""/><br /><sub><b>danieljs-dev</b></sub></a><br /><a href="https://github.com/cyranowebdev/trybe-proj-trybeer-v2/commits?author=danieljs-dev" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/PedimEduardo"><img src="https://avatars.githubusercontent.com/u/67610181?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Pedro Eduardo </b></sub></a><br /><a href="https://github.com/cyranowebdev/trybe-proj-trybeer-v2/commits?author=PedimEduardo" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/phelipe-ohlsen"><img src="https://avatars.githubusercontent.com/u/59030984?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Phelipe Ohlsen</b></sub></a><br /><a href="https://github.com/cyranowebdev/trybe-proj-trybeer-v2/commits?author=phelipe-ohlsen" title="Code">💻</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->
