Useful Python 3 features for scientists
=======================================

Unicode strings
---------------

In Python 2, only the basic ASCII character set was available in standard strings; to use the much more extensive Unicode set of characters, you had to prefix each string with a u::

        "an ascii string"
	u"a unicode string"

Unicode strings are the default in Python 3. This makes it more straightforward to e.g., include foreign languages, and print greek symbols (or emoji) in strings and comments. 

Division
--------

In Python 2, integer division is the default, so 1/2 evaluates to 0. This means frequently mutiplying by 1.0 when working with integer variables, like so:: 
	int_one * 1.0 / int_two.

In Python 3, the default division will yield a float, and integer division is accessed as int_one // int_two.

Unicode variable names
----------------------

As with strings, Python 3 expands variable names to include most Unicode symbols, where Python 2 could only use the basic ASCII character set for variable names. This means you can use foreign language words and letter-like symbols as variable names, e.g.::

	π = 3.14
	
(sadly, no emoji here, though that functionality may be on the horizon...)

Use caution if you're planning to share your code, though, as it's fairly easy to produce illegible code this way.

Recursive glob
--------------

Function annotations
--------------------

Matrix multiplication operator
------------------------------

Advanced print function
-----------------------

Concurrent futures
------------------

Advanced unpacking
------------------

Sensible comparison
-------------------
