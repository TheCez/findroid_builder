feat: chapters (#466)

* Add chapter markers and "skip chapter" on long press

* Fix linting problems

- Missing comma
- Unused import
- Comment block

* Add preferences options

* Drop chapter support for ExoPlayer

* Fix linting

* Remove Trailing spaces

* Remove TODO from marker color

* Move code to function

* Optimize imports

* Fix crash on episode skip

* Disable player control view animation

* Avoid crash when there are no chapters for media item

* Skip to next episode when skipping last chapter

* Load chapters from Jellyfin API instead of MPV Player

* Remove chapter gesture

* Fix build

* Fix linting

* Fix linting

* Support chapters with offline media

* Remove debug print

* Add chapter skipping

* Remove trailing spaces

* fix(chapters): display correct chapter while seeking

* refactor: faster and cleaner `getCurrentChapterIndex`

* refactor: seek to start of current chapter if player position is more than 5 seconds past start of chapter

* refactor: change "Matroska chapters" to just "Chapters"

The chapters feature also works for MP4 files so just make it generic

* Bump database version

* Add auto-migration for database version bump

* Save database schema

* chore: clean up

---------

Co-authored-by: Jarne Demeulemeester <jarnedemeulemeester@gmail.com>
