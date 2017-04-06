# api documentation for  [ember-cli-document-title (v0.3.3)](https://github.com/kimroen/ember-cli-document-title)  [![npm package](https://img.shields.io/npm/v/npmdoc-ember-cli-document-title.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-ember-cli-document-title) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-ember-cli-document-title.svg)](https://travis-ci.org/npmdoc/node-npmdoc-ember-cli-document-title)
#### Adding document title functionality to your ember app

[![NPM](https://nodei.co/npm/ember-cli-document-title.png?downloads=true)](https://www.npmjs.com/package/ember-cli-document-title)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ember-cli-document-title/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-ember-cli-document-title_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ember-cli-document-title/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-ember-cli-document-title/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-ember-cli-document-title/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kim Røen",
        "email": "kim@kimroen.com"
    },
    "bugs": {
        "url": "https://github.com/kimroen/ember-cli-document-title/issues"
    },
    "dependencies": {
        "ember-cli-babel": "^5.1.6"
    },
    "description": "Adding document title functionality to your ember app",
    "devDependencies": {
        "broccoli-asset-rev": "^2.4.2",
        "ember-cli": "2.8.0",
        "ember-cli-app-version": "^1.0.0",
        "ember-cli-dependency-checker": "^1.2.0",
        "ember-cli-htmlbars": "^1.0.3",
        "ember-cli-htmlbars-inline-precompile": "^0.3.1",
        "ember-cli-inject-live-reload": "^1.4.0",
        "ember-cli-qunit": "^2.1.0",
        "ember-cli-release": "^0.2.9",
        "ember-cli-sri": "^2.1.0",
        "ember-cli-test-loader": "^1.1.0",
        "ember-cli-uglify": "^1.2.0",
        "ember-disable-prototype-extensions": "^1.1.0",
        "ember-export-application-global": "^1.0.5",
        "ember-load-initializers": "^0.5.1",
        "ember-resolver": "^2.0.3",
        "loader.js": "^4.0.1"
    },
    "directories": {
        "doc": "doc",
        "test": "tests"
    },
    "dist": {
        "shasum": "0441d64e3ab7a64b220f8c54a144ab927d6138af",
        "tarball": "https://registry.npmjs.org/ember-cli-document-title/-/ember-cli-document-title-0.3.3.tgz"
    },
    "ember-addon": {
        "configPath": "tests/dummy/config"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "gitHead": "0c3b9923414406bffd6f748acf5fa6b29d56921e",
    "homepage": "https://github.com/kimroen/ember-cli-document-title",
    "keywords": [
        "ember-addon"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "kimroen",
            "email": "kim@kimroen.com"
        }
    ],
    "name": "ember-cli-document-title",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/kimroen/ember-cli-document-title.git"
    },
    "scripts": {
        "build": "ember build",
        "start": "ember server",
        "test": "ember try:each"
    },
    "version": "0.3.3"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module ember-cli-document-title](#apidoc.module.ember-cli-document-title)
1.  [function <span class="apidocSignatureSpan">ember-cli-document-title.</span>included (app)](#apidoc.element.ember-cli-document-title.included)
1.  string <span class="apidocSignatureSpan">ember-cli-document-title.</span>name



# <a name="apidoc.module.ember-cli-document-title"></a>[module ember-cli-document-title](#apidoc.module.ember-cli-document-title)

#### <a name="apidoc.element.ember-cli-document-title.included"></a>[function <span class="apidocSignatureSpan">ember-cli-document-title.</span>included (app)](#apidoc.element.ember-cli-document-title.included)
- description and source-code
```javascript
included = function (app) {
  // see: https://github.com/ember-cli/ember-cli/issues/3718
  if (typeof app.import !== 'function' && app.app) {
    app = app.app;
  }

  app.import('vendor/document-title/document-title.js');
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
