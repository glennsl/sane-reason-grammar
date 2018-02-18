# Sane ReasonML Grammar

This ia based on the grammar included in [OCaml and Reason IDE](https://github.com/reasonml-editor/vscode-reasonml), which
unfortunately is hand-tuned in a rather haphazard way to be "optimized" for a few of the original author's preferred themes,
to the detriment of everything else. This fork attempts to provide a more coherent grammar that properly distinguishes different
tokens so that they can be properly selected for highlighting. In effect, this should provide a better default for most themes
(except, of course, the select few the original grammar was hand-tuned for) and moves the repsonsibility of optimizing
highlighting for specific languages from the grammar to each theme, where it should be to remain maintainable (and quite
frankly just plain sane).

## Acknowledgement

Thanks to [Darrin Morrison](https://github.com/freebroccolo) for creating the original grammar this is based on.