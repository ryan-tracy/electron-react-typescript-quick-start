# electron-react-typescript-quick-start

> A bare minimum project structure to get started developing and building an Electron project with React and Typescript.

This boilerplate or template comes packed with...

- Use of [`electron-webpack`](https://github.com/webpack/webpack-dev-server) to serve the development environment and packageing
- Use of [`react`](https://reactjs.org/) for the development library.
- Use of [`typescript`](https://www.typescriptlang.org/) for strong typing to catch issues during development instead of at compile
- Use of [`electron-builder`](https://github.com/electron-userland/electron-builder) to build a distributable electron application

Make sure to check out documentation for more details.

- [`electron-webpack`'s documentation](https://webpack.electron.build/).
- [`electron-builder`'s documentation](https://www.electron.build/)
- [`electron`'s documentation](https://www.electronjs.org)
- [`react`s documentation](https://reactjs.org/)
- [`webpack`'s documentation](https://webpack.js.org/)
- [`typescript`'s documentation](https://www.typescriptlang.org/)

## Getting Started

Simply clone down this repository, install dependencies, and get started on your application.

The use of the [yarn](https://yarnpkg.com/) package manager is **strongly** recommended, as opposed to using `npm`.

```bash
# create a directory of your choice, and copy template using curl
mkdir new-electron-react-project && cd new-electron-react-project
curl -fsSL https://github.com/ryan-tracy/electron-react-typescript-quick-start/archive/master.tar.gz | tar -xz --strip-components 1

# or copy template using git clone
git clone https://github.com/ryan-tracy/electron-react-typescript-quick-start.git
cd electron-react-typescript-quick-start
rm -rf .git

# install dependencies
yarn
```

### Development Scripts

```bash
# run application in development mode with electron-webpack
yarn start

# transpile source code and build with electron-builder
yarn build
```
