# ReactExpressTemplate
Basic React/Redux and Express website that is held together using web pack that I created from video tutorials and looking things up online. 

Once you clone the repo you will need to delete the package.json file and use npm init in the root directory. Save all the default answers and it should save all the dependancies you will need. If not you will need to install the following items:
1. In Root Folder
 * npm init (index.js)
 * npm install --save express
 * npm install --save pug
 * npm install nodemon
2. In public folder
 * npm install --save webpack
 * npm install --save babel-cli babel-preset-react
 * npm install --save babel-loader babel-core
 * npm install --save react react-dom
 * npm install --save redux react-redux
 * npm install --save babel-preset-es2015 babel-preset-react

Once all your dependencies are installed you will need to add to the scripts in package.json "webpack":"webpack". Then in a terminal in the root directory run "npm run webpack" which will create your bundle.js file. Keep this runnning and open annother terminal in the root directory and run "nodemon". Now your website will be running on localhost:3000 where you changes you make can be viewed live. 
