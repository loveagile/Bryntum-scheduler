# Basic React Scheduler component template

This project was bootstrapped with the Bryntum [Create React App](https://github.com/facebook/create-react-app)
template `@bryntum/cra-template-javascript-scheduler`.

If you use typescript, please use the `@bryntum/cra-template-typescript-scheduler` template instead.

The template uses Bryntum Scheduler wrapped in the provided `BryntumScheduler` wrapper.
The template contains a basic integration of the React Scheduler control wrapper.

# Bryntum Repository access setup

**IMPORTANT NOTE!** These access instructions are mandatory when using the private Bryntum NPM repository.

The template uses npm packages from the Bryntum private NPM repository. You must be logged-in to this repository as a
licensed or trial user to access the packages.
If you do use the product under license, please update the **package.json** file and replace:

```json
"@bryntum/scheduler": "npm:@bryntum/scheduler-trial@5.3.0"
```

with

```json
"@bryntum/scheduler": "5.3.0",
```

Please check [Online npm repository guide](https://bryntum.com/products/scheduler/docs/npm-repository/)
for detailed information on the sign-up/login process. Also you can check bundled guide inside distribution zip
in `docs/guides/npm-repository.md`.

# React integration guide

Please check this
[Bryntum React integration online guide](https://bryntum.com/products/scheduler/docs/integration/react)
for detailed integration information and help. Also you can check bundled guide inside distribution zip
in `docs/guides/integration/react.md`.

# Installation

Use the following command to install the example packages after the successful login.

Using **npm**:

```shell
$ npm install
```

Using **yarn**:

```shell
$ yarn install
```

# Running a development server

To build example and start development server run this command:

Using **npm**:

```shell
$ npm start
```

Using **yarn**:

```shell
$ yarn start
```

Navigate to `http://localhost:3000/` or `http://127.0.0.1:3000/` in your browser. We recommend to use latest versions of
modern browsers like Chrome, FireFox, Safari or Edge (Chromium). The app will automatically reload if you change any of
the source files.

# Creating a production build

To build production code for the example run this command:

Using **npm**:

```shell
$ npm run build
```

Using **yarn**:

```shell
$ yarn run build
```

The build artifacts will be stored in the `build/` directory.

# Distribution zip references

* Bryntum API docs. Open `docs/index.html` in your browser
* Bryntum Repository guide `docs/guides/npm-repository.md`
* Bryntum React integration guide `docs/guides/integration/react.md`

# Online References

* [React Framework](https://github.com/facebook/create-react-app)
* [Bryntum React integration guide](https://bryntum.com/products/scheduler/docs/integration/react/)
* [Bryntum Scheduler documentation](https://bryntum.com/products/scheduler/docs/)
* [Bryntum Scheduler examples](https://bryntum.com/products/scheduler/examples/)
* [Bryntum npm repository guide](https://bryntum.com/products/scheduler/docs/npm-repository/)
* [Bryntum support Forum](https://forum.bryntum.com/)
* [Contacts us](https://bryntum.com/contact/)
