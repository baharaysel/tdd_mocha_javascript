# tdd_mocha_javascript
 Test driven development with mocha chai and javascript calculator
 from 
 Sam Barros
samaronybarros


npm install -g mocha

npm install --save chai

//Run a specific suite or test from a specific suite file.

mocha /path/to/test_suite.js

or

mocha -g “Test-2” /path/to/test_suite.js

//Run  a specific suite or test file by searching recursively in a directory tree.

mocha --recursive -g “Test-2” /directory/


mocha –-help


//Creating a project 
$ mkdir mocha-chai-tests
$ cd mocha-chai-tests
$ yarn init
or 
$ npm init -y

//Install chai and mocha.
$ yarn add chai mocha
or 
$ npm i chai mocha --save

$ mkdir tests
$ touch tests/calc.js


// to test 
$ yarn mocha tests/calc.js
or
$ mocha tests/calc.js


note: run the tests with empty calculator.js file then add one by one your code to pass tests.



