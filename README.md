# tsconfig-willclarktech

Default TypeScript configuration for personal projects.

## Installation

Install the package:

```sh
npm install --save-dev https://github.com/willclarktech/tsconfig-willclarktech
```

## Usage

In TS projects extend from the default config in your TypeScript configuration file:

```json
{
	"extends": "tsconfig-willclarktech/tsconfig-base.json"
}
```

In React projects extend from the `react` config:

```json
{
	"extends": "tsconfig-willclarktech/tsconfig-react.json"
}
```

In library projects extend from the `library` config:

```json
{
	"extends": "tsconfig-willclarktech/tsconfig-library.json"
}
```
