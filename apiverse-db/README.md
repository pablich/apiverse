# apiverse-db

## Usage

``` js
const setupDatabase = require('apiverse-db');

setupDatabase(config).then(db => {
    const { Agent, Metric } = db
}).catch(err => console.error(err))
```
