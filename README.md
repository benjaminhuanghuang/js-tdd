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
```
Create .babelrc


## Run test
```
  npx mocha "src/**/*.test.js" --recursive --require @babel/register
```  