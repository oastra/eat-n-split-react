# Eat-n-Split

This project is a React application designed to help friends split expenses. It allows users to add friends, track balances, and split bills, ensuring that everyone pays their fair share. The application is styled using CSS and provides an intuitive user interface for managing expenses among friends.

## Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

### Available Scripts

In the project directory, you can run:

#### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

#### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

#### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

#### `npm run eject`

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

## Project Structure

- `index.js`: The entry point for the React application, where the root component is rendered.
- `App.js`: The main component that includes logic for adding friends, selecting friends, and splitting bills.
- `index.css`: Contains all the styles used in the application to ensure the app is visually appealing and responsive.

## Project Overview

The application consists of features that allow users to:

1. **Add Friends**: Users can add friends to their list with a name and image.
2. **Select Friends**: Users can select a friend to split expenses with.
3. **Split Bills**: Users can enter the bill amount and split it between themselves and their selected friend.

### Components

- **App.js**: The main application logic, including handling friends and bill splitting.
- **Button.js**: A reusable button component for various actions like adding friends and submitting forms.
- **FriendsList.js**: Manages the list of friends and handles selection.
- **FormAddFriend.js**: A form to add a new friend with a name and image URL.
- **FormSplitBill.js**: A form to split a bill with a selected friend.

### Styling

- **index.css**: Provides the necessary styles for the application, including color schemes, layout, and responsive design elements.

### Dependencies

- `react`: The core library for building the user interface.
- `react-dom`: Handles the rendering of React components.

### Author

- **Olha Chernysh**
