# Project
#### Build Status
[![Build Status](https://travis-ci.org/miles990/helloworld.svg?branch=master)](https://travis-ci.org/miles990/helloworld) 

#### Comment
Demo a private npm package for print "Hello World".


# Required
- Node.js
- Private npm server - [Sinopia](https://github.com/rlidwka/sinopia) (https://github.com/rlidwka/sinopia)


# Test
```
node test/app.js
```


# Turtorial
#### Install [Sinopia](https://github.com/rlidwka/sinopia)
```
npm install -g sinopia
```

#### Run private npm server
```
sinopia
```

#### Open private npm server (sinopia default)
[http://localhost:4873](http://localhost:4873)

#### Set npm config
```
npm set registry http://localhost:4873
```

#### Write npm module or clone this project
```
git clone https://github.com/miles990/helloworld.git
```

#### Publish npm module to private server
```
cd [project_folder]
npm adduser
npm publish
```

#### Test code 
app.js
```
require('helloworld.js')();
```

# Linsence
The MIT License (MIT)

Copyright (c) 2016 miles990

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
