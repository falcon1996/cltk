Pali
****

Pali is a Prakrit language native to the Indian subcontinent which flourished between 5th and 1st century BC, now only used as a liturgical language. It is widely studied because it is the language of much of the earliest extant literature of Buddhism as collected in the Pāli Canon or Tipiṭaka and is the sacred language of Theravāda Buddhism. (Source: `Wikipedia <https://en.wikipedia.org/wiki/Pali>`_)


Alphabet
=========


.. code-block:: python

   In [1]: from cltk.corpus.pali.alphabet import CONSONANTS, DEPENDENT_VOWELS, INDEPENDENT_VOWELS

   In [2]: print(CONSONANTS)
   ['ක', 'ඛ', 'ග', 'ඝ', 'ඞ', 'ච', 'ඡ', 'ජ', 'ඣ', 'ඤ', 'ට', 'ඨ', 'ඩ', 'ඪ', 'ණ', 'ත', 'ථ', 'ද', 'ධ', 'න', 'ප', 'ඵ', 'බ', 'භ', 'ම', 'ය', 'ර', 'ල', 'ව', 'ස', 'හ', 'ළ', 'අං']



Corpora
=======

Use ``CorpusImporter()`` or browse the `CLTK GitHub organization <https://github.com/cltk>`_ (anything beginning with ``pali_``) to discover available Pali corpora.

.. code-block:: python

   In [1]: from cltk.corpus.utils.importer import CorpusImporter

   In [2]: c = CorpusImporter('pali')

   In [3]: c.list_corpora
   Out[3]: ['pali_text_ptr_tipitaka']

