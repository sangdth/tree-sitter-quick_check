# tree-sitter-quick_check

A grammar to test your Tree-sitter development workflow

Navigate to the root of this project in a terminal / command prompt

- Run `npm install`
- Add ./node_modules/.bin to your PATH
If you don't add this, prefix all tree-sitter commands with ./node_modules/.bin/; e.g., tree-sitter generate becomes ./node_modules/.bin/tree-sitter generate
Windows users need to replace forwards slashes with back slashes.
- Run `tree-sitter generate`
- Run `node-gyp configure`
- Run `node-gyp build`
- Run `tree-sitter test`
