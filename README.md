# Stopword Remover

A simple package to remove stop words from text. This package is written in TypeScript but can be used in both TypeScript and JavaScript projects.

## Installation

You can install the package using npm:

```bash
npm install stopword-remover
# or
yarn add stopword-remover
# or
bun install stopword-remover
```

## Code:

```bash
const { removeStopWords } = require('stopword-remover');

const text = "This is a simple example to demonstrate the removal of stop words.";
const result = removeStopWords(text);
console.log(result);

```

