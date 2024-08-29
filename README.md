
<img width="1247" alt="Screenshot 2024-08-29 at 18 40 33" src="https://github.com/user-attachments/assets/af753049-ebc3-4af1-94c6-0e2c5d6bad19"> <img width="1257" alt="Screenshot 2024-08-29 at 18 41 16" src="https://github.com/user-attachments/assets/d9b8277e-8e02-4bda-bac3-15d430200507">



## Shopmate-React-Redux-Webpage

Shopmate is a demo React Redux E-Commerce Web Application (Global Level State Application), using **"Redux"** and **"Redux-Toolkit"** features. React Core, Hooks, Routing, HTML, CSS, Responsive Screen, Redux, and Redux-Toolkit functionalities have been used in this project and deployed on Netlify.

**Note:** "Redux" and "Redux-Toolkit" have been employed in this React project; "useContext" and "useReducers" have not been used here.

**This webpage can be seen by using this URL:** https://shopmate-redux-arnob.netlify.app

## To Install Dependences

Before launching this web application, be sure to install all required dependencies, which are listed in the package.json file.

To install all dependences, run this command from your project folder: `npm install`

## To Install NodeJS

Make sure you have NodeJS installed in your machine first, The installation instructions are here: https://nodejs.org/en/

## To Install React-Router 

Open up your terminal and bootstrap a new React app by: `npx create-react-app`

Then go to that project folder, and write this command via terminal from your project folder: `npm install react-router-dom`

(To check for more details about React-Router, please visit: https://reactrouter.com/en/main )

## To Install Redux and Redux-Toolkit

To install Redux and Redux-toolkit, run this command from your project folder:

`npm install react-redux@8`

`npm install @reduxjs/toolkit`

### More about React-Redux and Redux-Toolkit

**Documentation:** https://redux-toolkit.js.org/

Vocab,

- Redux is a pattern and library for managing and updating application state, using events called "actions".
  
- Slice: A "slice" is a collection of Redux reducer logic and actions for a single feature in your app, typically defined together in a single file. The name comes from splitting up the root Redux state object into multiple "slices" of state.
  
- Action: An action is a plain JavaScript object that has a `type` field. You can think of an action as an event that describes something that happened in the application. An action object can have other fields with additional information about what happened. By convention, we put that information in a field called `payload`.
  
- `useSelector` hook lets our component extract whatever pieces of data it needs from the Redux store state.
  
- `useDispatch` hook returns a reference to the `dispatch` function from the Redux store. You may use it to dispatch actions as needed.
  
- The `<Provider>` component makes the Redux `store` available to any nested components that need to access the Redux store.

Basic Steps To Follow:

- Create ‘**slice’** for data with name, initialState and reducers
  
- Get actions from slice.actions and export them

- Export reducers
  
- Import reducer inside store.js and register it
  
- Export store
  
- Cover the entire application with **Provider** with access to **{store}**

Steps to perform operations:

- Import the actions (add/remove)
  
- Use **useDispatch** so we can call actions

(To change anything in store, we need to dispatch the action)

- Use **useSelector** to get state information (cart/counter)

(For more details about Redux Devtool, visit: https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd?hl=en )

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
