good-logger
===========

[![NPM](https://nodei.co/npm/good-logger.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/good-logger/)

This logger ain't like any logger. It's a good logger. `console.log` is bad. `good-logger` is good. Stop using a bad logger. Stop using `console.log`. Please use a good logger. Please use `good-logger`.

- `process.env.LOGGING = false` disables logging.

![Example](https://i.imgur.com/CQ0qaur.png)

```JavaScript
const logger = require('good-logger');

logger.info('Use this when you want to log non-sense');
logger.warn('Use this when something wrong goes but you just don\'t want to call it an error');
logger.err('Use this when you make a grave mistake in your code');
logger.recv('Use this with things like webservers (receiving a request) or a bot (receiving a message)');
logger.sql('Use this if you use some SQL and you want to log it nicely');
```

