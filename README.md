# File Zipper & Unzipper

This project is a simple yet effective PHP-based solution for compressing and extracting files. It provides an intuitive web interface for handling `.zip`, `.gz`, and `.rar` files, making it a versatile tool for file management directly from a browser.

## Features
- **Extract Files**: Supports `.zip`, `.gz`, and `.rar` file extraction.
- **Create Archives**: Compress directories into `.zip` archives.
- **User-Friendly Interface**: Easy-to-use web form for file selection and path configuration.
- **Real-Time Feedback**: Displays status updates on processing, including success and error messages.
- **Configurable Paths**: Allows specifying custom paths for extraction and compression.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/canmerkut/file-zipper-unzipper.git
   ```
2. Place the files in a web-accessible directory on your PHP-enabled server.
3. Ensure the server has the necessary PHP extensions:
   - `ZipArchive` for `.zip` files.
   - `zlib` for `.gz` files.
   - `RarArchive` for `.rar` files.
4. Access the tool through your web browser.

## Usage
1. Navigate to the interface in your browser.
2. Use the **Archive Unzipper** section to:
   - Select a file to extract.
   - Specify an optional extraction path.
3. Use the **Archive Zipper** section to:
   - Input the directory to compress.
   - Generate a `.zip` archive.
4. Check the status messages for processing results.

## Requirements
- PHP 7.0 or later
- Extensions:
  - `ZipArchive` for `.zip`
  - `zlib` for `.gz`
  - `RarArchive` for `.rar`

## Example Screenshot
![Interface Screenshot](https://raw.githubusercontent.com/canmerkut/File-Zipper-Unzipper-Rar-Included/refs/heads/main/screenshot.jpg)

## About
Created by [Can Merküt](https://github.com/canmerkut), a passionate developer focused on delivering practical web tools. For suggestions or contributions, feel free to reach out or submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
