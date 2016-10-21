## Testing typescript

A learning project
- from [https://www.typescriptlang.org/docs/handbook/react-&-webpack.html](https://www.typescriptlang.org/docs/handbook/react-&-webpack.html)

Structure
- src
- dist


Installs
 - npm init
 - npm install -g typescript webpack
 - npm install --save react react-dom @types/react @types/react-dom
 - npm install --save-dev ts-loader source-map-loader
 - npm link typescript    ( use central typescript )

 Added a page for the raytracer
 change this, in webpack.config
 
 module.exports = {
    entry: "./src/raytracer.ts",
    output: {
        filename: "./dist/raytracer.js",
    },