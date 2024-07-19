# Stopword Remover

A simple package to remove stop words from text. This package is written in TypeScript but can be used in both TypeScript and JavaScript projects.

## Installation

You can install the package using npm:

```bash
npm install cdx-stopword-remover
# or
yarn add cdx-stopword-remover
# or
bun install cdx-stopword-remover
```

## Code:

```bash
import { removeStopWords } from 'stopword-remover'

const text = "This is a simple example to demonstrate the removal of stop words.";
const result = removeStopWords(text);
console.log(result);

```

