Module: Automatized Tests and TDD

## PLUGINS

### ENZIME

NOTE: React Native don't have a DOM module then, we must to install "react-dom" for use with enzyme.

```bash 
yarn add enzyme enzyme-adapter-react-16 react-dom -D
```

* Open package.json and edit jest node to:

```javascript
"jest": {
    "preset": "react-native",
    "setupFiles": [
      "<rootDir>src/setupTests.js"
    ]
  }
```

STUDY_NOTE: An example of test can be found in "__tests__/App-test.js"