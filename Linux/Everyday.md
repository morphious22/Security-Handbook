#### grep: The 'grep' command is used for searching for text within files.

The first parameter to grep is the search term, and the second is the file to search in.

_#Searching for a keyword in file_

    grep Bob afile
    grep Bob* afile

_#Using the case insensitive parameter_

    grep -i bob afile

---
#### apropos: The 'apropos' tool is used to search man pages for key words, usually to find the 'appropriate' tool to use in a particular situation.

_#Searching for a keyword in all man pages_

    apropos "manual"
---
#### Dealing with processes

_#Seeing all running processes_

    ps aux
    ps auxf (More info)  

_#Seeing the top resource consuming processes_

    top

_#Killing a process_

    kill pid
---
