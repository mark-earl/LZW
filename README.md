# LZW Compression and Decompression

This repository hosts Python scripts for performing file compression and decompression utilizing the Lempel-Ziv-Welch (LZW) compression algorithm. The LZW algorithm is a renowned lossless data compression technique that efficiently replaces repetitive byte patterns with codes, thereby reducing the overall size of the data.

## Contents

- [`A_P2_LZW.ipynb`](A_P2_LZW.ipynb): Implementation of LZW compression using 12-bit code words.
- [`A_P2_LZW_M.ipynb`](A_P2_LZW_M.ipynb): Implementation of LZW compression with variable-length code words ranging from 9 to 16 bits.
- [`test/`](/test/): Directory containing test files for compression and decompression.

## File Structure

Both Jupyter Notebooks (`A_P2_LZW.ipynb` and `A_P2_LZW_M.ipynb`) follow a consistent structure:
1. **Filename Definition**: This cell defines the filename for the file to be compressed/decompressed.
2. **Compression Function**: Defines the function for compressing files using the LZW algorithm.
3. **Decompression Function**: Defines the function for decompressing files compressed with the LZW algorithm.
4. **Test Cell**: Executes tests for compression and decompression using test files.
5. **Clean Cell**: Removes compressed and decompressed files (.lzw/.lzw2 and .2/.2M) from the directory.

## Requirements

- Python 3.x

## How to Use

1. Open either `A_P2_LZW.ipynb` or `A_P2_LZW_M.ipynb` in a Jupyter Notebook environment.
2. Execute the cells step by step.
3. Modify the filename in the first cell to compress/decompress different files.
4. Execute the test cell to verify the correctness of compression and decompression.
5. Use the clean cell to remove compressed and decompressed files from the directory.

## Acknowledgments

The implementation of the LZW algorithm in this repository draws inspiration from various online resources and textbooks on data compression algorithms. Special thanks to the authors and contributors of those resources.
