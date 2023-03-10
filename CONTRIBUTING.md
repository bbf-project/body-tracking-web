# Contributing

First off, thank you for considering contributing to this project. It's people like you that make this project such a great tool. We appreciate your help!

[CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md)

## Reporting Bugs, Suggesting Enhancements and Asking Questions

If you have found a problem with this project, please report it by creating a new [issue](https://github.com/LucaCiucci/body-tracking-web/issues). Please include as much information as possible.

If you have a suggestion or you want to require a new feature, you may do so by creating a new issue or, if it might require a lot of discussion, by creating a new [discussion](https://github.com/LucaCiucci/body-tracking-web/discussions).

If you want to just ask a question, you may prefer to create a new discussion, or an issue if you think it might be something that could be improved in the documentation and/or the way the project works.

## Contributing Code

If you want to contribute code, you may do so by creating a new [pull request](https://github.com/LucaCiucci/body-tracking-web/discussions) and we will review it as soon as possible.

The next sections will guide you through the process of setting up the project on your machine, how to run it and how to orient yourself in the codebase.

### Project Setup

This project uses [Node.js](https://nodejs.org/en/) and the default package manager is [npm](https://www.npmjs.com/). You just need to install Node.js on your machine in order to be able to run the project.

Once you have Node.js installed, it is highly recommended to install [Visual Studio Code](https://code.visualstudio.com/) as your code editor. It is not mandatory, but it will make your life easier.

Once you have installed this tools, you can clone the project on your machine. If you are not a collaborator, you will need to fork the project first in order to be able to push your changes, otherwise you will get an error when you try to push your changes.

Once you have cloned the project, you can install the dependencies by running `npm install` in the root of the project and then `npm start` to start the development server. You can read more about the available scripts in the [package.json](./package.json) file, the main [README](./README.md) might also be useful.

### Codebase

In the root of the project, you will find the necessary files to run the project, such as the [package.json](./package.json), [tsconfig.json](./tsconfig.json), etc. These files are used by the Node.js runtime to run the project.

#### `src` folder

The main code of the project is located in the [src](./src) folder. The [index.ts](./src/index.ts) file is the entry point of the project.

Inside the [src](./src) folder, you will find some files that describes the top level components of the project. The "sub-apps" are located in the [src/apps](./src/apps) folder.

#### `public` folder

The [public](./public) folder contains the static files that are served "as is" by the server. The [index.html](./public/index.html) file is the entry point of the client side of the project.

#### `assets` folder

TODO?

#### `docs` folder

This folder contains a user-friendly documentation of the project. It will be transformed into a website and hosted on GitHub Pages.

Note that, when the static website is generated by the [deploy action](./.github/workflows/jekyll-gh-pages-and-app.yml), an additional subfolder `app/` will be added to the root of the website and the built app will be hosted there.

#### `tests` folder

TODO ...

#### Dependencies

This project has many dependencies, but the most important ones are:
 - [MediaPipe](https://google.github.io/mediapipe/) for the body tracking
 - [React](https://reactjs.org/) for the UI
 - [Monaco Editor](https://microsoft.github.io/monaco-editor/) for the scripts editor

### Commit Messages

<!--This project uses [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) to generate the changelog. Please follow the guidelines when writing your commit messages.-->

TODO ...

### Pull Requests

To contribute code, you will need to create a new pull request.

TODO ...