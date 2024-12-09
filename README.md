# js-utilities

## Setup
We can setup a project for `JavaScript` or `React` by using `Vite`:

```shell
$ npm create vite@latest
```

## Publish the package
The package can be published to `npm (Node Package Manager)`. Firstly, login to `npm`:

```shell
$ npm login
```

If `2FA (Two-Factor Authentication)` is not setup, you may need to use the one-time code via sms text message or sent to the email inbox.

To publish the package and push the code changes to `npm`:

```shell
$ npm publish --access public
```

## Install the Package
The package can be installed as a `dependency`:

```shell
$ npm install @hackdanismo/js-utilities
```

The package is currently hosted on `npm` here: `https://www.npmjs.com/package/@hackdanismo/js-utilities`

## Using the Package
All functions contained in the library are exported using the `src/index.js` file. This will export individual files that contain the functions.

```javascript
// Export all functions within the bar.js inside the foo directory
export * from "./foo/bar";
```

Once installed we can start to use the package. Begin by importing the function to be used using the `import` keyword in the JavaScript file or React component.

In this example, we are importing the `foo()` method:

```javascript
import { foo } from "@hackdanismo/js-utilities";
```

In this example, we are importing the `foo()` and `bar()` methods:

```javascript
import { foo, bar } from "@hackdanismo/js-utilities";
```

We can the use the function, or functions, we require in our code:

```javascript
foo();
```