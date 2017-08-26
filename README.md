# health
the simplest health check middleware for express app

## usage
```javascript
import Express from 'express';
import Health from 'health';

const app = Express();

app.use(Health());

app.listen(9000);
```

The endpoint is exposed as `http://localhost:9000/health`. Done!!!
