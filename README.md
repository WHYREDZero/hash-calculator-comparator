# System Integrity Tool
SIT is a general purpose hash calculation and comparison tool. When pointed to a file or directory, it will generate a separate ".hash" file for each file given as input. The hashes are generated using MD5 sum (plan to upgrade to SHA256).
## Usage:
python3 sit.py [options]
* -g: Generate hashes for files at a location.
* -c: Compare and verify file integrity for files at a location.
* -h: Display the help dialog.
Please note that this program is still in the development phase. The following features are planned for future releases:
* Use the SHA256 algorithm for hashing
* Support for very large files
* GUI
* Centralized database for hashing
* Automatic file monitoring