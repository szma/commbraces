commbraces
==========

Comment style braces parser for python


Simple but useful "braces" for python:

Example:
--------

def mytestfun(n): #[
    for i in range(n):#[
    print i
    #here is some pretty complicated code...not wrong indentation wanted!
#]
#]        

Usage:
-------

python commbrace.py < before.py > after.py