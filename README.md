# Fisher Yates Shuffle package

This package is a simple implementation of the Fisher Yates Shuffle algorithm. It is a simple and efficient algorithm to shuffle a list of elements.

## Installation

```bash
npm install fisher-yates-shuffle
```

or

```bash
yarn add fisher-yates-shuffle
```

or

```bash
pnpm add fisher-yates-shuffle
```

## Usage

### CommonJS

```javascript
const shuffle = require("fisher-yates-shuffle");

const list = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];

const shuffledList = shuffle(list);
```

### ES6

```javascript
import { FisherYates } from "fisher-yates-shuffle";

const list = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];

const shuffledList = FisherYates(list);
```
