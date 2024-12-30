
# **Secret Tool**
![Banner](https://raw.githubusercontent.com/wanzxploit/secret/refs/heads/main/banner.png)

## Description

**Secret Tool** is a tool for encoding and obfuscating files in various programming languages using base64 encoding. 
This tool supports multiple languages such as Python, Bash, HTML, JavaScript, and PHP. With this tool, your files 
will be protected and hard to read by unauthorized users.

It’s perfect for protecting source code or files that you want to hide the original content or protect from reverse engineering.

## Features

- **Supports multiple languages**: Python, Bash, HTML, JavaScript, PHP.
- **Base64 Obfuscation**: Obfuscates code using base64 encoding to hide the original logic.
- **Obfuscated output files**: The obfuscated files will be saved with the `_secret` suffix added to the file name.
- **UTF-8 Encoding Validation**: Ensures the input files can be encoded with UTF-8.
- **User-friendly**: Displays clear status messages for success or failure.

## Installation

### 1. Prerequisites

Make sure you have Python 3 and pip installed on your system. If not, install them first:

#### On **Linux**:
```bash
sudo apt update
sudo apt install python3 python3-pip
```

#### On **Termux**:
```bash
pkg update
pkg install python
```

### 2. Clone Repository and Install

Run the following commands in your terminal:
```bash
git clone https://github.com/wanzxploit/secret
cd secret
make install
```

This will install the `secret` command and make it available globally in your terminal.

## Usage

1. To obfuscate a file, simply use the command:
   ```bash
   secret <file>
   ```

   For example:
   ```bash
   secret example.py
   ```
   The output file will be named `example_secret.py`.

2. To clear all files and uninstall the tool, run:
   ```bash
   bash clear.sh
   ```

## Supported Languages

- Python (`.py`)
- Bash (`.sh`)
- HTML (`.html`)
- JavaScript (`.js`)
- PHP (`.php`)

## Notes

- Ensure your files are encoded in UTF-8 for proper obfuscation.
- Obfuscation is intended for protection but is not a substitute for secure coding practices.

## Credits

**Developed by Wanz Xploit**
