batch-renamer
=============

Rename files in batch while keeping their index.
This script's only goal is to save copy-paste time when renaming a batch of files.

Instructions
-------------

* Clone it and make the script file executable on Linux.

        chmod +x batch-renamer

* Run ./batch-renamer and provide the **five** necessary parameters:
    1. Index character that represents the digits
    2. Original file pattern, including index characters
    3. Processed file pattern, including index characters
    4. Index start
    5. Index end

Usage example:

    ./batch-renamer XXX originalXXX.txt processedXXX.txt 15 23

This will batch rename all files with filenames like _originalXXX.txt_ to _processedXXX.txt_ where _XXX_ are digits between 015 and 023.

