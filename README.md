# Caesar Cipher Tool

This project is a **Python implementation** of the Caesar Cipher for encoding and decoding messages. The Caesar Cipher is a type of substitution cipher where each letter in the plaintext is shifted by a certain number of positions in the alphabet.

## Features
- **Encrypt** a message by shifting the letters.
- **Decrypt** a message by reversing the shift.
- Allows user input for the text and shift value.
- Can handle non-alphabet characters without changing them.
- Includes an ASCII art logo displayed at the start of the program.

## How It Works
The program takes three inputs from the user:
1. **Direction**: Whether you want to "encode" or "decode" the message.
2. **Message**: The text you want to encrypt or decrypt.
3. **Shift Number**: The number of positions to shift the alphabet by.

### Example:
- Input:
  - Direction: `encode`
  - Message: `hello`
  - Shift Number: `5`
- Output:  
  - Encrypted Message: `mjqqt`

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/caesar-cipher-tool.git
   ```
2. Navigate to the project directory:
   ```bash
   cd caesar-cipher-tool
   ```
3. Run the program:
   ```bash
   python caesar_cipher.py
   ```

## ASCII Art
The program includes an ASCII art logo that is generated using a custom class called `art` within the project itself.

## Dependencies
- Python 3.x

## License
This project is licensed under the MIT License 
