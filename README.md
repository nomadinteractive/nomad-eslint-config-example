## Nomad Eslint Example

This is an example app repository for showcasing how nomad-codecheck is used. For nomad-codecheck, visit it's repository: https://github.com/nomadinteractive/nomad-codecheck

To install

```npm install```

To Run

```npm run check```

## Developing a new rule in nomad-codecheck working copy and using this example with local copy as package dependency:

To test local nomad-codecheck working copy as dependency, update package.json with the file location like:

```"nomad-codecheck": "file:../nomad-codecheck"```

then `npm install` (Unfortunately an npm install is needed every time changing codecheck repository).

## License

[MIT](LICENSE.md)
