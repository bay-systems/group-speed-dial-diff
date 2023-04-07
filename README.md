# Group Speed Dial Diff


## About

Script that simplifies comparing Group Speed Dial backup files.

This script is intended for if you have more than one Group Speed Dial backup file and want to see the differences between the files.

It only shows the differences between the files.

Group Speed Dial backup files are normally difficult to read since they contain a very long line of text.  This script creates a copy of each file, splits them, and does processing of them to only show you the relevant information that is different in each file, i.e. the URLs that are different in each one.

This can be useful if you want to synchronize your Group Speed Dial dials across multiple systems.

Since the Group Speed Dial import process overwrites existing dials, if you are importing dials from another system this script is useful to make sure you do not remove dials.

## Usage

The script takes two Group Speed Dial backup files as arguments:
```bash
gsddiff <file1> <file2>
```

