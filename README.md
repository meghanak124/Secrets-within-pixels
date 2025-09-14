This project, Secrets Within Pixels, is an implementation of image steganography, a technique used to hide secret messages within images. By modifying the Least Significant Bit (LSB) of pixel values, this project ensures secure and undetectable communication.

With the rise of cyber threats and data breaches, secure communication has become a necessity. Traditional encryption methods often raise suspicion, but steganography allows us to hide messages within everyday images, making them unnoticeable to attackers. This project was developed to explore the possibilities of secure communication through Python-based steganography techniques.

TECHNOLOGIES USED :

Programming Language: Python

Libraries:

Pillow – For image processing

NumPy – For efficient pixel manipulation

Tkinter – For GUI implementation

Development Environment: VS Code

FEATURES:
User-Friendly Interface – Built using Tkinter for easy encoding and decoding

LSB Steganography – Uses the Least Significant Bit (LSB) method for hiding messages

Supports PNG & JPEG – Works with different image formats

Error Handling & Validation – Prevents incorrect input selection

Lightweight & Efficient – Minimal processing overhead for embedding and extracting messages

WORKING :

Encoding Process:

Select an image

Enter the secret message

Save the stego-image with the hidden message

Decoding Process:

Select a stego-image

Extract the hidden message

PERKS:

Minimal Image Distortion – Modifies only the LSB to ensure high image quality

Fast Execution – Optimized pixel manipulation using NumPy for quick processing

Secure & Stealthy – The embedded message is not easily detectable
