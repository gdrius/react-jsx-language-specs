React JSX language specs
========================

This adds React JSX syntax highlighting to gtksourceview based editors
(Gedit, Anjuta IDE, etc).
[React JSX](https://facebook.github.io/react/docs/jsx-in-depth.html) is 
a JavaScript syntax that looks similar to XML.

Installation
------------

To install a language spec for user only, you need to copy the 
`react-jsx.lang` file into the
`~/.local/share/gtksourceview-3.0/language-specs/` directory.
For gtk2 based editors put the lang file into the
`~/.local/share/gtksourceview-2.0/language-specs/` directory.

For a system-wide installation you need to copy the `react-jsx.lang` file
into `/usr/share/gtksourceview-3.0/language-specs` directory.
