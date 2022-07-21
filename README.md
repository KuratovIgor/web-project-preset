# JavaScript project preset #

==============================================================
### Use build preset in your WEB project for comfortable development. You can change project configuration as you like.
## Preset includes:
* ### *[Webpack](https://webpack.js.org/) configuration*
   * *Optimize include libraries*
   * Copy files (customizable)
   * *Dev server*
   * *Auto include scripts into HTML*
   * *Build css / sass / scss / less*
   * *JS / TS babel*
   * *Images and icons loader*
   * *ESLint*
   * *StyleLint*
* ### *[ESLint](https://eslint.org/) configuration*
   * *Airbnb*
* ### *[StyleLint](https://stylelint.io/) configuration*
   * *Lint sass/scss*
   * *Styles order*
### *Preset uses node.js 16.11.0 and npm 8.0.0!*
### Webpack default uses entry file extension .ts. If you want to use JavaScript:
 1. #### Change webpack config
```javascript
entry: {
    main: ['@babel/polyfill', './scripts/index.js'],
},
```
2. Change extension index.ts file into .js 
## Start project:
   * ### Build for development 
      ```npm run dev```
   * ### Build for production
      ```npm run build```
   * ### Run watch in live
      ```npm run watch```
   * ### Start dev server
      ```npm run start```
