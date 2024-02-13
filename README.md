
# Encryption and Decryption Tool

This project provides a simple graphical user interface (GUI) for encrypting and decrypting files using a basic XOR cipher algorithm. It allows users to select a file, specify a security key, and perform encryption or decryption accordingly.

## Installation

- Clone or download the repository to your local machine.
- Ensure you have Java Development Kit (JDK) installed.
- Open the project in your preferred Integrated Development Environment (IDE).
- Compile and run the EncryptionAndDecryption.java file.

```bash
    git clone https://github.com/princeprakhar/Encryption-and-Decryption-project.git

```
```bash
    javac EncryptionAndDecryption.java
    java EncryptionAndDecryption

```

## Usage/Examples
Launch the application.
- Enter your desired security key in the provided text field.
- Click the "Open file" button to select the file you want to encrypt or decrypt.
- Once the file is selected, the program will perform the encryption or decryption operation based on the provided key.
- Upon completion, a message dialog will indicate the success of the operation.

## Functionality
The core functionalities of this tool include:
- Encryption: XOR operation between the bytes of the selected file and the provided key.
- Decryption: XOR operation between the bytes of the encrypted file and the same key, effectively reversing the encryption process.


## Dependencies
This project utilizes the following dependencies:
- `javax.swing.*`: Provides GUI components for Java applications.
- `java.awt.*`: Provides classes for creating and managing graphical user interfaces.
- `java.io.*`: Provides classes for input/output operations, used for file handling.
## Limitations

- `Security`: The XOR cipher used in this tool is very basic and not suitable for secure encryption. It's intended for educational purposes only.
- `File Size`: Large files may take longer to encrypt or decrypt, and the application's performance may vary accordingly.
- `Key Management`: The security key is currently provided directly through the GUI, which may not be secure. In a real-world scenario, proper key management practices should be implemented.


## Contributions
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## Author
- [@princeprakhar](https://www.github.com/princeprakhar)
  
## License
This project is licensed under the MIT License.
