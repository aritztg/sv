sv
==

Spreadsheet viewer

Works well with both python2 and python3.


Some uses:

$ sv file.xlsx | head

$ cat file.xlsx | sv | cut -f2 | sort | uniq -c | sort -rn | head

