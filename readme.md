# Lodash TypeScript Demo

This repo is to [help with this](https://twitter.com/BenNadel/status/845245716314378245).

The steps to create this were:

```
yarn add lodash
yarn add -D typescript
yarn add -D @types/lodash
git init
yarn init -y
./node_modules/.bin/tsc --init
touch index.ts
```

After that the `tsconfig.json` was modified to set `moduleResolution` to `node`.

And the import to lodash was used in `index.ts`.

And NPM scripts were added to demonstrate it's working. So that you can just `npm install` / `yarn install` then:

```
npm start
```

And finally created a `.gitignore` file.