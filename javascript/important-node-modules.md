### HTTP Request

* axios

### Web Framework

* express

### Validation

* Joi

### Authentication

* Passport

### Async Helper Methods

* async

### Websockets

* Primus

### Utilities/misc:

* moment.js
  * use to parse, validate, manipulate, compare and display dates/time
* uuid
  * make random uuid v1 and v4
* n
  * node version manager
* Nodemailer
  * use when you want to send mailes from node
* Dotenv
  * use when you need to load environment variables from a .env file into `process.env`
  
### CLI:

* Commander:
  * use when you want to build a CLI utility that takes all the arguments as flags on the command line
* Inquirer:
  * use when you want to build an “interactive” CLI utility that takes options sequentially (similar to how when you run npm init and it asks you a series of questions to generate the package.json file)
  
### Logging:

* Winston:
  * use when you need a logging library and need different log outputs
* Bunyan:
  * use when you need a logging library and can deal with JSON being the only log output you want to have different loggers for different components, request, or functions (i.e. – these loggers might parse things differently)
* Morgan:
  * use when you’re using Express and you want to log your HTTP requests
note: this would be used in conjunction with something like Winston or Bunyan. Since it’s middleware, it know how to handle the request and log it, but doesn’t handle the transportation to a log output that Winston and Bunyan do.

### Linter:

* ESlint:
 * use when you need a linter to automatically find (and fix) syntax and code pattern issues in your code
