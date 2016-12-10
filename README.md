# Python-Keystroke-Dynamics
Simple keystroke dynamic software written in Python

## Usage:

Clone, ensure you have the imported modules available (PyHook, pythoncom, matplotlib).

Run the script, note that it will save all of your data where you specify it upon startup. Events are stored as a JSON list. This can be appended to. Enter a 'username' (filename) which will write to the .csv file, when you are done, hit ESC. This will end the input procedure.

From there you can graph your event, giving the 'username' that you chose during the record procedure. 

It is possible to generate 2 time based metric from events:

* Time between keydown events
* Time between the keyup events

Sadly, due to the hook functionality, PyHook only runs on Windows.
