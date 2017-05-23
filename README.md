# SafeHTML for Elm

This package is a safe subset of [elm-lang/html](https://github.com/elm-lang/html) that aims prevents arbitrary javascript execution.

The following changes has been made:
* The _attribute_ function has been unexposed.
* The _property_ function has been unexposed.
* The _node_ function has been unexposed.
* The _on_ function has been unexposed.
* Sanitazion has been introduced into the href attribute to filter for "javascript:"
