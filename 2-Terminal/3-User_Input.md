# User Input
In this tutorial, we will learn how to get input data from the user

**All examples bellow use the same import statement**<br />
**TypeScript**: `import { terminal } from "@illuxdev/exolix-terminal";`<br />
**JavaScript**: `const { terminal } = require("@illuxdev/exolix-terminal");`

# Basic Input
**TypeScript**
```ts
// ...
terminal.read("What is your name?").then(name => {
    terminal.log(`Hello ${name}, how are you?`);
});
// ...
```

**JavaScript**
```js
// ...
terminal.read("What is your name?").then(name => {
    terminal.log(`Hello ${name}, how are you?`);
});
// ...
```

# Basic Input With Validator
**TypeScript**
```ts
// ...
terminal.read("What is your name?", answer => {
    if (answer.length == 0) {
        return false;
    }

    return true;
}).then(name => {
    terminal.log(`Hello ${name}, how are you?`);
});
// ...
```

**JavaScript**
```js
// ...
terminal.read("What is your name?", answer => {
    if (answer.length == 0) {
        return false;
    }

    return true;
}).then(name => {
    terminal.log(`Hello ${name}, how are you?`);
});
// ...
```
