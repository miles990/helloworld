# Project
Demo a private npm package for print "Hello World".


# Require
- Private npm server - [Sinopia](https://github.com/rlidwka/sinopia) (https://github.com/rlidwka/sinopia)


# Test
```
node test/app.js
```


# How to use
#### Install [Sinopia](https://github.com/rlidwka/sinopia)
```
npm install -g sinopia
```

#### Run private npm server
```
sinopia
```

#### Write code 
app.js
```
var helloworld = require('helloworld.js')();
```


# CI
[![Build Status](https://travis-ci.org/miles990/helloworld.svg?branch=master)](https://travis-ci.org/miles990/helloworld) 


# Linsence
MIT