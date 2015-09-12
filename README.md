# journal
This small command line utility manages a user's journal.

# Description
When run for the first time, journal will create a Journal directory in the user's home directory, then it will create a folder for the year, a folder for the month, and a file for the day. It will then time stamp the file with the user's name and the date and time. Finally it will open the file with the user's chosen text editor(default nano). When run again the journal command will only create a folder for year and month and file for the date if one does not already exist. A new timestamp will only be added if the file was last edited greater than ten minutes prior.

To change the default text editor, the user can run:
sudo journal --texteditor <new_editor>

To see usage a user can type journal --help.

# Setup
Once this repo is cloned, move the journal file into /usr/bin so that it can be run anywhere. Also make sure to chmod to allow execution:
chmod u+x journal ;
sudo cp journal /usr/bin
