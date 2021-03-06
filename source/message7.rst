#7. Sum
=======

.. note::

   If you have any ideas or enhancements for this page, please `edit it on GitHub`_!

Following documentation is a cooperative result combined from our `Discord chat`_ and numerous pull requests.
Thanks to everyone who helped!


Image
-----

This image was produced from the seventh radio transmission using :doc:`previously contributed code <radio-transmission-recording>`.

.. image:: message7.png
   :width: 176px

This partly annotated version of the image was made using :ref:`code from message #3 <message3-code>`.

.. image:: message7-annotated.svg
   :width: 176px


Interpretation
--------------

This image shows all known operators and functions

.. image:: functions.png
   :width: 500px

Count of operand symbols before function symbol defines how many operands the function expects.
if this is correct, we need to do the following to calculate sum of three numbers:

.. image:: operands_usage.png
   :width: 500px


Decoded
-------

.. literalinclude:: message7-decoded.txt


Code
----

Revised version of the Haskell code that supports the ``add`` glyph is published on the :ref:`message #3 page <message3-code>`.

Contributed by Discord users @pink_snow and @fryguybob.

Example output:

.. image:: message7-annotated-full.svg
   :width: 176px


.. _edit it on GitHub: https://github.com/zaitsev85/message-from-space/blob/master/source/message7.rst
.. _Discord chat: https://discord.gg/xvMJbas
