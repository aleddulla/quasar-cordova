# Quasar App (quasar-cordova)

A Quasar Project

## Install the dependencies
```bash
yarn
# or
npm install
```

### Start the app in development mode (hot-code reloading, error reporting, etc.)
```bash
quasar dev
```


### Lint the files
```bash
yarn lint
# or
npm run lint
```


### Format the files
```bash
yarn format
# or
npm run format
```



### Build the app for production
```bash
quasar build
```

### Install Cordova CLI
```bash
npm install -g cordova

Note that when it asks for "Cordova app id" this is usually a reverse domain name of your company which is used to uniquely identify your app.
cd src-cordova
```

### Add android platform
```bash
cordova platform add android
cordova requirements - check that everything is fine or not.
```

### Generate Cordova Project
```bash
Now build android for development
quasar dev -m cordova -T android
quasar mode add cordova
```

### Generate aap or apk bundle
```bash
cordova build android --release -- --packageType=apk
```
### Publishing to Store:
```bash
https://quasar.dev/quasar-cli-webpack/developing-cordova-apps/publishing-to-store#Introduction
```

### DEMO:


