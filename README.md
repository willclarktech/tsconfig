# tsconfig-willclarktech

Default TypeScript configuration for personal projects.

## Installation

Install the package:

```sh
npm install --save-dev willclarktech/tsconfig-willclarktech
```

Or via `bun`:

```sh
bun add --save-dev github:willclarktech/tsconfig-willclarktech
```

## Usage

Extend from the relevant config in your project’s TypeScript configuration file. For example:

```json
{
	"extends": "@willclarktech/tsconfig/base.json"
}
```

Available configs:

| Project type       | Config                                       |
| ------------------ | -------------------------------------------- |
| NodeJS application | `@willclarktech/tsconfig/node.json`          |
| NodeJS library     | `@willclarktech/tsconfig/library.json`       |
| Types-only library | `@willclarktech/tsconfig/library-types.json` |
| Bun project        | `@willclarktech/tsconfig/bun.json`           |
| Browser project    | `@willclarktech/tsconfig/browser.json`       |

## Additional configuration

The following configuration options have defaults but are likely to be overridden in your project:

1. `baseUrl`
1. `include`
1. `outDir`
1. `target`

For projects using React or other JSX-based libraries, you may also need to set the following:

1. `jsx`
