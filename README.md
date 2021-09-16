# @robcthegeek's Dojo Starter Kit / TypeScript and Jest

## Environment Setup

> With thanks to the awesome [TypeScript Deep Dive](https://basarat.gitbook.io/typescript/) from [Basarat Ali Syed (`@basarat`)](https://github.com/basarat).

1. Install [Git](https://git-scm.com/downloads)
1. Install [Node](https://nodejs.org/en/download/)
2. Restart your shell _(sometimes needed to ensure your PATH is correct)_.
3. Check all good via Node version: `node --version`
4. Clone the repository: `git clone https://github.com/robcthegeek/dojo-starter-node-typescript`
5. Browse to the folder: '`dojo-starter-node-typescript`'
6. Install the NPM packages: `npm i`
7. Run the tests! `npm t`

If all is well, you should see something like:

```
> jest

 PASS  test/solution.test.ts
  √ Tests are wired up correctly (1 ms)

Test Suites: 1 passed, 1 total
Tests:       1 passed, 1 total
Snapshots:   0 total
Time:        1.473 s, estimated 2 s
Ran all test suite
```

### Continuous Test Running

* I ✨**highly**✨ recommend [Wallaby](https://wallabyjs.com/) with [VS Code](https://code.visualstudio.com/) 😍
* If you want something free, just simply run Jest in 'watch' mode via `npm run tw`
