FCWS  Backend(Express/Mongoose)
==== 

This is a backend server implemented by express for fcws. The front end part is in [fcws-ionic](https://github.com/rdmclin2/fcws-ionic)

## How to install
clone the repo:
```
$ git clone git@github.com:rdmclin2/fcws-backend.git
```

install the dependencies
```
$ cd fcws-backend && npm install
```

## Load data
Make sure you have mongodb installed in your computer,then 
```
$ cd fcws-backend/bin && sh init.sh
```
This will load the users and districts data from the shell scripts

## Run
Test the backend along with the front end
```
# run in the devlopment mode 
$ make run
# run in production mode 
$ make start
# restart the production mode 
$ make restart
# run tests
$ make test
```

# The MIT License (MIT)

Copyright (c) 2016 Calvin Meng

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.