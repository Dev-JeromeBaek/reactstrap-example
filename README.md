# Awesome-React-Babel7-Skeleton

## Set Up React, Webpack 4, and Babel 7 (2018)

## Demo

> https://Dev-JeromeBaek.github.io/awesome-react-babel7-skeleton/

## Folder Structure

After creation, your project should look like this:

```
awesome-react-redux-skeleton/
  README.md
  .prettierrc
  package.json
  webpack.config.dev.js
  webpack.config.js
  static/
    js/
      bundle.js
    media/
      image.afa5b8b9.png
  public/
    index.html
    favicon.ico
  src/
    assets/
      css/
        style.css
      images/
        image.png
    components/
      App.js
      Test.jsx
    index.js
  index.html
  favicon.ico
```

For the project to build, **these files must exist with exact filenames**:

- `public/index.html` is the page template;
- `src/index.js` is the JavaScript entry point.

## Build Setup

npm

```bash
# install dependencies
npm install

# serve with hot reload at 0.0.0.0
npm run start

# build for production with minification.
npm run build

# serve with hot reload dev-server at 0.0.0.0
npm run dev

# remove previous build files and build for production with minification.
npm run clean
```

or using yarn

```bash
# install dependencies
yarn install

# serve with hot reload at 0.0.0.0
yarn start

# build for production with minification.
yarn build

# serve with hot reload dev-server at 0.0.0.0
yarn dev

# remove previous build files and build for production with minification.
yarn clean
```

### babel set

```bash
{
    "presets": [
        "@babel/preset-env",
        "@babel/preset-react"
    ],
    "plugins": [
        "@babel/plugin-syntax-dynamic-import",
        "@babel/plugin-syntax-import-meta",
        "@babel/plugin-proposal-class-properties",
        "@babel/plugin-proposal-json-strings",
        [
            "@babel/plugin-proposal-decorators",
            {
                "legacy": true
            }
        ],
        "@babel/plugin-proposal-function-sent",
        "@babel/plugin-proposal-export-namespace-from",
        "@babel/plugin-proposal-numeric-separator",
        "@babel/plugin-proposal-throw-expressions"
    ]
},
```

### package.json

```bash
"devDependencies": {
  "@babel/core": "^7.0.0",
  "@babel/plugin-proposal-class-properties": "^7.0.0",
  "@babel/plugin-proposal-decorators": "^7.0.0",
  "@babel/plugin-proposal-export-namespace-from": "^7.0.0",
  "@babel/plugin-proposal-function-sent": "^7.0.0",
  "@babel/plugin-proposal-json-strings": "^7.0.0",
  "@babel/plugin-proposal-numeric-separator": "^7.0.0",
  "@babel/plugin-proposal-throw-expressions": "^7.0.0",
  "@babel/plugin-syntax-dynamic-import": "^7.0.0",
  "@babel/plugin-syntax-import-meta": "^7.0.0",
  "@babel/preset-env": "^7.0.0",
  "@babel/preset-react": "^7.0.0",
  "babel-loader": "^8.0.0",
  "css-loader": "^1.0.0",
  "file-loader": "^2.0.0",
  "html-webpack-plugin": "^3.2.0",
  "react-hot-loader": "^4.3.6",
  "style-loader": "^0.23.0",
  "uglifyjs-webpack-plugin": "^1.3.0",
  "url-loader": "^1.1.1",
  "webpack": "^4.17.1",
  "webpack-cli": "^3.1.0",
  "webpack-dev-server": "^3.1.6"
},
"dependencies": {
  "react": "^16.4.2",
  "react-dom": "^16.4.2"
}
```

## How to make your react project

npm

- Fork and clone this repository.
- Run `npm install` on your terminal.
- Open `src/components` directory.
- Make your component and Start your project.
- Run `npm run build` or `npm run clean` on your terminal
- Do setting for github.io hosting.

yarn

- Fork and clone this repository.
- Run `yarn install` on your terminal.
- Open `src/components` directory.
- Make your component and Start your project.
- Run `yarn build` or `yarn clean` on your terminal
- Do setting for github.io hosting.
