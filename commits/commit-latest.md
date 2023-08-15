feat: picture-in-picture (#277)

* add pip

* fixed OnResume() OnStop()
add picture in picture button
add pip settings

* fixed sourceRectHint
add aspectRatio

* fix import

* improve hide playerControls

* add onNewIntent()

* Home button/gesture settings

* add summary

* add GESTURE_EXCLUSION_AREA_SIDE

* remove if else in sourceRectHint
fix onStop() behavior

* fix behavior when using pip button, now go home

* test

* fix onStop()

* fix: mpv aspect ratio

* fix when in PiP mode and starting new playback

* refactor: pip implementation

Remove option to disable pip button, always show the button when pip is supported
Remove the option to completely disable pip
Format using ktlint

* fix when in pip mode and play a new video

* fix recent app behavior

* lint

* Some adjustments

* fix: Aspect ratio is too extreme

* fix: Activity recreation

* fix merge issues

* fix merge issues

* ktlintFormat

* Add Picture in Picture

* fix

* fix sourceRectHint, updateZoomMode before entering pip

* lint

* fix: disable pip when player is locked

* lint

* lint

* fix: sourceRectHint

* fix: replace media items in mpv

* fix: don't show skip intro button in pip

* chore: remove `android:resizeableActivity` from manifest since the default is already `true`

* refactor: remove option to force 16:9 aspect ratio

* refactor: update strings

---------

Co-authored-by: Jarne Demeulemeester <jarnedemeulemeester@gmail.com>
