# journal
This small command line utility manages a user's journal.

# Description
When run for the first time, journal will create a Journal directory in the user's home directory, then it will create a folder for the month a file for the day. It will then time stamp the file with the user's name and the date and time. Finally it will open the file with the user's chosen text editor(default nano).

To change the default text editor, the user can run:
sudo journal --texteditor <new_editor>
to change their preference for text editor.

To see usage a user can type journal --help.
