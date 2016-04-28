MyreStructuredText
==================

.. image:: image/ball1.gif

*emphasis:ref:`start`*
This is my first rest API document's test.
Please take care of me in next work days,I'll must work hard.

**strong emphasis :file:`python`**
:ref:`start`_ start
I've studied in globalrom for one month,thought it feels like my home is very beatifaul!

Title(标题) 
=========== 

Subtitle(子标题) 
---------------- 

Titles are underlined (or over-and underlined) with a printing nonalphanumeric 7-bit ASCII 
character. Recommended choices are "``= - ` : ' " ~ ^ _ * + # < >``". 
The underline/overline must be at least as long as the title text. 

A lone top-level (sub)section is lifted up to be the document's (sub)title.

===============
PARAGRAPH(段落)
===============

This is a paragraph.

  Paragraphs line up at their left edges, and are normally separated by blank lines.(缩进的段落是个引文)
    This is second 缩进段落。
    hello reset.
  exit first.
return forward.

===========
LISTS(列表)
===========

BULLET LISTS(子弹列表)
----------------------

Bullet lists

- This is item 1 
- This is item 2
- This is item 3
- Bullets are "-", "*" or "+". 
  Continuing text must be aligned 
  after the bullet and whitespace.

Note that a blank line is required before the first item and after the last, but is optional between items.


Enumerated lists(数字列表)
--------------------------

1. This is the first item 
2. This is the second item 
3. Enumerators are arabic numbers,single letters, or roman numerals 
4. List items should be sequentially,numbered, but need not start at 1 (although not all formatters will honour the first index). 
#. This item is auto-enumerated.

Definition lists(自定义列表)
----------------------------

what 
  Definition lists associate a term with a definition. 

how 
  The term is a one-line phrase, and the definition is one or more paragraphs or body elements, indented relative to the term. Blank lines are not allowed 
  between term and definition.
  
why
  why don't I know what are they talking.
  
 
ForMyself
---------
    
http://www.douban.com/

Field Lists(字段列表)
---------------------

**Introduce myself**

:Name: liwanzheng
:birth: 1992.12.15
:Authors: 
    Rand Lee,lyrand and lancer(and sundry other good-natured folks).

:Version: 1.0 of 2016/04/27
:Dedication: To my rest API.

:Hobbies: like monic,play badminton and chess,listen to music and watch movies.


Option Lists(选择列表)
----------------------

-a            command-line option "a" 
-b file       options can have arguments and long descriptions 
--long        options can be long also 
--input=file  long options can also have arguments 
/V            DOS/VMS-style options too

Literal Blocks(文子块)
----------------------

A paragraph containing only two colons 
indicates that the following indented 
or quoted text is a literal block. 

:: 

  Whitespace, newlines, blank lines, and 
  all kinds of markup (like *this* or \this) is preserved by literal blocks. 

  The paragraph containing only '::' 
  will be omitted from the result. 

The ``::`` may be tacked onto the very 
end of any paragraph. The ``::`` will be 
omitted if it is preceded by whitespace. 
The ``::`` will be converted to a single 
colon if preceded by text, like this:: 

  It's very convenient to use this form. 

Literal blocks end when text returns to 
the preceding paragraph's indentation. 
This means that something like this 
is possible:: 

      We start here 
    and continue here 
  and end here. 

Per-line quoting can also be used on 
unindented literal blocks:: 

> Useful for quotes from email and 
> for Haskell literate programming.

Line Blocks(小线段)
-------------------

| Line blocks are useful for addresses, 
| verse, and adornment-free lists. 
| 
| Each new line begins with a 
| vertical bar ("|"). 
|     Line breaks and initial indents 
|     are preserved. 
| Continuation lines are wrapped portions of long lines; they begin with spaces in place of vertical bars.
  
Block Quotes(块报价)
--------------------
 
Block quotes are just:

    Indented paragraphs,

        and they may nest.
  
Doctest Blocks(Doctest块)
-------------------------

Doctest blocks are interactive 
Python sessions. They begin with 
"``>>>``" and end with a blank line.

>>> print "This is a doctest block." 
This is a doctest block.

============
Tables（表）
============

Grid table(网格表)
------------------

+------------+------------+-----------+ 
| Header 1   | Header 2   | Header 3  | 
+============+============+===========+ 
| body row 1 | column 2   | column 3  | 
+------------+------------+-----------+ 
| body row 2 | Cells may span columns.| 
+------------+------------+-----------+ 
| body row 3 | Cells may  | - Cells   | 
+------------+ span rows. | - contain | 
| body row 4 |            | - blocks. | 
+------------+------------+-----------+
| item  lists| number list| 1. item1  |
|            |            | 2. item2  |
|            |            | 3. item3  |
+------------+------------+-----------+

Simple table（简单表)
---------------------

=====  =====  ====== 
   Inputs     Output 
------------  ------ 
  A      B    A or B 
=====  =====  ====== 
False  False  False 
True   False  True 
False  True   True 
True   True   True 
=====  =====  ======



Transitions(过渡线)
-------------------

A transition marker is a horizontal line 
of 4 or more repeated punctuation 
characters.

------------

A transition should not begin or end a 
section or document, nor should two 
transitions be immediately adjacent.


=========================
Explicit Markup(直解标记)
=========================

Footnotes(脚注)
---------------

Footnote references, like [5]_. 
Note that footnotes may get 
rearranged, e.g., to the bottom of 
the "page".
.. [5] A numerical footnote. Note 
   there's no colon after the ``]``. 

-------------------------------

Autonumbered footnotes are 
possible, like using [#]_ and [#]_.
.. [#] This is the first one. 
.. [#] This is the second one.

They may be assigned 'autonumber 
labels' - for instance, 
[#fourth]_ and [#third]_.

.. [#third] a.k.a. third_

.. [#fourth] a.k.a. fourth_

---------

Auto-symbol footnotes are also 
possible, like this: [*]_ and [*]_.
.. [*] This is the first one. 
.. [*] This is the second one.
  
Citation(引用)
---------------

Citation references, like [CIT2002]_. 
Note that citations may get 
rearranged, e.g., to the bottom of 
the "page".
.. [CIT2002] A citation 
   (as often used in journals).

Citation labels contain alphanumerics, 
underlines, hyphens and fullstops. 
Case is not significant.

Given a citation like [this]_, one 
can also refer to it like this_.

.. [this] here.  

Hyperlink Targets(超链接的文本)
-------------------------------

External hyperlinks, like Python_.
.. _Python: http://www.python.org/
External hyperlinks, like `Python 
<http://www.python.org/>`_.


Indirect Hypertlink Targets(间接超链接的目标)
---------------------------------------------

Python_ is `my favourite 
programming language`__.
.. _Python: http://www.python.org/
__ Python_

Implict Hyperlink Targets(隐式链接的目标)
-----------------------------------------

Titles are targets, too 
======================= 
Implict references, like `Titles are 
targets, too`_.


.. This text will not be shown 
   (but, for instance, in HTML might be 
   rendered as an HTML comment)
   

