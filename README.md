# react-without-cra (Now open to the public!)

<p align="center" width="100%">
    <img width="25%" src="public/x-cra-corrected.png">
</p>

A boilerplate for React made manually without the use of CRA.<br>
Never use create-react-app again!

Run npm init -y

Install the following pacakges via npm or yarn to get it up and running:<br>
Use --save-dev for all except react, react-dom and sass
- @babel/cli
- @bable/core
- @babel/preset-env
- @babel/preset-react
- babel-loader
- css-loader (if not using sass)
- eslint
- eslint-config-prettier
- eslint-plugin-jest
- husky (setup to use .jsx extensions when running commit/test)
- html-webpack-plugin
- jest
- jest-environment-jsdom
- prettier (use --save-dev and --save-exact)
- webpack 
- webpack-cli 
- webpack-dev-server
- react (make sure to use .jsx instead of .js for files)
- react-dom 
- sass (optional)
- sass-loader (optional, needed with sass)
- @testing-library/react 
- @testing-library/jest-dom

Make sure to use git init before installing husky<br>
<br>
This will make formatting consistent across all commits and any number of collaborators.<br>
To use TypeScript you may have to do some minor configuring and use .tsx extensions (haven't tested this yet)
