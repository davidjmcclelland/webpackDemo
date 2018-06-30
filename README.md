# webpackDemo 2-create-a-bundle
corresponds to this lesson:
https://webpack.js.org/guides/getting-started/

* This is the "after" example showing a project that is managed by webpack.
* We installed the lodash library using npm.
* regarding npm installations:
* * When installing a package that will be bundled into your production bundle, you should use npm install --save. 
* * If you're installing a package for development purposes (e.g. a linter, testing libraries, etc.) then you should use npm install --save-dev.
* The library has no link in the index.html, so it is not downloaded and the page doesn't work.
* This is intentional to illustrate the most fundamental problem webpack is designed to solve.