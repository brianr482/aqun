# How we working?
We really glad you're join us, before to contribute take a look for the follow guidelines.

## Workflow and Git conventions
**We use [Git Workflow](http://slides.com/tebagomez/guilds-scrum-agile#/8/14).**

**Commit Format**

    [type]: subject

        body

    footer

* **Subject**:
No more than 50 characters. Brief description of what the commit does.
* **Body**:
The body is optional but if you need to explain something more elaborately, you must do it here.
* **Footer**:
  Reference the Github branch issue.

**Commit types**
* **feat**: New feature.
* **fix**: Bug fix.
* **docs**: Documentation changes.
* **style**: Formatting, missing semi colors, etc; no code changes.
* **refactor**: Refactoring production code.
* **test**: Adding tests, refactoring test, no production code changes.
* **chore**: Updating build tasks, package manager configs, etc... no production code changes.

More info [Git Syleguide de Udacity](http://udacity.github.io/git-styleguide/).

## Coding conventions
* [ESLint](https://eslint.org/) plugin may help you to contribute with a clean code respecting the standards.
* We use the [StandardJS](https://standardjs.com/) rules.
* We use space indentation with 2 spaces tabulation size.

## How to contribute
- [Bug report](#bug-report)
- [Submitting changes](#submitting-changes)

### Bug report
You have to create an issue in the preferable that contains the following data:
* **Problem description**
* **Steps to produce the problem**
* **Expected behavior**
* **Real behavior**
* **Extra information**

### Submitting changes
* Make a fork with your github accounts.
* Checkout in develop branch from your fork copy.
* Create a new branch from **develop**:
  * About **bug branch**: It should be named  *bug-x* where *x* is the issue number.
  * About **feature branch**: it should be named feature/*name* where *name* should describe shortly the feature.
* The commits should has the format mentioned above.
