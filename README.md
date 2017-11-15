## Yarn task runner for Atom

Uses `atom-build` to run Yarn tasks from within the Atom editor. This
package requires `atom-build` to be installed. Largely copied from
`atom-build-npm-apm`.

This package fixes the bug that yarn install always runs in production mode. This is due to the fact that `atom-build` copies env variables and this will result that process.env.NODE_ENV always equals production.
