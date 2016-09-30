How to Turn a Web app into An Electron Desktop App
Step 1.
Open Terminal: npm init 
To create package.json
Step 2.  npm install electron-packager 
Installs Electron
Step 3. Create main.js
- to point to your html file
Step 4. Place your index.html file (in this case our angular folder)
Step 5: edit package.json     
"scripts": {
    "start": "electron main.js",
    "build": "electron-packager . AngularApp"
  }
Step 6. In terminal: npm i electron-packager --save-dev and npm i electron-prebuilt --save-dev
Step 7: Done: click to open AngularApp


---------------------------------------------------------
To use: 
1. In terminal, run npm install (make sure nodejs is installed)
2. App should now work
