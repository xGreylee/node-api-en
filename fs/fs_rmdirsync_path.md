<!-- YAML
added: v0.1.21
changes:
  - version: v7.6.0
    pr-url: https://github.com/nodejs/node/pull/10739
    description: The `path` parameters can be a WHATWG `URL` object using
                 `file:` protocol. Support is currently still *experimental*.
-->

* `path` {string|Buffer|URL}

Synchronous rmdir(2). Returns `undefined`.

*Note*: Using `fs.rmdirSync()` on a file (not a directory) results in an `ENOENT`
error on Windows and an `ENOTDIR` error on POSIX.

