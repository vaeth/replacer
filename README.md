# replacer

Search and replace python regular expressions within many files interactively

(C) Martin Väth (martin at mvath.de).
This project is under the MIT license

The aim of the project is to replace regular expressions interactively
in a collection of files.

Its functionality is similar to the perl script `plrep` from
https://github.com/vaeth/mv_perl/
as well as to the ancient python script
https://github.com/vaeth/pyrep/
In a sense, it can be considered a successor of both projects,
also properly dealing with replacements of expressions over multiple lines.
(In the previous projects, multiple lines had only been rudimentarily
implemented or not at all, respectively.)

To install this script, just copy the content of bin/ into your `$PATH`.
To get zsh completion, copy the content of zsh/ to your zsh's `$fpath`,
perhaps `/usr/share/zsh/site-functions/`.

For Gentoo, there is an ebuild in the `mv` repository
(available by `app-select/eselect-repository` or `app-portage/layman`).
