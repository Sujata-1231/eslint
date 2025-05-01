1. What is ESLINT?

2. Benefits of ESLINT

- Error Detection at runtime.
- Code consistency.
- Code indentation consistency. (Like how )
- Steps:

- Create index.js file to write the code.
- install 'npm install --save-dev eslint' why saving as dev dependency? because we want to use it in development only we don't want
  this in production that's why saved as dev dependencies.

- then add this inside package.json file.
- then run this command to see the issues -> npm run lint

```js
 "scripts": {
    "lint": "eslint"
  },
```

1. ./node_modules/.bin/eslint --init
2. You can also run this command directly using 'npm init @eslint/config@latest'
