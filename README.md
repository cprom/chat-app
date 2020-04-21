# PrivateChat

A React JS app for private chat and post between two people or a group.
Invitation and account setup is made either through registering an account or an email link invitation send through the app to a recipient. 


## Example.  
* Person A register’s an account to the page and logs in.  

* The choices they will have is create a chat room.  They will provide the name of the chat room and invite people to the chat.  First phase will have the invite to a chat room being made through an email link and at a later point we will create a search to allow them to add people to a chatroom from list of all users in the PrivateChat group.

* Request received through email with initial invite token and initial invite account.  Person clicks on it and they will arrive at an initial screen to create and update their invite account.  When they update it they are notified account in logged in and they can click on the login button from the navbar on top. 

* Initial login.  They see the chat room they are invited to and the post and comments made.

* All theses chatrooms are invites only.

* For now the private chatrooms are for a small group and content and features later added would only be known between the small group.
When members are added to the private chat all team members will receive a notification marked to icon indicating new members invited so at any time all members know who is on the private chat.

## Technologies:

Node.js, Reactjs, Mongoose, Mongo db,  mysql, Serializer, passport, nodemailer and material ui.





-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `npm run build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
