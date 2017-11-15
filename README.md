# Yarn task runner for Atom

Uses [atom-build][] to run Yarn tasks from within the [Atom][] editor. This
package requires [atom-build][] to be installed. Largely copied from
[atom-build-npm-apm][].

This package fixes a bug when running yarn install always running with NODE_ENV=production.
This bug causes devDependencies not to be installed when running Yarn: install from within Atom 

[atom-build]: https://github.com/noseglid/atom-build
[Atom]: https://atom.io
[atom-build-npm-apm]: https://github.com/AtomBuild/atom-build-npm-apm
