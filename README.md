java c
Faculty of Arts  Science 
Fall 2024 Quiz 6 - V2 
CSC 110 Y1F 
Question 1. Object Mutation [3   marks]
Part (a) [1   mark]
Consider   the   code   below.
>>>   lst   =   [3,   1,   2]
>>>   lst.sort()
What   will   lst   refer   to   after   executing   every   line   above?   Circle   the   correct   option   below.
a)      [1,   2,   3]
b)      [3,   1,   2]
c)      [3,   2,   1]
d)   This   will   raise   an   Error   since   there   is   no   method   called   list   .sort.
Part (b) [1   mark]
Consider   the   following   code:
>>>   lst1   =   [1,   2,   3]
>>>   lst2   =   [1,   2,   3]
Which   of the   following   expressions   would   evaluate   to True?   Select all that   apply.
a)   type(lst1) == type(lst2)
b)      lst1   is   lst2
c)      lst1   ==   lst2
d)    id(lst1) ==   id(lst2)
Part (c) [1   mark]
Consider   the   following   code:
>>>   s   =   '   CSC110   '
>>>   z   =   s
>>>   s   =   s   +   '   Y   '
>>> m   =   s
Which   of   the   following   is   true   after   all   the   above   code   is   executed?   Select all that   apply.
a)    z   refers   to    '   CSC110Y   '
b)   m   refers   to    '   CSC110Y   '
c)    z   and   m   have   the   same   id   after   all   the   above   code   is   executed
d)   An   error   is   raised   when   the   above   code   is   executed.
Question 2. Object Mutation [5   marks]
Consider   the   function   f1:
def   f1(lst:   list,   s:   set)   ->   set:
"""         """
...
new_set   =   set()
new_list =   lst
for element   in   sorted(s):
new_list.append(eleme代 写CSC 110 Y1F Fall 2024 Quiz 6 - V2Python
代做程序编程语言nt)
new_set.add(element)
return new   set
And   suppose   we   execute   the   following   in   the   console:
>>> my_list   =   [0,   1,   2]
>>> my_set   =   {3,   2,   1}
>>> my_other_set   = f1(my_list, my_set)
Part (a) [2   marks]
What value   will   my_list   refer   to?
a)      [0,   1,   2]
b)      [0,   1,   2,   1,   2,   3]
c)      [0,   1,   2,   3,   2,   1]
d)      [0,   1,   1,   2,   2,   3]
Part (b) [3   marks]
Which   expressions   below   evaluate   to   True?   Select all that   apply.
a)   my_set   ==   {0,   1,   2,   3}
b)   my_set   ==   {1,   2,   3}
c)   my_set   ==   {3,   2,   1}
d)   my_other_set is my_list
e)   my_other_set   is   my_set
f)   my_other_set   == my_set
Question 3. Memory Model [4   marks]Below   is   an   object-based   memory   model   diagram   showing   the   state   of   the   memory   model   at   the   moment immediately before a   program   ends.
Part (a) [1   mark]
If the   last   thing   the   program   did   was print(stuff),   what   would   be   the   output?
Part (b) [3   marks]
Complete the following code so it will generate the memory model   diagram   shown   above   by   putting   an   expression   or   statement   in   each   of the   three   boxes.   Do   not   add   in   any   extra   lines   or   change   anything   else.
def   bar(num: float, lst:   list)   ->   None:
def   foo(lst: list, num:   int)   ->   None:
bar(12.5,   lst)
bar(100.0, lst)
if   __name__ ==   '   __main__   '   :
stuff   =
i   =   1
foo(stuff,   i)






         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
