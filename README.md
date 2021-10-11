# GCORP

GCORP Frontend, this project contains one web application handling the GOMRI Corporation website:
## Requirements

The following is required to install and run Angular:

- `Git`
- `NodeJS 10.1.x`
- `NPM >= 12.0.0`

Validate the setup by executing:

- `git --version`
- `node --version`

# Install (\*nix)

Download the source code:

```console
$ git clone [repository] frontend
```

Change directory:

```console
$ cd gcorp
```

Fetch dependencies:

```console
$ npm install
```

Start the web server, the application will automatically reload if any of the source files change:

```console
$ npm start
```

##### Using the proxy file to re-route calls to the backend

Start the application using the defualt proxy configuration. 

    npm run ng serve --host dev.mylocal.com --port 4204 --proxy-config proxy.conf.json

or simply

    npm run start:proxy

### Running the application locally against the different environments

Target the test environment locally
  
    npm run start:test

# Contribute

Create a branch (if the feature comprises multiple commits):

```console
$ git checkout -b [feature]
```

Push the changes:

```console
$ git push origin [feature]
```

# Test

Detailed information about writing and executing Angular tests is available in the official [documentation](https://angular.io/guide/testing).

## Unit

Run all the unit tests (in a given language):

```console
$ npm run ng test [b2c/shared/data-api]
```
