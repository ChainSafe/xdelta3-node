# Contribution Guidelines

Thanks for your interest in contributing to XDelta3. It's people like you that push the open source ecosystem forward.

## Prerequisites

- :gear: [NodeJS](https://nodejs.org/) (LTS)
- :toolbox: [Npm](https://docs.npmjs.com/)
- 🚤: [Zig](https://ziglang.org/)

Make sure these dependencies are installed. For zig it's version should be greater or equal to `0.13.0`.

### MacOS Specifics

When using MacOS, there are a couple of extra prerequisites that are required.

- python
- coreutils (e.g. via `brew install coreutils`)

## Getting Started

- :gear: Run `git submodule init` to initialize submodule.
- :gear: Run `git submodule update` to fetch latest code for submodules.
- :gear: Run `npm i` to install dependencies.
- :gear: Run `npm run build:native` to build native dependencies.
- :gear: Run `npm run build:ts` to build js lib.

## Tests

To run tests:

- :test_tube: Run `yarn test:unit` for unit tests.

## First Time Contributor?

Unsure where to begin contributing to XDelta3-Node? Here are some ideas!

- :pencil2: See any typos? See any verbiage that should be changed or updated? Go for it! Github makes it easy to make contributions right from the browser.
- :mag_right: Look through our [outstanding unassigned issues](https://github.com/ChainSafe/xdelta3-node/issues?q=is%3Aopen+is%3Aissue+no%3Aassignee). (Hint: look for issues labeled `good first issue` or `help-wanted`!)
- :speech_balloon: Join our [Discord chat](https://discord.gg/aMxzVcr)!
  [![Discord](https://img.shields.io/discord/593655374469660673.svg?label=Discord&logo=discord)](https://discord.gg/aMxzVcr)

## Reporting A Bug?

- :spiral_notepad: [Create a new issue!](https://github.com/ChainSafe/xdelta3-node/issues/new/choose) Select the type of issue that best fits, and please fill out as much of the information as you can.

## Contribution Process

1. Make sure you're familiar with our contribution guidelines _(this document)_!
2. Create your [own fork](https://github.com/ChainSafe/xdelta3-node/fork) of this repository.
3. Make your changes in your local fork.
4. If you've made a code change, make sure to lint and test your changes (`yarn lint` and `yarn test:unit`).
5. Make an open pull request when you're ready for it to be reviewed. We review PRs on a regular basis. See Pull request etiquette for more information.
6. You may be asked to sign a Contributor License Agreement (CLA). We make it relatively painless with CLA-bot.

## Github Style Guide

**Branch Naming**

If you are contributing from this repository prefix the branch name with your Github username (i.e. `myusername/short-description`)

**Pull Request Naming**

Pull request titles must be:

- Adhering to the [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/#summary) spec
- Short and descriptive summary
- Written in imperative present tense
- Not end with a period

For example:

- feat: add lodestar prover for execution api
- fix: ignore known block in publish blinded block flow
- refactor(reqresp)!: support byte based handlers

**Pull Request Etiquette**

- Pull requests should remain as drafts when they are not ready for review by maintainers. Open pull requests signal to the maintainers that it's ready for review.
- If your pull request is no longer applicable or validated to fix an issue, close your pull request.
- If your pull request is fixable and needs additional changes or commits within a short period of time, switch your pull request into a draft until it's ready.
- Otherwise, close your pull request and [create a new issue instead.](https://github.com/ChainSafe/lodestar/issues/new/choose)

## Community

Come chat with us on [Discord](https://discord.gg/aMxzVcr) and join our public weekly planning meetings!
