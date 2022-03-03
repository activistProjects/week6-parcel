# Using Parcel instead of Create-React-App

## Steps

- Create an empty folder
- type: npm init -y (creates a npm package.json)
- type: npm i -D parcel (installs Parcel)
- type: npm i react react-dom (installs React libraries)
- create a src folder
- create a index.js, App.jsx and index.html file
  - copy the contents of what are in these files (minus the code in App.jsx)
- in package.json create a "script" (this will run your server to render your React):
  -    "dev": "parcel src/index.html --open"
- create a .gitignore file
  - copy what is in this file
- create a local git repo (you should know this already):
  - git init
  - git add .
  - git commit -m "message"
- type npm run dev (this will run your React App)
- NO MORE NEEDING CREATE REACT APP!!! :)