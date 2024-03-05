# anti ntfs test

<https://en.wikipedia.org/wiki/Comparison_of_file_systems>

|File System|filename(255)|
|---|---|
|NTFS|in Win32 (case-insensitive) except `/\:*"?<>`|
|Ext4|Any byte except NUL, /|
|APFS|Unicode 9.0 encoded in UTF-8|

## git in windows

warning: the following paths have collided (e.g. case-sensitive paths
on a case-insensitive filesystem) and only one from the same
colliding group is in the working tree:

  'A.md'
  'a.md'

error: invalid path 'ntfs/:*"?<>.md'
