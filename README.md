# NextLevelWeek #03

<div align="center">
  <img alt="Happy" src="https://github.com/lmaoclost/NextLevelWeek-3/blob/main/.github/logo.jog" width="280"/>
</div>

<br />
<div align="center">
  <img alt="License" src="https://img.shields.io/badge/license-MIT-191A1E">

  <a href="https://rocketseat.com.br">
    <img alt="Made by Rocketseat" src="https://img.shields.io/badge/made%20by-Rocketseat-%237519C1">
  </a>

  <a href="https://www.linkedin.com/in/renansmoliveira/">
    <img alt="Follow me Linkedin" src="https://img.shields.io/badge/Follow%20up-renansmoliveira-191A1E?style=social&logo=linkedin">
  </a>
</div>

Project for a [Course](https://github.com/rocketseat-education/nlw-03-omnistack) that has the purpose to code a project named Happy using Node, ReactJS and React Native. This project connects orphanages and peopple that wants to visit them.

## Some Images

### WEB

<div align="center">
  <div style="display: flex; flex-direction: 'row'; align-items: 'center';">
    <img alt="Web" src="https://github.com/lmaoclost/NextLevelWeek-3/blob/main/.github/web-landing.jpg" width="400px">
    <img alt="Web" src="https://github.com/lmaoclost/NextLevelWeek-3/blob/main/.github/web-list.jpg" width="400px">
  </div>
</div>

### Mobile

<div align="center">
  <div style="display: flex; flex-direction: 'row'; align-items: 'center';">
    <img alt="Mobile" src="https://github.com/lmaoclost/NextLevelWeek-3/blob/main/.github/Home-mobile.jpg" width="250px">
    <img alt="Mobile" src="https://github.com/lmaoclost/NextLevelWeek-3/blob/main/.github/preview-mobile.jpg" width="250px">
  </div>
</div>

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development.

### Prerequisites

Node, yarn and a text editor. I'm using VSCode.

## Day 1, 3: FrontEnd

Open a terminal.

```
$ cd /web
$ yarn
$ yarn start
```

Go to http://localhost:3000 and the project is up and running! To use the backend, make sure that it is running.

## Day 2: BackEnd

Go to another terminal.

```
$ cd /server
$ yarn
$ yarn typeorm migration:run
$ yarn start
```

The Backend will be running in the http://localhost:3333. To test the routes, i'm leaving this [Insomnia file](https://github.com/lmaoclost/NextLevelWeek-3/blob/main/backend/Insomnia_2020-10-16). Make sure that you change the baseURL inside [images_view.ts](https://github.com/lmaoclost/NextLevelWeek-3/blob/main/backend/src/views/images_view.ts) so the images can be displayed correctly in mobile.

## Day 4, 5: Mobile

I'm using Expo, so make sure that you have it. Go to [Api.ts](https://github.com/lmaoclost/NextLevelWeek-3/blob/master/mobile/src/services/api.ts) and change the baseURL to the server IP. If you're running the backend on localhost, the IP has the one in the expo page.

```
$ cd /mobile
$ yarn
$ yarn start
```

Go to the expo page and connect.

## Built With

- [Typescript](https://devdocs.io/typescript/) - Main Language
- [Node.js](https://nodejs.org/en/) - Backend framework
- [React.js](https://reactjs.org/) - JS framework for WEB
- [React Native](https://facebook.github.io/react-native/) - JS framework for APPs
- [Knex](https://typeorm.io/) - Typescript ORM
- [SQLite](https://www.sqlite.org/index.html) - Database
- [Expo](https://expo.io/) - Used to improve the app development

## Authors

- **Renan Oliveira** - [GitHub](https://github.com/lmaoclost), [LinkedIn](https://www.linkedin.com/in/renansmoliveira/)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

Made with ❤️ by Renan Oliveira.
