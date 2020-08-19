# Experiment with mob.sh

![Build Status Badge](https://github.com/wonderbird/experiment-with-mob-sh/workflows/Node.js%20CI/badge.svg)

Some experiments with the https://www.remotemobprogramming.org / https://mob.sh experience.
More infos: https://www.remotemobprogramming.org/#resources .

## Note

You can use this repo as a template for new Node.js projects. Simply fork it :-)
If you have forked it already, see https://deanmalone.net/post/how-to-fork-your-own-repo-on-github/ .

## Development

To build the project

```sh
npm install
npm run test
npm run lint
```

To continuously monitor the tests while developing

```sh
npm run test:watch
```

Before pushing to github, please run all tests and the linter

```sh
npm run test
npm run lint
```

## References

* https://www.remotemobprogramming.org
* https://mob.sh
* http://espeak.sourceforge.net, https://formulae.brew.sh/formula/espeak (not required on Apple macOs - you have a "say" command there)
