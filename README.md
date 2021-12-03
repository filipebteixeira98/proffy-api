<h1 align="center">
  <img src=".github/logo.svg" alt="Logo" height="70">
</h1>

<h3 align="center">
  Proffy - Get in touch with any teacher and learn what you want.
</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/filipebteixeira98/">
    <img alt="Made by" src="https://img.shields.io/badge/made%20by-Filipe%20Teixeira-%239871F5"></a>

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/filipebteixeira98/proffy-api?color=%239871F5">

  <a href="https://github.com/filipebteixeira98/proffy-api/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/filipebteixeira98/proffy-api?color=%239871F5"></a>

  <img alt="GitHub" src="https://img.shields.io/github/license/filipebteixeira98/proffy-api?color=%239871F5">
</p>

<p align="center">
  <a href="#-about-the-project">About the project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-getting-started">Getting started</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-how-to-contribute">How to contribute</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-license">License</a>
</p>

<img alt="Layout" src="https://res.cloudinary.com/eliasgcf/image/upload/v1596552194/proffy/proffy-mockup_a2owui.png">

## 📚 About the project

This project was developed on the Next Level Week #02 event by [Rocketseat](https://rocketseat.com.br/) 🚀&nbsp;💜

This application is designed to connect teachers and students. For teachers, it is possible to define the start and end time of classes, the hourly price and describe themselves. Students can get in touch and choose favorites teachers.

## 🚀 Technologies

Technologies that I used to develop this application

- [Node.js](https://nodejs.org/en/)
- [TypeScript](https://www.typescriptlang.org/)
- [Express](https://expressjs.com/pt-br/)
- [CORS](https://www.npmjs.com/package/cors/)
- [Knex.js](https://knexjs.org/)
- [SQLite](https://www.sqlite.org/index.html/)

## 💻 Getting started

### Requirements

- [Node.js](https://nodejs.org/en/)
- [Yarn](https://classic.yarnpkg.com/)

**Clone the project and access the folder**

```bash
$ git clone https://github.com/filipebteixeira98/proffy-api.git && cd proffy-api
```

**Follow the steps below**

```bash
# Install dependencies
$ yarn

# Make sure you do not have knexfile.ts misconfigured

# Use the script to run the migrations
$ yarn knex:migrate

# To finish, run the api service
$ yarn start

# Well done, project is started!
```

## 🤔 How to contribute

**Make a fork of this repository**

```bash
# Fork using GitHub official command line
# If you don't have the GitHub CLI, use the web site to do that.

$ gh repo fork filipebteixeira98/proffy-api
```

**Follow the steps below**

```bash
# Clone your fork
$ git clone https://github.com/filipebteixeira98/proffy-api.git && cd proffy-api

# Create a branch with your feature
$ git checkout -b my-feature

# Make the commit with your changes
$ git commit -m 'feat: My new feature'

# Send the code to your remote branch
$ git push origin my-feature
```

After your pull request is merged, you can delete your branch

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Made with 💜&nbsp; by Filipe Teixeira 👋 &nbsp;[See my linkedin](https://www.linkedin.com/in/filipebteixeira98/)
