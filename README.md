# BLOWFISH_ALGORITHM
Blowfish encryption algorithm, a symmetric key block cipher known for its simplicity and security.

Blowfish operates on 64-bit
blocks and supports key lengths ranging from 32 to 448 bits. This implementation
includes key generation, encryption, and the core Blowfish operations, such as
the Feistel function and the P-array and S-boxes initialization. Through test cases
and comparison with a reference Java implementation(GFG) the code demonstrates the
correctness and reliability of the Blowfish encryption algorithm in a simplified form.
Blowfish’s flexibility and efficiency make it a valuable choice for various secure data
encryption applications.

The result of encrypting "123456abcd132536" with the key "aabb09182736ccdd"
using the Blowfish encryption algorithm is a ciphertext. When decrypted, the
ciphertext yields the original plaintext.

Run the .ipynb file(blowfish_encrypt_decrypt.ipynb), while running the decrypt function, There may not be the desired decrypted text. just Run only the decrypt function again to get the desired result.

Results are shown in the jupyter notebook. 

# IMAGE ENCRYPTION USING BLOWFISH ALGORITHM 
Developed a application for Image Encryption and Decryption. The Folder IMAGE_ENCRYPTION consists the files
give the password.jpg as input or you can replace with any other jpg/jpeg file. the code processesss and saves the following files
(Compressed_password.jpg, encode.bin, cipher.txt, decrpted_password.jpg) which are uploaded to the folder for reference. Make sure the jpg/jpeg and py/ipynb are in the same directory.

# AUDIO ENCRYPTION USING BLOWFISH ALGORITHM

This implementation showcases the practical application of the Blowfish algorithm
in securing audio data. The key initialization, generation, and encryption processes
collectively contribute to enhancing the confidentiality and integrity of audio files.
Key Initialization The Blowfish algorithm for audio encryption begins with initializing substitution boxes (S-Boxes) and permutation boxes (P-Boxes) essential for the
encryption process. These boxes are initialized with predefined hexadecimal values
and derived from the digits of pi. The folder AUDIO_ENCRYPTION consists the files after compiling

# VIDEO ENCRYPTION USING BLOWISH ALGORITHM

This implementation showcases the practical application of the Blowfish algorithm
in securing video data. The key initialization, generation, and encryption processes
collectively contribute to enhancing the confidentiality and integrity of video files.
The folder VIDEO_ENCRYPTION consista the files after compiling


Blowfish is a popular choice for several reasons, It has undergone rigorous testing
and proven its security. It achieves speed by leveraging built-in instructions on contemporary microprocessors for fundamental bit manipulation operations. Blowfish
is open-source and available in the public domain.


