Tables
******

Tables are terrible because text and tabular format don't go together very well.

Grid Table
==========

+----------+-----------+
| Column 1 | Column 2  |
+==========+===========+
| yes      | really    |
+----------+-----------+
| this crazy to format |
+----------------------+

Easy to span columns and stuff, but you have to actually have all the grids made of ``+``, ``-``, ``|``, and ``==`` line up.
As you edit the text, you'll have to tweak the table formatting.

However, you can put paragraphs and lists, etc. in the grid table.


Simple Table
============

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

I'm guessing the number of spaces matters a lot.
