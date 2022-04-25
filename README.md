# csproj-version

Node.js-based tool to modify the version in a C# project file (`.csproj`).

Main use case is CI automation.

## Installation

csproj-version is not on NPM, but you can install it from GitHub:

### Using npm with git

```bash
npm install -g git://github.com/kagekirin/csproj-version.git
npm install -g git+ssh://git@github.com:kagekirin/csproj-version.git
npm install -g git+https://git@github.com/kagekirin/csproj-version.git
npm install -g git+ssh://git@github.com:kagekirin/csproj-version.git[#<commit-ish>]
npm install -g git+ssh://git@github.com:kagekirin/csproj-version.git[#semver:^x.x]
npm install -g github:kagekirin/csproj-version[#<commit-ish>]
```

### Using npm with the tarball

```bash
npm install -g https://github.com/kagekirin/csproj-version/tarball/main
```
