<h1 align='center'>
  <a href='https://github.com/STPace/ts-lib-template'>
    <samp>@heliapan/ts-lib-template</samp>
  </a>
</h1>

<p align='center'>
  <a href='https://github.com/STPace/ts-lib-template/actions/workflows/release.yml'><image src='https://github.com/STPace/ts-lib-template/actions/workflows/release.yml/badge.svg?branch=main' alt='Release'/></a>
  <a href='https://npm.im/@heliapan/ts-lib-template'><image src='https://badgen.net/npm/v/@heliapan/ts-lib-template' alt='npm version'/></a>
  <a href='https://github.com/xojs/xo'><image src='https://img.shields.io/badge/code_style-XO-5ed9c7.svg' alt='XO code style'/></a>
  <a href='https://github.com/semantic-release/semantic-release'><image src='https://img.shields.io/badge/semantic-release-e10079.svg?logo=semantic-release' alt='semantic-release'/></a>
</p>

## Features

- Use [pnpm](https://pnpm.js.org/) as the package manager
- Use [xv](https://github.com/typicode/xv) as the test runner
- Code style lint by [xo](https://github.com/xojs/xo)
- Run Typescript with [esno](https://github.com/antfu/esno), and bundle with [tsup](https://github.com/egoist/tsup)
- Npm publish by [semantic-release](https://npm.im/semantic-release) with [github-action](https://docs.github.com/en/actions)

## Checklist

- [ ] Search `@heliapan/ts-lib-template` and replace it with your package name.
- [ ] Search `heliapan` and replace it with your npm name.
- [ ] Search `STPace` and replace it with your github name.
- [ ] Change the version in `package.json`.
- [ ] Generate [npm authentication token](https://docs.npmjs.com/creating-and-viewing-access-tokens) and copy it.
- [ ] Navigate to your GitHub repository page, click Settings and then Secrets. Click on New repository secret, fill in `NPM_TOKEN` as the Name, paste the npm token created on the previous step inside the Value field and hit Add secret.
- [ ] Clean up the `README.md`.

enjoy :)

## License

MIT &copy; [heliapan](https://github.com/heliapan)
