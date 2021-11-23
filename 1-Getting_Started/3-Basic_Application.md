# Let's create a very simple command line application
Let's start by logging a message to the console.<br />
Before we start, lets install the terminal module from exolix.

**Npm**
```
npm i @illuxdev/exilix-terminal
```

**Yarn**
```
yarn add @illuxdev/exolix-terminal
```

**TypeScript**
```ts
import { terminal } from "@illuxdev/exolix-terminal";

// Log a message
terminal.log("Hello, world!");
```

**JavaScript**
```js
const { terminal }  = require("@illuxdev/exolix-terminal");

// Log a message
terminal.log("Hello, world!");
```
