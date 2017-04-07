# api documentation for  [python (v0.0.4)](https://github.com/73rhodes/node-python)  [![npm package](https://img.shields.io/npm/v/npmdoc-python.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-python) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-python.svg)](https://travis-ci.org/npmdoc/node-npmdoc-python)
#### Interact with a long-running python child process

[![NPM](https://nodei.co/npm/python.png?downloads=true)](https://www.npmjs.com/package/python)

[![apidoc](https://npmdoc.github.io/node-npmdoc-python/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-python_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-python/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-python/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-python/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Darren DeRidder"
    },
    "bugs": {
        "url": "https://github.com/73rhodes/node-python/issues"
    },
    "dependencies": {},
    "description": "Interact with a long-running python child process",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "3094e898ef17a33aa9c3e973b3848a38e47d1818",
        "tarball": "https://registry.npmjs.org/python/-/python-0.0.4.tgz"
    },
    "engines": {
        "node": ">= 0.4.1"
    },
    "gitHead": "69754aaa57658193916a1bf5fc391198098f74f6",
    "homepage": "https://github.com/73rhodes/node-python",
    "main": "./lib/python.js",
    "maintainers": [
        {
            "name": "drderidder",
            "email": "drderidder@gmail.com"
        }
    ],
    "name": "python",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/73rhodes/node-python.git"
    },
    "scripts": {},
    "version": "0.0.4"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module python](#apidoc.module.python)
1.  [function <span class="apidocSignatureSpan">python.</span>shell (command, callback)](#apidoc.element.python.shell)



# <a name="apidoc.module.python"></a>[module python](#apidoc.module.python)

#### <a name="apidoc.element.python.shell"></a>[function <span class="apidocSignatureSpan">python.</span>shell (command, callback)](#apidoc.element.python.shell)
- description and source-code
```javascript
shell = function (command, callback) {
  command = 'print "Command Start"; ' + command + '\nprint "Command End"';
  if (command.charAt[command.length-1]!='\n') command += '\n';
  cmdQueue.push({'command':command, 'callback':callback, 'data': '', state: 'pending'});
  processQueue();
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
