# Byte
Tasks
# BYTE Cybersecurity Recruitment Tasks

Solutions and writeups for the recruitment tasks for [BYTE Cybersecurity Tasks]

---

## Task 01: Cryptography
- **Methodology**: The string `QkFJTntiQTczX1E4Ul9BcmhIQ19YNHlHY0R9` was decoded using Base64, followed by a ROT13 rotation cipher transformation.
- **Execution**: Run python task1_crypto/solve.py.

---

## Task 02: Steganography
- **Methodology**: The downloaded PNG file was corrupted at the header level. Fixed the first 8 bytes to match the official PNG Magic Bytes (`89 50 4E 47 0D 0A 1A 0A`).
- **Execution**: Run `python task2_stego/fix_png.py corrupted.png repaired.png`.


## Task 03: Binary Exploitation
- **Methodology**: Analyzed the dummy binary to determine the stack buffer size, identified the buffer overflow vulnerability, and redirected execution flow to the flag function.
- **Remote Endpoint**: cybersub.bytesoc.dev:9999
- **Execution**: Run python task3_pwn/exploit.py.
