# Parcel bundler starter kit

If you're looking to get started using the Parcel JS bundler as a Webpack alternative, then this is the place for you.

Following on from a recent blog post on [using Parcel JS as a Webpack alternative](https://robkendal.co.uk/blog/2019-04-26-using-parcel-bundler-as-a-webpack-alternative/), I've put together this quick and simple starter kit so you can worry less about the setup and configuration and more about developing!

## Getting started

It couldn't be easier to get started. Simply fork or clone the repo into a local folder and run the `yarn` install command:

```
yarn install
```

This will install the following dependencies:

- Parcel JS bundler
- Babel (including the env preset)

## Running the starter kit

To start the development server, you'll want this command:

```
yarn start
```

This will quickly bundle all of the necessary files and kick off the development server, which is generated at `http://localhost:1234`. 

## How to use the starter kit

Everything is kept quite simple and as unopinionated as possible so that you can start developing quickly and however you choose. 

The important files of note are:

- `/index.html` -- this is where the project starts and Parcel looks for its first bundle starting point
- `/src/app.css` -- as mentioned, the first file where the system looks for CSS information 
- `/src/index.js` -- the initial JavaScript file that Parcel comes across as a starting point; it simply injects a string into the index.html page