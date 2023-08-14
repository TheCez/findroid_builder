refactor: use `WindowInsetsControllerCompat` instead of deprecated methods (#302)

* refactor: remove deprecated methods to hide system ui

* fix: action bar reappear after changing the brightness

* lint: run ktlintFormat

* refactor: remove sdk check

* fix: system bars stay visible after closing dialog

* fix: add player theme to set navigationbar and statusbar colors to transparent

* fix: draw behind navigationbar and statusbar

* refactor: remove swipeToShowStatusBars extensions

Remove fix for status bar reappearing on LineageOS after changing brightness with gesture.
This can always be added back when official Android version from manufacturers also need this fix.

---------

Co-authored-by: Jarne Demeulemeester <jarnedemeulemeester@gmail.com>
