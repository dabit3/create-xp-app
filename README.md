![create-xp-app](http://reactnative.training/createxpapp2.png)

### [ReactXP](https://github.com/Microsoft/reactxp)  Project Generator

This app works on React Native (iOS, Android, Windows) and web. Most of the app's code is contained in App.tsx.

## To get started, install the create-xp-app cli globally
```
npm i -g create-xp-app
```

## To create a new ReactXP app

1. Run create-xp-app <projectName>
```
create-xp-app MyProject
```


![cli](http://reactnative.training/figlett4.jpg)

### To run web and ios in dev mode

```
npm run dev
```

This compiles the TypeScript code and spins up a webpack-dev-server with hot module replacement at `http://localhost:8080`, and spins up the iOS emulator which can be set to live reload via its developer menu.

### To run on web:

1. Run npm run web-watch
```
npm run web-watch
```

This compiles the TypeScript code and recompiles it whenever any files are changed.

2. Open index.html in your browser to view the result.

### Building for React Native (iOS, Android, Windows)

1. Run npm run rn-watch
```
npm run rn-watch
```

This compiles the TypeScript code and recompiles it whenever any files are changed.

2. In another command prompt run npm start
```
npm start
```

This starts the React Native Packager.

Use the command line, Xcode or Android Studio to build and deploy the native app code just like you would with any other React Native project.
