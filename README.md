# Package-Skeleton
> An empty repo for starting your js package

## Usage
Just clone the repo and start hacking in it
```
$ git clone --depth 1 -b master https://github.com/nuclei/package-skeleton.git yourRepo
$ git remote set-url origin https://github.com/yourName/yourRepo.git
$ cd yourRepo && npm i
```

### Tests
By default `npm test` assures you stick to the `standardjs` rules, catches typescript errors and validates your readme using `standard-readme`.

```
$ npm test
```

### Build
Run `npm run build` to convert your source file defined in the `package.json` as `package.config.src` into a compiled js file defined by `package.main`.

```
$ npm run build
$ npm run build:watch
```
