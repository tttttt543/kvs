# kvs 

Key Value storage for Browser(IndexedDB), Node.js, In-Memory.

It is a monorepo for kvs.

## Packages

- Browser
    - [@kvs/indexeddb](./packages/indexeddb): Use IndexedDB
        - For WebWorker and ServiceWorker
    - [@kvs/localstorage](./packages/localstorage): Use LocalStorage
        - For Browser
- Node.js
    - [@kvs/node-localstorage](./packages/node-localstorage): Use [node-localstorage](https://github.com/lmaccherone/node-localstorage)
        - For Node.js
- In-Memory
    - [@kvs/memorystorage](./packages/memorystorage): In-Memory Storage
        - For debug

If you want to custom implementation, please test with [@kvs/common-test-case](./packages/common-test-case).

## Changelog

See [Releases page](https://github.com/azu/kv/releases).


## Development

    yarn install
    yarn run build

## Running tests

    yarn test

## Contributing

Pull requests and stars are always welcome.

For bugs and feature requests, [please create an issue](https://github.com/azu/kv/issues).

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Author

- [github/azu](https://github.com/azu)
- [twitter/azu_re](https://twitter.com/azu_re)

## License

MIT © azu
