# 💬 chattr — One-to-One Chat Application

**chattr** is a real-time one-to-one chat web app built with **React**, **Node.js**, **Express**, and **PostgreSQL**. It supports user authentication, private chatting, message editing, and deletion options, all in a clean and responsive interface.

---

##  Purpose

- To **connect people instantly** via direct messaging.
- To **create friendships** by enabling simple, real-time conversations.
- To **learn full-stack development** by implementing features like authentication, routing, and database interactions in a real-world scenario.

---

##  Features

-  User Registration & Login (with persistent login via localStorage)
-  One-to-One messaging (polls new messages every 1 seconds)
-  Edit messages (only by sender)
-  Delete messages:
- "Delete for Me"
- "Delete for Everyone" (only sender can delete for both)
-  Right-click context menu on messages


---

## Tech Stack

- **Frontend**: React, Axios
- **Backend**: Node.js, Express
- **Database**: PostgreSQL
- **Styling**: Plain CSS

---

## project structure
One-oneChat/
├── backend/
│ ├── controllers/
│ │ └── messageController.js
│ │ └── authController.js
│ ├── db.js
│ ├── queries
│ ├── server.js
| ├── node_modules
│ ├── package.json
│ ├── package-lock.json
│ └── .env
│
├── frontend/
│ ├── node_modules/
│ ├── public/
│ └── src/
│ ├── components/
│ │ ├── ChatBox.css
│ │ ├── chatBox.jsx
│ │ ├── ContactList.jsx
│ │ ├── ContactList.css
│ │ ├── NavBar.jsx
│ │ └── NavBar.css
│ ├── App.jsx
│ ├── App.css
│ ├── App.test.js
│ ├── index.jsx
│ ├── index.css
│ ├── logo.svg
│ ├── reportWebVitals.js
│ ├── package.json
│ ├── package-lock.json
│ └── setupTests.js
├── .gitignore

---

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
