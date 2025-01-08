# SecureStride

## Overview
SecureStride is a Python-based security tool designed to implement stringent security protocols to safeguard sensitive data on Windows devices. It provides file encryption and basic system protection mechanisms to ensure that sensitive data remains confidential.

## Features
- **File Encryption**: Encrypts and decrypts files using the Fernet symmetric encryption.
- **System Protection**: Verifies User Account Control (UAC) and prepares for additional system-specific security configurations.

## Requirements
- Python 3.x
- `cryptography` library: Install via `pip install cryptography`

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/securestride.git
   ```
2. Navigate to the project directory:
   ```bash
   cd securestride
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. **Encrypt a File**:
   To encrypt a file, place the file in the project directory and modify the `securestride.py` script to call `encrypt_file()` with the desired filename:
   ```python
   secure_stride.encrypt_file('sensitive_data.txt')
   ```

2. **Decrypt a File**:
   To decrypt, modify the script to call `decrypt_file()`:
   ```python
   secure_stride.decrypt_file('sensitive_data.txt')
   ```

3. **System Protection**:
   Run the script to apply basic system protection measures:
   ```bash
   python securestride.py
   ```

## Logging
All operations performed by SecureStride are logged in `securestride.log` for auditing and debugging purposes.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your improvements.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.