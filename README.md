Copyright (c) 2013, Phil Gooch. 
This software is licenced under the [GNU Library General Public License](http://www.gnu.org/copyleft/gpl.html) Version 3, 29 June 2007.

See LICENSE.txt file for license details.

* * * *


ClauseSplitter for GATE
================================================

This crude plugin attempts to split English sentences into clauses, using some simple grammatical rules. It could probably be adapted for other European languages.

How to use this plugin
=======================

ClauseSplitter is compatible with [GATE version 7.1](http://www.gate.ac.uk/) and higher. Simply create an instance of the JAPE or JAPE Plus Transducer, and point it to the _main.jape_ file in this folder.

Be sure to add a Tokenizer, Sentence Splitter and POS Tagger to your pipeline before running this plugin.

You can replace calls to the VG macro with the {VG} annotation if you are using the ANNIE VP Chunker, or with {Predicate} if you are using the Predicate Phrase Chunker. If so, make sure you add either VG or Predicate to the list of input annotations.
