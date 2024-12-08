## How to run

1. Open [https://stackblitz.com/~/github.com/mizdra/repro-volar-get-language-id-error?file=example/index.ts](https://stackblitz.com/~/github.com/mizdra/repro-volar-get-language-id-error?file=example/index.ts)
1. When the following prompt appears, select "Allow".
    - ![This workspace contains a TypeScript version. Would you like to use the workspace TypeScript version for TypeScript and JavaScript language features?](docs/switch-workspace-tsdk-prompt.png)
1. Open tsserver log

Expected: Error message is output to the tsserver log.
Actual: Error message is not output to the tsserver log.
