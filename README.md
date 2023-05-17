# iNotebook - Secure Note-Taking Web Application 

In today's digital world, staying organized is essential. To address this need, I created iNotebook, a web application that allows users to store, modify, and delete their notes securely. With user authentication and robust security measures, iNotebook ensures that users' data remains confidential and protected from unauthorized access.

Features:

User Authentication: iNotebook implements a user authentication system to ensure that only registered users can access their notes. This feature prevents unauthorized users from viewing or modifying sensitive information.

Secure Note Storage: All user notes are securely stored in a MongoDB Atlas database. By leveraging the power of cloud storage, users can access their notes from anywhere, anytime, without the risk of data loss.

Password Encryption: To protect user passwords, iNotebook utilizes encryption techniques. Passwords are encrypted before being stored in the database, ensuring that even if the data is compromised, hackers cannot access the original passwords.  iNotebook incorporates salted passwords, adding an extra layer of security. By appending a unique salt value to each user's password before encryption, the system prevents hackers from using precomputed rainbow tables or dictionary attacks to crack passwords.

Data Isolation: Each user can only access and modify their own notes. Through proper authorization and data isolation techniques, iNotebook ensures that users' data remains private and isolated from other users.

![iNotebook](https://github.com/Vikassoni91/iNotebook/assets/90946288/ae2a5188-63ac-4ebc-a3a6-cc96714a5e7f)

To add a Note
![iNotebook](https://github.com/Vikassoni91/iNotebook/assets/90946288/b3dc5aa1-1bf5-4c27-b195-5a40b96ddd4d)

Login Page
![iNotebook](https://github.com/Vikassoni91/iNotebook/assets/90946288/6251cfb1-182c-4a55-9f77-66f9fb7f8167)

SignUp Page
![iNotebook](https://github.com/Vikassoni91/iNotebook/assets/90946288/1c804c1c-d20a-41ca-9a07-c992cd92bb2b)


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
