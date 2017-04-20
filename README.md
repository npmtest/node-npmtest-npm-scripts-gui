# npmtest-npm-scripts-gui

#### basic test coverage for  npm-scripts-gui (v0.0.24)  [![npm package](https://img.shields.io/npm/v/npmtest-npm-scripts-gui.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-npm-scripts-gui) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-npm-scripts-gui.svg)](https://travis-ci.org/npmtest/node-npmtest-npm-scripts-gui)

#### GUI for npm scripts

[![NPM](https://nodei.co/npm/npm-scripts-gui.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/npm-scripts-gui)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-npm-scripts-gui/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-npm-scripts-gui/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-npm-scripts-gui/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-npm-scripts-gui/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-npm-scripts-gui/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-npm-scripts-gui/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-npm-scripts-gui/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-npm-scripts-gui/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-npm-scripts-gui/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-npm-scripts-gui/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-npm-scripts-gui/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-npm-scripts-gui/build/test-report.html](https://npmtest.github.io/node-npmtest-npm-scripts-gui/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-npm-scripts-gui/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-npm-scripts-gui/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-npm-scripts-gui/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-npm-scripts-gui/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-npm-scripts-gui/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-npm-scripts-gui/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-npm-scripts-gui/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-npm-scripts-gui/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "npm-scripts-gui",
    "productName": "NSG",
    "version": "0.0.24",
    "description": "GUI for npm scripts",
    "main": "bin/cli.js",
    "bin": {
        "npm-scripts-gui": "bin/cli.js",
        "nsg": "bin/cli.js"
    },
    "scripts": {
        "stylus": "stylus -c src/styles/base.styl -u autoprefixer-stylus -o styles",
        "stylus-themes": "stylus -c src/styles/themes -u autoprefixer-stylus -o styles/themes",
        "transpile-scripts": "babel src/scripts --out-dir scripts",
        "transpile-cli": "babel src/cli.js > bin/cli.js",
        "transpile-index": "babel src/index.js > index.js",
        "transpile-postinstall": "babel src/postInstall.js --out-file postInstall.js",
        "test": "echo 'no tests'",
        "postinstall": "node postInstall.js",
        "update-version": "./bin/update_version.rb",
        "prepublish": "./bin/prepublish.rb",
        "fail": "echo 'i will fail!' ; exit 1"
    },
    "author": "Sam Eaton",
    "license": "MIT",
    "devDependencies": {
        "autoprefixer-stylus": "^0.8.1",
        "babel-cli": "^6.3.13",
        "babel-preset-es2015": "^6.3.13",
        "babel-preset-react": "^6.5.0",
        "stylus": "^0.52.4"
    },
    "dependencies": {
        "chalk": "^1.1.1",
        "chokidar": "^1.4.2",
        "cubbie": "0.0.8",
        "electron-prebuilt": "^0.35.4",
        "fangs": "0.0.11",
        "lodash": "^4.5.1",
        "ps-tree": "^1.0.1",
        "react": "^0.14.7",
        "react-dom": "^0.14.7"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/samueleaton/npm-scripts-gui"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
