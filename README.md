# SENA-DATE

Una utilidad para manejar dechas en  un formato timestamp y long time

## INSTALL

```bash
npm install sena-date
```

## Uso 

```js

const { getTimeStamp, getLongTime } = require('sena-date')

getTimeStamp(); //179242800000
getLongTime('en-ES'); // 'Monday, october 19, 2026 ...'
```