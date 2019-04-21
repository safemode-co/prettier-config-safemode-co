# prettier-config-safemode-co

This is a general config for prettier. It includes prettier as a dependency, to make sure that all projects use the same prettier version.

## Install

- `npm remove prettier`
- `rm .prettierrc`
- `npm i -D prettier-config-safemode-co`
- `echo 'module.exports = require("prettier-config-safemode-co");' > .prettierrc.js`