---
layout: base
title:  'Statistics of Degree in UD_English-GUM'
udver: '2'
---

## Treebank Statistics: UD_English-GUM: Features: `Degree`

This feature is universal.
It occurs with 3 different values: `Cmp`, `Pos`, `Sup`.

16947 tokens (9%) have a non-empty value of `Degree`.
3182 types (19%) occur at least once with a non-empty value of `Degree`.
2853 lemmas (22%) occur at least once with a non-empty value of `Degree`.
The feature is used with 5 part-of-speech tags: <tt><a href="en_gum-pos-ADJ.html">ADJ</a></tt> (12429; 7% instances), <tt><a href="en_gum-pos-ADV.html">ADV</a></tt> (4510; 2% instances), <tt><a href="en_gum-pos-SCONJ.html">SCONJ</a></tt> (4; 0% instances), <tt><a href="en_gum-pos-DET.html">DET</a></tt> (3; 0% instances), <tt><a href="en_gum-pos-PUNCT.html">PUNCT</a></tt> (1; 0% instances).

### `ADJ`

12429 <tt><a href="en_gum-pos-ADJ.html">ADJ</a></tt> tokens (100% of all `ADJ` tokens) have a non-empty value of `Degree`.

`ADJ` tokens may have the following values of `Degree`:

* `Cmp` (450; 4% of non-empty `Degree`): <em>more, better, greater, larger, further, higher, lower, smaller, easier, less</em>
* `Pos` (11659; 94% of non-empty `Degree`): <em>other, many, new, good, little, first, different, same, last, own</em>
* `Sup` (320; 3% of non-empty `Degree`): <em>most, best, least, largest, highest, greatest, worst, biggest, latest, smallest</em>

<table>
  <tr><th>Paradigm <i>good</i></th><th><tt>Pos</tt></th><th><tt>Cmp</tt></th><th><tt>Sup</tt></th></tr>
  <tr><td><tt>_</tt></td><td><em>good</em></td><td><em>better</em></td><td><em>best</em></td></tr>
  <tr><td><tt><tt><a href="en_gum-feat-Number.html">Number</a></tt><tt>=Sing</tt></tt></td><td></td><td><em>Better</em></td><td></td></tr>
</table>

`Degree` seems to be **lexical feature** of `ADJ`. 97% lemmas (2288) occur only with one value of `Degree`.

### `ADV`

4510 <tt><a href="en_gum-pos-ADV.html">ADV</a></tt> tokens (51% of all `ADV` tokens) have a non-empty value of `Degree`.

The most frequent other feature values with which `ADV` and `Degree` co-occurred: <tt><a href="en_gum-feat-PronType.html">PronType</a></tt><tt>=EMPTY</tt> (4510; 100%).

`ADV` tokens may have the following values of `Degree`:

* `Cmp` (366; 8% of non-empty `Degree`): <em>more, later, less, longer, earlier, better, further, sooner, slower, Lesser</em>
* `Pos` (4012; 89% of non-empty `Degree`): <em>really, well, back, still, too, again, away, much, all, probably</em>
* `Sup` (132; 3% of non-empty `Degree`): <em>most, best, least, longest, fastest, foremost</em>
* `EMPTY` (4377): <em>so, just, when, then, also, how, now, here, very, there</em>

<table>
  <tr><th>Paradigm <i>well</i></th><th><tt>Pos</tt></th><th><tt>Cmp</tt></th><th><tt>Sup</tt></th></tr>
  <tr><td><tt>_</tt></td><td><em>well</em></td><td><em>better</em></td><td><em>best</em></td></tr>
  <tr><td><tt><tt><a href="en_gum-feat-Typo.html">Typo</a></tt><tt>=Yes</tt></tt></td><td><em>well</em></td><td></td><td></td></tr>
</table>

`Degree` seems to be **lexical feature** of `ADV`. 98% lemmas (583) occur only with one value of `Degree`.

### `SCONJ`

4 <tt><a href="en_gum-pos-SCONJ.html">SCONJ</a></tt> tokens (0% of all `SCONJ` tokens) have a non-empty value of `Degree`.

`SCONJ` tokens may have the following values of `Degree`:

* `Pos` (4; 100% of non-empty `Degree`): <em>such, like</em>
* `EMPTY` (2880): <em>that, if, as, because, for, while, by, of, in, after</em>

### `DET`

3 <tt><a href="en_gum-pos-DET.html">DET</a></tt> tokens (0% of all `DET` tokens) have a non-empty value of `Degree`.

The most frequent other feature values with which `DET` and `Degree` co-occurred: <tt><a href="en_gum-feat-Definite.html">Definite</a></tt><tt>=EMPTY</tt> (3; 100%), <tt><a href="en_gum-feat-PronType.html">PronType</a></tt><tt>=Tot</tt> (2; 67%).

`DET` tokens may have the following values of `Degree`:

* `Pos` (3; 100% of non-empty `Degree`): <em>all, Some</em>
* `EMPTY` (15388): <em>the, a, this, an, all, some, these, that, no, any</em>

### `PUNCT`

1 <tt><a href="en_gum-pos-PUNCT.html">PUNCT</a></tt> tokens (0% of all `PUNCT` tokens) have a non-empty value of `Degree`.

`PUNCT` tokens may have the following values of `Degree`:

* `Pos` (1; 100% of non-empty `Degree`): <em>—</em>
* `EMPTY` (25765): <em>,, ., -, ", (, ), ?, [, ], —</em>

## Relations with Agreement in `Degree`

The 10 most frequent relations where parent and child node agree in `Degree`:
<tt>ADJ --[<tt><a href="en_gum-dep-conj.html">conj</a></tt>]--> ADJ</tt> (395; 95%),
<tt>ADJ --[<tt><a href="en_gum-dep-amod.html">amod</a></tt>]--> ADJ</tt> (63; 89%),
<tt>ADV --[<tt><a href="en_gum-dep-conj.html">conj</a></tt>]--> ADV</tt> (55; 87%),
<tt>ADJ --[<tt><a href="en_gum-dep-compound.html">compound</a></tt>]--> ADJ</tt> (28; 100%),
<tt>ADJ --[<tt><a href="en_gum-dep-advcl.html">advcl</a></tt>]--> ADJ</tt> (27; 87%),
<tt>ADJ --[<tt><a href="en_gum-dep-parataxis.html">parataxis</a></tt>]--> ADJ</tt> (22; 100%),
<tt>ADJ --[<tt><a href="en_gum-dep-obl-npmod.html">obl:npmod</a></tt>]--> ADJ</tt> (11; 79%),
<tt>ADJ --[<tt><a href="en_gum-dep-obl.html">obl</a></tt>]--> ADJ</tt> (11; 69%),
<tt>ADJ --[<tt><a href="en_gum-dep-ccomp.html">ccomp</a></tt>]--> ADJ</tt> (9; 82%),
<tt>ADV --[<tt><a href="en_gum-dep-advcl.html">advcl</a></tt>]--> ADJ</tt> (8; 100%).

