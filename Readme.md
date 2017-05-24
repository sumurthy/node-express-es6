# Example of a basic node ExpressJs server with ES6 support

`npm init -y`

`npm install --save-dev babel-cli babel-preset-env`

`npm install express`

New `.babelrc` file with following contents

```json
{
  "presets": ["env"]
}
```

Add to `package.json`

```json
 "scripts": {
    "dev": "babel-node app.js"
  },
```

Start node app from comman line

`npm run dev`
`> node@1.0.0 dev C:\Users\suramam\git\node`
`> babel-node app.js`

Example app listening on port 3000!

That's it...

