# Getting Started
## Available Scripts

In the project directory, you can run:
### `npm start` or `yarn start` 

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


# Intro

This folder structure is good if you hav up to 20 components

### hooks

The hooks folder contains every single custom hook in your entire project. This is a useful folder to have in any size project since almost every project will have multiple custom hooks so having a single place to put them all is really useful.

### components

The components folder in the simple folder structure is incredibly straightforward since it will contain every single component in your entire application. For small projects,  complicated components structure  is not needed and a single folder is just fine.

### __tests__

The final folder in this structure is for all your test code. Generally on smaller projects like this I find that people tend to store all their tests in one folder. Overall, I think this is fine for smaller projects.

### Pros

As mentioned the biggest pro of this folder structure is the pure simplicity of it, but beyond that this structure really isn't doing much for you.

### Cons

You will notice that this folder structure doesn't say what to do with things like images, utility functions, React contexts, etc. This is because for the most part smaller projects don't have many of these bonus files so you can get away with just storing all those files in the root of your src folder. Obviously, as your project scales this will become a mess quick which is why any project beyond small projects should be using at least an intermediate folder structure.