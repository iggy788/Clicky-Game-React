# Clicky-Game-React

## Overview

In this game, you'll play a memory game I made with React.
### Instructions

1. Check out the [My Game](https://clicky-game.netlify.com/).

2. Create a new React application using [Create React App](https://github.com/facebookincubator/create-react-app).

3. The application should render different images (of your choice) to the screen. Each image should listen for click events.

4. The application should keep track of the user's score. The user's score should be incremented when clicking an image for the first time. The user's score should be reset to 0 if they click the same image more than once.

5. Every time an image is clicked, the images rendered to the page should shuffle themselves in a random order.

6. Once the user's score is reset after an incorrect guess, the game should restart.

7. When complete, the application should be deployed to Github Pages. See the README generated with Create React App for instructions on deploying the application to Github Pages.

- - -
### App Structure
```
├── public
│   ├── images
│   └── favicon.ico
│   └── index.html
│   └── manifest.json
│   └── style.css
│
├── src
│   ├── components
│   │   ├── Footer.js
│   │   ├── GameItem.css
│   │   ├── GameItem.js
│   │   ├── Header.js
│   │   ├── MainPart.js
│   │   ├── Score.js
│   │   └── footer.css
│   ├── materialize
│   │   │── css
│   │   │   ├── materialize.css
│   │   │   └── materialize.min.css
│   │   │── fonts
│   │   │   └── TBD
│   │   └── js
│   │   │   ├── materialize.js
│   │   │   ├── materialize.min.js
│   │   │   └── test.css
│   │   └── LISCENSE
│   ├── App.css
│   ├── App.js
│   ├── App.test.js
│   ├── index.css
│   ├── index.js
│   ├── logo.svg
│   └── registerServiceWorker.js
│
├── .gitignore
│
└── package.json
```
