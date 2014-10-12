sv
==

Spreadsheet viewer

Some uses:

$ sv file.xlsx | head

$ cat file.xlsx | sv | cut -f2 | sort | uniq -c | sort -rn | head

