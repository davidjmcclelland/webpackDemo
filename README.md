# webpackDemo
corresponds to this lesson:
https://webpack.js.org/guides/getting-started/

* This is a "before" example showing a project that is not managed by webpack.
* It contains a dependency on lodash library, but the dependency is only found
if you know where to look in the js file. 
* The library has no link in the index.html, so it is not downloaded and the page doesn't work.
* This is intentional to illustrate the most fundamental problem webpack is designed to solve.