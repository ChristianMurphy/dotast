# dotast

> Graphviz **DOT** **A**bstract **S**yntax **T**ree

**DOTAST** discloses graphviz as an abstract syntax tree.  _Abstract_
means not all information is stored in this tree and an exact replica
of the original document cannot be re-created.  _Syntax Tree_ means syntax
**is** present in the tree, thus an exact syntactic document can be
re-created.

**DOTAST** is a subset of [unist](https://github.com/syntax-tree/unist), and implemented by [redot](https://github.com/redotjs/redot).
