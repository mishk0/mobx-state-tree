---
id: installation
title: Installation
---

<div id="codefund"></div>

-   NPM: `npm install mobx mobx-state-tree --save`
-   Yarn: `yarn add mobx mobx-state-tree`
-   CDN: https://unpkg.com/mobx-state-tree/dist/mobx-state-tree.umd.js (exposed as `window.mobxStateTree`)
-   CodeSandbox [TodoList demo](https://codesandbox.io/s/y64pzxj01) fork for testing and bug reporting

Typescript typings are included in the packages. Use `module: "commonjs"` or `moduleResolution: "node"` to make sure they are picked up automatically in any consuming project.

Supported browsers:

-   MobX-state-tree runs on any ES5 environment
-   However, for MobX version 4 or 5 can be used. MobX 4 will run on any environment, MobX 5 only on modern browsers. See for more details the [MobX readme](https://github.com/mobxjs/mobx#browser-support)

Supported devtools:

- [Reactotron](https://github.com/infinitered/reactotron)
- [MobX DevTools](https://chrome.google.com/webstore/detail/mobx-developer-tools/pfgnfdagidkfgccljigdamigbcnndkod)
- The Redux can be connected as well as demonstrated [here](https://github.com/mobxjs/mobx-state-tree/blob/1906a394906d2e8f2cc1c778e1e3228307c1b112/packages/mst-example-redux-todomvc/src/index.js#L6)
