# Getting Started in the React Ecosystem
A list of resources to get on-boarded to the react ecosystem

This guide assumes you already have a good understanding of JavaScript, HTML, and CSS

I originally wrote this guide for onboarding new employees into the react/redux/webpack ecosystem, and split it up into parts... You should go through each of these resources and be sure to split the parts up into days or multiple days so you don't get information overload. Afterwards, you might want to go even further and learn about Immutable, Flow, Nuclide, Atom-IDE

- Recommended Browser: Chrome (has many useful react and redux dev tools)
- Recommended Editor: [Atom](https://atom.io/)


## Part 1: ECMASCRIPT 2015
- Read the documentation on [ECMAScript 6 Syntax](http://babeljs.io/docs/learn-es2015/)
- Read about the [ES6 features](https://github.com/lukehoban/es6features#readme)
- Learn about [Babel and Transpiling](https://kleopetrov.me/2016/03/18/everything-about-babel/)
- Complete the [ES6 tutorial](http://ccoenraets.github.io/es6-tutorial/)
- Watch the videos in [this course on Egghead.io about ES6](https://egghead.io/series/learn-es6-ecmascript-2015)
- [ES6 One Liners to Show Off](https://appendto.com/2017/03/es6-one-liners-to-show-off/)

## Part 2: React.js
- Go through the [New React Tutorial](https://facebook.github.io/react/tutorial/tutorial.html)
- Familiarize yourself with [React DevTools for Chrome](https://github.com/facebook/react-devtools#react-developer-tools-)
- Look at [Create React App](https://github.com/facebookincubator/create-react-app) - a tool to easily get started making a react app.
- If you're in the mood, [watch some videos](https://facebook.github.io/react/community/videos.html)
- Explore [some example code](https://github.com/facebook/react/wiki/Examples)
- Go through the [React Router Guide](https://reacttraining.com/react-router/web/guides/quick-start)
- [React Lifecycle Methods](https://engineering.musefind.com/react-lifecycle-methods-how-and-when-to-use-them-2111a1b692b1) - how and when to use them
- Learn about [5 Types of React Application State](http://jamesknelson.com/5-types-react-application-state/)
- [8 things to learn in React before using Redux](https://www.robinwieruch.de/learn-react-before-using-redux/)

## Part 3: Redux
- If you want to understand where the idea came from, [watch the Flux presentation](https://www.youtube.com/watch?v=nYkdrAPrdcw)
- Watch the Redux course on egghead.io: [Getting Started With Redux](https://egghead.io/series/getting-started-with-redux) - from the creator of Redux, [Dan Abramov](https://twitter.com/dan_abramov)
- Read the entirety of the [redux documentation](http://redux.js.org/docs/introduction/index.html)
- Watch the next Redux course on egghead.io: [Building React Applications with Idiomatic Redux](https://egghead.io/courses/building-react-applications-with-idiomatic-redux)
- Are you still confused about Thunks? [What the heck is a 'thunk'?](https://daveceddia.com/what-is-a-thunk/)
- Familiarize yourself with [Redux DevTools for chrome](https://github.com/zalmoxisus/redux-devtools-extension) - They do cool things like replaying action history, and state inspection.
- Want to become more efficient with Redux? [Learn about Reselect](https://github.com/reactjs/reselect#reselect)
- Building a large application? Learn [The Duck Pattern](https://github.com/erikras/ducks-modular-redux#ducks-redux-reducer-bundles)

## Part 4: Webpack 2
- Learn about the [Webpack 2 Concepts](https://webpack.js.org/concepts/) 
- [Install Webpack](https://webpack.js.org/guides/installation/) in one of your projects, or a new project.
- Read about configuring [Webpack Dev Server](https://webpack.js.org/configuration/dev-server/)
- Read about [Hot Module Replacement](https://webpack.js.org/guides/hot-module-replacement/)

## Part 5: Node.js
You've already been using Node.js behind the scenes in most of these tools. If you want to create your own back end to serve your application, look into Express:
- [Node.js](https://nodejs.org/en/docs/)
- Before you bury yourself in packages, [learn the Node.js runtime itself](https://medium.freecodecamp.org/before-you-bury-yourself-in-packages-learn-the-node-js-runtime-itself-f9031fbd8b69)
- Getting Started with [Express](http://expressjs.com/en/starter/installing.html)
- Many people have switched from `npm` to `yarn`: [Getting Started with Yarn](https://yarnpkg.com/en/docs/getting-started)

## Part 6: Testing
- [Getting Started with Jest](https://facebook.github.io/jest/docs/en/getting-started.html) - Delightful JavaScript Testing
- Testing React components with [Enzyme](https://github.com/airbnb/enzyme#enzyme)
- [ReactTestUtils](https://facebook.github.io/react/docs/test-utils.html), testing React components in the DOM
- Redux testing tips (actions/async actions, reducers, containers, and middleware): http://redux.js.org/docs/recipes/WritingTests.html 
- [Testing Reselect](https://github.com/reactjs/reselect#q-how-do-i-test-a-selector)

## Part 7: Putting it all together
- Try setting up a project from scratch using `yarn init` and then add react, redux, webpack, middleware, other libraries, etc.
- Build out a mini-app using all of these technologies to make sure you understand:
  - How to create react components
  - How to create actions, thunks, and reducers in redux
  - How to create redux modules using the [Duck Pattern](https://github.com/erikras/ducks-modular-redux#ducks-redux-reducer-bundles)
  - How to make your own server using Node/Express
  - Configure a build process in webpack
  - Use webpack to process CSS and Image files so your entire project builds into 1 js file (or multiple - see Code Splitting below)
  
If you want to see an example, I've created my own [react-app-scaffolding](https://github.com/malechite/react-app-scaffolding) from scratch using all of the above information. (note: this scaffolding assumes you have a back-end that provides a JWT token)


## BONUS: Still want to learn more?
### Immutable - Immutable collections for JavaScript
- Video: [React.js Conf 2015 - Immutable Data and React](https://www.youtube.com/watch?v=I7IdS-PbEgI)
- [Immutable Getting Started Guide](https://facebook.github.io/immutable-js/)
- [Getting Started With Immutable.js](https://gist.github.com/trobertsonsf/18e2a2906e3221b6c085)
- [Documentation](https://facebook.github.io/immutable-js/)
### Flow - a static type checker for JavaScript
- [Introduction to type checking with Flow](https://flowtype.org/docs/getting-started.html#_)
### Other Testing Tools
- [Karma](https://karma-runner.github.io/0.13/index.html) - a test runner.
- [Jasmine](http://jasmine.github.io/2.3/introduction.html), a testing framework:
### Nuclide - a suite of plugins for Atom for developing JavaScript applications
- [Getting Started with Nuclide](https://nuclide.io/docs/quick-start/getting-started/)
### Atom IDE - a set of optional packages to bring IDE-like functionality to Atom
- [Introducing Atom IDE](http://blog.atom.io/2017/09/12/announcing-atom-ide.html)
- [Getting started with Atom IDE](https://ide.atom.io/)
### Socket.io
- [Socket.io Documentation](http://socket.io/docs/)
- [Socket.io Tutorial](http://socket.io/get-started/)
### Code Splitting
- [Webpack: Code Splitting by Routes](https://medium.com/@puppybits/webpack-code-splitting-by-routes-92f96cf733f2)
- [React Router 4 code splitting w/ RxJS & Webpack](https://medium.com/@luigiplr/react-redux-react-router-4-code-splitting-w-rxjs-webpack-32eabedf0e9)
### JWT
- [Secure Your React and Redux App with JWT Authentication](https://auth0.com/blog/secure-your-react-and-redux-app-with-jwt-authentication/) - by Auth0
- [Building a React/Redux App with JSON Web Token (JWT) Authentication](http://blog.slatepeak.com/build-a-react-redux-app-with-json-web-token-jwt-authentication/)
- [Securing React Redux Apps With JWT Tokens](https://medium.com/@rajaraodv/securing-react-redux-apps-with-jwt-tokens-fcfe81356ea0)
### Misc articles and other resources
- [Navigating the React.JS Ecosystem](https://www.toptal.com/react/navigating-the-react-ecosystem)
- [10 React mini-patterns](https://hackernoon.com/10-react-mini-patterns-c1da92f068c5)






