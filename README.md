#  Encryption and Decryption Application

## Overview
This application allows users to select any file from their computer, view its details, and perform encryption and decryption operations using the OpenSSL library. The encryption algorithm used is AES (Advanced Encryption Standard) with a 256-bit key size and CBC (Cipher Block Chaining) mode.

## Features
- **File Selection**: Users can browse and select any existing file on their computer.
- **File Details Display**: The application displays the following details of the selected file:
  - File Path
  - File Size
  - File Extension
- **Encryption**:
  - Uses AES-256-CBC algorithm to encrypt the selected file.
  - Ensures secure encryption using OpenSSL.
- **Decryption**:
  - Allows users to retrieve the original file from the encrypted one.
- **Custom File Saving**:
  - Users can select the name and location before saving the encrypted or decrypted file.

## Requirements
- C++
- Qt Framework / QML
- OpenSSL Library
  
## Demo

https://github.com/user-attachments/assets/ef38cfdf-bd53-47bc-bdec-de883524c28a


## ScreenShots
![SelectFile](https://github.com/user-attachments/assets/512322af-1378-4db9-a951-6c7555cd1ea8)

![Ecrypt](https://github.com/user-attachments/assets/8469e946-da11-417a-83ed-377d4dc9e13e)

![Decrypt](https://github.com/user-attachments/assets/be53bc20-1e20-4b35-82bc-811ac4fefdaf)






