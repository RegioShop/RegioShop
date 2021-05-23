# RegioShop

[![lerna](https://img.shields.io/badge/maintained%20with-lerna-cc00ff.svg)](https://lerna.js.org/)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)

## Development

### Commit

To commit your changes please use the [https://github.com/commitizen/cz-cli#using-the-command-line-tool](commitzen cli).

> HINT: git >= 2.9.5 is necessary

#### Windows

Run `npm run cm``.

#### Commit Linux / MacOS

Run `npm run git:addPrepareMsgHook` to add the prepare message hook.
With this hook the commitzen cli is started automatically by running `git commit`.

### Quality tools

#### Commitlint (`commitlint.config.js`)

Checks if your commit messages meet the [conventional commit format](conventionalcommits.org/en/v1.0.0/).

#### Prettier (`.prettierrc.js`)

Formats the code to enforcing a style guide.

#### Markdownlint (`.markdownlint.json`)

Check markdown files against the defined rules.
