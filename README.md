ABOUT:

This program is a simple GUI application built with Python, Pillow(PIL) and tkinter(tk), which helps in encrypting and decrypting images using XOR operation. This program allows users to input an image and instantly encrypt it.

FEATURES:

1) Helps encrypt and decrypt any image using XOR operation.
2) Once the image is encrypted, they can be decrypted by clicking the decrypt button.
3) User friendly.
4) Clear button to reset the form easily.
5) Pillow(PIL) is a python module which helps users input image data.
6) tkinter is a python module which supports designing of the output page.

USER INTERFACE:

1) Upload image: Button through which image in the form of jpg, png, jpeg and bmp can be uploaded.
2) Encrypt button: Encrypts the provided image by changing the values of pixels.
3) Decrypt button: Decrypts the already encrypted image using the XOR operation.
4) Clear: Clears all input and output fields.
5) Output label: Shows whether the message is encrypted or decrypted.
6) If the Decrypt button is pressed before encrypting an image, an error message is displayed in the output label.
7) Output images are auto saved.
8) Encrypted image is saved as strong_encrypted_image and decrypted image is saved as strong_decrypted_image.

REQUIREMENTS:

1) Python(version 3.10 or advanced).
2) Pillow(to be pip installed through command prompt 'pip install Pillow').
3) Numpy(to be pip installed through command prompt 'pip install numpy').

HOW XOR OPERATION WORKS:

The XOR (also called 'exclusive OR') operation is a mathematical operation, used in image encryption and decryption by treating each byte of the image data and the key as binary values and performing a bitwise XOR on them. The result of this operation is a modified byte, which effectively scrambles the image data. To decrypt, the same XOR operation is performed again using the same key, which reverses the scrambling and restores the original image. XOR returns 1 when inputs differ and 0 when they're the same.

EXAMPLE:

1) for example, we have a byte with a value of 5 (binary 0101) and a key byte with a value of 10 (binary 1010). 
2) Encryption: 5 XOR 10 = 15 (binary 1111).
3) On XORing values (1010 and 1111) we obtain the binary value 5(0101).
4) Decryption: 15 XOR 10 = 5.
5) It gives back the original data.
  

6) 5 (0101) XOR 10 (1010) = 15 (1111)
7) 15 (1111) XOR 10 (1010) = 5 (0101)  # original value restored.

HOW TO RUN:

1) Install python 3.10 or advanced.
2) Install the required modules (Pillow and Numpy).
3) Run the script.

IMAGE DESCRIPTION:

1) The introductory screen to upload an image:
<img width="1920" height="1080" alt="Screenshot (28)" src="https://github.com/user-attachments/assets/f94f3016-3c6c-4cb7-bc0b-1354117ea6e5" />

2) On uploading an image:
<img width="1920" height="1080" alt="Screenshot (29)" src="https://github.com/user-attachments/assets/4bd6277c-9337-4f86-b875-aab667c18351" />

3) By pressing the decrypt button we are provided with an error.
<img width="1920" height="1080" alt="Screenshot (35)" src="https://github.com/user-attachments/assets/ca922368-b92b-4fb0-ba97-2d93cb17314d" />

4) On encrypting the image:
<img width="1920" height="1080" alt="Screenshot (31)" src="https://github.com/user-attachments/assets/dfab2c0d-f915-4b27-aad9-3d105697ed1f" />
<img width="1920" height="1080" alt="Screenshot (30)" src="https://github.com/user-attachments/assets/ff5f4c9a-4b67-42a9-a970-ebbfdcf28c7a" />

5) On decrypting the encrypted image:
<img width="1920" height="1080" alt="Screenshot (33)" src="https://github.com/user-attachments/assets/ce8e3938-8be5-46af-84f8-d813168072d3" />
<img width="1920" height="1080" alt="Screenshot (32)" src="https://github.com/user-attachments/assets/6974f424-065a-488c-b550-4b4b49e0d5dc" />

6) By clearing the page, previously input data is erased.
<img width="1920" height="1080" alt="Screenshot (34)" src="https://github.com/user-attachments/assets/6d55a843-d1e7-465b-b001-dad5e3e85142" />
