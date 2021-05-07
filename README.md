Boilerplate project already supports:

- TypeScript
- Webpack
  - importing assets, images, styles, etc...
- ReactJS
- A secure tunnel using [`localtunnel`](https://github.com/localtunnel/localtunnel)

## How to use:

- Run `yarn` or `npm install` to install dependencies
- Run `yarn start` or `npm start` to start developing, you should have a URL that looks like this

> you can change the subdomain inside [`webpack.config.js`](./webpack.config.js)

```
https://miro-plugin-boilerplate.loca.lt
```

> If the page shows 404 make sure to refresh again, this means that webpack didn't finish compilation yet.

- Paste the URL in `web-plugin url` in your app settings
- open a board & you should see your app in the main toolbar when you click the
  three dots.

## How to build the app:

Run `yarn run build` or `npm run build`
