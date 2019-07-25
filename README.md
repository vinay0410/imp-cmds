# imp-cmds

Get all changed files in a particular directory, skipping hidden files and dirs, with most recently changed being printed first
```
find /home/vinaysharma -not -path '*/\.*' -type f -printf '%TY-%Tm-%Td %TT %p\n' | sort -r | head -1000
```
