# SHA-1 Password Cracker

This Python tool attempts to crack a given SHA-1 hash by comparing it with the hashes of the most common passwords.

## Features:
- Converts common passwords from a list into their SHA-1 hash equivalents.
- Compares the input SHA-1 hash with the generated hashes to find a match.
- Supports an input file (`1000-most-common-passwords.txt`) containing common passwords.

## Usage:

1. Clone or download the repository.
2. Make sure the `1000-most-common-passwords.txt` file is present in the same directory as the script.
3. Run the script:
   ```bash
   python main.py
