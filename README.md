commbraces
==========

Comment style braces parser for python


Simple but useful "braces" for python:

Example:
--------
<code>
def mytestfun(n): #[
    for i in range(n):#[
    print i
    #here is some pretty complicated code...not wrong indentation wanted!
#]
#]        
</code>
Usage:
-------

python commbrace.py < before.py > after.py


This code is based on:
curlypy.py by Niall McCarroll  

Distributed under the MIT/X11 License (http://www.mccarroll.net/snippets/license.txt)
