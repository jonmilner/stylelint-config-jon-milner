# Stylelint

> My personal [stylelint](https://github.com/stylelint/stylelint) configuration

## Installation

```bash
yarn add --dev stylelint stylelint-config-jon-milner
```

## Usage

Create a `.stylelintrc` file in your project root:

```json
{
  "extends": "stylelint-config-jon-milner"
}
```

### Extending

Add a "rules" key to `.stylelintrc` to override the default rules.

```json
{
  "extends": "stylelint-config-jon-milner",
  "rules": {
    ...
  }
}
```

## [Changelog](CHANGELOG.md)
