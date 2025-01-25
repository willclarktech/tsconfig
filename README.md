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
	"extends": "tsconfig-willclarktech/base.json"
}
```

Available configs:

| Project type       | Config                                      |
| ------------------ | ------------------------------------------- |
| NodeJS application | `tsconfig-willclarktech/node.json`          |
| NodeJS library     | `tsconfig-willclarktech/library.json`       |
| Types-only library | `tsconfig-willclarktech/library-types.json` |
| Bun project        | `tsconfig-willclarktech/bun.json`           |
| Browser project    | `tsconfig-willclarktech/browser.json`       |

## Additional configuration

The following configuration options have defaults but are likely to be overridden in your project:

1. `baseUrl`
1. `include`
1. `outDir`
1. `target`

For projects using React or other JSX-based libraries, you may also need to set the following:

1. `jsx`
