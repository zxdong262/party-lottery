# party-lottery

Choose lucky ones to receive gifts during party.


## Development setup

```
yarn install
cp src/config.sample.js src/config.js
edit src/config.js
yarn start
```


## Release to production

```
yarn release
```

Static files are generated in [docs](./docs) folder.
You may deploy these static files to any server.
This app is pure client side, deploy it just like deploying any other static websites.


## Todo

- Preload memebers avatar image
- Disallow clicking button too quickly
