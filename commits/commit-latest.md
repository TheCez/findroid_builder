fix: episode indicator wrapping on second line (#468)

Fixes #445

The episode indicator background was constrained to a 24dp box. If this box could not contain the count, then the count would wrap onto a new line.

The proposed solution is to use a rounded rectangle as the background instead. This can then expand into a chip as needed to accommodate larger numbers without wrapping.
