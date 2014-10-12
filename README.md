svc
==

Spreadsheet viewer and converter
--

Sometimes you are working in your terminal and suddenly... you should check quickly the contents from an excel file.

SVC outputs xls/x data into a tsv, so you can operate with these files as always.


Some example uses:

    $ sv file.xlsx | head
    
    $ cat file.xlsx | sv | cut -f2 | sort | uniq -c | sort -rn | head


Updates
--

* Works well with both python2 and python3.
* It should work well in Debian and its derivatives, and in OSX.

Requeriments
--
* You should have installed python (2 or 3) in your system.
* SVC uses the wonderful xlrd library.