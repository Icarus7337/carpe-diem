This was my summer research internship project that I implemented and furthered on the basis of a research paper about visual cryptography.

The basic motive behind this project was to see if the concepts of visual cryptography can be extended to encryption and decryption of confidential data by means of embedding it in the image.

The project was designed to work under some constraints and the assumptions made are as follows:
•	The image that is to be divided into shares needs to be in .bmp format and should be black and white only. Any other colour interferes with the process of share generation.
•	The size of the data that needs to be encoded should be less than or equal to the number of pixels in the image. In case of lesser size, padding can be used along with a size parameter.
•	For the purposes of authentication, the properties of a hash function are assumed to be true, namely:
I.	Computational efficiency
II.	Pre Image Resistance
III.	Weak Collision Resistance
IV.	Strong Collision Resistance

A detailed explanation can be found in the REPORT file.
