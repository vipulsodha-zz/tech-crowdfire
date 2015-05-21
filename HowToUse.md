## The following are the steps how to use Eslint.

1. Include the .eslintrx file in your root folder.

2. Download the Esling npm using 'npm install eslint'

3. Add the following in your package.json
  '"scripts": {
    "test": "npm run lint &&  node_modules/.bin/mocha -u bdd ",
    "lint": "node node_modules/.bin/eslint ./*.js test/ && echo Lint Passed."
  }'

3. Run:
  'npm test'