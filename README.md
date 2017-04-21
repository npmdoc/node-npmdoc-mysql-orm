# npmdoc-mysql-orm

#### api documentation for  [mysql-orm (v0.0.8)](https://github.com/battlesnake/node-mysql-orm)  [![npm package](https://img.shields.io/npm/v/npmdoc-mysql-orm.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-mysql-orm) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-mysql-orm.svg)](https://travis-ci.org/npmdoc/node-npmdoc-mysql-orm)

#### ORM frontend for MySQL, uses JSON schema to define tables and relationships.  This supports automatic table re-generation with indexes, default values, foreign keys, reference options, query logging and more.

[![NPM](https://nodei.co/npm/mysql-orm.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mysql-orm)

- [https://npmdoc.github.io/node-npmdoc-mysql-orm/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mysql-orm/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mysql-orm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mysql-orm/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-mysql-orm/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-mysql-orm/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "mysql-orm",
    "version": "0.0.8",
    "description": "ORM frontend for MySQL, uses JSON schema to define tables and relationships.  This supports automatic table re-generation with indexes, default values, foreign keys, reference options, query logging and more.",
    "main": "index.js",
    "scripts": {
        "test": "./run-tests.js testuser testpwd testdb31415926"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/battlesnake/node-mysql-orm"
    },
    "keywords": [
        "mysql",
        "orm",
        "object schema",
        "object relational mapping",
        "dry",
        "rest",
        "crud"
    ],
    "author": "Mark K Cowan <mark@battlesnake.co.uk>",
    "license": "GPL2",
    "bugs": {
        "url": "https://github.com/battlesnake/node-mysql-orm/issues"
    },
    "homepage": "https://github.com/battlesnake/node-mysql-orm",
    "contributors": [
        {
            "name": "Mark K Cowan"
        }
    ],
    "engines": {
        "node": "*"
    },
    "dependencies": {
        "mysql": "*",
        "underscore": "*",
        "async": "*",
        "cli-color": "*"
    },
    "devDependencies": {
        "read": "*"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
