feat: lock player controls (#372)

* feat: lock player controls

Add Lock Player feature.

This feature is similar to the feature found in the stock Jellyfin Android app and in the VLC app.

When enabled, it disables the gestures (seek, volume and brightness control), disables the default player controls and leaves only two buttons: a back button and an "unlock" button.
Pressing the unlock button reverts the player back to the initial state, e.g. gestures enabled and default buttons shown.

Works with ExoPlayer and MPV Player.

Let me know of any issues.

* Update PlayerGestureHelper.kt

* Fixed spacing issues

* fixed bug + formatting

* Simplified code

* Fixed spacing

* fixed trailing line?

* refactor: set locked layout initial visibility in xml

---------

Co-authored-by: jarnedemeulemeester <jarnedemeulemeester@gmail.com>
