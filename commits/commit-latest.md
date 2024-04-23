fix: some languages are displayed incorrectly in the track selector

See https://github.com/androidx/media/blob/release/libraries/common/src/main/java/androidx/media3/common/util/Util.java additionalIsoLanguageReplacements for the list of languages being mapped. Seems like always taking the last part and feeding that to Locale works.

Closes #737
