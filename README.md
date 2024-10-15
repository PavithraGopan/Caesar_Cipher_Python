# Caesar_Cipher_Python

# Secret Code Generator - Python 

This is a Python program that acts as a **Secret Code Generator** using a basic Caesar cipher technique. The program allows you to encode and decode messages by shifting the letters in the alphabet by a specified amount.

## Features
- **Encode a Message**: Converts a plain text message into a coded message using a shift value (like a Caesar cipher).
- **Decode a Message**: Converts a coded message back to its original form by reversing the shift.
- **Handles Upper and Lower Case**: The program preserves the case of letters during encoding/decoding.
- **Ignores Non-Alphabet Characters**: Spaces, punctuation, and numbers remain unchanged.
- **Edge Case Handling**: Correctly handles wrapping around the alphabet (e.g., Z to A) and invalid inputs.

## How It Works
1. The user is presented with a simple menu with three options:
   - Encode a message.
   - Decode a message.
   - Exit the program.
2. Depending on the user’s choice, they can input a message and a shift value.
3. The message is encoded or decoded accordingly, and the result is printed on the screen.

## Example Usage

```bash
Secret Code Generator
1. Encode a message
2. Decode a message
3. Exit
Please select an option (1, 2, 3): 1

Enter the message to encode: Hello, World!
Enter the shift number: 3
Encoded message: Khoor, Zruog!

Secret Code Generator
1. Encode a message
2. Decode a message
3. Exit
Please select an option (1, 2, 3): 2

Enter the message to decode: Khoor, Zruog!
Enter the shift number: 3
Decoded message: Hello, World!

Secret Code Generator
1. Encode a message
2. Decode a message
3. Exit
Please select an option (1, 2, 3): 3

Exiting the Secret Code Generator.

