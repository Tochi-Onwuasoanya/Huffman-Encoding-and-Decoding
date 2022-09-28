# Huffman-Encoding-and-Decoding
A lossless compression program for text files, images, or any other binary input in Java. Successfully compresses up to 95% of size in O(N*log(N))
# Overview
 This project contains a program for performing Huffman enoding-decoding (or compression-decompression) for different files. This is done by encoding files using the huffman algorithm, and then decoding the file. 
 # Encode
 There are two primary methods in the program, called encode and decode. The encode() method generates a frequency table for each character and uses a Huffman tree to generate the bitstring for each character. It then iterates through the file and replaces each character with its corresponding bitstring.
 # Decode
 The decode() method then references this frequency table and iterates through the encoded file, replacing each bitstring with its corresponding character.The encoding and decoding procedures can be perfomed separately as we store the encoded
output and the frequency files during the encoding phase. 
# How to run
Running the code is fairly straightforward. It depends on the files BinaryIn.java, BinaryOut.java, HuffmanSubmit.java, and Huffman.java. Once all the files are in the same directory, the code can be compiled. 

Running the file HuffmanSubmit.java will take the input files ur.jpg as well as alice30.txt and apply the encoding and decoding procedure on both. This behavior can be changed through the main() function in the file HuffmanSubmit.java. 
This project was made using the eclipse IDE, so running it only involves pressing the green "run" arrow. 

The test file we used in the project was the provided alice30 file.This project compresses ur.jpg and then decodes it.
