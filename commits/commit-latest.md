fix: snackbar not showing in landscape mode (#476)

* Fix snackbar not showing in landscape

This affected also all tablets since they use the landscape view!

Added `setTextMaxLines` because for some reason the text is truncated on tablets.

Fixes #473.

Co-Authored-By: Jcuhfehl <91626737+Jcuhfehl@users.noreply.github.com>

* Remove unused import

---------

Co-authored-by: Jcuhfehl <91626737+Jcuhfehl@users.noreply.github.com>
