# SafeHTML for Elm

This package is a safe subset of [elm-lang/html](https://github.com/elm-lang/html) that aims prevents arbitrary javascript execution.

The following changes has been made:
* The attribute function has been unexposed.
* The property function has been unexposed.
* The node function has been unexposed.
* The on node function has been unexposed.
* Sanitazion has been introduced into the href attribute to filter for "javascript:"