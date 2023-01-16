# talks
Repository of talks

Creating a new Presentation:

*. Create a new branch, make a copy of `template`, and `cd` there

*. git submodule current version of reveal.js

```bash
$ git submodule add https://github.com/hakimel/reveal.js.git
$ cd reveal.js
$ git submodule update --init --recursive
```

*. copy package.json and gulpfile.js from the reveal.js folder to the talk directory
Update/install npm modules to make sure it works with this version:

```bash
$ npm install
```

*. Start the server:

```bash
$ npm start
```
