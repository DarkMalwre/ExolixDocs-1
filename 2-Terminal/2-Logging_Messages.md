# Logging Messags
In this tutorial, we will learn how to log different messages to the terminal

**All examples bellow use the same import statement**<br />
**TypeScript**: `import { terminal } from "@illuxdev/exolix-terminal";`<br />
**JavaScript**: `const { terminal } = require("@illuxdev/exolix-terminal");`

# Basic Text
**TypeScript**
```ts
// ...
terminal.log("Hello, terminal!");
// ...
```

**JavaScript**
```js
// ...
terminal.log("Hello, terminal!");
// ...
```

# Success Message
**TypeScript**
```ts
// ...
terminal.success("Hello, success message!");
// ...
```

**JavaScript**
```
// ...
terminal.success("Hello, success message!");
// ...
```

# Warning Message
**TypeScript**
```ts
// ...
terminal.warning("Hello, warning message!");
// ...
```

**JavaScript**
```js
// ...
terminal.warning("Hello, warning message!");
// ...
```

# Error Message
**TypeScript**
```ts
// ...
terminal.error("Hello, error messag!");
// ...
```

**JavaScript**
```js
// ...
terminal.error("Hello, error messag!");
// ...
```