# OBSOLETE: INSTEAD, USE https://github.com/denis-sokolov/supergenpass-bin


# API usage

```js
var sgp = require('sgp');

var generated_password = sgp(password, domain, [length]);
```

# CLI usage

```
$ npm install sgp -g
$ sgp | pbcopy
domain: github.com
password:
$
```
