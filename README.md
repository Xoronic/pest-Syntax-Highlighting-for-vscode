# pest syntax highlighter

A syntax highlighter for [pest](https://github.com/pest-parser/pest)'s PEG
grammar files.

**Enjoy!**

## Release Notes

### 0.0.1

Initial release.

### 0.0.2

Added support for:

-   Builtin Variables (`COMMENT`, `WHITESPACE`), Operations (`PUSH`, `POP`,
    `PEEK`) and Constants.
-   Multiline comments (nestable)

Thanks [flying-sheep](https://github.com/flying-sheep) for contributing!

### 0.1.0

The following changes were made:

-   Identifiers with capital letters are now recognized as an identifier.
-   `@`, `$`, `_`, `*` and `?` are now highlighted as as operators.

Thanks to [drmason13](https://github.com/drmason13) for contributing!
