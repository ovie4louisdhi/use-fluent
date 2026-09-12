# use-fluent

A handful of React hooks I keep copy-pasting between projects

## Examples

```bash
import { useDebounce, useLocalStorage } from './src';

const debounced = useDebounce(value, 300);
```

## What it does

- useMediaQuery SSR-safe
- useDebounce with leading/trailing options
- Tiny: no dependencies besides React
- useLocalStorage with JSON serialization

## Install

```bash
npm install
npm test
```

## Project structure

```text
├── .github/
│   ├── dependabot.yml
│   └── pull_request_template.md
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── faq.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── scripts/
│   └── dev.sh
├── src/
│   ├── index.js
│   ├── useDebounce.js
│   └── useLocalStorage.js
├── .gitignore
├── CHANGELOG.md
├── LICENSE
├── SECURITY.md
└── package.json
```

## Development

```bash
npm install
```

## FAQ

**Is this production ready?**  
It works for my use case; review the code before relying on it.

**Why no framework?**  
The stdlib covers what this project needs.

## License

MIT. Do whatever you want.
