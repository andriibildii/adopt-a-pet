# Adopt a Pet!

In this project, I practiced using React Router (v5 - 5.2.0) to add client-side routing to a React Application.

Specifically, I builded a pet adoption website that allows users to view all the adoptable pets of a particular species and view the profiles of specific adoptable pets.

At the start, the app rendered a `HomePage` component that fetched and displayed all adoptable pets. We had also a `PetDetailsPage` to display the details for a particular pet (**src/pages/detail/index.js**), but this component not rendered until I create a route to display it.

My task was to add client-side routing to the application using React Router so that:

- The `HomePage` component responds to the browser’s current URL by displaying only pets of the species the user wishes to view.
- The `PetDetailsPage` page displays when the browser’s current URL includes a specific pet’s id.
- The `PetDetailsPage` displays data for the correct pet based on the id in the URL parameters’ values.
- When the user searches for a pet in the search bar, they are redirected to the `SearchPage`, which uses the query parameter called `name` to filter pets by name.
- When a user clicks a pet whose details are not available, they are redirected to a `PetNotFoundPage`.
- From the `PetNotFound` page, users can click “Go Back” button that will take them to page they were previously on.

The components that I have been primarily working with:

- **src/App.js** (App)
- **src/pages/home/index.js** (HomePage)
- **src/pages/detail/index.js** (PetDetailsPage)
- **src/pages/search/index.js** (SearchPage)
- **src/pages/petNotFound/index.js** (PetDetailsNotFound)

Using Mock Service Worker (MSW) to replicate the functionality of an external API. To use MSW, you’ll want to use Google Chrome and enable third-party cookies.

Main steps:

1. Installing React Router and adding a Router to the project.
2. Creating the Route
3. Using URL Parameters in the React Components (useParams())
4. Replacing a Tags with React Router Elements (to NavLink & Link )
5. Adding Another Route
6. Adding a Search Feature
7. Adding a PetDetailsNotFound Page

## Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

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

### `yarn build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
