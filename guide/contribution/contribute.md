# Contributing to Augury

*First things first, thank you for contributing. We know it takes a lot of time and effort. Everything in this document is meant to provide you with as much insight as possible with regards to our contribution standards. As you read it, it is important to remember that these are just __guidelines__ and not rules. Please use your best judgement when applying them.*

#### Table of Contents

1. __[I'm new. Anything I should know?](#im-new-anything-i-should-know)__
   * [The manual](#the-manual)
   * [Code of Conduct](#code-of-conduct)
2. __[How do I actually contribute?](#how-do-i-actually-contribute)__
   * [Developing](#developing)
   * [Coding Style](#coding-style)
   * [Pull Requests](#pull-requests)
   * [Bugs](#bugs)
4. __[Get In Touch](#how-to-get-in-touch)__
5. __[License](#license)__

## I'm new. Anything I should know?

Hello and welcome! Before diving into any code, there are a few things you should look over. To help, here are few resources below we thought you might find useful. We'll update these from time to time so make sure you regularly skim this section, even if you've been contributing for a while.

### The manual 

[README](https://github.com/rangle/augury/blob/dev/README.md)

The first thing you should do is _read_ the [README](https://github.com/rangle/augury/blob/dev/README.md). We've put a lot of love and care in writing it and it should provide you with the context you need for contributing to this project. Really, you should read it. 

### Code of Conduct

[Code of Conduct](https://github.com/rangle/augury/blob/dev/CODE_OF_CONDUCT.md)

In the interest of making the Augury project a safe and friendly place for people from diverse backgrounds, we'll be adhering to a [Contributor Code of Conduct](https://github.com/rangle/augury/blob/dev/CODE_OF_CONDUCT.md). As a contributor, you'll be expected to uphold this code as well as report unacceptable behaviour to [augury@rangle.io](mailto:augury@rangle.io).



## How Do I Actually Contribute?

*Remember: No contribution is too small and no issue is too trivial. If you see a typo, we'd love to get a PR. We actually hate typos...they're the worst.*

### Developing

[Developer wiki](https://github.com/rangle/augury/wiki)

To contribute to Augury you should have a good understanding of Angular and TypeScript. Each build of Augury is done with npm and then imported into Chrome as an extension. We have [a README just for developers](https://github.com/rangle/augury/wiki),  as well [a ARCHITECTURE guide](https://github.com/rangle/augury/wiki) with a detailed technical overview.  Jumping into a new codebase can be daunting, so the ARCHITECTURE guide is your best friend. 

### Coding Style

- Use semicolons;
- Commas last,
- 2 spaces for indentation (no tabs)
- Prefer `'` over `"`
- 80 character line length
- Try to use array operations (`map`, `reduce`, `find`, etc) instead of traditional `while` or `for` loops. 
- Use the ES6 arrow function syntax when defining your functions
- Try and use appropriate types for your data

More information on some of these coding styles can be found in `tslint.json` file of this repository.

TypeScript linter is part of our build task and will run in either `npm run build` or `npm start`

### Pull Requests

The core team will be monitoring for pull requests.

*Before* submitting a pull request, please make sure the following is done…

1. Fork the repo and create your branch from `master`.
   
2. If you've added code that should be tested, add tests.
   
3. If you've changed APIs, development workflow or aspects of the architecrure, update the corresponding documentation.
   
4. TypeScript linter is part of our build task, make sure your code lints before submitting your PRs.

### Bugs

We are using GitHub Issues for our public bugs. We will follow up with any issues and report on when we have a fix in progress. Before filing for a new task, try to make sure your problem doesn't already exist.

If you do find a new issue, the best way to get a bug fixed is to provide a test case with either one of the example apps bundled in the repo, or by making your own Angular 2.0 application illustrating the reduced use case. You can also include code snippets, though only if they illustrate the issue in a concise way. Don't forget to include the version of Angular 2.0 app you're using!

*At the moment, we offer limited backwards compatibility until Angular 2.0 stabilizes. Please check [README](https://github.com/rangle/augury/blob/dev/README.md#supported-version) for the version Augury currently supports.
   
   ​

## How to Get in Touch

### The chat room

[Slack](https://augury-slack.herokuapp.com/)

Okay, [manuals](https://github.com/rangle/augury/blob/dev/README.md) and [textbooks](https://github.com/rangle/augury/wiki) are great and all but they make for poor conversation. Feel free to [join us on Slack](https://augury-slack.herokuapp.com/)! Whether you're looking for answers to technical questions, suggestion of a new feature, or just want to share funny pictures, there's a channel for that. You can also ask us questions in private. We can't wait to hear from you.

## License

[MIT](https://github.com/rangle/augury/blob/dev/LICENSE)