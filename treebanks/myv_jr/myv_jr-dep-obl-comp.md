---
layout: base
title:  'Statistics of obl:comp in UD_Erzya-JR'
udver: '2'
---

## Treebank Statistics: UD_Erzya-JR: Relations: `obl:comp`

This relation is a language-specific subtype of <tt><a href="myv_jr-dep-obl.html">obl</a></tt>.
There are also 8 other language-specific subtypes of `obl`: <tt><a href="myv_jr-dep-obl-agent.html">obl:agent</a></tt>, <tt><a href="myv_jr-dep-obl-cau.html">obl:cau</a></tt>, <tt><a href="myv_jr-dep-obl-inst.html">obl:inst</a></tt>, <tt><a href="myv_jr-dep-obl-lfrom.html">obl:lfrom</a></tt>, <tt><a href="myv_jr-dep-obl-lmod.html">obl:lmod</a></tt>, <tt><a href="myv_jr-dep-obl-lmp.html">obl:lmp</a></tt>, <tt><a href="myv_jr-dep-obl-lto.html">obl:lto</a></tt>, <tt><a href="myv_jr-dep-obl-tmod.html">obl:tmod</a></tt>.

43 nodes (0%) are attached to their parents as `obl:comp`.

43 instances of `obl:comp` (100%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.06976744186047.

The following 12 pairs of parts of speech are connected with `obl:comp`: <tt><a href="myv_jr-pos-ADV.html">ADV</a></tt>-<tt><a href="myv_jr-pos-NOUN.html">NOUN</a></tt> (14; 33% instances), <tt><a href="myv_jr-pos-ADV.html">ADV</a></tt>-<tt><a href="myv_jr-pos-VERB.html">VERB</a></tt> (11; 26% instances), <tt><a href="myv_jr-pos-ADV.html">ADV</a></tt>-<tt><a href="myv_jr-pos-PRON.html">PRON</a></tt> (6; 14% instances), <tt><a href="myv_jr-pos-ADJ.html">ADJ</a></tt>-<tt><a href="myv_jr-pos-NOUN.html">NOUN</a></tt> (2; 5% instances), <tt><a href="myv_jr-pos-ADJ.html">ADJ</a></tt>-<tt><a href="myv_jr-pos-PRON.html">PRON</a></tt> (2; 5% instances), <tt><a href="myv_jr-pos-ADV.html">ADV</a></tt>-<tt><a href="myv_jr-pos-ADV.html">ADV</a></tt> (2; 5% instances), <tt><a href="myv_jr-pos-ADJ.html">ADJ</a></tt>-<tt><a href="myv_jr-pos-ADV.html">ADV</a></tt> (1; 2% instances), <tt><a href="myv_jr-pos-ADJ.html">ADJ</a></tt>-<tt><a href="myv_jr-pos-PART.html">PART</a></tt> (1; 2% instances), <tt><a href="myv_jr-pos-ADP.html">ADP</a></tt>-<tt><a href="myv_jr-pos-ADV.html">ADV</a></tt> (1; 2% instances), <tt><a href="myv_jr-pos-ADV.html">ADV</a></tt>-<tt><a href="myv_jr-pos-PROPN.html">PROPN</a></tt> (1; 2% instances), <tt><a href="myv_jr-pos-DET.html">DET</a></tt>-<tt><a href="myv_jr-pos-NOUN.html">NOUN</a></tt> (1; 2% instances), <tt><a href="myv_jr-pos-DET.html">DET</a></tt>-<tt><a href="myv_jr-pos-NUM.html">NUM</a></tt> (1; 2% instances).


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 5 obl:comp	color:blue
1	Вал	вал	NOUN	N	Case=Nom|Definite=Ind|Number=Sing	2	obj	_	GTtags=Sg,Nom,Indef
2	сайсь	саемс	VERB	V	Mood=Ind|Number[subj]=Sing|Person[subj]=3|Tense=Past|Valency=2	0	root	_	GTtags=TV,Ind,Prt1,ScSg3
3	меельцекс	меельце	ADJ	A	Case=Tra|Definite=Ind|Number=Plur,Sing	2	xcomp	_	GTtags=SP,Tra,Indef|SpaceAfter=No
4	,	,	PUNCT	CLB	_	6	punct	_	_
5	прявттонть	прявт	NOUN	N	Case=Abl|Definite=Def|Number=Sing	6	obl:comp	_	GTtags=Sg,Abl,Def
6	мейле	мейле	ADV	Adv	AdvType=Tim	3	advmod:tmod	_	GTtags=Temp|SpaceAfter=No
7	.	.	PUNCT	CLB	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 2 obl:comp	color:blue
1	Кирёнь	Кирё	PROPN	N	Animacy=Hum|Case=Gen|Definite=Ind|NameType=Giv|Number=Plur,Sing	2	nmod	_	GTtags=Ant_Mal,Prop,SP,Gen,Indef
2	ёвтниматнеде	ёвтнемс	VERB	V	Case=Abl|Definite=Def|Number=Plur|Valency=2|VerbForm=Vnoun	3	obl:comp	_	GTtags=TV,NomAct,N,Pl,Abl,Def
3	мейле	мейле	ADV	Adv	AdvType=Tim	7	obl	_	GTtags=Temp
4	Миколонь	Микол	PROPN	N	Animacy=Hum|Case=Gen|Definite=Ind|NameType=Giv|Number=Plur,Sing	5	nmod	_	GTtags=Prop,Ant_Mal,SP,Gen,Indef
5	седеезэ	седей	NOUN	N	Case=Nom|Number=Sing|Number[psor]=Sing|Person[psor]=3	7	nsubj	_	GTtags=Sg,Nom,PxSg3
6	а	а	AUX	Pcle	Polarity=Neg	7	aux:neg	_	GTtags=Neg
7	таркасо	тарка	NOUN	N	Case=Ine|Definite=Ind|Number=Plur,Sing	0	root	_	GTtags=Sem/Plc,SP,Ine,Indef|SpaceAfter=No
8	.	.	PUNCT	CLB	_	7	punct	_	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 3 obl:comp	color:blue
1	Кавтошка	кавто	NUM	Num	Case=Cmp|Definite=Ind|Number=Plur,Sing|NumType=Card	2	nummod	_	GTtags=Card,SP,Cmpr,Indef
2	чить	чи	NOUN	N	Case=Nom|Definite=Ind|Number=Plur	6	obj	_	GTtags=Pl,Nom,Indef
3	теде	те	PRON	Pron	Case=Abl|Definite=Ind|Number=Sing|PronType=Dem	4	obl:comp	_	GTtags=Dem,Sg,Abl,Indef
4	мейле	мейле	ADV	Adv	AdvType=Tim	6	obl:tmod	_	GTtags=Sem/Time
5	эзь	а	AUX	V	Mood=Ind|Number[subj]=Sing|Person[subj]=3|Polarity=Neg|Tense=Past|VerbType=Aux	6	aux:neg	_	GTtags=Aux,Neg,Ind,Prt1,ScSg3
6	яка	якамс	VERB	V	Connegative=Yes	0	root	_	GTtags=ConNeg
7	библиотекав	библиотека	NOUN	N	Case=Lat|Definite=Ind|Number=Plur,Sing	6	obl:lto	_	GTtags=Sem/Plc,SP,Lat,Indef|SpaceAfter=No
8	.	.	PUNCT	CLB	_	6	punct	_	_

~~~

