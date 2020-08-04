# System Integrity Tool
SIT is a general purpose hash calculation and comparison tool. When pointed to a file or directory, it will generate a separate ".hash" file for each file given as input. The hashes are generated using MD5 sum (plan to upgrade to SHA256).

## Usage:
python3 sit.py [options]
* -g: Generate hashes for files at a location.
* -c: Compare and verify file integrity for files at a location.
* -h: Display the help dialog.
