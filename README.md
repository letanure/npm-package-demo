# npm-package-demo

A demo package built with TypeScript.

## Installation

```bash
npm install npm-package-demo
```

or

```bash
yarn add npm-package-demo
```

## Scripts

- `build`: Compile TypeScript files
- `ci`: Run build, linting, and tests
- `lint:all`: Run all linting scripts
- `lint:exports`: Check exports using @arethetypeswrong/cli
- `lint:format:fix`: Format code using Biome
- `lint:format`: Check code formatting using Biome
- `lint:ts`: Type-check TypeScript files
- `prepublishOnly`: Run CI checks before publishing
- `release:local`: Version and publish changes locally
- `test:all`: Run all tests
- `test:run`: Run tests using Vitest
- `test:watch`: Run tests in watch mode

## Development

1. Clone the repository:
   ```bash
   git clone https://github.com/letanure/npm-package-demo.git
   ```
2. Install dependencies:
   ```bash
   pnpm install
   ```
3. Make your changes
4. Run tests:
   ```bash
   pnpm test:all
   ```
5. Build the package:
   ```bash
   pnpm build
   ```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.

## Acknowledgements

Thanks to Matt Pocock ([@mattpocockuk](https://twitter.com/mattpocockuk)) for his article on [How to Create an NPM Package](https://www.totaltypescript.com/how-to-create-an-npm-package#6-using-tsup-to-dual-publish)