# JavaScript: Test-Driven Development (ES6) Study Project
- https://www.linkedin.com/learning/javascript-test-driven-development-es6/

## Advantages
- TDD foreces use to clearify our thinking
- TDD improves communistaions
- TDD improves the structure of code
- Allows developers to make worry-free changes

## Disadvantages
- Take longer at first
- Isn't always a favorite with management
- Beware of writing bad tests



## Setup
```
  npm install -D mocha chai
  npm install -D @babel/core @babel/preset-env @babel/register

  npm i -D chai-exclude

  npm i -D sinon
```
Create .babelrc


## Run test
```
  npx mocha "src/**/*.test.js" --recursive --require @babel/register
```  


## Using Environment variable
```
"scripts": {
    "test": "NODE_ENV=test npx mocha \"src/**/*.test.js\" --recursive --require @babel/register --file src/mocha-setup.js"
  },
```