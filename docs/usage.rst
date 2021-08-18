Required parameter
~~~~~~~~~~~~~~~~~~

--ali (input alignment)
^^^^^^^^^^^^^^^^^^^^^^^

--output\_path (path)
^^^^^^^^^^^^^^^^^^^^^

the directory of your output path

Optional parameter
~~~~~~~~~~~~~~~~~~

--mode con(default)\|rep
^^^^^^^^^^^^^^^^^^^^^^^^

how to construct a sequence for HMM data base search + con : generate a
consensus sequence found using ``hmmemit --symfrac 0`` + rep : pick up a
representative single sequence from input alignment with highest
pairwise similarity

--database (hmm database)
^^^^^^^^^^^^^^^^^^^^^^^^^

the hmm database you want to use. (default version: 3.1b1 \| May 2013)

--file\_name (output file name)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

your output file name. (default is your input file name)

--hmmer\_path (path)
^^^^^^^^^^^^^^^^^^^^

the path of your hmmer scripts (hmmfetch hmmpress hmmscan) (default
version: h3.1b2 \| February 2015)

--gb\_path (path)
^^^^^^^^^^^^^^^^^

the path of your gblocks file (default version: 0.91b) #### --iq\_path
(path) the path of your iqtree file (default version: 1.6.10)

Example
-------

use command:
~~~~~~~~~~~~

python3 freq\_extractor.py --ali example\_files/example\_input.fasta
--output\_path output --file\_name example1 ## Support or Contact

Having trouble with Pages? Check out our
`documentation <https://help.github.com/categories/github-pages-basics/>`__
or `contact support <https://github.com/contact>`__ and we’ll help you
sort it out.
