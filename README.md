# web-pack-template

A general web pack template directory to be used for front-end development

> sass files are not accounted for

Packages to be installed[all the packages being installed have been configured]

1. npm:
   `npm init -y`

2. webpack:
   `npm install webpack webpack-cli --save-dev`

   run webpack [npx webpack] // for live-server [npx webpack --watch]

3. css-loaders(the rules may vary with sass loader):
   `npm install --save-dev style-loader css-loader`

4. html -webpack -plugin:
   `npm install --save-dev html-webpack-plugin`

   - run html-webpack-plugin [npm run build]

5. babel-loader:
   `npm install -D babel-loader @babel/core @babel/preset-env webpack`

- dev server [npm run dev]

- BundleAnalyzerPlugin [disabled] [npm run build]
