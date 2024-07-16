# Country Code Splitter

`country-code-splitter` module is used to split phone numbers by country code.

### Installation

```
npm install country-code-splitter --save
```


Ex : 

```
let country_splitter = require('country-code-splitter');
console.log(country_splitter.getNumber("+160987654329"));
```

O/P : 

```
{ code: '+1', number: '60987654329' }
```

		