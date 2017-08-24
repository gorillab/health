# health
the simplest health check middleware for express app

## usage
```javascript
import Express from 'express';
import health from 'health';

const app = Express();

app.use(health);
app.listen(9000);
```

The endpoint is exposed as `http://localhost:9000/health`. Done!!!
