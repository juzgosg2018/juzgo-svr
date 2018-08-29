## Install dependencies for backend
```bash
npm i
```

## Install dependencies for Angular 6

```bash
cd admin
npm i
```

## Run Admin Angular 6 App

```bash
cd admin
ng build
```

## Run Admin Angular 6 App as standalone

```bash
cd admin
ng serve
```

## API Backend for juzgo

[Spreadsheet](https://docs.google.com/spreadsheets/d/1kXgDxi8pCt4IlZ-PPt2avkPgaRtf9eNPWCTHQ6fGk9c/edit#gid=1313757103)


## Firebase Admin

```javascript
var admin = require("firebase-admin");

var serviceAccount = require("path/to/serviceAccountKey.json");

admin.initializeApp({
  credential: admin.credential.cert(serviceAccount),
  databaseURL: "https://juzgosg-1e65c.firebaseio.com"
});
```