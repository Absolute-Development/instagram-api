

## Install

```
$ npm install instagram-user
```


## Usage

```js
const instagramUser = require('instagram-api-wrapper');

(async () => {
	console.log(await instagramUser('unicorns'));
	//=> {description: 'A wonderful description', email: 'unicorns@foo.com', ...}
})();
```


## API

### instagramUser(username)

Returns a `Promise<Object>` with the user information.

#### username

Type: `string`

Instagram username.
