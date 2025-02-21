# Vigenère Cipher in Python

This project implements a Vigenère cipher in Python. The script can both encrypt and decrypt text using a provided key.

## Features

- **Encryption and Decryption:**  
  Uses a Vigenère cipher algorithm to shift characters based on a repeating key.
  
- **Flexible Input:**  
  - Converts all letters to lowercase before processing.
  - Leaves non-alphabet characters (such as spaces, numbers, or punctuation) unchanged.
  
- **Reusable Functions:**  
  Contains helper functions `encrypt()` and `decrypt()` that wrap the main `vigenere()` function.

## How It Works

1. **Vigenère Function:**  
   For each letter in the input message, the function:
   - Finds the corresponding letter in the key (cycling through the key with modulo arithmetic).
   - Determines the shift (offset) using the position of the key letter in the alphabet.
   - Applies the shift (addition for encryption, subtraction for decryption) to the message character.
   
2. **Encryption vs. Decryption:**  
   The function takes an optional parameter `direction`:
   - A value of `1` encrypts the text.
   - A value of `-1` decrypts the text.

## Usage

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/your-repo-name.git

2. **Navigate to the Project Directory:**
   ```bash
   cd vigenere_Python_Cypher

3.**Run the Script:**
   ```bash
   python vigenere.py

*(Make sure you have Python 3 installed on your system.)*

```
## Contributing

Contributions are welcome! Feel free to fork this repository, improve the code, or add new features. When submitting pull requests, please include a brief description of your changes.

## License

This project is open source and available under the [MIT License]

## Credits
 - g3tech
 - freecodecamp