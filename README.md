# @arbenk/standards

Reusable linting and formatting standards for JavaScript and TypeScript projects.

## What this package exports

- ESLint flat config: `@arbenk/standards/eslint`
- Prettier config: `@arbenk/standards/prettier`

## Install

```bash
npm install -D @arbenk/standards eslint prettier typescript
```

## Use ESLint (flat config)

Create `eslint.config.js` in your project:

```js
import standards from '@arbenk/standards/eslint';

export default standards;
```

Run ESLint:

```bash
npx eslint .
```

This preset intentionally stays close to ESLint and typescript-eslint recommended defaults.

## Use Prettier

Create `prettier.config.js` in your project:

```js
import standards from '@arbenk/standards/prettier';

export default standards;
```

This preset intentionally uses Prettier defaults as its base.

Run Prettier:

```bash
npx prettier . --check
```

## Publish

```bash
npm publish --access public
```
