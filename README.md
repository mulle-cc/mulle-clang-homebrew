# Doesn't work anymore. Needs attention.

# mulle-clang-homebrew
◀️ Shim for compiling homebrew packages with the mulle-objc compiler

To use [mulle-clang](https://github.com/Codeon-GmbH/mulle-clang) inside a [brew.sh](https://brew.sh) formula use:

```
   # order is important!
   depends_on 'mulle-cc/software/mulle-clang-homebrew' => :build
   depends_on 'mulle-cc/software/mulle-clang-project' => :build
```
