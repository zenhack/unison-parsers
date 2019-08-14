WIP parser combinator library for unison.

The library itself is in the .parsers namespace. There are also some
basic predicates and utility functions on characters in the .ascii
namespace, which should probably be pushed into the stdlib, once there's
a process for doing that. Finally there is a .json namespace that
includes a WIP JSON parser, with at least one known bug. This is the
best example code that exists currently.

You will need to be running unison master in order to use this; it
depends on a `Char` builtin that was added after alpha release.

Note that this is poorly tested; please report bugs, but also expect
them for now.
