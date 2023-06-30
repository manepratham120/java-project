
                                        Huffman Coding String Compression
This project is an implementation of the Huffman coding algorithm for string compression in the Java programming language.
Huffman coding is a lossless data compression algorithm that works by assigning variable-length codes to different characters based on their frequency of occurrence. 
This allows more frequent characters to have shorter codes, resulting in efficient compression.

                                        How Huffman Coding Works

1 Frequency Analysis: The algorithm begins by analyzing the input string and counting the frequency of each character.

2 Building the Huffman Tree: Based on the character frequencies, the algorithm constructs a binary tree called the Huffman tree. Each leaf node of the tree represents a character along with its frequency, and the path from the root to each leaf node represents the binary code for that character.

3 Generating Huffman Codes: Traversing the Huffman tree, the algorithm assigns unique binary codes to each character. The codes are assigned in such a way that no code is a prefix of another code. This property allows for efficient decoding without ambiguity.

4 Encoding: The input string is encoded using the generated Huffman codes. Each character is replaced with its corresponding Huffman code, resulting in a compressed representation of the original string.

5 Decoding: The compressed string can be decoded by traversing the Huffman tree using the binary codes. Starting from the root, we follow the path based on the input bits until we reach a leaf node, which represents a decoded character. This process is repeated until the entire compressed string is decoded.

![Screenshot 2023-06-30 201936](https://github.com/manepratham120/java-project/assets/122907546/d9095a59-8402-40a4-99f8-7dfe934c2438)
![Screenshot 2023-06-30 202011](https://github.com/manepratham120/java-project/assets/122907546/7316fe77-0d24-4d73-82e9-bfd8a9342110)
![Screenshot 2023-06-30 202023](https://github.com/manepratham120/java-project/assets/122907546/e81470e4-1750-4c82-a8d0-557b5e3774e6)
![Screenshot 2023-06-30 202039](https://github.com/manepratham120/java-project/assets/122907546/1c9541c8-94a5-43c8-a9d7-791697879da0)

