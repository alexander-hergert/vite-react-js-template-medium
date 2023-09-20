# Template for React Vite setup with JavaScript

This is the setup I use for medium React projects in JavaScript.
The projects have multiple pages and prefered way for fetching is React Query.

## This template uses following setups

- Please remove the .git file by using command "rm -rf .git"
- Then use "git init" again
- Then "npm install" or "yarn install"
- Then "npm update" or "yarn upgrade"

### Using Vite for bundling

[Vite](https://vitejs.dev/guide/) is a lightning-fast build tool for React projects.

### Using Tailwind-CSS for quick Styling

[Tailwind-CSS](https://tailwindcss.com/docs/guides/vite) simplifies styling in your React application.

### Prepared React Testing Library and Jest

- [React Testing Library](https://testing-library.com/docs/react-testing-library/intro/) is a user-centric testing library that encourages testing your React components as users would interact with them.
- [Jest](https://jestjs.io/docs/getting-started) is a JavaScript testing framework that provides a simple and powerful toolset for testing JavaScript applications, including React components, with built-in test runners and assertions.

### React Query for fetch operations

-[React Query](https://tanstack.com/query/v3/docs/react/overview) React Query is a popular JavaScript library for managing and caching asynchronous data in React applications. It simplifies data fetching, caching, and synchronization with the UI, making it easier to build fast and responsive web applications.

### Using React Router for routing

- [React Router](https://reactrouter.com/en/main/start/overview) React Router is a popular library for routing in React applications. It allows you to navigate between different pages or views in your single-page application (SPA). With React Router, you can define routes and render components based on the URL, creating a seamless user experience.

### images

- public/images with favicon
- favicon-32x32.png

### styles

- normalize.css
- index.css

### Files

#### [useContext](https://react.dev/reference/react/useContext)

- Prepared simple context and main.jsx wrapped in ContextProvider. (Use it to pass States between components)

#### [useReducer](https://react.dev/reference/react/useReducer)

- Prepared useReducer in the context.jsx (Organize your logic using a reducer to change the state. Make immutable changes!)
- reducer.js with very simple template for the logic

#### utils functions

- utils.js currently has (customFetch, saveDataToLocalStorage, loadDataFromLocalStorage) functions.

#### animations

- animations.js has prepared animations for framer library for react animations.

#### App data

- data.js holding static data for the web app

#### customHooks

- useFetchData.jsx
- reactQueryCustomHooks.jsx for examples

#### Loader

- Loader.jsx a Styled-Component which you can use to represent fetching animation.

#### Footer

- Footer.jsx a footer component for Frontend Mentor. (Change your name there or styles or delete)

#### React Query Example components

- ExampleReactQuery.jsx

#### Example Test

- components/Example/Counter.jsx
- .tests/Example/Counter.test.jsx

You can run tests by using ("npm run test" or "yarn test" depending on your package manager).

What you don't need you can remove and ofcourse install more dependencies which you might need for sure 😊
I hope this might inspire you to create your own template which you can keep on modifying and ofcourse create different variants.

Happy coding!
