<p align="center">
  <img src="./static/images/quiver-black.png" alt="Quiver Logo">  
</p>

<h1 align="center">Quiver</h1> 

<!-- [![Build Status](https://img.shields.io/travis/npm/npm/latest.svg?style=flat-square)](https://travis-ci.org/npm/npm)  -->
[![npm](https://img.shields.io/npm/v/npm.svg?style=flat-square)](https://www.npmjs.com/package/npm) 
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com) 
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](https://github.com/your/your-project/blob/master/LICENSE)
> This app is a proof of concept and is not intended to be used for active trading

Trade equities, options and crypto assets through Robinhood and Binance.

## Installing / Getting started

A quick introduction of the minimal setup you need to get a quiver up &
running.

```shell
git clone git@github.com:josephemswiler/quiver.git <app-name>
cd <app-name>
npm install
npm run dev
```

Running the dev script will launch the express server for NextJS on port 3000.
Navigate to `http://localhost:3000` to view the running application.

## Developing

### Built With
- [NextJS](https://nextjs.org/) - Server side rendered react
- [MongoDb](https://www.mongodb.com/) via [mLab](https://www.mlab.com/) and [Mongoose](http://mongoosejs.com/)
- [ExpressJS](https://expressjs.com/)
- [React](https://reactjs.org/)
- [Redux](https://redux.js.org/)
- [Redux-Saga](https://github.com/redux-saga/redux-saga)
- [ChartJS](https://www.chartjs.org/)
- [Robinhood-Node](https://github.com/aurbano/robinhood-node)
- [Binance-Api-Node](https://github.com/binance-exchange/binance-api-node)

### Prerequisites
Install the following global npm dependencies:
- [Nodemon](https://nodemon.io/)


### Setting up Dev

To develop the project further:

```shell
git clone git@github.com:josephemswiler/quiver.git <app-name>
cd <app-name>
npm install
```

The project supports hot reloading during development with the webpack server built into NextJS. Simply run dev and begin coding.

### Building

To build to production:

```shell
npm run build
```

### Deploying / Publishing
give instructions on how to build and release a new version
In case there's some step you have to take that publishes this project to a
server, this is the right time to state it.

```shell
packagemanager deploy your-project -s server.com -u username -p password
```

And again you'd need to tell what the previous code actually does.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](/tags).


<!-- ## Configuration

Here you should write what are all of the configurations a user can enter when
using the project.

## Tests

Describe and show how to run the tests with code examples.
Explain what these tests test and why.

```shell
Give an example
``` -->

## Style guide

This project uses the StandardJS style guide. The project contains a script to lint the style with the `prettier` plugin and fix any inconsistencies automatically before commit. It is recommended that you install the [Prettier-Standard - JavaScript formatter](https://marketplace.visualstudio.com/items?itemName=numso.prettier-standard-vscode) for VSCode.

<!-- ## Api Reference

If the api is external, link to api documentation. If not describe your api including authentication methods as well as explaining all the endpoints with their required parameters.


## Database

Explaining what database (and version) has been used. Provide download links.
Documents your database design and schemas, relations etc...  -->

## Licensing

Copyright (c) 2011-2017 Quiver

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
