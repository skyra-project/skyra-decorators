# Contributing

**The issue tracker is only for issue reporting or proposals/suggestions. If you have a question, you can find us in our [Discord Server](https://join.skyra.pw)**.

To contribute to this repository, feel free to create a new fork of the repository and
submit a pull request. We highly suggest [ESLint](https://eslint.org/) to be installed
in your text editor or IDE of your choice to ensure builds from GitHub Actions do not fail.

1. Fork, clone, and select the **master** branch.
2. Create a new branch in your fork.
3. Make your changes.
4. Commit your changes, and push them.
5. Submit a Pull Request [here](https://github.com/skyra-project/skyra-decorators/pulls)!

## Skyra-Decorators Concept Guidelines

There are a number of guidelines considered when reviewing Pull Requests to be merged. _This is by no means an exhaustive list, but here are some things to consider before/while submitting your ideas._

- Skyra-Decorators should never change klasa's or discordjs's default behavior. Skyra-Decorators should only add to Klasa and discord.js, and be as consistent as possible with them.
- Everything in Skyra-Decorators should be generally useful for the majority of users. Don't let that stop you if you've got a good concept though, as your idea still might be a great addition.
- Everything should follow our ESLint rules as closely as possible, and should pass lint tests even if you must disable a rule for a single line.