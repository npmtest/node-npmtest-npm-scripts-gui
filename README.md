# npmtest-npm-scripts-gui

#### basic test coverage for  [npm-scripts-gui (v0.0.24)](https://github.com/samueleaton/npm-scripts-gui#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-npm-scripts-gui.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-npm-scripts-gui) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-npm-scripts-gui.svg)](https://travis-ci.org/npmtest/node-npmtest-npm-scripts-gui)

#### GUI for npm scripts

[![NPM](https://nodei.co/npm/npm-scripts-gui.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/npm-scripts-gui)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-npm-scripts-gui/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-npm-scripts-gui/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-npm-scripts-gui/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-npm-scripts-gui/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-npm-scripts-gui/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-npm-scripts-gui/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-npm-scripts-gui/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-npm-scripts-gui/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-npm-scripts-gui/tree/gh-pages/build)|

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
    "author": {
        "name": "Sam Eaton"
    },
    "bin": {
        "npm-scripts-gui": "bin/cli.js",
        "nsg": "bin/cli.js"
    },
    "bugs": {
        "url": "https://github.com/samueleaton/npm-scripts-gui/issues"
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
    "description": "GUI for npm scripts",
    "devDependencies": {
        "autoprefixer-stylus": "^0.8.1",
        "babel-cli": "^6.3.13",
        "babel-preset-es2015": "^6.3.13",
        "babel-preset-react": "^6.5.0",
        "stylus": "^0.52.4"
    },
    "directories": {},
    "dist": {
        "shasum": "763e99f283159a365cacea6ea6844a42d665fb7a",
        "tarball": "https://registry.npmjs.org/npm-scripts-gui/-/npm-scripts-gui-0.0.24.tgz"
    },
    "gitHead": "9f24c9165a3eb6b65ca395baa15de5d49442a58f",
    "homepage": "https://github.com/samueleaton/npm-scripts-gui#readme",
    "license": "MIT",
    "main": "bin/cli.js",
    "maintainers": [
        {
            "name": "same"
        }
    ],
    "name": "npm-scripts-gui",
    "optionalDependencies": {},
    "productName": "NSG",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/samueleaton/npm-scripts-gui.git"
    },
    "scripts": {
        "fail": "echo 'i will fail!' ; exit 1",
        "postinstall": "node postInstall.js",
        "prepublish": "./bin/prepublish.rb",
        "stylus": "stylus -c src/styles/base.styl -u autoprefixer-stylus -o styles",
        "stylus-themes": "stylus -c src/styles/themes -u autoprefixer-stylus -o styles/themes",
        "test": "echo 'no tests'",
        "transpile-cli": "babel src/cli.js > bin/cli.js",
        "transpile-index": "babel src/index.js > index.js",
        "transpile-postinstall": "babel src/postInstall.js --out-file postInstall.js",
        "transpile-scripts": "babel src/scripts --out-dir scripts",
        "update-version": "./bin/update_version.rb"
    },
    "version": "0.0.24"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
