
DevBridge Sourcery Academy 2021 app. Team INBIF (If not bug its a feature).
### To login:
userName: John Doe<br />
password: inbif<br />
Or in UserContext.jsx line 22, set isLoggedIn to true

## Run the project

- To run this project you will need [Node](https://nodejs.org/en/). We strongly recommend to use [nvm](https://github.com/nvm-sh/nvm) for installing node.
- After installing nvm go to project directory and run:
  - `nvm install [version in .nvmrc file]`
  - `nvm use`
  - `npm install`
  - `npm run start-server` - runs server
  - `npm start` - builds project for development

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `npm run lint`

Runs all linters and prettier and shows any warnings/errors in console.

### `npm run storybook`

Runs storybook for development.

### `npm run svgo`

Replaces SVG stroke value to currentColor.

### `npm run update-sprite`

Optimizes and add SVG to one file (sprite).

