## Create React App with multiple entry points

Attention: It's an `ejected` version of `create-react-app`, however, I'm going to push a PR for this missing feature.

To add more entry points, follow the steps:
- Add a new page in the `paths.js` in the property `appPages`. There are 2 existing pages there: `index` and `login`;
- Create your new files for the new page. You should add a new `.html` file inside the `public` folder and also add your new `.js` file (related to your "new" app) inside your `src` folder.
- Run `yarn start` or `npm start`;
- Access your using the following url `/.hml`, for example: `http://localhost:3000/login.html`
- Please, give me a ⭐️ if you liked
