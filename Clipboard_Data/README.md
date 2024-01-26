# ClipboardApp

## Description
This script reads data stored in the Windows clipboard and filters out any emails that have been copied. It provides a convenient way to extract valid emails from copied text.

## Usage

1. Copy any text to the Windows clipboard.
2. Open a terminal.
3. Run the script using the following command:
    ```bash
    python3 ClipboardApp.py
    ```
4. Paste any valid email from the copied text, and it will be displayed in the terminal.

## Example
```bash
$ python3 ClipboardApp.py
Paste your clipboard content here: This is a sample email: example@email.com
Valid email found: example@email.com

