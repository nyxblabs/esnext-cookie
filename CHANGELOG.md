# Changelog


## v0.0.2


### 🚀 Enhancements

  - **index.ts:** Add cookie parsing and serialization functions This commit adds two functions to parse and serialize cookies. The parse function takes a string representing a `Cookie` header value and returns an object of all cookie name-value pairs. The serialize function takes a cookie name-value pair and returns a `Set-Cookie` header string. These functions are useful for handling cookies in HTTP requests and responses. ([ab02561](https://github.com/nyxblabs/esnext-cookie/commit/ab02561))

### 🩹 Fixes

  - **package.json:** Change build script command from 'unbuild' to 'buildkarium' The build script command was changed to 'buildkarium' to reflect the correct command to build the application. ([ca00a44](https://github.com/nyxblabs/esnext-cookie/commit/ca00a44))

### 🏡 Chore

  - **.eslintrc): add rules and settings to eslint configuration 🔨 chore(karium.config.ts): add trailing commas to entries and rollup options 🔨 chore(src/index.ts:** Fix import statement and add trailing commas to entries The changes made to the eslint configuration file include adding rules and settings to improve the linting process. The karium configuration file now has trailing commas added to the entries and rollup options. In the src/index.ts file, the import statement was fixed, and trailing commas were added to the entries. ([10f627a](https://github.com/nyxblabs/esnext-cookie/commit/10f627a))
  - **.eslintignore): add README.md to ignored files 🎉 feat(README.md:** Add README.md file with usage instructions and badges The .eslintignore file was updated to ignore the README.md file. A new README.md file was added to the project with usage instructions and badges for npm version, npm downloads, bundle size, and license. The badges provide useful information about the project and the license. The usage instructions provide a clear and concise way to install and import the package. ([1e7c8ee](https://github.com/nyxblabs/esnext-cookie/commit/1e7c8ee))

### ❤️  Contributors

- Nyxb <contact@nyxb.xyz>

