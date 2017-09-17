# health

[![Build Status](https://img.shields.io/travis/gorillab/health.svg)](https://travis-ci.org/gorillab/health)
[![Dependencies Status](https://img.shields.io/david/gorillab/health.svg)](https://github.com/gorillab/health)
[![NPM Version](https://img.shields.io/npm/v/@gorillab/health.svg)](https://www.npmjs.com/package/@gorillab/health)
[![NPM Downloads](https://img.shields.io/npm/dt/@gorillab/health.svg)](https://www.npmjs.com/package/@gorillab/health)

The simplest health check middleware for express app

## installation
```bash
yarn add @gorillab/health

# or

npm install @gorillab/health --save
```

## usage
```javascript
import Express from 'express';
import Health from '@gorillab/health';

const app = Express();

app.use(Health());

app.listen(9000);
```

The endpoint is exposed as `http://localhost:9000/health`. Done!!!
