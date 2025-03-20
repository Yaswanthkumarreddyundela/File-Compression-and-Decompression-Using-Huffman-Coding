
---

# File Compression and Decompression Using Huffman Coding  

## Overview  
This project implements **Huffman Coding** to **compress and decompress text files** efficiently. It includes an **interactive web-based tool** where users can upload a `.txt` file, compress or decompress it, and download the resulting file.  

## Features  
✅ **Lossless Compression** using Huffman Coding  
✅ **Web-based Interface** for easy file upload & download  
✅ **Automatic File Handling** (compresses and decompresses `.txt` files)  
✅ **Shows Compression Ratio** after processing  
✅ **Error Handling** for invalid file types and empty files  

## Installation  

### Prerequisites  
Ensure you have:  
- A modern web browser (Chrome, Firefox, Edge)  
- A local or online web server (if needed for deployment)  

### Setup  
1. **Clone the repository**  
   ```bash
   git clone https://github.com/Yaswanthkumarreddyundela/File-Compression-and-Decompression-Using-Huffman-Coding.git
   cd File-Compression-and-Decompression-Using-Huffman-Coding/
   ```

2. **Run the project**  
   Open `index.html` in a browser, or host the files using a local server:  

## Usage  

### Steps to Compress a File  
1️⃣ Upload a `.txt` file from your computer.  
2️⃣ Click on the **"COMPRESS"** button.  
3️⃣ Wait for the process to complete and **download** the compressed file.  

### Steps to Decompress a File  
1️⃣ Upload a previously compressed `.txt` file.  
2️⃣ Click on the **"DE-COMPRESS"** button.  
3️⃣ Wait for the decompression process and **download** the original file.  

## How It Works  

### Huffman Coding Algorithm  
- **Step 1:** Count the frequency of each character in the text file.  
- **Step 2:** Construct a **Huffman Tree** using a **MinHeap**.  
- **Step 3:** Assign binary codes to each character (shorter codes for frequent characters).  
- **Step 4:** Encode the text using the generated Huffman codes.  
- **Step 5:** Store the Huffman tree along with the encoded data.  
- **Step 6:** For decompression, reconstruct the Huffman tree and decode the compressed data.  

## Project Structure  
```
📂 file_compressor-master  
 ├── 📄 index.html  # Main UI for compression & decompression  
 ├── 📄 info.html   # Information page about Huffman Coding  
 ├── 📄 script.js   # JavaScript logic for Huffman encoding & decoding  
 ├── 📄 styles.css  # Styles for the web interface  
 ├── 📂 assets/     # Icons and images used in UI  
```

## Screenshots  
🔹 **Main Interface**  
![Main UI](assets/Screenshot(711).png)  

🔹 **Compression & Decompression Process**  
![Processing](assets/Screenshot(710).png)  

## Future Enhancements  
🔹 Support for multiple file formats (e.g., `.csv`, `.json`)  
🔹 Cloud-based compression using **AWS Lambda**  
🔹 Improved UI/UX for better user experience  

---
