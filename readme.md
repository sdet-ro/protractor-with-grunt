How to get started:
```
npm install -g protractor
npm install -g grunt
npm install
```

to run the tests, open up a terminal and run the following command:

```
grunt e2e

```

.jshintrc config file added to the project.

{
  "jasmine": true,
  "mocha": true,
  "esversion":6,
  "loopfunc": true,
  "globals": {
    "esversion": 6,
    "angular": false,
    "browser": false,
    "inject": false,
    "_": false,
    "driver": false,
    "protractor": false,
    "$": false,
    "$$": false,
    "element": false,
    "by": false,
    "list": false
  }
}
```
