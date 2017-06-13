# ReactJS

## Create ReactJS Project Structure using command line :-

### Install the react command line tool globally so you can use it from any project directory.
Open a command prompt or git bash and type below command
```
npm install -g create-react-app
```

### Create an application
In command prompt or git bash, go to folder where you want to create application and run below command
```
create-react-app my-application
```
This command sets up a new react application inside the **my-application** directory and will have will have the following directory structure:
```
my-application/
  README.md
  node_modules/
  package.json
  .gitignore
  public/
    favicon.ico
    index.html
    manifest.json
  src/
    App.css
    App.js
    App.test.js
    index.css
    index.js
    logo.svg
    registerServiceWorker.js
```    
### To run app
In cammand prompt or git bash, go to your applicaiton folder e.g. **my-application** and run below command :
```
npm start
```
This will open in browser with http://localhost:3000 or Open http://localhost:3000 to view it in the browser.

### To run test cases
In cammand prompt or git bash, go to your applicaiton folder e.g. **my-application** and run below command :
```
npm test
```
### Builds the app for production to the build folder.
```
npm run build
```
