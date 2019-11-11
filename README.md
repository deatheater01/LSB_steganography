# LSB_steganography
this is a least significant bit steaganography in python


Hide binary with steg:
  -image IMAGE          Provide the original image
  -binary BINARY        The binary file to be obfuscated in the image
  -steg-out STEG_OUT    The resulting steganographic image

Reveal binary:
  -steg-image STEG_IMAGE
                        The steganographic image
  -out OUT              The original binary

Hide the message:

> python main.py -image original.png -binary original.bin -steg-out steg.png

Reveal the hidden message:

> python main.py -steg-image steg.png -out bin
