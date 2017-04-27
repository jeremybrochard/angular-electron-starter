# angular-electron-starter

Sample project for building desktop apps using Angular and Electron. 

Encapsulates built Angular apps into Electron apps.

The project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.0.1.

## Install and launch Angular app

- git clone https://github.com/jeremybrochard/angular-electron-starter.git 
- npm install
- ng serve

## Launch Electron app

- npm run-script electron-serve

This command will build the Angular app first, then it will copy the outputs to the "electron\app" folder.

Finnaly the app is executed with Electron binary.

## More commands

**Angular CLI commands:**

- ng serve 
- ng build 

See other commands in the [Angular CLI](https://github.com/angular/angular-cli) official documentation.

**Custom Electron commands:**

- npm run-script electron-build    

Build Angular app whith standard angular CLI and copy the outputs to the "electron\app" folder.

- npm run-script electron-config 

Copy the Electron app files (main.js and package.json for Electron' app). The "main.js" file is the entry point of the Electron app as defined in the "package.json" file.

- npm run-script electron-run 

Run the Electron app according to the files existing in the "electron\app" folder.

- npm run-script electron-serve 

Launch sequentially all the previous command.




