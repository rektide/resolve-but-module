# resolve-but-module

**do not use**

> fork of browserify/node-resolve that prefers modules

implements the [node `require.resolve()`
algorithm](https://nodejs.org/api/modules.html#modules_all_together)
such that you can `require.resolve()` on behalf of a file asynchronously and
synchronously. This fork prefers `module` to `main` in `package.json`.

# Do Not Use

Just use `resolve`. Add a packageFilter that does what this library hardcoded. See [example](https://github.com/rektide/esm-bare-to-browser/blob/1c74735a9e4de1e48ece459d89c0465dd8e9b9f5/resolve.js#L33-L38).
