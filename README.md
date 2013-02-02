screencaps
==========

Integrates Mac OS X's screenshot utility with DreamObjects for easy sharing.  The code is written in Python and utilizes the OS X built-in screencapture utility.

The utility calls "screencapture" in interactive mode, the equivalent of Shift-Command-4.  After a screen shot is taken, it is stored in the tmp directory, uploaded to DreamObjects, and the public DreamObjects link is copied to the clipboard.

In addition to being a useful command-line tool, a keyboard shortcut can be created to call an Automator workflow sesrvice to execute it.
