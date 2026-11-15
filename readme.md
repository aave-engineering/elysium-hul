
## @phantom-app-engineering/openapi-wallet-service@0.1.0

This generator creates Go/TypeScript/JavaScript client that utilizes [axios](https://github.com/axios/axios). The generated Node module can be used in the following environments:

Environment
* Node.js
* Webpack
* Browserify

Language level
* ES5 - you must have a Promises/A+ library installed
* ES6

Module system
* CommonJS
* ES6 module system

It can be used in both TypeScript and JavaScript. In TypeScript, the definition will be automatically resolved via `package.json`. ([Reference](https://www.typescriptlang.org/docs/handbook/declaration-files/consumption.html))

### Building

To build and compile the typescript sources to javascript use:
```
npm install
npm run build
```

### Publishing

First build the package then run `npm publish`

### Consuming

navigate to the folder of your consuming project and run one of the following commands.

_published:_

```
npm install @phantom-app-engineering/openapi-wallet-service@0.1.0 --save
```

_unPublished (not recommended):_

```
npm install PATH_TO_GENERATED_PACKAGE --save
```

### Documentation for API Endpoints

All URIs are relative to *http://localhost:8000*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*DefaultApi* | [**simulateTransaction**](docs/DefaultApi.md#simulatetransaction) | **POST** /simulations | Simulate a transaction
*HealthApi* | [**healthHandler**](docs/HealthApi.md#healthhandler) | **GET** /healthz | 
*KMSRPCApi* | [**postKmsRpc**](docs/KMSRPCApi.md#postkmsrpc) | **POST** /kms/rpc | 

## Documentation For Authorization


Authentication schemes defined for the API:
<a id="x-phantom-stamp"></a>
### x-phantom-stamp

- **Type**: API key
- **API key parameter name**: X-Phantom-Stamp
- **Location**: HTTP header

