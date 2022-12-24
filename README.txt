--- shift_console ---

Short Description:
Updates a file/dir backup location.
Can Be used to 'update' a backup of steam instead of copying the entire steam directory for example.

The why?
Saves writes to disk.
Faster than copying everything in circumstances where modified files are unknown & or
saves hassle of manually going in and out of directories looking for files that need to be backed/updated.


[DEVELOPER]
Please ensure win32 long paths are enabled either in registry or using gpedit.
    1. Run Gpedit.
    2. Computer Configuration -> Administrative Tools -> System -> Filesystem -> Enable Win32 long paths.

Any issues please run the exe from powershell and read any errors. Waters nice over here so enjoy.

Python Version: 3.9.2