npm install react react-dom
npm install -D typescript @types/react @types/react-dom
- - - - - - - - - - - - - - - - - - - - - - - - - - - -
tsconfig.json - compilerOptions: for type checking, and
not for code transpilation. 

Babel - for transpilation. Browser doesn't understand React or 
TypeScript code, so we need to convert it into JavaScript.

npm install -D @babel/core @babel/preset-env @babel/preset-react 
@babel/preset-typescript

.babelrc - list down the presets, which we gonna use.
It will transpile modern JavaScript features into a format,
that browsers can understand.

webpack - module bundler.
npm install -D webpack webpack-cli webpack-dev-server 
html-webpack-plugin babel-loader
- - - - - - - - - - - - - - - - - - - - - - - - - - - -