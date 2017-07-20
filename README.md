# node-diameter

[![Gitter](https://img.shields.io/badge/gitter-join%20chat-1dce73.svg)](https://gitter.im/node-diameter/node-diameter?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
[![npm version](https://badge.fury.io/js/diameter.svg)](http://badge.fury.io/js/diameter)
[![Build Status](https://travis-ci.org/node-diameter/node-diameter.svg?branch=master)](https://travis-ci.org/node-diameter/node-diameter)
[![Code Climate](https://codeclimate.com/github/node-diameter/node-diameter/badges/gpa.svg)](https://codeclimate.com/github/node-diameter/node-diameter)
[![Test Coverage](https://codeclimate.com/github/node-diameter/node-diameter/badges/coverage.svg)](https://codeclimate.com/github/node-diameter/node-diameter/coverage)

node-diameter is node.js implementation of Base Diameter protocol. 


## Usage

Check client and server in 'examples' directory. 

To see it in action:

````bash
$ npm install
````

### Start server:
````bash
$ npm run-script example-server
````

### Start client:
````bash
$ npm run-script example-client
````

## Complementary library

Makes it easier to work with diameter messages, by converting the arrays to objects:

[https://github.com/node-diameter/node-diameter-avp-object](https://github.com/node-diameter/node-diameter-avp-object)
