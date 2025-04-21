# 📦 FileCompression-Project-DS

## 📝 Project Overview

This project is a desktop-based Java application that performs **Text File Compression and Decompression using Huffman Coding**. Huffman Coding is an efficient greedy algorithm that reduces file size by encoding frequently used characters with shorter binary codes.

The application allows you to:
- Compress text files and reduce their size.
- Decompress files back to their original form.
- Compress any alphabetic string directly into a binary sequence.

---

## 🚀 How It Works

The app uses the **Huffman Tree** to assign binary codes to characters based on their frequency in the input. Characters that appear more frequently are assigned shorter codes, resulting in an overall reduced file size.

### ✅ Features
- 📂 **Select and Compress**: Browse and compress any text file.
- 🔁 **Decompress Files**: Restore previously compressed files.
- 🧾 **String Compression**: Enter a string manually to get its Huffman-encoded binary.
- 🖥️ **User-Friendly GUI**: Simple and intuitive interface for all actions.
- 💾 **Save Output**: Choose location to save compressed or decompressed files.

---

## 🛠️ How to Run

### Option 1: Using Pre-Built Executables
1. Clone or download the repository.
2. Go to the `Executable/` folder.
3. Run:
   - `EncoderGUI.jar` – Works on systems with Java installed.
   - `Encoder.exe` – Windows executable, no Java required.

### Option 2: From Source Code
1. Open the project in any Java IDE like IntelliJ IDEA or Eclipse.
2. Locate the `EncoderGUI.java` file in the `src/` directory.
3. Run the `main()` method inside `EncoderGUI`.

---

## 🧱 Folder Structure

file-compression-system/ ├── Executable/ │ ├── EncoderGUI.jar │ └── Encoder.exe ├── src/ │ └── (All Java source files including EncoderGUI.java) ├── README.md └── ...



---

## 💻 Technologies Used

- **Java** – Main programming language
- **Swing** – For building the GUI
- **File I/O** – For reading/writing input and output files
- **Huffman Coding Algorithm** – For compression logic

---

## ✍️ Author

**Swastik Singh Chauhan**

---

## 📜 License

This project is for academic use only. Feel free to explore and modify it as needed.

---



