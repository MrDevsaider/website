# Config

Ream loads `ream.config.js` from your project root.

## entry

- __Type__: `string`
- __Default__: `index.js`

The entry file of your app.

## rootPublicFiles

Hoist files from `/public/` to root path `/`, for example, with `rootPublicFile: ['foo.txt']`, you will be able to use `/foo.txt` to access `/public/foo.txt`.

## server

### host

- __Type__: `string`
- __Default__: `process.env.HOST || '0.0.0.0'`

Server host.

### port

- __Type__: `number`
- __Default__: `process.env.PORT || 4000`

Server port.