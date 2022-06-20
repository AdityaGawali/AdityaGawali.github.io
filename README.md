# [Aditya's Personal Portfolio Website](adityagawali.github.io)
### Installation
- Install [Node.js](https://nodejs.org/en/)
- Optional Extension of live server for VSCode
    - [Live Server Extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) 
- run ```npm init``` in project directory to create package.json 
- intall node-sass  using npm
    - ```npm install node-sass```
- intall gh-pages modules using npm
    - ```npm install gh-pages```
- In project directory, make changes to ```package.json``` by adding script tag as below
```   
"scripts": {
    "sass": "node-sass -w scss/ -o dist/css/ --recursive",
    "deploy": "gh-pages -d dist"
  },
```
### Images
- Profile image size: 250px x 250px
- Profile image small size: 150px x 150px
- Projects image size: 600px x 450px 

### To Add Projects
- Add project item list in ```project.html```
- Create unique ```projectx.html```
- With a unique class name  in ```projectx.html``` add styling to that class in ```main.scss```
