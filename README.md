# Java Image Steganography

Hide and extract text inside images using LSB technique.

## Files
Encryption.java – embed message  
Decryption.java – extract message  

## Compile
javac Encryption.java Decryption.java

## Encrypt
java Encryption <input_image_path> "<message_to_hide>" <output_image_path>

## Decrypt
java Decryption

## Notes
Use PNG/BMP images only.
