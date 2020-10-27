# CRA Boilderplate

## Install Code Formatting

On a fresh CRA installation run:

```
npm i --save-dev babel-eslint eslint-config-prettier eslint-loader eslint-plugin-prettier eslint-plugin-react prettier prettier-eslint
```

or

```
yarn add -D babel-eslint eslint-config-prettier eslint-loader eslint-plugin-prettier eslint-plugin-react prettier prettier-eslint
```

## Redux Setup

To install Redux and its dependencies run:

```
yarn add redux react-redux redux-logger redux-persist redux-saga reduxsauce reselect
```

## Using prettier-eslint

NOTE: this will only work if eslint and prettier are installed locally or globally. Please see instructions, at the first section, on Installing Code Formatting.

Also make sure that `eslint`, `prettier`, and `prettier-eslint` VSCode extensions are installed.

### Easy usage

Hover over lint errors and press `cmd` + `.` then select `Fix all prettier/prettier problems` or `Fix this prettier/prettier problems`

![prettier](https://github.com/redefinered/cra-boilerplate/blob/master/prettier.gif?raw=true "Prettier")
