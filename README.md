# ReactJS

## Create ReactJS Project Structure using command line :-

### Install the react command line tool globally so you can use it from any project directory.
Open a command prompt or git bash and type below command
```
npm install -g madebyform/react-cli
```

### Create an application
In command prompt or git bash, go to folder where you want to create application and run below command
```
react new my-application
```
This command sets up a new react application inside the **my-application** directory and will have will have the following directory structure:
```
my-app/
  assets/
  src/
    components/
    utils/
    views/
```    
### Generate React components
In cammand prompt or git bash, go to your applicaiton folder e.g. **my-application** and run below command :
react generate MyComponent firstProp:string secondProp:requiredObject

This will create a skeleton **mycomponent.jsx** file inside your **src/components** directory.
