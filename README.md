# Huffman-Encoding-and-Decoding 
Date:4/4/22
Tochi Onwuasoanya:  tonwuaso@u.rochester.edu 
# Overview
This project is a lossless compression program for text files, images, or any other binary input in Java. It successfully compresses up to 95% of size in O(N*log(N)). This project performs Huffman enoding-decoding (or compression-decompression) for different files. This is done by encoding files using the huffman algorithm, and then decoding the file. 

# Methods
There are two primary methods in the program, called 
encode and decode. The encode() method generates a frequency table for each character and uses a Huffman tree to generate the bitstring for each character.
It then iterates through the file and replaces each character with its corresponding bitstring. 
The decode() method then references this frequency table and 
iterates through the encoded file, replacing each bitstring with its corresponding character.The encoding and decoding procedures can be perfomed separately as
the encoded output and the frequency files are stored during the encoding phase. 

# Running the program
Running the code is fairly straightforward. It contains only two files: README and HuffmanSubmit.java.
It depends on the files BinaryIn.java, BinaryOut.java and Huffman.java. Once all the files are in the same directory, the code can be compiled. Running the file HuffmanSubmit.java will take the input files ur.jpg as well as alice30.txt and apply the encoding and decoding procedure on both. This behavior can be changed through the main() function in the file HuffmanSubmit.java. 
This project was made using the eclipse IDE, so running it only involves pressing the green "run" arrow. 
The test file used in the project was the provided ur.jpg file. In order to test another file, make sure to alter file name in the main method.I wrote booleans to the encode file, so the encode files are not represented as 0s and 1s. However, everything works perfectly fine. 

