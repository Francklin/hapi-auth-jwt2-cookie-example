# hapi-auth-jwt2 *example*

A ***functional example*** Hapi.js app demonstrating
[***hapi-auth-jwt2***](https://github.com/dwyl/hapi-auth-jwt2) authentication
using **Redis** (hosted on Heroku) with ***tests***!

[![Build Status](https://travis-ci.org/dwyl/hapi-auth-jwt2-example.svg)](https://travis-ci.org/dwyl/hapi-auth-jwt2-example)
[![Test Coverage](https://codeclimate.com/github/dwyl/hapi-auth-jwt2-example/badges/coverage.svg)](https://codeclimate.com/github/dwyl/hapi-auth-jwt2-example/coverage)
[![Code Climate](https://codeclimate.com/github/dwyl/hapi-auth-jwt2-example/badges/gpa.svg)](https://codeclimate.com/github/dwyl/hapi-auth-jwt2-example)
[![Dependency Status](https://david-dm.org/dwyl/hapi-auth-jwt2-cookie-example.svg)](https://david-dm.org/dwyl/hapi-auth-jwt2-cookie-example)

[![bitHound Score](https://www.bithound.io/github/dwyl/hapi-auth-jwt2-example/badges/score.svg)](https://www.bithound.io/github/dwyl/hapi-auth-jwt2-example)
[![Node.js Version](https://img.shields.io/node/v/hapi-auth-jwt2.svg?style=flat "Node.js 10 & 12 and io.js latest both supported")](http://nodejs.org/download/)
[![NPM Version](https://badge.fury.io/js/hapi-auth-jwt2.svg?style=flat)](https://npmjs.org/package/hapi-auth-jwt2)
[![HAPI 15.0.3](http://img.shields.io/badge/hapi-15.0.3-brightgreen.svg "Latest Hapi.js")](http://hapijs.com)
[![devDependency Status](https://david-dm.org/dwyl/hapi-auth-jwt2-example/dev-status.svg)](https://david-dm.org/dwyl/hapi-auth-jwt2-example#info=devDependencies)

## Environment Variables

To run this you will need to add an environment variable for your **JWT_SECRET** and **REDISCLOUD_URL**:
```
export JWT_SECRET=ItsNoSecretBecauseYouToldEverybody
export REDISCLOUD_URL=redis://rediscloud:OhEJvSgna@pub-redis-10689.eu-west-1-2.1.ec2.garantidata.com:10689
```

**Note**: you will need to set up your own Redis to use the code in this example in your project. if you're new to Redis check out our quick start guide: https://github.com/docdis/learn-redis


If you have ***any questions***, please ask! [![Join the chat at https://gitter.im/dwyl/chat](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/dwyl/chat/?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)  we are here to help!
