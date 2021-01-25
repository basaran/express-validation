express-validation
==================

`express-validation` is an express middleware that validates a request and returns a response with errors; if any of the configured validation rules fail. This fork supports "session" as a validation target for your schemas and based on express-validation v3.0.6.

Currently support Joi v17.x.x

## Parameter types
We support validating the following parameter types:

- headers
- params (path)
- query
- cookies
- signedCookies
- body
- session

## Install

Install with npm:

```sh
npm i express-validation-session --save
```

Install with yarn:

```sh
yarn add express-validation-session
```

## Example

Please visit the main repository for examples and up-to-date documentation.

https://github.com/AndrewKeig/express-validation

## License

This work is licensed under the MIT License (see the LICENSE file).

https://github.com/AndrewKeig/express-validation/blob/master/LICENSE
