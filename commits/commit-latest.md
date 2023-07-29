feat: add play/pause functionality to onDoubleTap (#450)

* feat: Add seek and play/pause functionality to onDoubleTap

This patch enhances the `onDoubleTap` method within the media player
component. It introduces a split-screen layout where the player view is
divided into three equal areas (in the ratio of 2:1:2).

1. Leftmost Area: When double-tapped, it seeks the media playback
backward by the defined seek increment
(`appPreferences.playerSeekBackIncrement`).

2. Middle Area: A double-tap in this area toggles the play/pause state
of the player. If the player is currently playing, it will be paused,
and if it's paused, it will be resumed.

3. Rightmost Area: When double-tapped, it seeks the media playback
forward by the specified seek increment
(`appPreferences.playerSeekForwardIncrement`).

* refactor: inline some variables and put x position inside when statement

---------

Co-authored-by: Jarne Demeulemeester <jarnedemeulemeester@gmail.com>
