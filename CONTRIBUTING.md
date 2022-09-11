# Contributing

All contributions are welcome as long as the issue for the contribution exists on the [issues](https://github.com/mbos2/astro-dev-starter/issues) board.  
Contribution code must follow code standards you can see in the projects code.

## Code of Conduct

Please read and follow the projects [Code of Conduct](/CODE_OF_CONDUCT.md).

## Get an issue assigned to you

If you want to work on a specific issue, you must always ask for the issue to be assigned to you.  
This way we reduce work collision between programmers.  
**Submitted PRs for issues that are not assigned to you will be rejected.**  
**If you do not report a progress on assigned issue within 7 days, and/or if you do not respond to messages about your progress from maintainers, issue will be unassigned from you without further notice.**

## How to start contributing

- Create a `fork` of this project.
- Clone the project locally by running this command: `git clone YOUR_PROJECT_FORK_URL.git`
- Checkout to the develop branch
- Run the command `git pull` to get the latest code
- Run the command `npm install` to install all necessary dependencies
- Create a new branch out of the `develop` branch
  - Branch naming convention: `dev/issue-ISSUE_NUMBER`
- Push the changes to your branch 
- Make a pull request against `develop` branch

**All PRs must include a commit message with the changes description!**  
**Always run `git pull` command from the `develop` branch before you create a new brach!**

It's always nice to have beginner-friendly issues labeled as a `good first issue` or `hacktoberfest`, but some more advanced topics might require extra knowledge.
## Technology Stack

To start contributing to this project, you should at least know: 
- Advanced HTML
- Advanced CSS & SASS
- Advanced JavaScript

Other technologies that this project involve: 
[Astro](https://astro.build/)
Node.js
TypeScript


## Coding Standards

### Naming conventions
- Use `snake-case` to name folders
- Use `snake-case` to name files that are **NOT** component files
- Use `PascalCase` to name component files and folders
- use `PascalCase` to name functions
- use `camelCase` to name object properties
- use `camelCase` to name code variables

### Formating

In this project we use Prettier code formater, and the configuration is included in the project.  
Please make sure to format the code according to the projects prettier configuration before making a PR.

### Code Readability, Reusability and Security

Readable code is easy to follow, and optimizes space and time.

- Write fewer lines if possible
- Use appropriate naming conventions to best describe what your code is about
- Do not include comments in the code if it is not absolutely necessary
- A single function should do a single task
- Try to avoid deep nesting
- Add error handling whenever you can
- Add user input validations whenever you can

## Dependencies

Please avoid introducing new dependencies to this project without consulting the maintainers first.

## Introducing New Features

New feature requests are always welcome.   
Every feature request will go through a discussion process with the maintainers of the project before making a final decision whether it will be included in the project or not. 
