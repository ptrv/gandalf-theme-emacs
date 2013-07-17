Gandalf theme
=============

Gandalf color theme for the emacs 24+ built-in color theme support.
The theme is a slightly modified version of the
[overtone/emacs-live](https://github.com/overtone/emacs-live) theme of
the same name (designed originally for the <code>color-theme</code>
package).

Installation
------------

### Manual ###

Add `gandalf-theme.el` to `color-theme-load-path`:

```lisp
(add-to-list 'custom-theme-load-path "~/path/to/gandalf-theme.el")
```

You can load the theme by `M-x load-theme RET gandalf RET`.

To load the theme on startup add the following to your `.emacs` file:

```
(load-theme 'gandalf t)
```
