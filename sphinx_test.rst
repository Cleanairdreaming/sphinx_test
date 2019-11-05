.. 道路源清单编制 documentation master file, created by
   sphinx-quickstart on Tue Nov  5 10:54:19 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

道路源清单编制
==========================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:



索引和表格
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

第一章 List
==================
* this is *Test*
* a list 

  * with a nested list
  * and some subitems  

  #. 第二节
  #. 第三节

  1. 节1
  2. 节2

* and here the parent list continues

第二章 Table
==================
+------------------------+------------+----------+----------+
| Header row, column 1   | Header 2   | Header 3 | Header 4 |
| (header rows optional) |            |          |          |
+========================+============+==========+==========+
| body row 1, column 1   | column 2   | column 3 | column 4 |
+------------------------+------------+----------+----------+
| body row 2             | ...        | ...      |          |
+------------------------+------------+----------+----------+

=====  =====  =======
A      B      A and B
=====  =====  =======
False  False  False
True   False  False
False  True   False
True   True   True
=====  =====  =======

第三章 Term
==================
尾气排放
   E = E1 + E2 ``text``

蒸发排放
   仅考虑汽油 **Test**

第四章 Lineblocks
==================
| These lines are
| broken exactly like in
| the source file.

第五章 Literal blocks
======================
This is a normal text paragraph. The next paragraph is a code sample::

   It is not processed in any way, except
   that the indentation is removed.

   It can span multiple lines.

This is a normal text paragraph again.

第6章 Doctest blocks
=====================
>>> 1 + 1
2

第7章 Hyperlink
=====================
This is a paragraph that contains a link: `Baidu`_.

.. _Baidu: https://baidu.com

=================
This is a heading
=================

第8章 \: \:
=====================
def my_function(my_arg, my_other_arg):
    """A function just for me.

    :param my_arg: The first of my arguments.
    :param my_other_arg: The second of my arguments.

    :returns: A message (just for me, of course).

    """

第9章 \.\.
=====================
.. function:: foo(x)
              foo(y, z)
   :module: some.module.name

   Return a line of text input from the user.

第10章 Images
=====================
.. image:: https://github.com/Cleanairdreaming/sphinx_test/tree/master/image/moves.jpg

=================
Section 2
=================

第11章 Footnotes and citations
=================================
Lorem ipsum [#f1]_ dolor sit amet ... [#f2]_

.. rubric:: 脚注

.. [#f1] Text of the first footnote.
.. [#f2] Text of the second footnote.

Lorem ipsum [ref]_ dolor sit amet.

.. [ref] https://doi.org/10.1016/j.envpol.2017.05.091

第12章 Substitutions
=================================
The |biohazard| symbol |name| must be used on containers used to
dispose of medical waste.

.. |biohazard| image:: https://github.com/Cleanairdreaming/sphinx_test/tree/master/image/warning.png
.. |name| replace:: *replacement text*
            
