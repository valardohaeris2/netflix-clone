# netflix-clone

## Tools used

### VS Code

IDE

### TMDB

Movie database used as a 3rd party tool to get movie data. Client makes a request to this service and they return movie data. We pull that info in and put it in our front-end. Created an API key and bearer token for authentication to the API.

### Postman

Allows you to send a request to any API or server. Used to test the API get request. API URL: https://api.themoviedb.org/3/movie/550?api_key=. Bearer token:

### REACT

Used to build scalable apps that wraps HTML, CSS, and Java Script and renders intelligently.

### npx

Package manager for NodeJS

### Firebase

Used to host the website, db, authentication

## Steps

1. Create TMDB account and API key
   - We'll make an API request to the TMDB service. In order to authenticate to the service, we need a API key
2. Setup Firebase hosting:
   - register app
   - install Firebase CLI
   - build > hosting. create hosting
3. Download npx to use npm modules instead of an SDK
4. Create a new React app npx dependencies: `npx create-react-app netflix-clone`
5. `npm start`
6. Install axios to use instead of Postman to send request from our code: `npm i axios`
7. Add a requests.js file
8. Add fetch endpoints to requests.js file
9. Create a axios.js file. Used so every request has the same base URL. Pass `instance` a base URL
10. Get movies & build rows

# My computer changes to look into changing back:

    sudo chown -R `whoami`:admin /usr/local/include/node
    sudo chown -R `whoami`:admin /usr/local/bin
    sudo chown -R `whoami`:admin /usr/local/share
    sudo chown -R `whoami`:admin /usr/local/lib/dtrace

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
