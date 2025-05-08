# caesar-cipher
# Caesar Cipher

This is a simple Caesar Cipher encryption/decryption program written in Python.

## How it works

- Takes a shift key as a command-line argument
- Reads plain text from standard input
- Encrypts alphabetic characters only
- Outputs the encrypted message in blocks of five characters

## How to run

To encrypt a message with a shift of 3:

```bash
python3 mycipher.py 3 < plaintext > cryptedtext
