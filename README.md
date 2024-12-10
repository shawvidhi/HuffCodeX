# 🛠️ HuffCodeX

HuffCodeX is an efficient text compressor that implements **Huffman Coding**, a lossless data compression algorithm. It compresses text by analyzing character frequencies and assigning binary codes, reducing file sizes without losing any data. It also includes a decoding function to restore the original text.

---

## ✨ Features

- 📚 **Custom Heap Implementation**: Includes a custom heap for building the Huffman tree efficiently.
- 🔗 **Encoding and Decoding**: Compresses input strings into binary codes and decodes them back into the original text.
- 🌳 **Dynamic Binary Tree Construction**: Builds a Huffman tree dynamically based on character frequencies in the input.
- ✅ **Lossless Compression**: Ensures data integrity during compression and decompression.

---

## 🧩 How It Works

1. **🔍 Frequency Analysis**: Counts the frequency of each character in the input string.
2. **🌲 Huffman Tree Construction**: Constructs a binary tree using a custom heap, where characters with lower frequencies have longer codes.
3. **💾 Encoding**: Assigns binary codes to each character based on the tree structure.
4. **🔄 Decoding**: Reverses the process to reconstruct the original string.

---

## 🚀 Usage

### Encoding Example
```text
Input String: abbccda
Output String: 101100011011110
```

### Decoding Example
```text
Input String: 101100011011110
Output String: abbccda
