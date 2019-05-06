# Learn JSDoc

An API document generator for Javascript.

[GitHub Link.](https://github.com/jsdoc/jsdoc)

# Environment Setup

> JSDoc requires NodeJS 8.15.0 and later, make sure you have a proper NodeJS installed.

```
npm init -y && npm i jsdoc
```

# Generate Document

The simplest way to generate documents is to run `jsdoc` command with Javascript files as arguments.
Here is an example:

```
npx jsdoc main.js book.js
```

This command will by default generate document files in `out` folder under current directory.
The `index.html` is the entry point of the generated documents, open it in your browser to
go through all the documents.

