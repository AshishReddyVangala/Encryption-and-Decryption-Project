This Java program performs encryption and decryption on a given message using a predefined key matrix. 
The program reads a message from a text file, encrypts it, and writes the encrypted message to a new file. 
It then decrypts the message using another predefined key and writes the decrypted message to a different file. 
This project is a simple example of how encryption and decryption can be performed using matrix operations.

## Features
- **Encryption**: Converts a plaintext message into an encrypted format using a predefined key matrix.
- **Decryption**: Converts the encrypted message back to its original plaintext form using a decryption key matrix.
- **File Handling**: Reads the input message from a file and writes the encrypted and decrypted messages to separate files.

## How It Works
1. **Message Input**: The program reads a plaintext message from a file named `message.txt`.
2. **Encryption**: The plaintext is encrypted using a key matrix `encKey = {{3, 2}, {5, 3}}`. The encryption process converts the message characters to numeric values, performs matrix multiplication, and then converts the result back to characters.
3. **Decryption**: The encrypted message is read from a file named `encrypted_message.txt`. The program then decrypts it using the decryption key matrix `decKey = {{23, 2}, {5, 23}}` and converts it back to the original plaintext.
4. **Output**: The encrypted message is saved in `encrypted_message.txt`, and the decrypted message is saved in `decrypted_message.txt`.


### Prerequisites
- Java Development Kit (JDK) installed on your machine.
- Text files `message.txt` containing the message to encrypt and `encrypted_message.txt` where the encrypted message will be stored.


### File Structure
- **`MainProject.java`**: The main Java file containing the encryption and decryption logic.
- **`message.txt`**: The input file containing the plaintext message to be encrypted.
- **`encrypted_message.txt`**: The output file where the encrypted message is saved.
- **`decrypted_message.txt`**: The output file where the decrypted message is saved.


## Authors
- Ashish
- Dermot
- Abby
- Anna
- Minahil


Version: **v2.0** - 2023-11-07: Initial release with encryption and decryption functionality.

