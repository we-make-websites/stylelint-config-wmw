# stylelint-config

We Make Website's stylelint rules and config

## Installation

Install [stylelint](https://stylelint.io/) and `@we-make-websites/stylelint-config`:

**With Yarn**
```
yarn add --dev stylelint @we-make-websites/stylelint-config
```

**With npm**
```
npm install stylelint @we-make-websites/stylelint-config --save-dev
```


## Usage
We Make Website’s stylelint rules come bundled in `@we-make-websites/stylelint-config`. To enable these rules, add a `stylelint` property in your `package.json`. See the [stylelint configuration docs](https://stylelint.io/user-guide/configuration/) for more details.
```
"stylelint": {
  "extends": ["@we-make-websites/stylelint-config"]
}
```

Now you can run stylelint by adding the following linting script to your `package.json`. See the [stylelint CLI docs](https://stylelint.io/user-guide/cli/) for more details.
```
"scripts": {
  "stylelint": "stylelint 'src/**/*.scss'"
}
```
Run it:

**With Yarn**
```
yarn run stylelint
```

**With npm**
```
npm run stylelint
```
