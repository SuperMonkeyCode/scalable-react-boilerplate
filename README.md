# Feature First / Scalable
The boilerplate aims to follow best practices for building highly scalable and reusable apps and component libraries.

Following the lead of the famous [React Boilerplate]() project, this starter project incorporates the Feature-first architecture, meaning that files are organized by the feature they implement, not the filetype.  This provides a mechanism to scale React projects because it encourages isolation, encapsulation and reusability.

We incorporate an ESLint configuration and follow strictly the [AirBnb JS & JSX style guides](https://github.com/airbnb/javascript).

# Documentation

## Getting Started
To try the example application out or to use the project, follow the instructions below.

1. **Clone repo**

    git clone https://github.com/RyanCCollins/scalable-react-boilerplate.git

2. **Install dependencies**

    npm run setup

3. **Run development server**

   npm run start

   Development server should be running at http://localhost:8080/

4. **Make build**

   npm run build

### File Structure
* Some files left out for brevity.  Please reference the files in the [Scalable React Boilerplate](https://github.com/RyanCCollins/feature-first-react-boilerplate) project for an example of the file structure.  The application will ultimately be in use in a production web application project and more info will be posted here when we have production level examples.
```
.
├── README.md
├── LICENSE
├── index.html
├── package.json
├── webpack.config.js
├── app/
|   ├── fonts
|   ├── images
|   ├── src
|   |   ├── components
|   |   |   ├── FeatureFirstComponent
|   |   |   |   ├── index.js
|   |   |   |   ├── index.module.scss
|   |   |   |   └── tests
|   |   |   |   |   └── index.test.js
|   |   |   ├── App.jsx
|   |   |   ├── Main.js
|   |   |   └── index.js
|   |   ├── containers
|   |   |   ├── MyContainer
|   |   |   |   ├── tests
|   |   |   |   |   ├── actions.test.js
|   |   |   |   |   ├── index.test.js
|   |   |   |   |   └── reducer.test.js
|   |   |   |   ├── actions.js
|   |   |   |   ├── constants.js
|   |   |   |   ├── index.js
|   |   |   |   ├── index.module.scss
|   |   |   |   └── reducer
|   |   |   └── index.js
|   |   ├── pages
|   |   ├── store
|   |   ├── utils
|   |   └── index.js
|   └── styles
├── .eslintignore
├── .eslintrc
├── .gitattributes
└── .gitignore
```

## Scripts
- **npm run setup**

    Installs the application's dependencies

- **npm run test**

     Runs unit tests

- **npm run test:watch**

     Watches for changes to run unit tests

- **npm run build**

     Bundles the application

- **npm run dev**

     Starts webpack development server

- **npm run lint**

     Runs the linter

- **npm run deploy**

     Creates the production ready files

- **npm run clean**

    Removes the bundled code and the production ready files


### Generators
Coming soon, the project will incorporate code generation following the best practices outlined by this project's setup.

## Technologies / Libraries

- [Node](https://nodejs.org/en/) - JS runtime environment
- [npm](https://www.npmjs.com/) - package manager
- [Babel](https://babeljs.io/) - ES6 transpiler
- [Webpack](https://webpack.github.io/) - module bundler & task runner
- [React](https://facebook.github.io/react/) - interfaces
- [react-hot-loader](https://github.com/gaearon/react-hot-loader) - hot reloading for react
- [react-router](https://github.com/rackt/react-router) - react application router
- [react-redux](https://github.com/rackt/react-redux) - react bindings for redux
- [react-css-modules](https://github.com/gajus/react-css-modules) - React CSS Modules implement automatic mapping of CSS modules.
- [react-foundation](https://github.com/nordsoftware/react-foundation) - Foundation React components, use or don't use.
- [Immutable](https://github.com/facebook/immutable-js) - data structures
- [Redux](https://github.com/rackt/redux) - awesome flux architecture
- [Redux Form](https://github.com/erikras/redux-form)- works with React Redux to enable an html form in React to use Redux to store all of its state.
- [redux-thunk](https://github.com/gaearon/redux-thunk) - thunk middleware for redux
- [isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) - API fetch network requests
- [redux-devtools](https://github.com/gaearon/redux-devtools) - redux development tool
- [SASS](http://sass-lang.com/) - styles
- [ESLint](http://eslint.org/) - linter
- [Mocha](http://mochajs.org/) - unit tests
- [jsdom](https://github.com/tmpvar/jsdom) - vdom to test React without browser
- [Expect](https://github.com/mjackson/expect) - assertion library
- [Chai / Immutable](http://chaijs.com/) - assertion library for Immutable JS
- A bunch of useful scripts


## Timeline / TODOS
* [x] Write README file
* [ ] Write component tests using Enzyme
* [ ] Write wiki / other documentation
* [ ] Implement a Rails like component generator

### Acknowledgements
![Scalable React Boilerplate Logo](https://github.com/RyanCCollins/cdn/blob/master/alumni-webapp/udacity-alumni-small.png?raw=true)
This boilerplate began its life as a fork of the [React Redux Simple Starter](https://github.com/RyanCCollins/react-redux-simple-starter) project and was setup as a starter project for the Udacity Alumni Web application open-source project.

It was created by several of the members of the Udacity Alumni product infrastructure team, including:
* [Ryan Collins](https://github.com/RyanCCollins)
* [Andreas Daiminger](https://github.com/adai183)
