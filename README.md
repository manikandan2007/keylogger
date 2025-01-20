# Keylogger Python Script

This is a simple keylogger script written in Python that logs all keystrokes and saves them to a text file (`keylogs.txt`). It uses the `pynput` library to capture keyboard events.

> **Note**: This script is intended for educational purposes only. Be sure to use it responsibly and in accordance with legal regulations.

## Requirements

Before running the script, make sure to install the necessary dependencies. You can install the `pynput` library by running:

```bash
pip install pynput
```

## Usage

1. Clone or download the repository to your local machine.
2. Navigate to the project folder in your terminal.
3. Run the script:

```bash
python keylogger.py
```

4. The script will start logging all keystrokes to a file called `keylogs.txt`.
5. The log file will store each keypress on a new line.

## Important Notes

- This script logs every keypress and appends it to `keylogs.txt` as plain text.
- It is important to use this script in a responsible and ethical manner, and only on machines where you have permission to capture keystrokes.
- Be aware that using keyloggers without consent may violate privacy and legal regulations.

## Example Output

The output file (`keylogs.txt`) will look like this:

```
h
e
l
l
o
(space)
w
o
r
l
d
```
