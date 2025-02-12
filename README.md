# PyObfuscate - Simple Python Code Obfuscator
## What is an Obfuscator?
An obfuscator is a tool or technique used to make code difficult to understand or read. This is often done to protect intellectual property, prevent reverse engineering, or enhance security by making it harder for unauthorized users to comprehend the code's logic and functionality. Obfuscation can involve renaming variables, removing comments, and applying various encoding techniques to obscure the original code structure.
 
 
## Overview
PyObfuscate is a simple Python code obfuscator that supports both Python 2 and Python 3. It allows users to obfuscate their Python scripts using various encoding techniques to protect their code from being easily read or understood.

## Features
- Supports Python 2 and Python 3.
- Multiple encoding options:
  - Marshal
  - Zlib
  - Base64
- Menu-driven interface for easy usage.
- Outputs the obfuscated code to a new file.

## Installation
No installation is required. Simply download the `encode.py` file and run it using Python.

## Usage
1. Run the script:
   ```bash
   python encode.py
   ```
2. Follow the on-screen menu to select the encoding option.
3. Provide the name of the Python file you want to obfuscate.
4. The obfuscated file will be saved with the suffix `_enc.py`.

## Encoding Options
- **1**: Encode using Marshal
- **2**: Encode using Zlib
- **3**: Encode using Base64 (Hex)
- **4**: Encode using Base64 (Base32)
- **5**: Encode using Base64 (Base64)
- **6**: Encode using Zlib + Marshal
- **7**: Encode using Zlib + Base64 (Hex)
- **8**: Encode using Zlib + Base64 (Base32)
- **9**: Encode using Marshal + Zlib
- **10**: Encode using Marshal + Base64 (Hex)
- **11**: Encode using Marshal + Base64 (Base32)
- **12**: Encode using Marshal + Base64 (Base64)
- **13**: Encode using Zlib + Marshal + Base64 (Hex)
- **14**: Encode using Zlib + Marshal + Base64 (Base32)
- **15**: Encode using Zlib + Marshal + Base64 (Base64)
- **16**: Special Encode
- **17**: Exit

## Author
- **Name**: Tristan-Brian
- **Date**: Sun Feb 12 00:19:27 2025
- **GitHub**: [Github.com/TristanBrian](https://github.com/TristanBrian)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
