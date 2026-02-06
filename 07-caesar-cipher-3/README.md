# Caesar Cipher CLI

Small interactive command-line Caesar cipher that prints a logo, then lets you encode or decode messages by shifting letters. Non-letter characters (spaces, punctuation, numbers) are preserved.

## Features
- Encode and decode with a single function (caesar)
- Wrap-around shift using modulo (e.g., z + 1 → a)
- Preserves non-alphabet characters
- Loop to process multiple messages without restarting