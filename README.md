## Create React App with multiple entry points

**Attention**: It's an `ejected` version of `create-react-app`, however, I'm going to push a PR for this missing feature. The non `ejected` version could be find here: https://github.com/DanZeuss/create-react-app

**There's a pending PR for this solution on https://github.com/facebook/create-react-app/pull/8249**

To add more entry points, follow the steps:
- Before cloning, slap ⭐️ now
- Add a new page in the `package.json` in the property `appPages`. There are 2 existing pages there: `index` and `login`;
- Create your new files for the new page. You should add a new `.html` file inside the `public` folder and also add your new `.js` file (related to your "new" app) inside your `src` folder.
- Run `yarn start` or `npm start`;
- Access your using the following url `/.hml`, for example: `http://localhost:3000/login.html`

