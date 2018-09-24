# It's Dealer Locator using ReactJS

How to setup the project in our local?

Git checkout https://github.com/Sakthivel/React-Dealer-Locator.git

yarn / npm install

yarn start / npm start

hit http://localhost:3000/

Now, we will able to see our application on our browser.

How to build the project?

yarn build / npm build

Note: yarn/npm watch is running our project so each change build command will run by default.

How to run unit test?

yarn test / npm test

it will run unit test

How to setup eslint into my project?

Step 1

Installing eslint and eslint-config-airbnb

Install eslint plugin for vscode
Install eslint (you can also install this globally but I like to install it locally)
yarn add eslint --dev
Install eslint-config-airbnb which need few other dependencies as well
yarn add eslint-config-airbnb eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-react --dev
Create .eslintrc file in the root directory and add the following lines
{
  "extends": [
    "airbnb"
  ]
}
Now, you will start seeing lint errors in your code.

