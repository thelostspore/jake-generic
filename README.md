[![devDependencies Status](https://david-dm.org/thelostspore/jake-generic/dev-status.svg)](https://david-dm.org/thelostspore/jake-generic?type=dev)

# jake-generic
A general-purpose Jakefile with sample app. WIP, unreleased. 

## Usage
This project has not officially been released. To use the `jake-generic` utils via `npm`, point to this repository (example below). You can reference any [commit-ish](https://docs.npmjs.com/files/package.json#git-urls-as-dependencies) - if none specified, defaults to `master`.

```javascript
// abbreviated package.json
dependencies: {
  "jake-generic": "git://github.com/thelostspore/jake-generic.git"
}
```

## Development

### Requirements
- `node` v6.x
- Depdencies management: `npm`
- Syntax: `jshint`
- Tests: `mocha` with `chai`

### Instructions
```bash 
git clone git://github.com/thelostspore/jake-generic.git
cd jake-generic
npm install
jake
```

### Testing
[`mocha`][mocha] is used with [`chai`][chai] assertions. To run tests, simply:
```
jake test
```

[mocha]: https://mochajs.org/
[chai]: http://chaijs.com/api/assert/ 