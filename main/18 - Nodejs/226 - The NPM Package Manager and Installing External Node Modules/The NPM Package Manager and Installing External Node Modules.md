# The NPM Package Manager and Installing External Node Modules

## The NPM Package Manager

NPM is a package manager for Node.js packages, or modules if you like. It's a command-line utility that allows you to install, update and remove Node.js packages.

www.npmjs.com hosts thousands of free packages to download and use.

The NPM program is installed on your computer when you install Node.js

## How to Install External Node Modules

```bash

npm install lodash

```

## How to Use External Node Modules

```javascript

const _ = require('lodash');

const items = [1, [2, [3, [4]]]]

const newItems = _.flattenDeep(items);

console.log(newItems);

```

## How to Uninstall External Node Modules

```bash

npm uninstall lodash

```

## How to Update External Node Modules

```bash

npm update lodash

```

## How to Install Global External Node Modules

```bash

npm install -g nodemon

```

## How to Use Global External Node Modules

```bash

nodemon app.js

```

## How to Uninstall Global External Node Modules

```bash

npm uninstall -g nodemon

```

## How to Update Global External Node Modules

```bash

npm update -g nodemon

```


## How to Use the Node REPL

The Node REPL is a JavaScript REPL that runs in the terminal.

REPL stands for Read, Evaluate, Print, Loop.

The Node REPL is very useful for experimenting with Node.js code and testing JavaScript syntax.


## now we will init the npm project

```bash

npm init

```

