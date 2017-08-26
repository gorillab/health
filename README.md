# health
the simplest health check middleware for express app

## install
```javascript
npm install gorillab-health --save

# or

yarn add gorillab-health
```

## usage
```javascript
import Express from 'express';
import Health from 'gorillab-health';

const app = Express();

app.use(Health());

app.listen(9000);
```

The endpoint is exposed as `http://localhost:9000/health`. Done!!!
