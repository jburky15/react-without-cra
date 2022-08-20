# react-without-cra

A boilerplate for React made manually without the use of CRA.<br>
Never use create-react-app again!

Run npm init -y

Install the following NPM pacakges to get it up and running:<br>
Use --save-dev for all except react, react-dom and sass
- @babel/cli
- @bable/core
- @babel/preset-env
- @babel/preset-react
- babel-loader
- eslint
- eslint-config-prettier
- husky (setup to use .jsx extensions when running commit/test)
- html-webpack-plugin
- prettier (use --save-dev and --save-exact)
- webpack 
- webpack-cli 
- webpack-dev-server
- react (make sure to use .jsx instead of .js for files)
- react-dom 
- sass (optional)

Make sure to use git init before installing husky<br>
<br>
This will make formatting consistent across all commits and any number of collaborators.<br>
To use TypeScript you may have to do some minor configuring and use .tsx extensions (haven't tested this yet)
