Expand command:
-----------------------
Expand copies files to the standard output, with tab characters expanded to space characters. The number of space characters to be printed can be given using the option "--tab"

Example:  expand --tab=200 FileName.txt
The above command would replace the tab characters with 200 space characters.


Modifications Done:
-----------------------
1-----> If the command is run with tab number characters option less than 10, then the tab characters in the file would be replace with 100 space characters.
Example: expand --tab=5 FileName.txt
The above command would replace the tab characters with 100 space characters.

2-----> If the command is run with tab number characters option more than or equal to 10 and less than 25, then the tab characters in the file would be replace with 300 space characters.
Example: expand --tab=15 FileName.txt
The above command would replace the tab characters with 300 space characters.

3-----> If the command is run with tab number characters option more than 25, then the tab characters in the file would be replace with a single space character.
Example: expand --tab=1000 FileName.txt
The above command would replace the tab characters with a single space character.

