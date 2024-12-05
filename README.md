# Text File Compression and Decompression System

A C++ project that efficiently compresses and decompresses text files using custom algorithms. The system reduces file size by dynamically mapping unique words to numeric indices and supports seamless recovery of the original text.

## Features

- **Efficient Compression**: Reduces file size by replacing words with shorter codes while preserving special characters and numbers.
- **Accurate Decompression**: Recovers the original file with zero data loss, including formatting and special markers.
- **Compression Ratio Calculation**: Provides insights into the compression efficiency.
- **Dynamic Word Mapping**: Uses STL data structures (`map` and `vector`) for optimal storage and lookup during compression and decompression.
- **Output Logging**: Logs word mappings and decompressed content for debugging and transparency.
- **File Handling**: Demonstrates robust file input and output operations in C++.

## Prerequisites

- A C++ compiler (e.g., GCC, Clang)
- Basic understanding of file handling and C++ STL
