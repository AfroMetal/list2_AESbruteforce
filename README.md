# Kryptografia i bezpieczeństwo - List 2
AES-256-CBC bruteforce on key prefix

# Usage

## Run
python "aesbrute.py" "cryptogram in base64" "iv in hex" "key suffix in hex" "key prefix space"

## Input
- iv have to be 16 characters long hex string
- key suffix have to be 32 or less characters long hex string
- key prefix space is hex string of characters allowed as 1st key char, for example '89ab' will only check keys starting with '8', '9', 'a' or 'b'

## Output
On success will give key, decrypted message and run time in seconds.

On fail will give 'Decryption failed.' information and run time in seconds.
