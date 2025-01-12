# React Native: Handling 'Cannot read properties of null (reading 'name')' Exception

This repository demonstrates a common error in React Native applications and provides a solution. The error, "Cannot read properties of null (reading 'name')", arises when trying to access a property of an object that is null or undefined. This often happens when dealing with asynchronous data fetching, where the data might not be available when the component initially renders.

## The Problem

The `bug.js` file contains a React Native component that fetches user data from an API.  However, it attempts to render the user's name before the data has been fetched, leading to the "Cannot read properties of null (reading 'name')" error.

## The Solution

The `bugSolution.js` file demonstrates how to resolve this issue by using optional chaining (?.) and nullish coalescing (??) operators. These operators provide a safe way to handle potentially null or undefined values, preventing the runtime error.

## How to Run

1. Clone this repository.
2. Navigate to the project directory.
3. Run `npm install` to install dependencies.
4. Run `npx react-native run-android` (or `npx react-native run-ios`) to run the app.

Feel free to experiment with both versions to see the difference.