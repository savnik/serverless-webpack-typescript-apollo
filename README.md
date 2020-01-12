Steps to reproduce:

1. Install by
   `yarn`

2. Run locally
   `yarn local`

3. Trigger api on GET request to:
   `http://localhost:4000/hello`

4. Error displayed is:

```
Serverless: Error while loading hello
Error: Serverless-offline: handler for 'hello' is not a function
    at Object.createHandler (/home/savnik/serverless-webpack-typescript-apollo/node_modules/serverless-offline/src/functionHelper.js:221:11)
    at handler (/home/savnik/serverless-webpack-typescript-apollo/node_modules/serverless-offline/src/ApiGateway.js:485:40)
    at module.exports.internals.Manager.execute (/home/savnik/serverless-webpack-typescript-apollo/node_modules/@hapi/hapi/lib/toolkit.js:41:33)
    at Object.internals.handler (/home/savnik/serverless-webpack-typescript-apollo/node_modules/@hapi/hapi/lib/handler.js:46:48)
    at exports.execute (/home/savnik/serverless-webpack-typescript-apollo/node_modules/@hapi/hapi/lib/handler.js:31:36)
    at Request._lifecycle (/home/savnik/serverless-webpack-typescript-apollo/node_modules/@hapi/hapi/lib/request.js:312:68)
    at processTicksAndRejections (internal/process/task_queues.js:93:5)
    at Request._execute (/home/savnik/serverless-webpack-typescript-apollo/node_modules/@hapi/hapi/lib/request.js:221:9)
```
