# MediaMonks - Frontend Coding Standards

## Eslint Configuration

To make sure your project is following the MediaMonks Frontend Coding Standards you should install `@mediamonks/eslint-config` and its peer dependencies as an [eslint extension](https://eslint.org/docs/user-guide/configuring#extending-configuration-files):

```
npx install-peerdeps --dev @mediamonks/eslint-config
```

And set `@mediamonks` as `extends` in your `.eslintrc.js` file:

```
module.exports = {
    "extends": "@mediamonks"
}
```

This Eslint extension is configured for JavaScript, [TypeScript](http://typescriptlang.org/), [React](https://reactjs.org/), [Vue](https://vuejs.org/) and [Muban](https://mediamonks.github.io/muban/) projects.
