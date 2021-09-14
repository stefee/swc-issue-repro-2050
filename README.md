Steps to re-build the repo:

1. `npm install`
2. `npm run build:repro-1`
3. `npm run build:repro-2`

Each folder (repro-1 and repro-2) has 3 directories:

* `server` is the source code
* `dist/server` is the actual output code from running swc
* `expected/server` is what we expect `dist/server` to contain after running swc
