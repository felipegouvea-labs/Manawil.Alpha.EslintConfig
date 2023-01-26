# ESLint Config - Manawil Labs
Welcome to the Manawil ESlint Config! This repository contains custom configuration files for the ESLint that adhere to the coding standards and best practices used by Manawil.

## Installation
To use these configuration in your project, you will need to have eslint installed.
```bash
  npm i eslint
```
Or if you are using Yarn
```bash
  yarn add eslint
```

## Usage
Once the packages are installed, you can use the Manawil ESLint Config by extending it in your `eslintrc.json` file.
```bash
{
  "extends": [
    "manawil"
  ]
}
```

## Configuration files
This repository contains the following configuration files:
- `react.js` - ESLint configuration for React projects
- `node.js` - ESLint configuration for Node/Express projects

## Contributing
We welcome contributions to the Manawil ESLint Config. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License
The Manawil ESLint Config is open-source software licensed under the MIT license.