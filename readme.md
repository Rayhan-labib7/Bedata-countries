
# bedata-countries

A ReactJs hook to get the country information

## How to use it?

You can use the project in this way : 


### Install
```bash
# with npm
npm install bedata-countries

# with yarn
yarn add bedata-countries

```

### Usage

- Import the package in your app:
```js
import {useCountry} from 'bedata-countries';
```
- Get the country information from the hook:
```js
const {loading, error, country} = useCountry('Bangladesh')
```