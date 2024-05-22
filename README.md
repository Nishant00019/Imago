# Imago
Imago is a software application designed to protect the confidentiality of images by converting them into a secure, unreadable format and then restoring them to their original state when needed.

Image Encrypter
Purpose: To protect images from unauthorized access by converting them into a scrambled, unreadable format.
Process:
Encryption Algorithm: Uses cryptographic algorithms (such as AES, DES, RSA) to transform the image data.
Encryption Key: A secret key used in the encryption algorithm to ensure only authorized parties can decrypt the image.
Output: The result is an encrypted file that appears as gibberish and cannot be interpreted as an image without decryption.

Image Decrypter
Purpose: To convert the encrypted image back to its original, readable format.
Process:
Decryption Algorithm: Uses the same cryptographic algorithm and key to reverse the encryption process.
Decryption Key: The same secret key (or a corresponding key in asymmetric encryption) used during encryption.
Output: The original image is restored and can be viewed or processed as usual.
