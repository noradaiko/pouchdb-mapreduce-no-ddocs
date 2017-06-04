DEPRECATION NOTICE
-----

The best way forward is a custom build of PouchDB while removing [pouchdb-changes-filter](https://www.npmjs.com/package/pouchdb-changes-filter) and [pouchdb-mapreduce](https://www.npmjs.com/package/pouchdb-mapreduce) which are the only packages that contain the `eval()` code. This is not technically possible with PouchDB v6 but could be made possible in the future.

pouchdb-mapreduce-utils ![semver non-compliant](https://img.shields.io/badge/semver-non--compliant-red.svg)
======

PouchDB utilities used by pouchdb-mapreduce.

### Usage

```bash
npm install --save-exact pouchdb-mapreduce-utils
```

For full API documentation and guides on PouchDB, see [PouchDB.com](http://pouchdb.com/). For details on PouchDB sub-packages, see the [Custom Builds documentation](http://pouchdb.com/custom.html).

### Warning: semver-free zone!

This package is conceptually an internal API used by PouchDB or its plugins. It does not follow semantic versioning (semver), and rather its version is pegged to PouchDB's. Use exact versions when installing, e.g. with `--save-exact`.

### Source

PouchDB and its sub-packages are distributed as a [monorepo](https://github.com/babel/babel/blob/master/doc/design/monorepo.md).

For a full list of packages, see [the GitHub source](https://github.com/pouchdb/pouchdb/tree/master/packages).


