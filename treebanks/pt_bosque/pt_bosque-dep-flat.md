---
layout: base
title:  'Statistics of flat in UD_Portuguese-Bosque'
udver: '2'
---

## Treebank Statistics: UD_Portuguese-Bosque: Relations: `flat`

This relation is universal.
There are 2 language-specific subtypes of `flat`: <tt><a href="pt_bosque-dep-flat-foreign.html">flat:foreign</a></tt>, <tt><a href="pt_bosque-dep-flat-name.html">flat:name</a></tt>.

16 nodes (0%) are attached to their parents as `flat`.

16 instances of `flat` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 1.4375.

The following 4 pairs of parts of speech are connected with `flat`: <tt><a href="pt_bosque-pos-NUM.html">NUM</a></tt>-<tt><a href="pt_bosque-pos-NUM.html">NUM</a></tt> (7; 44% instances), <tt><a href="pt_bosque-pos-NUM.html">NUM</a></tt>-<tt><a href="pt_bosque-pos-CCONJ.html">CCONJ</a></tt> (4; 25% instances), <tt><a href="pt_bosque-pos-PROPN.html">PROPN</a></tt>-<tt><a href="pt_bosque-pos-PROPN.html">PROPN</a></tt> (4; 25% instances), <tt><a href="pt_bosque-pos-NUM.html">NUM</a></tt>-<tt><a href="pt_bosque-pos-NOUN.html">NOUN</a></tt> (1; 6% instances).


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 3 flat	color:blue
1	Trinta	trinta	NUM	_	NumType=Card	4	nummod	_	MWE=trinta_e_sete|MWEPOS=NUM
2	e	e	CCONJ	_	_	1	flat	_	_
3	sete	sete	NUM	_	NumType=Card	1	flat	_	_
4	anos	ano	NOUN	_	Gender=Masc|Number=Plur	0	root	_	_

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 2 flat	color:blue
1	Trinta	trinta	NUM	_	NumType=Card	4	nummod	_	MWE=trinta_e_sete|MWEPOS=NUM
2	e	e	CCONJ	_	_	1	flat	_	_
3	sete	sete	NUM	_	NumType=Card	1	flat	_	_
4	anos	ano	NOUN	_	Gender=Masc|Number=Plur	0	root	_	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 4 flat	color:blue
1	TEATRO	TEATRO	PROPN	_	Gender=Masc|Number=Sing	0	root	_	MWE=TEATRO_NACIONAL_DE_D.Maria_II
2	NACIONAL	NACIONAL	PROPN	_	Number=Sing	1	flat:name	_	_
3	DE	DE	PROPN	_	Number=Sing	1	flat:name	_	_
4	D.	D.	PROPN	_	_	1	flat	_	_
5	MARIA	MARIA	PROPN	_	Number=Sing	1	flat:name	_	_
6	II	II	PROPN	_	Number=Sing	1	flat:name	_	SpaceAfter=No
7	.	.	PUNCT	_	_	1	punct	_	_

~~~


