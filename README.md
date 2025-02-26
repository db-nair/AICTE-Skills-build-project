Project Overview
This project implements a simple image steganography technique using Python and OpenCV. It allows users to hide a secret message within an image and later retrieve it using a passcode.

Features
Hides a text message inside an image by modifying pixel values.
Encrypts the message using character-to-pixel value mapping.
Requires a passcode for message retrieval.
Uses OpenCV for image processing.
Saves the modified image as encryptedImage.jpg.


Requirements
Ensure you have the following installed:
Python 3.x
OpenCV (pip install opencv-python)


How It Works
Encryption Process
Loads the image (2.jpg – replace with your actual image).
Accepts a secret message and passcode from the user.
Embeds the message into the image pixels.
Saves the encrypted image as encryptedImage.jpg.


Decryption Process
Loads the modified image.
Asks for a passcode.
If the passcode is correct, extracts and displays the hidden message.
Usage Instructions
Place your image (2.jpg) in the same directory as the script.
Run the script:
bash
Copy
Edit
python script.py
Enter a secret message and a passcode when prompted.
The encrypted image (encryptedImage.jpg) will be generated.
To decrypt, run the script again and enter the correct passcode.
Security Note
The method is basic and does not use advanced encryption.
Steganalysis tools may detect modifications in pixel values.
For stronger security, integrate AES encryption before embedding data.
