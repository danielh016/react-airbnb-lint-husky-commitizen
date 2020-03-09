# React Airbnb Lint Husky Commitizen

[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)

This project is a combination of various useful tools that helps setup a standardized coding style among the team. Feel free to clone and start your next React application with this setup.
This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## The tools included:

- [ESLint](https://eslint.org/) with [Airbnb Style Guide](https://github.com/airbnb/javascript) as the major lint configuration
- [Prettier](https://prettier.io/) which collaborates with ESLint and handles the coding style issues (while ESLint handles code quality issues)
- [Husky](https://www.npmjs.com/package/husky) that helps with Git hooks related issues
- [Lint-staged](https://www.npmjs.com/package/lint-staged) which runs the linting and prettier commands by the developer `git commit`s
- [Commitizen](https://github.com/commitizen/cz-cli) which assists the developers working on this project to write commit messages in the same style

## Before you start

Although most of the configurations were setup for you, there is still one thing that was required.
Please run

```
$ yarn global add commitizen
OR
$ npm install -g commitizen
```

to make sure commitizen works on your device.

## To start

Right before you start implementing, please do either `yarn install` or `npm install` (choose one of them, of course) to install all the dependencies
After all the dependencies were install (in `/node_modules`), you can start playing with your application with `yarn start`

## To know more:

You can read on this article:
[中文版](https://medium.com/@danielhu95/set-up-eslint-pipeline-zh-tw-990d7d9eb68e)
