# Awesome React Boilerplate

This repository contains React boilerplate with modern JavaScript tooling.

## What is included?

- Webpack
- Babel
- Hot Reload with react-hot-loader
- Production bundle analysis with webpack-bundle-analyzer
- Testing with Jest
- Common JS erros checking with ESLint
- Automatic code formatting with Prettier
- Husky to configure precommit hooks
- Accessibility issues checking with react-axe

## How to build you project based on this one?

1. Start by cloning this repository

`git clone git@github.com:krzysiek-szporer/awesome-react-boilerplate.git my-awesome-app`

2. Next remove .git folder with git setup and history for this boilerplate

`rm -rf .git`

3. Do the nessesery changes in package.json - name, author and delete repository, bugs & homepage keys

4. Initiate new git repository

`git init`

4. Next stage all the existing files

`git add --all`

5. First initial commit

`git commit -m "Initial commit"`

6. Assuming you have already created new repository for your project, add new remote

`git remote add origin ...`

7. Push exisiting repository

`git push -u origin master`

8. Now you can add missing keys from package.json by simply running this command:

`npm init -y`

9. At the end you can modify README file and commit changes

## How to start development?

Start by installing all dependencies, hit `npm install` and you are ready to code!

- Hit `npm run dev` to run webpack-dev-server and see live changes in the browser

- Hit `npm run build` when you are ready to deploy something cool

- Hit `npm run test` to test your application with Jest

- Hit `npm run format` to automaticaly format your code with Prettier

- Hit `npm run lint` for double check if you didn't break any JS rule listed by ESLint

Remeber that your code will be tested, linted and formatted before every commit by Husky using precommit hooks. Look for configuration files to adjust the behavior of some tools.

That's all, happy coding!
