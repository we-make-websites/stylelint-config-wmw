# stylelint-config-wmw

We Make Website's stylelint rules and config

## Installation

Install [stylelint](https://stylelint.io/) and `stylelint-config-wmw`:

**With Yarn**
```
yarn add --dev stylelint stylelint-config-wmw
```

**With npm**
```
npm install stylelint stylelint-config-wmw --save-dev
```


## Usage
We Make Website’s stylelint rules come bundled in `stylelint-config-wmw`. To enable these rules, add a `stylelint` property in your `package.json`. See the [stylelint configuration docs](https://stylelint.io/user-guide/configuration/) for more details.
```
"stylelint": {
  "extends": ["stylelint-config-wmw"]
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
