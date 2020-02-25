# react-from-scratch
A reference project to compare against your typical create-react-app starter

## Getting Started

User Manager provides a user interface which remotely accesses the identity service API.

### Prerequisites

* [node](https://nodejs.org/)
* [yarn](https://yarnpkg.com/)

### Installing

1. Clone the repository
```
git clone git@github.com:KevinThomson/react-from-scratch.git && cd react-from-scratch
```

2. Run `yarn` to install dependencies

3. (Optional) Update `.git/hooks/prepare-commit-msg` with the following to and make it executable `chmod +x .git/hooks/prepare-commit-msg` to enable commitizen on `git commit`
```
#!/bin/bash
exec < /dev/tty && node_modules/.bin/git-cz --hook || true
```