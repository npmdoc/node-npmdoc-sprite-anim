# npmdoc-sprite-anim

#### api documentation for  [sprite-anim (v0.2.0)](https://github.com/manuelodelain/sprite-anim#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-sprite-anim.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-sprite-anim) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-sprite-anim.svg)](https://travis-ci.org/npmdoc/node-npmdoc-sprite-anim)

#### Simple spritesheet animation engine

[![NPM](https://nodei.co/npm/sprite-anim.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sprite-anim)

- [https://npmdoc.github.io/node-npmdoc-sprite-anim/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sprite-anim/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sprite-anim/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sprite-anim/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-sprite-anim/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-sprite-anim/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Manuel Odelain"
    },
    "bugs": {
        "url": "https://github.com/manuelodelain/sprite-anim/issues"
    },
    "dependencies": {
        "inherits": "^2.0.1",
        "raf": "^3.0.0",
        "tiny-emitter": "^1.0.0"
    },
    "description": "Simple spritesheet animation engine",
    "devDependencies": {
        "browserify": "^10.2.3",
        "http-server": "^0.8.0",
        "uglifyjs": "^2.4.10",
        "watchify": "^3.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "80c13cb214a4e6bd9ae1de7427b22f7706d99a49",
        "tarball": "https://registry.npmjs.org/sprite-anim/-/sprite-anim-0.2.0.tgz"
    },
    "gitHead": "af400e114f35de00caa7bb0793e040df200f021d",
    "homepage": "https://github.com/manuelodelain/sprite-anim#readme",
    "keywords": [
        "spritesheet",
        "sprites",
        "animation",
        "animations",
        "sprite",
        "texture packer"
    ],
    "license": "MIT",
    "main": "src/SpriteAnim.js",
    "maintainers": [
        {
            "name": "manuelodelain"
        }
    ],
    "name": "sprite-anim",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/manuelodelain/sprite-anim.git"
    },
    "scripts": {
        "build": "npm run build-dev && npm run build-prod",
        "build-dev": "browserify src/SpriteAnim.js --s SpriteAnim -o dist/sprite-anim.js",
        "build-prod": "browserify src/SpriteAnim.js --s SpriteAnim | uglifyjs -o dist/sprite-anim.min.js",
        "start": "http-server",
        "test": "echo \"Error: no test specified\" && exit 1",
        "watch": "watchify src/SpriteAnim.js --s SpriteAnim -o dist/sprite-anim.js -dv"
    },
    "version": "0.2.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
