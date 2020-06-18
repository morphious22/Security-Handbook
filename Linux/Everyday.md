##### grep: The 'grep' command is used for searching for text within files.

The first parameter to grep is the search term, and the second is the file to search in.

* Searching for a keyword in file
grep Bob afile
grep Bob* afile

* Using the case insensitive parameter
grep -i bob afile

##### apropos: The 'apropos' tool is used to search man pages for key words, usually to find the 'appropriate' tool to use in a particular situation.

* Searching for a keyword in all man pages
apropos "manual"
