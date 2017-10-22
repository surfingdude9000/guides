---
title: Files and IO
---
## Files and IO

Data can be stored in files such as text files on the computer. Python can read and write to files on the computer. The syntax code to open a file is in the form of: 
```python
open(filename, mode).
```
The first argument is a string containing the filename. The second argument describes the way the file can be used.
'r' argument reads the file only. 'w' argument opens the file for writing
The file can be closed with this code syntax:
```python
filename.close().
```

## Return
Open returns a file object

## Code Sample
```python
open(filename, 'r')
open(filename, 'w')
```

#### More Information:
File Input Output: [Python Tutorial] https://docs.python.org/2/tutorial/inputoutput.html


