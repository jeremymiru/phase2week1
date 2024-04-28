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


# week1-codechallengephase2
# Date 2024/04/28

# By Jeremy Kariuki
## Description
State Management:
The component uses React's useState hook to manage state.
It maintains state for searchQuery, which represents the user's search query for filtering expenses.
It also maintains state for expenses, an array containing a list of expense objects.
Another state, sortOrder, is used to keep track of the sorting order.
Event Handlers:
handleSearchChange: Updates the searchQuery state based on user input in the search input field.
handleSort: Handles sorting of expenses based on the specified key (e.g., date, description, category, amount).
Filtering Expenses:
The filteredExpenses variable filters the expenses array based on the search query entered by the user.
Adding Expenses:
The AddExpenseForm component is a separate function component responsible for rendering a form to add new expenses.
It maintains local state for the date, description, category, and amount of the new expense.
When the form is submitted, it creates a new expense object and adds it to the expenses array.
Rendering:
The PurchaseTable component renders a header with the title "The Royal Bank Of Flatiron," a search input field, and the AddExpenseForm.
It renders a table with columns for date, description, category, and amount.
Each row in the table corresponds to an expense object from the filteredExpenses array.
## Installation
You use git clone to be able to download the documents in the GitHub

## Installation Requirements
Git

### Installation instruction
```
Git clone https://github.com/jeremymiru

```

# Live Link
[Git](gh-pages link)

## Technologies used
Github
Javascript
JSX
CSS

## Support and contact details
github.com/jeremy-kariuki

### License
The content of this site is licensed under the MIT license
Copyright (c) 2018.
